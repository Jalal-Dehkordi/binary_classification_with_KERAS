# binary_classification_with_KERAS
Implementation of binary classification using the Keras library
## Introduction
This repository contains code for implementing a binary classification problem using the Keras library. The goal is to classify movie reviews as either positive or negative based on their content.

## Data Description
The IMDB dataset consists of 50,000 movie reviews, split into 25,000 for training and 25,000 for testing. Each set contains an equal number of positive and negative reviews.

## Data Preparation
Data and tags are vectorizing

## Network Structure
The neural network consists of three dense layers with 16 units in the first two layers and 1 unit in the final layer.

## Model Compilation
The model is configured with the rmsprop optimizer and the cost function binary_crossentropy.

## Setting Aside a Validation Set
Data is split into a validation set (x_val and y_val) and a partial training set (partial_x_train and partial_y_train).

## Training
The model is trained for 20 epochs with a batch size of 512.
Model Evaluation

### Overfitting

The accuracy of the model on the training data is higher than on the validation data, indicating overfitting. To prevent this, training is limited to 3 epochs.

## Conclusion
This simple approach achieves an accuracy of 88%. Further advanced techniques could potentially improve performance.

