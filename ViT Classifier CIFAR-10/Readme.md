# 🤖 ViT Classifier on CIFAR-10

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

This project demonstrates the implementation of a Vision Transformer (ViT) model for image classification on the CIFAR-10 dataset using TensorFlow and Keras. Vision Transformers, originally introduced in the paper "An Image is Worth 16x16 Words", have shown strong performance on image recognition tasks by applying Transformer architectures directly to sequences of image patches.

---

## 🧠 **Model Architecture**

- **Model Type**: Vision Transformer (ViT)
- **Dataset**: CIFAR-10 (60,000 32x32 color images in 10 classes)
- **Libraries Used**:
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib
  - sklearn (for evaluation metrics)

---

## 🛠 **Features**

- ✨ Converts input images into patches
- 🎯 Embeds the patches and adds positional encodings
- 🧠 Utilizes multi-head self-attention and feed-forward layers
- 📊 Trains the transformer model on CIFAR-10
- 📈 Evaluates accuracy and visualizes predictions

---

## 📦 **Installation**

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

---

## 🚀 **How to Run**

1. Open the `Vit.ipynb` notebook
2. Run each cell in order to:
   - Load and preprocess the CIFAR-10 dataset
   - Build the ViT model
   - Train and evaluate the model
   - Visualize predictions

---

## 📊 **Results**

The model is evaluated using classification metrics and confusion matrix. Accuracy and loss graphs are plotted for visual interpretation of model performance.

---

## 📁 **Project Structure**

```
📂 ViT CIFAR-10 Project
├── 📓 Vit.ipynb              # Main notebook for training and evaluating the ViT model
├── 📊 Data/                  # CIFAR-10 dataset (auto-downloaded)
├── 📈 Plots/                 # Generated visualization outputs
└── 📝 README.md             # Project documentation
```

---

## 👨‍💻 **Author**

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bavish007) **[M. Bavish Reddy](https://github.com/bavish007)**

</div>

---

## 📜 **License**

This project is licensed under the **MIT License**.

Copyright (c) 2024 **[M. Bavish Reddy](https://github.com/bavish007)**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
