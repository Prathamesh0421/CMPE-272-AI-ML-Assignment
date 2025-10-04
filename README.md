# CMPE-272-AI-ML-Assignment


# Assignment 2: Classification - Customer Churn Prediction

## 🎯 Objective
In this assignment, you will build a **classification model** to predict **customer churn**.  
Churn prediction is essential for businesses to identify customers at risk of leaving and take action to retain them.

---

## 📊 Datasets

### 1. [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Description:** Contains customer data from a telecommunications company, including information about services, account status, and whether the customer churned.  
- **Why this dataset?** It’s one of the most popular datasets for customer churn prediction and works well for classification problems.  
- **Key Features:**  
  - Customer tenure  
  - Monthly charges  
  - Contract type  
  - Payment method  
  - Churn label (Yes/No)  

---

### 2. [Customer Personality Analysis](https://www.kaggle.com/imakash3011/customer-personality-analysis)
- **Description:** Helps classify customers based on demographics, purchase behavior, and marketing campaign data.  
- **Use Case:** Predict which customers will respond to marketing campaigns or predict churn based on customer behavior.  
- **Key Features:**  
  - Income  
  - Education level  
  - Marital status  
  - Number of purchases  
  - Complaint counts  

---

## 📝 Instructions

### 1. Data Preprocessing
- Load the dataset using Pandas.  
- Convert categorical variables (e.g., ContractType) into numerical values using one-hot encoding.  
- Handle missing data and scale features if necessary.  
- Split the data into training and test sets (e.g., **80% training, 20% testing**).  

### 2. Train a Classification Model
- Choose a classification algorithm:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- Train the model to predict whether a customer will churn (`Churn` column).  

### 3. Model Evaluation
- Evaluate the model using metrics:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion matrix  
- Plot a **ROC curve** and calculate the **AUC score** to assess model performance.  

### 4. Analysis
- Write a short analysis explaining:  
  - How well your model performed  
  - Which features were most important in predicting churn  
  - Whether the model produced **false positives** or **false negatives**  

---

## 📂 Submission
- **Jupyter Notebook (`.ipynb`)** with code, comments, and explanations  
- **Short Report (1–2 pages)** discussing:  
  - Model performance  
  - Feature importance  
  - Recommendations for improving customer retention  

---
