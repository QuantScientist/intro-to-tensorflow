# Introduction to TensorFlow
In this tutorial the steps needed to clean a dataset and prepare it for modeling using the machine learning library
TensorFlow. The tutorial uses the [Wine](http://archive.ics.uci.edu/ml/datasets/Wine) dataset from the
[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml).

## Prerequesits
This tutorial includes several machine learning terms. To get a good mathematical understanding of these concepts,
please read the Math Primer.

## Installation Notes
There are a few packages you will need in order to run this tutorial. We recommend installing the miniconda environment,
which makes the installation process quite easy. Please see the
[README](https://github.com/PythonWorkshop/intro-to-sklearn) file for this mornings session for instructions on how to
install miniconda.

In order to run this tutorial, you will need the following Python packages:
* numpy
* pandas
* seaborn
* sklearn
* skflow
* tensorflow

(skflow is not part of tensorflow ??)

The first five packages can be installed with the following command:

```
pip install numpy pandas seaborn sklearn skflow
```

Alternatively if you are using conda you can do:

```
conda install numpy pandas seaborn scikit-learn
```

For TensorFlow, the installation depends on your environment. Below are installation instructions. For detailed
instuctions, please see the TensorFlow
[README](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/g3doc/get_started/os_setup.md) file.

### NOTE:
What's better to use? The virtual environment or normal pip installation?

## Play with outliers

I have added a fun interactive application using the Python visualization library called Bokeh. The app allows you to
pick features from the wine data set and set an outlier threshold to explore how this affects the data. The application
source code is in the `playing_with_outliers` directory and is called `main.py`. To run this application, you will need
to install bokeh:

```
pip install bokeh
```

Then, to run the application, download the `playing_with_outliers` directory. Then, in the directory where you downloaded
it, run:

```
bokeh serve --show playing_with_outliers
```