# 🌸 Flower Classification using CNN & Transfer Learning

This project builds a deep learning model to classify flower images into multiple categories using a real-world dataset. It demonstrates both a custom Convolutional Neural Network (CNN) and a transfer learning approach using **MobileNetV2** to achieve higher accuracy.

## 📌 Problem Statement

The objective is to classify images of flowers into predefined categories by building an image classification model. The dataset consists of real-world images with varying lighting, background, and orientation conditions, making it a challenging multi-class classification task.

---

## 🧠 Models Used

### 1. **Custom CNN**
- Designed a CNN architecture with convolutional, max-pooling, dropout, and dense layers.
- Applied regularization techniques including dropout, early stopping, and batch normalization.
- Achieved validation accuracy of **68%** after tuning and augmentation.

### 2. **Transfer Learning (MobileNetV2)**
- Utilized pretrained **MobileNetV2** from TensorFlow Keras Applications.
- Fine-tuned the model on our flower dataset.
- Achieved validation accuracy of **88%**.

---

## ⚙️ Techniques Applied

- Image preprocessing: resizing, normalization.
- Data augmentation: random flips, zooms, rotations.
- Stratified train-validation split for balanced class distribution.
- Callbacks: EarlyStopping and ModelCheckpoint.
- Dropout and layer-wise tuning for regularization.
- Transfer learning using MobileNetV2.

---

## 📊 Results

| Model         | Validation Accuracy |
|---------------|---------------------|
| Baseline CNN  | 42%                 |
| Tuned CNN     | 68%                 |
| MobileNetV2   | **88%**             |

---


## 🛠️ Tech Stack

- Python 3
- TensorFlow / Keras
- NumPy, Matplotlib
- Google Colab (for training)

---



