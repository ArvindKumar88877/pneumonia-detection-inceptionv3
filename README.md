# Pneumonia Detection using Transfer Learning

## Objective

This project aims to fine-tune a pre-trained **Inception-V3** model to classify chest X-ray images from the [PneumoniaMNIST](https://medmnist.com/) dataset into **normal** or **pneumonia** categories. The goal is to build a robust classifier by handling **class imbalance** and minimizing **overfitting** through careful use of data augmentation, transfer learning, and regularization techniques.

---

## Dataset

- **Name**: [PneumoniaMNIST](https://medmnist.com/)
- **Source**: Part of the MedMNIST v2 benchmark.
- **Description**: A binary classification dataset of 28×28 grayscale chest X-ray images labeled as:
  - `0`: Normal
  - `1`: Pneumonia
- **Challenge**: The dataset is significantly imbalanced — the training set contains far more pneumonia cases than normal ones, making it essential to use class weighting or other balancing strategies.

---

