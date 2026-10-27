# CNN MNIST Classifier from Scratch

## Overview
This project implements a multi-layer Neural Network classifier for the MNIST handwritten digit dataset built entirely from scratch using Python and NumPy, avoiding high-level deep learning frameworks.

## Architecture & Pipeline
- **Parameter Initialization**: Random weight ($W_1, W_2, W_3$) and bias ($b_1, b_2, b_3$) initialization.
- **Forward Propagation**: Implements ReLU activation functions and Softmax output normalization.
- **Backward Propagation**: Computes analytical gradients of loss with respect to weights and biases.
- **Training Loop**: Iterative gradient descent over training batches with accuracy tracking.

## Data
- **Dataset**: MNIST digit recognition dataset (`data/train.csv`).
- **Splits**: 1,000 samples dev set, remaining samples training set, normalized pixel values divided by 255.0.

## Method & Algorithms
- **Multilayer Perceptron / Neural Network**: Pure NumPy implementation of forward prop, ReLU activation, Softmax, cross-entropy / derivative backpropagation, and gradient descent optimization.

## Verified Results & Metrics
- Achieved **95.37% training accuracy** and **93.5% dev accuracy** on the MNIST dataset through iterative gradient descent training.

## Limitations & Caveats
- Built as a foundational deep learning exercise using pure NumPy without GPU acceleration or automated autograd.

## Run Instructions
```bash
jupyter notebook digit-recongnizer.ipynb
```
