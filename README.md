# sfzlint-container

[rye](https://rye.astral.sh/) project for using [sfzlint](https://github.com/jisaacstone/sfzlint/)

## Generate project and install packages

```shell
rye init sfzlint-container
cd sfzlint-container
rye add pyyaml
rye add --git https://github.com/jisaacstone/sfzlint.git sfzlint
rye sync
```

## Run sfzlint

```shell
rye run sfzlint /PATH_TO_SFZ_FILES
```

or activate venv and run

```shell
pwd # /sfzlint-container
source .venv/bin/activate
sfzlint /PATH_TO_SFZ_FILES
```
