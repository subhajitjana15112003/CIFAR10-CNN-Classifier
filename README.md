# CIFAR10-CNN-Classifier
A deep learning project using PyTorch and CNN architecture to classify images from the CIFAR-10 dataset with training and evaluation support.
# CIFAR-10 CNN Image Classifier

This project implements a Convolutional Neural Network (CNN) using PyTorch for image classification on the CIFAR-10 dataset.

## Features
- CNN built using PyTorch
- CIFAR-10 dataset
- Training and evaluation pipeline
- Accuracy calculation

## Technologies Used
- Python
- PyTorch
- Torchvision

## Dataset
CIFAR-10 contains 60,000 32x32 color images in 10 classes.

## Model Architecture
- Conv2D -> ReLU -> MaxPool
- Conv2D -> ReLU -> MaxPool
- Conv2D -> ReLU -> MaxPool
- Fully Connected Layers

## Installation

```bash
pip install -r requirements.txt
```

## Run Project

```bash
python train.py
```

## Output
- Training Loss
- Test Accuracy

## Future Improvements
- Add Dropout
- Add Batch Normalization
- Use GPU Training
- Hyperparameter Tuning

