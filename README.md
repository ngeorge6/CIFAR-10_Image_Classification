CIFAR-10 Image Classification with PyTorch

Overview

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using PyTorch. The model includes multiple convolutional layers with dropout, batch normalization, and ELU activations. It is trained on the training set and evaluated on the test set.

The notebook is structured to allow easy modification of model architecture, training parameters, and output saving.

Features

Uses CIFAR-10 dataset (automatically downloaded via torchvision.datasets)
Multi-layer CNN with Conv2D, MaxPooling, Dropout, and Dense layers
Training with Adam optimizer and categorical cross-entropy loss
Evaluation of model performance on test data
Option to save outputs (predictions, metrics) to data/ folder

Requirements

Python 3.10+
PyTorch (torch, torchvision, torchaudio)
pandas and numpy for output saving
CPU or GPU (optional, GPU will accelerate training if available)

Usage

Clone the repository.
Install dependencies: pip install torch torchvision torchaudio pandas numpy
Run the notebook: CIFAR10_PyTorch.ipynb
Model outputs and results will be saved to data/ folder if configured.

Dataset

CIFAR-10 dataset is automatically downloaded via PyTorch’s torchvision.datasets. No manual download is needed.

Notes

The notebook is split into segments for clarity:
Imports and hyperparameter definition
Data loading and preprocessing
Model construction
Training
Evaluation and saving outputs
