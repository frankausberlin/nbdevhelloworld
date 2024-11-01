# nbdevhelloworld

from [here](https://nbdev.fast.ai/tutorials/tutorial.html)

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Developer Guide

If you are new to using `nbdev` here are some useful pointers to get you
started.

### Install nbdevhelloworld in Development mode

``` sh
# make sure nbdevhelloworld package is installed in development mode
$ pip install -e .

# make changes under nbs/ directory
# ...

# compile to have changes apply to nbdevhelloworld
$ nbdev_prepare
```

## Usage

### Installation

Install latest from the GitHub
[repository](https://github.com/frankausberlin/nbdevhelloworld):

``` sh
$ pip install git+https://github.com/frankausberlin/nbdevhelloworld.git
```

or from [conda](https://anaconda.org/frankausberlin/nbdevhelloworld)

``` sh
$ conda install -c frankausberlin nbdevhelloworld
```

or from [pypi](https://pypi.org/project/nbdevhelloworld/)

``` sh
$ pip install nbdevhelloworld
```

### Documentation

Documentation can be found hosted on this GitHub
[repository](https://github.com/frankausberlin/nbdevhelloworld)’s
[pages](https://frankausberlin.github.io/nbdevhelloworld/). Additionally
you can find package manager specific guidelines on
[conda](https://anaconda.org/frankausberlin/nbdevhelloworld) and
[pypi](https://pypi.org/project/nbdevhelloworld/) respectively.

## How to use

Fill me in please! Don’t forget code examples:

``` python
1+1
```

    2


### Flow
``` python
# mamba create -n nbd --clone base
# mamba install -c conda-forge -y jupyterlab
# mamba install -c fastai -y nbdev
# nbdev_install_quarto
# pip install jupyterlab-quarto
# echo "make repo nbdevhelloworld on github"
# git clone https://github.com/fastai/nbdevhelloworld.git
# cd nbdevhelloworld
# nbdev_new
# git add .
# git commit -m'Initial commit'
# git push
## git-token: "Settings" --> "Developer settings"
## enable GitHub --> “Settings” --> “Pages” --> “Branch” to “gh-pages” --> “Save”
# https://frankausberlin.github.io/nbdevhelloworld
# nbdev_install_hooks
# nbdev_export
# pip install -e '.[dev]'
# nbdev_preview
# http://localhost:7582/core.html
### make changes in core
# nbdev_prepare
```

