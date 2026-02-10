# Customer Churn Prediction using Machine Learning

## Overview

Customer churn is a critical business problem, as losing customers directly impacts revenue and growth. The objective of this project is to build a machine learning model to predict which customers are likely to churn, enabling proactive retention strategies.

This project demonstrates an end-to-end machine learning workflow, including data cleaning, feature engineering, model training, evaluation, and interpretation.

---

## Dataset

The dataset contains customer information including:

- Demographics
- Account information
- Contract type
- Billing and payment details
- Customer tenure
- Churn status (target variable)

Target variable:
- Churn (1 = customer churned, 0 = customer retained)

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

## Machine Learning Workflow

The following steps were performed:

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Feature engineering using one-hot encoding
4. Train-test split
5. Model training using:
   - Random Forest Classifier
   - Logistic Regression (with feature scaling)
6. Model evaluation using:
   - Accuracy score
   - Confusion matrix
   - ROC curve and AUC score
7. Feature importance analysis

---

## Model Performance

Both models demonstrated strong predictive capability.

Random Forest provided the best overall performance and captured complex relationships between features.

The ROC curve showed strong classification performance, indicating the model can effectively distinguish between churn and non-churn customers.

---

## Key Insights

The most important factors influencing churn included:

- Contract type
- Customer tenure
- Monthly charges
- Total charges

Customers on shorter contracts and with higher monthly charges were more likely to churn.

---

## Business Impact

This model could be used by businesses to:

- Identify high-risk customers
- Target retention campaigns
- Reduce customer churn
- Improve revenue stability

---


