# 🚀 Loan Default Prediction
A machine learning project to predict loan defaults, helping financial institutions assess risk effectively.

## 📌 Overview
Loan default prediction is critical in the financial sector. This project applies **classification models** to predict whether a customer will **default on a loan** based on their financial history.
https://www.kaggle.com/datasets/nikhil1e9/loan-default?utm_source=chatgpt.com

### 🔹 Key Highlights:
✅ **Data Preprocessing:** Encoding, feature selection, and scaling  
✅ **Handling Class Imbalance:** Used **SMOTE** for a balanced dataset  
✅ **Model Selection:** Compared **Logistic Regression, Random Forest, and XGBoost**  
✅ **Best Model:** **XGBoost with 90.94% accuracy and 89% recall**  

---

## 📊 Dataset
- **Total Rows:** 255,347
- **Numerical Features:** Age, Income, Loan Amount, Credit Score, etc.
- **Categorical Features:** Employment Type, Loan Purpose, Has Mortgage, etc.
- **Target Variable:** **Default (0 = No, 1 = Yes)**

---

## 📉 Data Preprocessing
✔ **Checked for missing values** (No missing data found)  
✔ **Encoded categorical variables** using **One-Hot Encoding**  
✔ **Scaled numerical features** using **MinMaxScaler**  
✔ **Balanced dataset** with **SMOTE** (88% vs. 11% → 50% vs. 50%)  

---

## 📈 Model Comparison
| Model | Accuracy | Recall (Default 1) | F1-Score |
|--------|----------|-----------------|----------|
| **Logistic Regression** | 87.3% | 86% | 87% |
| **Random Forest** | 90.8% | 86% | 90% |
| **Optimized Random Forest** | 90.9% | 86% | 90% |
| **XGBoost (Best Model)** | **90.94%** | **89%** | **91%** |

📌 **Final Model: XGBoost** → Achieved **highest recall (89%)**, meaning fewer loan defaulters were missed.

