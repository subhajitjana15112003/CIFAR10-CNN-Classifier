# CIFAR10-CNN-Classifier
A deep learning project using PyTorch and CNN architecture to classify images from the CIFAR-10 dataset with training and evaluation support.

## Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

The model is trained on colored images and performs multi-class image classification using deep learning techniques.

---

## Objective

The main objective of this project is to:

- preprocess image datasets
- build a CNN deep learning model
- classify images accurately
- understand CNN implementation using PyTorch
- learn image classification workflow

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Jupyter Notebook

---

## Dataset Information

### Dataset:
CIFAR-10 Dataset

The dataset contains 60,000 colored images divided into 10 classes.

### Image Size
- 32 × 32 RGB Images

### Classes
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Deep Learning Workflow

### 1. Data Preprocessing

- Dataset loading using Torchvision
- Image transformation using transforms
- Image normalization
- Train-test splitting
- DataLoader implementation

---

### 2. CNN Architecture

The Convolutional Neural Network contains:

#### Convolution Block 1
- Conv2D → 32 Filters
- ReLU Activation
- MaxPooling

#### Convolution Block 2
- Conv2D → 64 Filters
- ReLU Activation
- MaxPooling

#### Convolution Block 3
- Conv2D → 128 Filters
- ReLU Activation
- MaxPooling

#### Fully Connected Layers
- Linear Layer → 256 Neurons
- ReLU Activation
- Output Layer → 10 Classes

---

### 3. Model Training

- Loss Function: CrossEntropyLoss
- Optimizer: Adam Optimizer
- Framework: PyTorch
- Epochs: 10

---

## Project Structure

```bash
CIFAR10-CNN-Classifier/
│
├── train.py
├── README.md
├── requirements.txt
├── .gitignore
├── saved_model.pth
└── data/
```

---

## Features

- Image normalization
- CNN model implementation
- Multi-class image classification
- Training and evaluation pipeline
- Accuracy calculation
- PyTorch-based deep learning workflow

---

## Output

The model outputs:

- Training Loss
- Classification Accuracy

## Future Improvements

- Add Dropout Layers
- Add Batch Normalization
- GPU/CUDA Training
- Data Augmentation
- Hyperparameter Tuning
- Transfer Learning
- Streamlit Deployment

---

## Learning Outcomes

Through this project, I learned:

- Fundamentals of CNN
- Image preprocessing techniques
- Deep learning workflow
- PyTorch implementation
- Forward and backward propagation
- Model evaluation techniques

---

## Author

Subhajít Jana  
B.Tech AI & ML Student

