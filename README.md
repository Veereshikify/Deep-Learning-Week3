# 👕 Deep Learning – Week 3: Computer Vision & CNNs

This repository contains my **Week 3 Deep Learning Assignment and Mini Project**, implemented using Python and PyTorch.

The main focus is understanding Convolutional Neural Networks (CNNs) and applying deep learning techniques to image classification using the Fashion-MNIST dataset.

## 📚 Topics Covered

- Images as tensors
- Convolution and filters
- Padding and pooling
- CNN architecture
- Image normalization
- PyTorch datasets and DataLoaders
- ANN vs CNN comparison
- Model evaluation and error analysis

## 📝 Assignment 3 – Build and Evaluate a CNN

**Notebook:** `CNN_Assignment_3.ipynb`

### Work Completed
- Loaded and visualized Fashion-MNIST images.
- Built a fully connected neural network (ANN).
- Built a Convolutional Neural Network (CNN).
- Compared ANN and CNN performance.
- Plotted training and validation curves.
- Examined five misclassified images.

### Model Performance

| Model | Test Accuracy |
|---|---:|
| ANN | 87.34% |
| CNN | 90.81% |

## 🚀 Mini Project 3 – Fashion Item Recognition

**Notebook:** `Fashion_Item_Recognition.ipynb`

Built a deep learning model to classify clothing images into 10 categories using the Fashion-MNIST dataset.

### Fashion-MNIST Classes

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

### Model Architecture

**CNN:**
- Convolutional layer (32 filters)
- ReLU activation
- Max pooling
- Convolutional layer (64 filters)
- ReLU activation
- Max pooling
- Fully connected layers
- Dropout

**ANN Baseline:**
- Flatten layer
- Fully connected layers
- ReLU activation

### Model Performance

| Model | Test Accuracy |
|---|---:|
| ANN | 87.86% |
| CNN | 90.86% |

The CNN achieved approximately **3 percentage points higher accuracy** than the ANN baseline.

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab
- Fashion-MNIST

## 📂 Repository Structure

```text
Deep-Learning-Week3/
│
├── CNN_Assignment_3.ipynb
├── Fashion_Item_Recognition.ipynb
├── fashion_cnn.pth
├── fashion_ann.pth
└── README.md
```

## 💾 Saved Models

- `fashion_cnn.pth` – Trained CNN model.
- `fashion_ann.pth` – Trained ANN baseline model.

## 🎯 Learning Outcome

Through this assignment and mini project, I gained practical experience in computer vision, CNN architectures, image preprocessing, model training, performance evaluation, and comparing deep learning models.

---

**Developed as part of my Deep Learning learning journey.**

**Author:** Veeresh

**GitHub:** [Veereshikify](https://github.com/Veereshikify)
