# Batch Normalization in CNNs: Training Stability and Convergence (CIFAR-10)

##  Overview
This project investigates how Batch Normalization (BN) improves the training stability and convergence of convolutional neural networks. The study compares three models: a baseline CNN, a CNN with Batch Normalization, and a CNN combining Batch Normalization with Dropout.

The objective is not only to evaluate performance but to understand how BN changes the learning dynamics of neural networks.

---

##  Objectives
- Analyse training instability in neural networks
- Understand internal covariate shift
- Evaluate the effect of Batch Normalization on convergence speed
- Compare BN with and without Dropout
- Interpret training behaviour using visualisations

---

## 📊 Dataset
The project uses the CIFAR-10 dataset:

- 50,000 training images
- 10,000 test images
- 10 classes (airplane, car, bird, etc.)
- Image size: 32×32×3

Dataset Source:
https://www.cs.toronto.edu/~kriz/cifar.html

---

##  Models Implemented

### 1. Baseline CNN (No BN)
- Standard convolutional neural network
- Used to observe unstable training behaviour

### 2. CNN with Batch Normalization
- Batch normalization layers added after convolution layers
- Improves stability and convergence

### 3. CNN with BN + Dropout
- Combines normalization and regularisation
- Provides improved generalisation

---

##  Visualisations

The notebook generates the following plots:

1. Validation Accuracy (BN vs No BN)
2. Validation Loss (Training Stability)
3. Convergence Speed (Training Accuracy)
4. Model Comparison (BN vs BN + Dropout)

All plots use colourblind-friendly styles for accessibility.
