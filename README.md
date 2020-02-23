# Bodhi

[![Generic badge](https://img.shields.io/badge/python-3.7-blue.svg)](https://shields.io/)
[![codecov](https://codecov.io/gh/kvnvk/Bodhi/branch/master/graph/badge.svg?token=N1doUdLcSh)](https://codecov.io/gh/kvnvk/Bodhi)
[![Generic badge](https://img.shields.io/badge/style-Black-black.svg)](https://github.com/psf/black)

The back end service powering Focus Trainer

## Development

#### Setup

```buildoutcfg
pip install -r requirements.txt
pre-commit install
```

#### Run Tests

```buildoutcfg
PYTHONPATH=. python3 nose bodhi/tests
```
