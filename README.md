# Autoencoder with Different Optimisers

This Jupyter Notebook demonstrates the use of an autoencoder network implemented in PyTorch. The notebook includes experiments with different optimization algorithms: Stochastic Gradient Descent (SGD) with and without momentum, and RMSprop.

## Overview

An autoencoder is a type of neural network used to learn efficient representations of data, typically for dimensionality reduction or feature learning. This notebook implements a basic autoencoder with the following components:

- **Encoder**: Maps input data to a latent space representation.
- **Decoder**: Reconstructs the original input data from the latent space.
- **Loss Function**: Mean Squared Error (MSE) to measure reconstruction accuracy.
- **Optimisers**: Different optimisers are used to train the network, including SGD (with and without momentum) and RMSprop.

## Requirements

- Python 3.x
- PyTorch
- Matplotlib
- NumPy
