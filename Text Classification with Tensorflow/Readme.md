#   🤖 Text Classification with TensorFlow

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

This project presents a basic text classification model built with TensorFlow and Keras. It classifies text samples into predefined categories using a simple neural network and preprocessing pipeline.

---

## 📚 **Overview**

- **Dataset**: IMDB movie reviews (binary sentiment classification)
- **Model**: Embedding Layer + GlobalAveragePooling + Dense Layers
- **Libraries**:
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib

---

## 🧠 **Model Architecture**

- Texts are tokenized and converted to sequences
- Padded sequences are passed through an embedding layer
- The model uses global average pooling followed by dense layers
- Output layer with sigmoid activation for binary classification

---

## 🛠 **Features**

- ✨ **Text preprocessing** with Keras `Tokenizer`
- 🎯 **Simple yet effective** neural network for sentiment classification
- 📊 **Training and evaluation** on the IMDB dataset
- 📈 **Visualizations** of accuracy and loss

---

## 📦 **Installation**

```bash
pip install tensorflow numpy matplotlib
```

---

## 🚀 **How to Run**

1. Open `Text Classifier.ipynb`
2. Run all cells to:
   - Load and preprocess text data
   - Build and compile the model
   - Train and evaluate on IMDB dataset
   - Visualize training history

---

## 📊 **Results**

- The model achieves reasonable performance on the IMDB sentiment dataset
- Graphs show training/validation accuracy and loss

---

## 📁 **Project Structure**

```
📂 Text Classification Project
├── 📓 Text Classifier.ipynb    # Main notebook for preprocessing, training, and evaluation
├── 📊 Data/                   # Dataset files (auto-downloaded)
├── 📈 Plots/                  # Generated visualization outputs
└── 📝 README.md              # Project documentation
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
