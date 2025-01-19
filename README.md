## Poetry
```
poetry new trading
poetry lock
poetry install
poetry run which python
```
## Sphinx
```
sphinx-quickstart
# Edit conf.py to add .. in search path
# Edit index.rst to add modules
sphinx-apidoc -o docs/source trading/
cd docs
make html
```