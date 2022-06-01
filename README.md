# Emotions_Detector
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

Kaggle Challenge - https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

Facial Emotion Recognition on FER2013 Dataset Using a Convolutional Neural Network. 

80-10-10 ratio for training-validation-test sets.

Winner - 71.161% accuracy

This Model -  66.369% accuracy

![emotions](https://user-images.githubusercontent.com/28602282/48102098-ab737b80-e1e6-11e8-8541-517de2be0064.png)

## Getting Started

These instructions will get this model up and running. Follow them to make use of the `main.py` file to recognize facial emotions using custom images. This model can also be used as facial emotion recognition part of projects with broader applications

### Prerequisites
Install these prerequisites before proceeding-
```
 pip install tensorflow
 pip install keras
 pip install numpy
 pip install pandas
 pip install opencv-python
```

### Method 1 : Using the built model 

If you don't want to train the classifier from scratch, you can make the use of `main.py` directly as the the repository already has `fer.json` (trained model) and `fer.h5` (parameters) which can be used to predict emotion on any test image present in the folder.

### Method 2 : Build from scratch
Clone this repository.
Download and extract the dataset from Kaggle link above.

Run the `Emotion.ipynb` file, which would generate `CNN.json` and `weights.h5` files for you.

# Model Summary

The layers in the Convolution Neural Network used in implementing this classifier can be summarized as follows.

![image](https://user-images.githubusercontent.com/86120558/171444504-24456214-7259-4ecf-8c25-f249a3bccdd0.png)
