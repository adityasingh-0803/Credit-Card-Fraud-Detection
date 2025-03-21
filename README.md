# 🚀 Credit Card Fraud Detection  

This project develops a **machine learning model** to detect fraudulent credit card transactions using the **Kaggle Credit Card Fraud Detection dataset**. It focuses on handling **class imbalance**, feature engineering, and optimizing model performance.  

---

## 📂 Dataset  

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Size:** 284,807 transactions  
- **Fraud Cases:** ~0.17% (highly imbalanced)  

---

## 🏗️ Approach  

### ✅ **Data Preprocessing**  
✔ Removed missing/duplicate values  
✔ Scaled transaction amounts  
✔ Created new features (e.g., transaction frequency, spending patterns)  

### ✅ **Handling Imbalanced Data**  
✔ Used **SMOTE (Synthetic Minority Oversampling Technique)** to balance fraud cases  

### ✅ **Model Training & Evaluation**  
✔ Models tested: **Logistic Regression, Random Forest, XGBoost**  
✔ Used **AUC-ROC, Precision-Recall, and Confusion Matrix** for evaluation  

---

## 📊 Model Performance  

- **Random Forest AUC-ROC:** ~0.95  
- **XGBoost AUC-ROC:** ~0.98  
- **False Positive Rate (FPR) reduced significantly** with feature engineering  

---

## 🛠️ Installation & Usage  

### **1️⃣ Clone Repository**  
```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```
### **2️⃣ Install Dependencies**
pip install -r requirements.txt
