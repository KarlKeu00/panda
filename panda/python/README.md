PyPANDA: PANDA's Python Interface
========
Overview
-
PyPANDA is a Python 3 interface to PANDA. With PyPANDA, you can quickly develop plugins
to analyze behavior of a running system, record a system and analyze replays, or do
nearly anything you can do using PANDA's C/C++ APIs.

Autogenerated pypanda documentation is available at [docs.panda.re](https://docs.panda.re).


## Installing

1) Build the regular C/C++ binaries for PANDA according to the documentation. If using build.sh, run `build.sh --python` to automatically complete the subsequent steps.

2) Install pypanda dependencies with:
```
# apt-get install -y genisoimage wget libffi-dev
# pip3 install colorama 'protobuf>=4.25.1' 'cffi>=1.14.3'
```
Note CFFI is a build dependency for pypanda and your protobuf version needs to match your system version.

3) Build and install the `pandare` Python package
```
$ cd panda/panda/python/core
$ python setup.py install
```

### Technical details
See detailed installation, usage and example programs [here](./docs/USAGE.md).

## Examples
Examples are provided in the [examples directory](./examples/).
