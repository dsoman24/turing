# Turing Machine Simulators
Python is Turing-Complete after all...

[https://pypi.org/project/turingmachines24/](https://pypi.org/project/turingmachines24/)

### Installation

`pip install turingmachines24`


### How to update:

Change version number

Delete everything in dist

`python setup.py sdist bdist_wheel`

`twine upload --skip-existing dist/*`