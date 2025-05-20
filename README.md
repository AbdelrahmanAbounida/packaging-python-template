# packaging-python-temp

## Steps to build from scratch

### 1. Projec Setup

```sh
python -m venv venv
pdm init
pdm add ... # for adding new pkg
pdm add -dG test pytest # for dev /linting / testing ,...
```

### 2- Run inital Test

```sh
pdm run pytes
```

### 3- Publish with CICD

update the existing workflows as required

### 4- Pypi setup

Go to pypi and make project trused
https://pypi.org/manage/account/publishing

### 4- Others

TODO::

- CICD: https://packaging.python.org/en/latest/guides/publishing-package-distribution-releases-using-github-actions-ci-cd-workflows/
- Add linting, formatting , ..
- CLI: https://packaging.python.org/en/latest/guides/creating-command-line-tools/
- Versioning: https://packaging.python.org/en/latest/discussions/versioning/
