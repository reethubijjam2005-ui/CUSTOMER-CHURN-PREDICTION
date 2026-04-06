# Customer Churn Prediction Using Machine Learning

## Project Overview
Customer churn prediction is an important business problem where the goal is to identify customers who are likely to leave a service or business.  
This project uses machine learning techniques to analyze customer data and predict churn based on customer demographics and behavior.

## Objective
The main objective of this project is to build a predictive model that can help businesses identify customers at risk of churning and take proactive steps to retain them.

## Dataset
The dataset used in this project is downloaded from Kaggle using `kagglehub`.

**Dataset Source:**  
https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

## Features Used
The dataset includes features such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

**Target Variable:**  
- `Exited` (1 = Churned, 0 = Not Churned)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

## Machine Learning Models Used
The following models were implemented and compared:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Project Workflow
1. Download dataset using KaggleHub
2. Load and inspect the dataset
3. Perform data cleaning and preprocessing
4. Encode categorical variables
5. Split the data into training and testing sets
6. Scale the features where necessary
7. Train multiple machine learning models
8. Evaluate model performance
9. Compare results and identify the best model

## Evaluation Metrics
The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

## Results
The machine learning models were able to predict customer churn with good accuracy.  
Among the tested models, the best-performing model can be selected based on ROC-AUC and accuracy scores.

## How to Run the Project

### Step 1: Install Required Libraries
```bash
pip install kagglehub pandas numpy matplotlib seaborn scikit-learn
