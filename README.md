# Neural Network Implementation in Python

This repository contains a Python script that demonstrates the implementation of a basic neural network using logistic regression for binary classification. The script is designed to help beginners understand the core concepts of neural networks, including data generation, model training, and visualization of results.

## Features

- **Random Data Generation**: Generates a synthetic dataset with two features and 10,000 samples, suitable for binary classification.
- **Binary Classification**: Uses logistic regression to classify data points into two categories based on simple and complex conditions.
- **Visualization**: Plots the binary outputs and predictions to help visualize how the model is classifying the data.
- **Parameter Initialization**: Implements He and Xavier initialization methods for setting up the initial weights and biases, optimizing the neural network's learning process.
- **Learning and Prediction**: Demonstrates forward propagation, cost calculation, backpropagation, parameter updates, and accuracy assessment, offering a hands-on experience with the fundamental mechanics of neural networks.

## Usage

1. **Data Generation and Setup**: The script starts by setting a seed for reproducibility, generating random data, and defining binary labels based on specified conditions.

2. **Model Training**: It employs logistic regression to predict probabilities, classify data, and calculate loss, demonstrating how to train a simple neural network.

3. **Visualization**: After training, it visualizes the results, showing the predicted versus actual classifications, and highlights incorrect predictions.

4. **Parameter Tuning**: Explores how different learning rates affect model performance, helping users understand the importance of hyperparameter tuning in neural networks.

## Getting Started

To run the script, ensure you have Python installed along with the libraries `numpy`, `pandas`, and `matplotlib`. Clone this repository, navigate to the directory containing the script, and run:

```bash
python neural_network_script.py
