# 🦠 Breast Cancer Prediction using Machine Learning

---

## Description

This project presents a complete machine learning pipeline for **breast cancer classification**, aiming to support early detection and improve diagnostic accuracy. The system analyzes medical features extracted from tumor data to classify cases as **benign or malignant**.

By leveraging multiple machine learning algorithms and optimizing model performance, this project demonstrates how data-driven approaches can assist healthcare professionals in making more reliable decisions.

---

## 📍 Overview

This project applies supervised machine learning techniques to classify breast cancer tumors using the **Breast Cancer Wisconsin dataset**. It includes an end-to-end workflow from data preprocessing to model evaluation and deployment.

Key aspects of the project:

* Data preprocessing and feature analysis
* Model comparison across multiple algorithms
* Performance optimization using scaling and tuning
* Deployment through a simple web-based application

---

## 📊 Dataset

* **Source:** Kaggle / UCI Breast Cancer Wisconsin Dataset
* **Samples:** 569
* **Features:** 30 numerical features
* **Target Variable:**

  * `0` → Benign
  * `1` → Malignant

The dataset contains features computed from digitized images of breast tumor cells.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Flask (for web app)

---

## 🔄 Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling and transformation
4. Model training using multiple algorithms
5. Model comparison and evaluation
6. Hyperparameter tuning (SVM optimization)
7. Final model testing and validation

---

## 🤖 Model

* **Algorithms Used:**

  * Decision Tree (CART)
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)
  * Naive Bayes

* **Best Model:** Support Vector Machine (SVM)

* **Optimization:** Hyperparameter tuning with scaling

---

## 📈 Results

The optimized SVM model achieved strong classification performance:

* **Accuracy:** ~99%
* **Precision:** ~96%
* **Recall:** ~96%
* **F1 Score:** ~96%

### Confusion Matrix Insights:

* Very low false positives
* **Zero false negatives in test results**
  👉 Critical for medical diagnosis (no missed malignant cases)

---

## 📊 Key Insights

* Feature scaling significantly improved model performance
* SVM outperformed other models after standardization
* The model effectively distinguishes between benign and malignant tumors
* High recall makes the model reliable for healthcare applications

---

## 💻 Application (GUI)

A simple web application was developed using Flask to demonstrate real-world usage:

* Accepts input data (manual or file upload)
* Processes input through the trained model
* Returns prediction results (Benign / Malignant)

---
## 📈 Results

The optimized SVM model achieved:

- **Accuracy:** ~99%  
- **Precision:** ~96%  
- **Recall:** ~96%  
- **F1 Score:** ~96%  

### Confusion Matrix

<img width="786" height="341" alt="Screenshot 2026-04-16 at 4 42 51 PM" src="https://github.com/user-attachments/assets/cd9ad3f4-e8e7-4897-861a-8fbcb5010938" />


### Insights:
- Zero false negatives ✅  
- Only 1 false positive  
- High reliability for medical diagnosis  


