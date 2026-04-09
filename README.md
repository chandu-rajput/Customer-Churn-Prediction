# Customer Churn Prediction

## 📌 Project Overview
This project focuses on predicting customer churn using multiple machine learning models. The goal is to identify customers who are likely to leave, with a strong emphasis on maximizing recall to minimize missed churn cases.

---

## 🎯 Objective
- Predict whether a customer will churn or not  
- Compare multiple ML models  
- Select the best model based on business requirements (high recall)

---

## ⚙️ Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering (tested and evaluated)  
4. Model Building  
5. Model Evaluation using ROC-AUC and Recall  
6. Final Model Selection  

---

## 🤖 Models Used
- Logistic Regression  
- Random Forest  
- SVM (Support Vector Machine)  
- XGBoost  

---


## 🏆 Final Model
**SVM (Support Vector Machine)** was selected as the final model due to its higher recall, making it more effective at identifying churn customers.
- | SVM | 0.838 | **0.804** |
---

## 🔍 Key Insights
- Recall is the most important metric for churn prediction  
- SVM performed best in detecting churn customers  
- Feature engineering (AvgCharges, TotalServices, TenureGroup) did not improve performance  
- Original features were sufficient and avoided unnecessary complexity  

---

## 📁 Dataset

You can access the dataset here:  
👉 **[Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)**

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Imbalanced-learn  

---
