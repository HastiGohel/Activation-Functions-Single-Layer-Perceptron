# Activation Functions & Single Layer Perceptron (SLP)

This project demonstrates how to build and train a **Single Layer Perceptron** using TensorFlow/Keras for binary classification.  
We explore **two dataset options** and visualize common activation functions.

---

## 📂 Dataset Options

### **Option 1 – Study & Sleep Correlation Dataset**
- **Features**: Hours of Study, Sleep Hours
- **Label**: Pass (1) or Fail (0)
- Created manually for demonstration purposes.

### **Option 2 – Kaggle `StudentsPerformance` Dataset**
- **Source**: `StudentsPerformance.csv`
- **Selected Features**: Math Score, Reading Score
- **Label Rule**: Pass (1) if both scores ≥ 50, else Fail (0)

---

## 🛠 Features Implemented
- Single Layer Perceptron model using **Keras Sequential API**
- **Sigmoid** activation in output layer for binary classification
- Compilation with **Adam optimizer** & **Binary Crossentropy loss**
- Model training for 10–15 epochs
- Testing with new unseen data points
- Visualization of activation functions (**Sigmoid**, **Tanh**, **ReLU**)

---

## 📦 Requirements
Install dependencies:
```bash
pip install numpy pandas tensorflow matplotlib scikit-learn
