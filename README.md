# Customer Churn Prediction using XGBoost

## Overview
This project focuses on predicting customer churn using Machine Learning.  
Customer churn refers to customers leaving a service or company.  
The model is built using the **XGBoost Classifier**, which provides high accuracy and efficient performance for classification tasks.

The project helps businesses identify customers who are likely to leave, allowing them to take preventive actions.

---

# Features
- Data preprocessing and cleaning
- Handling missing values
- Feature encoding
- Exploratory Data Analysis (EDA)
- Model training using XGBoost
- Performance evaluation
- Churn prediction system
- Accuracy visualization

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

# Dataset
The dataset contains customer-related information such as:
- Customer ID
- Gender
- Tenure
- Monthly Charges
- Contract Type
- Internet Service
- Payment Method
- Total Charges
- Churn Status

Example Target Variable:
- `1` → Customer will churn
- `0` → Customer will stay

---

# Project Workflow

## 1. Data Collection
Dataset is loaded using Pandas.

## 2. Data Preprocessing
- Removing unnecessary columns
- Handling null values
- Encoding categorical features
- Feature scaling

## 3. Exploratory Data Analysis
Visualization techniques are used to analyze:
- Customer distribution
- Churn ratio
- Correlation between features

## 4. Model Training
The dataset is split into training and testing sets.

XGBoost Classifier is used for training the model.

## 5. Model Evaluation
Evaluation metrics:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

---

# XGBoost Model

The project uses the following model:

```python
from xgboost import XGBClassifier

model = XGBClassifier()
model.fit(X_train, y_train)
