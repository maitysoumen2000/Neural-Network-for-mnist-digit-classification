# Neural Network for MNIST Digit Classification

## Overview
This Python script implements a **fully connected neural network** for classifying digits from the MNIST dataset. The program uses a simple feedforward neural network architecture, trains the model on different train-test splits, and evaluates the performance using metrics like accuracy and confusion matrix.

---

## Features

1. **MNIST Dataset Handling**:
   - Loads the MNIST dataset from a CSV file.
   - Normalizes pixel values and reshapes the images for visualization and training.
   - Supports one-hot encoding of labels for multi-class classification.

2. **Neural Network Implementation**:
   - Four-layer fully connected neural network.
   - Activation functions:
     - `Sigmoid` for hidden layers.
     - `Softmax` for the output layer.
   - Cross-entropy loss function for training.

3. **Training and Evaluation**:
   - Supports configurable train-test splits (70:30, 80:20, and 90:10).
   - Tracks training loss and accuracy across epochs.
   - Generates a confusion matrix and accuracy score for test data.

4. **Visualization**:
   - Displays sample MNIST images.
   - Plots training loss and accuracy over epochs.
   - Visualizes the confusion matrix.

---

## Neural Network Architecture

- **Input Layer**: 784 neurons (28x28 pixels).
- **Hidden Layers**:
  - Layer 1: 128 neurons.
  - Layer 2: 64 neurons.
  - Layer 3: 32 neurons.
- **Output Layer**: 10 neurons (digits 0–9).

---

## Dependencies

Ensure the following libraries are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

Install missing dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
