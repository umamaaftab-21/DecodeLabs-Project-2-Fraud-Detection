# DecodeLabs Project 2 – Supervised Learning & Fraud Detection Pipeline

## Internship Domain

Data Science

## Project Overview

This project focuses on building a supervised machine learning pipeline to identify fraudulent transactions in a highly imbalanced dataset. The project includes data preprocessing, SMOTE-based class balancing, classification model training, hyperparameter tuning, and model evaluation using Precision, Recall, and ROC-AUC.

## Dataset

- Dataset Type: Financial Transactions
- Problem Type: Binary Classification
- Target: Fraudulent vs Non-Fraudulent Transactions
- Dataset Characteristics: Highly Imbalanced

## Key Tasks Completed

### 1. Data Preprocessing

- Inspected the dataset structure and data types
- Prepared the features and target variable
- Split the dataset into training and testing sets
- Applied appropriate preprocessing techniques

### 2. Handling Class Imbalance

- Identified class imbalance in the target variable
- Applied SMOTE (Synthetic Minority Over-sampling Technique)
- Generated synthetic samples for the minority class
- Used SMOTE only on the training data

### 3. Classification Models

Trained multiple supervised learning algorithms:

- Logistic Regression
- Random Forest Classifier

### 4. Model Evaluation

The models were evaluated using:

- Precision
- Recall
- ROC-AUC

Accuracy was not used as the primary evaluation metric because the dataset is highly imbalanced.

### 5. Hyperparameter Tuning

- Tuned the Random Forest model using hyperparameter optimization
- Compared model performance after tuning
- Evaluated the tuned model using Precision, Recall, and ROC-AUC

## Final Result

The tuned Random Forest model achieved:

- Precision: 0.5305
- Recall: 0.8878
- ROC-AUC: 0.9819

These metrics were used to evaluate the model's ability to identify fraudulent transactions while considering the class imbalance.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- SMOTE
- Logistic Regression
- Random Forest
- Jupyter Notebook
- Hyperparameter Tuning

## Project File

The complete analysis, model training, tuning, and evaluation are available in:

`Project_2_Fraud_Detection.ipynb`
