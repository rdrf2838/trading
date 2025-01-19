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
sphinx-apidoc -o docs src/python/trading/
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

pyenv install --list
pyenv install 3.12.8
pyenv local 3.12
poetry install
eval $(poetry env activate)
```

## Installing as user
```
python -m pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple trading
```

# TODO

# DONE
- dev dependencies
- github actions shared...
- remove conda entirely
- build and upload to python package manager
- packages and releases