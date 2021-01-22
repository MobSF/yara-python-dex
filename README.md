# yara-python-dex

[![PyPI version](https://badge.fury.io/py/yara-python-dex.svg)](https://badge.fury.io/py/yara-python-dex)
![Test](https://github.com/MobSF/yara-python-dex/workflows/Test/badge.svg)


Prebuilt dex-enabled yara-python wheels


## Build Locally

```
pip install wheel
pip wheel --wheel-dir=yara-python-dex git+https://github.com/MobSF/yara-python-dex.git
pip install --no-index --find-links=yara-python-dex yara-python-dex
```

## Dev

```
python -m pip install --upgrade pip
pip install setuptools wheel
git submodule update --init --recursive
python setup.py bdist_wheel
```

## Update yara-python

```
cd yara-python
git checkout tags/v3.11.0
cd ..
git submodule update --init --recursive
git add yara-python
```
