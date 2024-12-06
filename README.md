# Image Classification Using Neural Network

## Overview

This project implements image classification using a neural network with the **Fashion MNIST** dataset. The dataset contains 60,000 training images and 10,000 test images of 28x28 grayscale fashion items across 10 categories. The goal is to train a model that accurately classifies the images into their respective categories.

## Key Features

- **Data Normalization**: Preprocessing the data to improve model convergence.
- **Neural Network Architecture**:
  - Flatten layer for input.
  - Fully connected layers with ReLU activation.
  - Dropout for regularization.
  - Softmax for multi-class classification.
- **Model Evaluation**: Includes accuracy score, confusion matrix, and classification report.
- **Visualization**: Heatmap of the confusion matrix for better understanding of classification results.

## Dataset

The **Fashion MNIST** dataset includes the following categories:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Requirements

Install the following Python packages to run the project:
- `tensorflow`
- `keras`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the dependencies using:
```bash
pip install tensorflow keras numpy scikit-learn matplotlib seaborn
