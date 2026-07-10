
# OCTMNIST Classification with PyTorch

This repository contains my Assignment 0 – Part III work for a deep learning course.  
It implements a convolutional neural network (CNN) for OCTMNIST classification using PyTorch.

## Contents

- `medical-imaging-cnn-dl.ipynb`  
  Implements:
  - Loading the OCTMNIST dataset via MedMNIST
  - Dataset statistics and exploratory analysis
  - Visualizations of sample images and class distribution
  - Preprocessing and normalization
  - Optional handling of class imbalance (e.g., weighted loss or augmentation)
  - Train/validation/test split
  - CNN/FCNN model with at least three layers
  - Training and validation loops with loss and accuracy tracking
  - Test evaluation (accuracy, precision, recall, F1)
  - Plots comparing training/validation/test loss and accuracy

## Environment & Dependencies

- Python 3.8+
- PyTorch and TorchVision
- MedMNIST
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook or JupyterLab

Example setup:

```bash

pip install torch torchvision medmnist numpy matplotlib scikit-learn jupyter
