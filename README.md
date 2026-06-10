# CIFAR10 Image Classification using CNN

A Convolutional Neural Network built with PyTorch to classify 
60,000 RGB images across 10 real-world categories.

## Results
- Test Accuracy: 76.15%
- Validation Loss: 0.967

## Dataset
CIFAR10 — 60,000 images (32x32 RGB), 10 classes, ~170 MB

## Model Architecture
- Conv2d layers: transform 3-channel input → 16-channel feature maps
- MaxPool2d: halves spatial dimensions at each stage
- Fully Connected layers: final 10-class output
- Optimizer: SGD | Loss: CrossEntropyLoss | Training: GPU

## Tech Stack
Python, PyTorch, torchvision, Matplotlib, Jupyter Notebook

## Key Concepts Demonstrated
- CNN architecture design
- GPU-accelerated training
- Overfitting analysis via loss curves
- Model saving and loading
