# CIFAR-10 Image Classification with PyTorch

## Overview
This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using PyTorch.  
The model includes multiple convolutional layers with dropout, batch normalization, and ELU activations. It is trained on the training set and evaluated on the test set.  

The notebook is structured to allow easy modification of model architecture, training parameters, and output saving.

## Features
- Uses CIFAR-10 dataset (automatically downloaded via `torchvision.datasets`)  
- Multi-layer CNN with `Conv2D`, `MaxPooling`, `Dropout`, and Dense layers  
- Training with Adam optimizer and categorical cross-entropy loss  
- Evaluation of model performance on test data 

## Dataset
- CIFAR-10 dataset is automatically downloaded via PyTorch’s `torchvision.datasets`  
- No manual download is required  

## Requirements
- Python 3.10+  
- Libraries: `torch`, `torchvision`, `torchaudio`, `pandas`, `numpy`  
- CPU or GPU (GPU will accelerate training if available)  

Install dependencies:
```
pip install torch torchvision torchaudio pandas numpy
```

## Usage
1. Clone the repository  
2. Install dependencies  
3. Run the notebook:  
```
CIFAR10_PyTorch.ipynb
```

## Project Structure
```
project_folder
│
├── CIFAR10_PyTorch.ipynb
└── README.md
```

## Notes
- The notebook is split into segments for clarity:  
  1. Imports and hyperparameter definition  
  2. Data loading and preprocessing  
  3. Model construction  
  4. Training  
  5. Evaluation and saving outputs  
