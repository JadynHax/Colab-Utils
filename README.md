# Welcome to Colab Utils
A collection of some nice, easy-to-use, and convenient utilities for working with [Google Colaboratory](https://colab.research.google.com).

## Contents
- [Installation](#installation)
- [Usage](#usage)

## Installation
To install (in Colab **only**), put the following line in a cell at the top of your notebook:
```ipython
!pip install --upgrade colab-utils
```
If you already have a `pip install` line for other reasons, you can also simply add `colab-utils` to that line.

## Usage
Seeing as there are several submodules to Colab Utils (much like the `google.colab` module within Colab), it is recommended to import the submodules themselves, rather than the main module. For example:
```py
# If you're only working with one submodule, just import it

# Of course, if you intend to work with multiple submodules,
# you can always simply import all of them.
from colab_utils import *
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MDM4NDI3OTIsMTU4MTczOTY5LDE5Nj
cyMDM4NTddfQ==
-->