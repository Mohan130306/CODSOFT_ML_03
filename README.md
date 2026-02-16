<<<<<<< HEAD
# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn prediction is a crucial task for subscription-based businesses, as retaining existing customers is often more cost-effective than acquiring new ones. This project aims to build a **machine learning model** that predicts whether a customer will **churn (exit)** or **remain** with the company using historical customer data.

Multiple machine learning algorithms were trained and evaluated to identify the most effective model for predicting customer churn.

---

## 🎯 Objectives
- Analyze customer demographic and account data
- Perform data preprocessing and feature engineering
- Encode categorical variables into numerical format
- Train and evaluate different machine learning models
- Compare model performance and draw conclusions

---

## 📂 Dataset Description
The dataset contains historical data of customers from a subscription-based service.

### 🔑 Features
- **Customer Information**:  
  `CreditScore`, `Age`, `Gender`, `Geography`
- **Account & Usage Details**:  
  `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`

### 🚫 Removed Identifier Columns
- `RowNumber`
- `CustomerId`
- `Surname`  
(These do not contribute to churn prediction.)

### 🎯 Target Variable
- **`Exited`**
  - `0` → Customer stayed
  - `1` → Customer churned

⚠️ The dataset is **imbalanced**, which reflects real-world churn scenarios.

---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
- **Tools**:
  - VS Code
  - Jupyter Notebook
  - Python Virtual Environment (venv)

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Loaded the dataset using pandas
- Inspected data structure and target distribution

### 2️⃣ Data Preprocessing
- Dropped identifier columns
- Encoded categorical features such as `Gender` and `Geography`
- Validated data types and feature consistency

### 3️⃣ Feature & Target Separation
- Features (`X`) and target variable (`y`) were separated
- Dataset was split into training and testing sets

---

## 🤖 Machine Learning Models Implemented

### 🔹 Logistic Regression
- Used as a baseline classification model
- Simple and interpretable

### 🔹 Random Forest Classifier
- Ensemble-based model
- Captures non-linear relationships
- Performs better than baseline

### 🔹 Gradient Boosting Classifier
- Boosting-based ensemble technique
- Achieved the best overall performance

---

## 📊 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

Special attention was given to predicting the churn class accurately.

---

## 🏆 Results & Conclusion
- All three models were successfully trained and evaluated
- Ensemble models outperformed Logistic Regression
- **Gradient Boosting / Random Forest** achieved the best performance
- Proper preprocessing and feature handling significantly improved results

This project demonstrates a complete end-to-end machine learning workflow for customer churn prediction.

---

## 📁 Project Structure
=======
# CODSOFT_ML_03
>>>>>>> db9be95bea5c7fc2b8f60efb9f0ef5011a4825e6
