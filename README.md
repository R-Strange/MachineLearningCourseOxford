# The Environmental Research DTP Artificial Intelligence Training Course
Welcome to the the Env-Res Artificial Intelligence Training Course GitHub page. You can find copies of the slides, and problem and solution notebooks for exercises here.

## Requirements

This python-based course assumes that you're using the following tools:

* Anaconda
* Python 3+
* Numpy
* Pandas
* Scikit-learn
* Keras
* Tensorflow

## Installations

#### Python 3+ and Anaconda

To install python 3+ and anaconda on a windows machine, visit https://www.anaconda.com/distribution/

You may use pip or install libraries from source but these won't be supported

For UNIX/LINUX, python is preinstalled. Check your version by running `python --version` You can download the appropriate anaconda distribution from the anaconda website, or `wget`ting their tarballs.

#### Numpy, Pandas, Scikit-learn

In the anaconda prompt for windows, or the UNIX/LINUX terminal, run the following commands

```bash
conda create -n machine_learning python=3.7
conda activate machine_learning
conda install numpy
conda install pandas
conda install scipy
conda install -c conda-forge scikit-learn
```

#### Keras and TensorFlow

This instruction set assumes you are not using CUDA-capable discrete GPUs. If you are, see the Keras and TensorFlow documentation for your installation directions.

In anaconda prompt or terminal, type the following

```bash
conda create -n deep_learning python=3.6
conda activate deep_learning
conda install -c anaconda keras
```



## Directory Structure

The root directory contains a `Deck` folder, and the `Day 1` and `Day 2` folders that contain all the relevant problem and solution jupyter notebooks
