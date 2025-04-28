# CNNs with Keras

This repository contains a Jupyter notebook demonstrating the implementation of Convolutional Neural Networks (CNNs) using Keras with TensorFlow backend.

## Overview

The notebook `CNNs_with_Keras.ipynb` walks through the process of:
- Setting up the environment
- Loading and preprocessing the ETH-80 dataset
- Building a CNN model architecture
- Training the model
- Visualizing the results using TensorBoard

## Dataset

The notebook uses the ETH-80 dataset, which contains images of 8 categories:
- Apple
- Cow
- Cup
- Dog
- Horse
- Pear
- Tomato
- Car

The dataset is split into training and validation sets with images of various angles and orientations.

## Requirements

- TensorFlow
- Keras
- TensorBoardColab
- NumPy
- PIL (Python Imaging Library)

## Running the Notebook

1. Ensure all dependencies are installed
2. Download the ETH-80 dataset from the provided link
3. Run the cells in sequential order

## Model Architecture

The notebook implements a Convolutional Neural Network with:
- Multiple convolutional layers
- Max pooling layers
- Dense layers with appropriate activation functions
- The model is trained for 50 epochs with a batch size of 32

## Visualization

TensorBoard is used to visualize the training process and model performance metrics.
