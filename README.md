# MNIST Digit Recognition using Neural Network
-------
This repository contains code for training and evaluating a neural network from scratch to recognize handwritten digits from the MNIST dataset.
------
## Overview

The main script model.ipynb demonstrates the process of:

- Pre-processing: Loading the MNIST dataset, normalizing the data, and preparing it for training and testing.
- Neural Network: Initializing the parameters, implementing forward and backward propagation, and updating the parameters.
- Training: Training the neural network on the MNIST training set.
- Evaluation: Assessing the model's performance on both training and test data, including accuracy and visualization of learning curves.
- Prediction: Visualizing the predictions of the neural network on sample images.
-------
## Usage

- Clone the Repository

- Install Dependencies: Make sure you have the necessary dependencies installed. You can install them using pip:
```
pip install numpy pandas matplotlib
```
- Run the Script: Execute the script to train the model and evaluate its performance.
-------
## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
--------
## Project Structure

mnist_nn.py: The file that contains the script for loading data, defining the neural network, training, and evaluation.
train-images.idx3-ubyte: The dataset file containing training images.
train-labels.idx1-ubyte: The dataset file containing training labels.
t10k-images.idx3-ubyte: The dataset file containing test images.
t10k-labels.idx1-ubyte: The dataset file containing test labels.
