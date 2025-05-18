# CIFAR-10 Image Classification with CNNs

This project builds and trains a Convolutional Neural Network (CNN) to classify images from the **CIFAR-10** dataset into 10 object categories.

---

## 🧠 Goal

Develop a CNN that can correctly classify 32x32 color images across 10 categories, including airplanes, cats, trucks, and more.

---

## 📦 Dataset

- **Name:** CIFAR-10
- **Size:** 60,000 32x32 RGB images
  - 50,000 training images
  - 10,000 test images
- **Classes:** 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)

---

## 🏗️ Model Summary

- Convolution + MaxPooling layers
- Flatten + Dense layers
- Dropout for regularization
- Softmax activation on output layer
- Optimizer: Adam
- Loss: Categorical Crossentropy

---

## 🎯 Accuracy

Achieves around **70–80%** accuracy depending on training duration and tuning.

---

## 📦 Requirements

```bash
pip install tensorflow numpy matplotlib
