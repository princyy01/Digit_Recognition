This project involves building a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.


## Introduction

This project demonstrates the use of a CNN to classify handwritten digits from the MNIST dataset. The dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

## Dataset

The MNIST dataset is a classic dataset in the field of machine learning and computer vision. It contains grayscale images of handwritten digits, each of size 28x28 pixels.

## Model Architecture

The CNN model is built using TensorFlow and Keras and consists of the following layers:

- Convolutional Layer with 64 filters and a kernel size of 3x3, followed by ReLU activation and MaxPooling
- Convolutional Layer with 32 filters and a kernel size of 3x3, followed by ReLU activation and MaxPooling
- Convolutional Layer with 32 filters and a kernel size of 3x3, followed by ReLU activation
- Flatten Layer to reshape the output before feeding it into a Dense Layer
- Dense Layer with 64 units and ReLU activation
- Dense Layer with 32 units and ReLU activation
- Output Dense Layer with 10 units and softmax activation
