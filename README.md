# Setup
## Poetry
```
poetry new trading
poetry lock
poetry install
poetry sync (also removes packages!)
poetry run which python


```
## Sphinx
```
sphinx-quickstart docs
# Edit conf.py to add .. in search path and add autodocs
# Edit index.rst to add modules
sphinx-apidoc -o docs trading/
cd docs
make html
```
## GitHub
```
git init
git remote add origin <url>
git push -u -f origin master
```

## Python
```
conda env create -f environment.yml
conda activate trading3.12
poetry install
```

# TODO
- dev dependencies
- remove conda entirely
- github actions shared...
- build and upload to python package manager
- packages and releases