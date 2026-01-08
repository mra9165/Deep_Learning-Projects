# 🥔 Potato Disease Classification – End-to-End Deep Learning Project

## 📌 Project Overview
Potato crops are highly susceptible to diseases that can significantly affect crop yield and quality.  
This project presents an **end-to-end deep learning–based image classification system** to detect potato leaf diseases using images collected from **Kaggle**.

The goal is to assist in **early disease detection** using computer vision and deep learning techniques.

---

## 🎯 Objectives
- Build a CNN-based image classification model
- Detect potato leaf diseases accurately
- Perform data preprocessing, training, and evaluation
- Create a scalable end-to-end ML pipeline

---

## 🏷️ Classes
The model classifies potato leaf images into:
- 🟢 **Healthy**
- 🟠 **Early Blight**
- 🔴 **Late Blight**

---

## 🗂️ Dataset
- **Source:** Kaggle
- **Type:** Image Dataset
- **Classes:** Healthy, Early Blight, Late Blight

### 📁 Dataset Structure
dataset/
│── train/
│   ├── Healthy/
│   ├── Early_Blight/
│   └── Late_Blight/
│
│── test/
│   ├── Healthy/
│   ├── Early_Blight/
│   └── Late_Blight/

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

---

## ⚙️ Project Workflow
Data Collection (Kaggle)
        ↓
Data Preprocessing
(Resizing, Normalization, Augmentation)
        ↓
Train-Test Split
        ↓
CNN Model Building
        ↓
Model Training
        ↓
Model Evaluation
(Accuracy, Loss)
        ↓
Prediction on New Images

---

## 🧠 Model Architecture
- Convolutional Neural Network (CNN)
- Convolution + ReLU Activation
- MaxPooling Layers
- Fully Connected Dense Layers
- Softmax Output Layer (3 Classes)
---
## 📊 Model Performance
- Training Accuracy: 99.19%
- Validation Accuracy: 99.48%



---
  
