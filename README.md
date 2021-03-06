# CloudnetPy

[![Build Status](https://travis-ci.org/actris-cloudnet/cloudnetpy.svg?branch=master)](https://travis-ci.org/actris-cloudnet/cloudnetpy)
[![Documentation Status](https://readthedocs.org/projects/cloudnetpy/badge/?version=latest)](https://cloudnetpy.readthedocs.io/en/latest/?badge=latest)
[![PyPI version](https://badge.fury.io/py/cloudnetpy.svg)](https://badge.fury.io/py/cloudnetpy)
[![DOI](https://zenodo.org/badge/233602651.svg)](https://zenodo.org/badge/latestdoi/233602651)

CloudnetPy is a Python software for producing vertical profiles of cloud properties from ground-based 
remote sensing measurements. The Cloudnet processing combines cloud radar, optical lidar, microwave 
radiometer and model data. Measurements and model data are brought into common grid and 
classified as ice, liquid, aerosol, insects, and so on. 
Then, geophysical products such as ice water content can be 
retrieved in the further processing steps.

CloudnetPy is a refactored fork of the currently operational (Matlab) processing code. The Python version features several revised methods, extensive documentation, and more.

* CloudnetPy documentation: https://cloudnetpy.readthedocs.io/en/latest/
* Cloudnet website: http://devcloudnet.fmi.fi

<img src="docs/source/_static/20190423_mace-head_classification.png">

## Installation

### From PyPI
```
$ python3 -m pip install cloudnetpy
```

### From the source
```
$ git clone https://github.com/actris-cloudnet/cloudnetpy
$ cd cloudnetpy/
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ python3 -m pip install .
```

## Contributing

We encourage you to contribute to CloudnetPy! Please check out the [contribution guidelines](CONTRIBUTING.md) about how to proceed.
