# tfkeras
Setting up Python tooling for developers new to Python, can be challenging.

This repository provides a Conda environment for Python machine learning. This environment includes:
 * python 3.12.8
 * scikit-learn
 * tensorflow/keras
 * numpy
 * pandas
 * ipython
 * jupyter
 * kaggle
 * keras-tuner

The environment is also opinionated about testing, linting and formatting and installs the following as well:
 * pytest
 * behave
 * flake8
 * black

## Prerequisite
You'll need the conda package manager.

## Setting up your environment

```
$ git clone https://github.com/hammingweight/tfkeras.git
$ cd tfkeras
$ conda env create
$ conda activate tfkeras
```
 
