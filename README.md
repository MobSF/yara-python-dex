# yara-python-dex


## Build Locally

```
pip install wheel
pip wheel --wheel-dir=yara-python-dex --build-option="build" --build-option="--enable-dex" git+https://github.com/MobSF/yara-python-dex.git
pip install --no-index --find-links=yara-python-dex yara-python-dex
```
