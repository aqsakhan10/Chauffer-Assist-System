### SRH UNIVERSITY OF APPLIED SCIENCES
#### Professor: Mr.Alexander Iliev

# Virtual wardrobe

Virtual wardrobe is a program to identify the clothes from the wardrobe.

## Introduction

### Pandas: 

It is a Python package providing fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. In addition to this it has the broader goal of becoming the most powerful and flexible open source data analysis/manipulation tool available in any language.   

### NumPy: 

It is the fundamental package needed for scientific computing in Python. It provides sophisticated (broadcasting) functions, tools for integrating C/C++ and Fortran code, useful linear algebra, Fourier transform, and random number capabilities.

### openCV: 

It is an open source computer vision and machine learning software library. It has more than 2500 optimized algorithms, which can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects, extract 3D models of objects, produce 3D point clouds from stereo cameras, stitch images together to produce a high resolution image of an entire scene etc.

### Colab: 

Google Colab is a free cloud service which supports free GPU! You can: improve your Python programming language coding skills.

## Pre-requisites

1) Create project on google colab
2) Installing Python 3.0
3) Installing numpy
4) Install PIL 1.7
5) Install openCV

## Operating System

* Windows
* Mac OS
* Linux

## Installation

```bash
pip install keras
pip install OpenCV
pip install Numpy
pip install TensorFlow
```

## Files

DataPreprocessing.py - Load the training & test data into data frames and normalize the data

Wardrobe.py - Prepare the model by adding 4 convolutional layers and 2 dense layers and training for 25 epochs

ImagePrediction.py - Input the image from webcam and predict the type of apparel.

```python
DataPreprocessing.py
Wardrobe.py
ImagePrediction.py
```

## Dataset

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits

```python
fashion-mnist_test.csv
fashion-mnist_train.csv
```
