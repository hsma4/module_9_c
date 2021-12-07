# Advanced forecasting with Feedforward Neural Networks
# HSMA 2020

-----

**Welcome to the third and final section in our series of HSMA forecasting classes**.  In this 1.5 hour class you will be introduced to forecasting using feedforward neural networks.

## Course structure

1. A lecture introducting the theory of forecasting with Neural Networks
2. Two code-along lectures in Jupyter notebooks 

## Learning outcomes

**By the end of the class you will have**

* New tools to appraise and question forecasting studies
* Hands on experience of manipulating time series in python
* Hands on experience of producing forecasts using Keras and TensorFlow.

## Setup for the course

**Google colab is the easiest way to run the notebooks in this module (see links below)**.  The notebooks have been tested with Tensorflow 2.7 (and 2.3).  If you wish to run the code locally you are provided with a conda environment (see binder/environment.yml) that you can use to install the dependencies.  To install follow these instructions.

0. Optionally you may want to update conda before creating the virtual environment
   * `conda update conda`

1. Open an anaconda prompt (or terminal on Mac and Linux) in the same directory as the course files.  Run the following command

   * `conda env create -f binder/environment.yml`

2. Conda will resolve the enviornment and ask if you wish to install it.  Answer 'y'. Installation will take several minutes.  It installs an environment called `hsma_forecast3`.  You need to activate it.

   * `conda activate hsma4_forecast9c`

3. To follow the code along lectures and complete the exercises please use Jupyter-Lab.  To run it enter the following command into your anaconda prompt or terminal (making sure you are in the same directory as the files)

   * `jupyter-lab`

Jupyter will then open.


# Launch Notebooks in Google Colab

If you are experiencing issues with Jupyter-Lab on your personal computer then you can also run the notebooks in google colab.  Use the links below to launch them

## Code along lectures

https://github.com/hsma4/module_9_c

* Code along 1: Preprocessing data and autoregression basics [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_c/blob/main/code_along_lectures/01_autoregression.ipynb)

* Code along 2: Forecasting using a feedforward neural network [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma4/module_9_c/blob/main/code_along_lectures/02_autoregression_keras.ipynb)


