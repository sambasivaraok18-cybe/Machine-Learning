# Neural Network Optimizers: SGD vs RMSProp vs Adam

This repository contains the code and tutorial for a machine learning experiment comparing three neural network optimization algorithms.

The goal of this project is to demonstrate how different optimizers influence neural network training behaviour and classification performance.

## Tutorial Topic

Neural Network Optimizers: Comparing SGD, RMSProp and Adam

## Dataset

The experiments use the CIFAR-10 dataset, a well-known benchmark dataset for image classification.

Dataset characteristics:

- 60,000 colour images
- 10 object classes
- Image resolution: 32 × 32 pixels
- 50,000 training images
- 10,000 test images

Dataset available at:
https://www.cs.toronto.edu/~kriz/cifar.html 


A fully connected neural network (MLP) was used for the experiments.

Architecture:

- Flatten layer
- Dense layer (256 neurons, ReLU)
- Dense layer (128 neurons, ReLU)
- Output layer (10 neurons, Softmax)

## Optimizers Compared

The tutorial evaluates three popular optimizers:

- Stochastic Gradient Descent (SGD)
- RMSProp
- Adam

The performance of these optimizers is compared using:

- training loss convergence
- validation accuracy
- test accuracy
- confusion matrix
- prediction visualizations



requirements.txt -
numpy
pandas
matplotlib
seaborn
tensorflow
scikit-learn
