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
Seeing as there are several submodules to Colab Utils (much like the `google.colab` module within Colab), I recommend you import the submodules themselves, rather than the main module. For example:
```py
# If you're only working with one submodule, just import it
# by name. For example, using the drive submodule:
from colab_utils import drive

# Of course, if you intend to work with multiple submodules,
# you can always simply import all of them.
from colab_utils import *
```
Otherwise, if you *need* to import the main module to avoid name conflicts, I recommend you at least import it with a shorter name (that doesn't contain an underscore), like so:
```py
import colab_utils as utils
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNDc0MDY2NzcsMTU4MTczOTY5LDE5Nj
cyMDM4NTddfQ==
-->