## 📌 PCA from Scratch to Machine Learning Application

This project demonstrates a complete implementation of Principal Component Analysis (PCA), starting from its mathematical foundation using NumPy and extending to practical usage in a machine learning pipeline.

---

## 🚀 Overview

Principal Component Analysis (PCA) is a widely used dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space while preserving maximum variance.

In this project, PCA is:
- Implemented manually using linear algebra concepts  
- Applied to a real dataset  
- Integrated into a classification pipeline  

---

## ⚙️ Implementation Details

### 🔹 From Scratch (NumPy)
- Data standardization  
- Covariance matrix computation  
- Eigenvalues and eigenvectors  
- Sorting principal components  
- Explained variance calculation  

### 🔹 Using Scikit-learn
- PCA transformation  
- Dimensionality reduction  
- Model training using Decision Tree classifier  

---

## 📊 Dataset

- Digits Dataset from Scikit-learn  
- 64 input features (8×8 pixel images)  
- Multi-class classification problem (digits 0–9)

---

## 📉 Key Results

- Reduced feature space from 64 to ~21 components  
- Achieved around 81% classification accuracy  
- Observed trade-off between:
  - Number of components  
  - Model performance and overfitting  

---

## 🧠 Key Learnings

- PCA identifies directions of maximum variance  
- Eigenvectors represent principal directions  
- Too many components can lead to overfitting  
- Optimal dimensionality improves generalization  

---

## 🛠️ Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📁 Project Structure

pca-from-scratch-to-ml-pipeline/
│
├── pca_from_scratch_and_application.ipynb
└── README.md

---

## 📌 Future Improvements

- Accuracy vs number of components plot  
- Comparison with other models (SVM, Logistic Regression)  
- Explained variance threshold-based selection  
- Cross-validation for better evaluation  

---

## 🎯 Motivation

This project focuses on understanding how PCA works internally, rather than just using library functions. It bridges the gap between theory and real-world machine learning applications.
