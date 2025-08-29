# MNIST Classification Suite: From Linear Models to Deep Networks

## Overview
This repository contains a complete implementation of various machine learning models for classifying handwritten digits from the MNIST dataset. The project is structured to demonstrate the progression from basic linear classifiers to advanced deep learning architectures, including comprehensive hyperparameter analysis and model comparisons.

## Project Structure
- **Part A: Linear Classification Models**
  - Binary Logistic Regression (from scratch)
  - Multi-class Softmax Regression (from scratch and using PyTorch)
- **Part B: Custom Feedforward Neural Network**
  - Implementation of a flexible multi-layer perceptron (MLP)
  - Training loop with early stopping and performance tracking
- **Part C: Comprehensive Analysis**
  - Hyperparameter tuning (learning rate, batch size, architecture)
  - Model comparison (logistic vs. softmax vs. neural networks)
- **Bonus: Convolutional Neural Network (CNN)**
  - Simple CNN architecture
  - Comparison with fully connected networks
  - Regularization analysis (dropout and batch normalization)

## Key Features
- Manual implementation of loss functions and gradient updates
- Flexible neural network architecture with Xavier initialization
- Detailed visualization of training/validation curves
- Hyperparameter analysis for learning rates, batch sizes, and layer configurations
- Comparison of computational complexity and training efficiency
- Regularization techniques: dropout and batch normalization

## Requirements
- Python 3.7+
- PyTorch
- torchvision
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
