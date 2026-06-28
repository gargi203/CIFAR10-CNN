# 🖼️ CIFAR-10 Image Classification using Convolutional Neural Networks (CNN)

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge\&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.21-orange?style=for-the-badge\&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=for-the-badge\&logo=keras)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge\&logo=jupyter)

---

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** from scratch using **TensorFlow/Keras** for image classification on the **CIFAR-10** dataset.

The model is trained to classify images into one of **10 object categories** and demonstrates the effectiveness of deep learning techniques such as:

* Batch Normalization
* Dropout
* Data Augmentation
* Early Stopping
* Model Checkpointing

The final model achieved a **Validation Accuracy of 86.22%**.

---

## 📂 Dataset

The project uses the **CIFAR-10** dataset, consisting of **60,000 RGB images**.

* Training Images: **50,000**
* Testing Images: **10,000**
* Image Size: **32 × 32 pixels**
* Number of Classes: **10**

### Classes

* ✈️ Airplane
* 🚗 Automobile
* 🐦 Bird
* 🐱 Cat
* 🦌 Deer
* 🐶 Dog
* 🐸 Frog
* 🐴 Horse
* 🚢 Ship
* 🚚 Truck

---

## 🧠 CNN Architecture

Input (32 × 32 × 3)

↓

Conv2D (32 Filters)

↓

Batch Normalization

↓

Conv2D (32 Filters)

↓

MaxPooling

↓

Dropout

↓

Conv2D (64 Filters)

↓

Batch Normalization

↓

Conv2D (64 Filters)

↓

MaxPooling

↓

Dropout

↓

Conv2D (128 Filters)

↓

Batch Normalization

↓

Conv2D (128 Filters)

↓

MaxPooling

↓

Dropout

↓

Flatten

↓

Dense (256)

↓

Dropout

↓

Output Layer (Softmax – 10 Classes)

---

## 📈 Model Performance

| Metric              | Value                           |
| ------------------- | ------------------------------- |
| Validation Accuracy | **86.22%**                      |
| Optimizer           | Adam                            |
| Loss Function       | Sparse Categorical Crossentropy |
| Framework           | TensorFlow / Keras              |

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* SciPy
* Scikit-learn
* Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```text
CIFAR10-CNN/
│
├── data/
├── images/
├── models/
│   └── cifar10_cnn_86.keras
│
├── results/
├── src/
│
├── CIFAR10_CNN_86_Percent.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/CIFAR10-CNN.git
```

Move into the project directory

```bash
cd CIFAR10-CNN
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

### macOS/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
CIFAR10_CNN_86_Percent.ipynb
```

Run all cells to train and evaluate the CNN.

---

## 📊 Future Improvements

* Transfer Learning using EfficientNetB0
* ResNet50 Implementation
* Hyperparameter Optimization
* TensorBoard Integration
* Model Deployment using Streamlit
* Real-time Image Prediction


---

## ⭐ If you found this project useful

Please consider giving the repository a ⭐ on GitHub.
