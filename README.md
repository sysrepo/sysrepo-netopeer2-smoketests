[![Build Status](https://travis-ci.org/sysrepo/sysrepo-netopeer2-smoketests.svg?branch=master)](https://travis-ci.org/sysrepo/sysrepo-netopeer2-smoketests)

# Sysrepo - Netopeer2 smoke tests

Basic smoke tests for [Sysrepo](https://github.com/sysrepo/sysrepo) & [Netopeer2](https://github.com/CESNET/Netopeer2) based on [ncclient](https://github.com/ncclient/ncclient). The tests can be executed individually as a python script, e.g.:
```
python test_basic_operations.py
```
or altogether as a whole testsuite by executing:
```
python -m unittest discover -v
```
