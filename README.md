# 📘 CrimeCast: Crime Category Forecasting (Kaggle Competition)

## 🚀 Project Overview
This project was developed as part of the **Kaggle CrimeCast competition**, focused on forecasting crime categories using structured historical crime data.  
The objective was to build a machine learning model that accurately predicts crime types based on temporal, spatial, and contextual features.

I secured **Rank 175 / 957** participants with an **accuracy score of 0.95320** (leaderboard highest: 0.96480).

---

## 🧰 Tech Stack & Tools
- **Python**
- **Pandas, NumPy**
- **Scikit-Learn**
- **XGBoost**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📊 Problem Statement
Given anonymized crime data with features such as **location**, **date**, **time**, and other metadata, the task is to classify each instance into one of the predefined crime categories.

---

## 🧠 Approach

### **1. Exploratory Data Analysis**
- Inspected feature distributions  
- Visualized temporal patterns  
- Checked for missing values and anomalies  

### **2. Feature Engineering**
- Extracted time-based features (hour, month, weekday, etc.)  
- Encoded categorical variables  
- Normalized numeric attributes (if required)

### **3. Model Development**
Tested multiple algorithms:
- Logistic Regression  
- Random Forest  
- XGBoost   

Used:
- Hyperparameter tuning  
- Cross-validation  
- GridSearch or RandomizedSearch  

### **4. Evaluation**
- **Primary metric:** Accuracy  
- Also evaluated confusion matrix & class-wise performance  

Final model achieved **0.95320 accuracy**, consistently performing well across categories.

🔒 *Dataset is not included in the repository as per Kaggle competition rules.*

## 🏁 Results
✔ **Rank:** 175 / 957  
✔ **Accuracy:** 0.95320  
✔ Strong generalizable performance  
✔ Effective feature engineering + boosting ensemble  
---


