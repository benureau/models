**models** is a small library implementing some specific algorithms for learning forward and inverse models, most specifically Locally Weighted Linear Regression (LWLR).

It was created to support code for  [experiments on sensorimotor learning](http://fabien.benureau.com). It might somehow be useful to you, especially if you want to rerun, check or tweak the aforementioned experiments.

Its documentation although somehow existent, is notably incomplete and outdated. However, care it taken to keep tests and usage examples functioning.

### OpenScience License

This software is placed under the [OpenScience license](http://fabien.benureau.com/openscience.html), which is the LGPL, with the additional condition that if you publish scientific results using this code, you have to publish the corresponding modifications of the code.

> If you publicly release any scientific claims or data that were supported or generated by the Program or a modification thereof, in whole or in part, you will release any modifications you made to the Program. This License will be in effect for the modified program. 

## Installation

1. Get the code
1. `python setup.py install`
##### (Optional) C++ speed-up
1. Install [cython](cython.org)
1. Go to `cdataset/`
1. `python setup.py install`
##### (Optional) Tests
1. To run the tests and examples, you will need to install [robots](github.com/humm/robots)

## Usage

See the `examples/` and `tests/` folders.

