# Diabetes Disease Prediction using Logistic Regression

## Project Overview
This project aims to predict whether a patient has diabetes based on diagnostic health measurements. The model uses Logistic Regression, a widely accepted algorithm for binary classification, to analyze and classify patients effectively. The goal is to support early diagnosis and assist medical practitioners with data-driven decision-making.

## Table of Contents

1.Project Overview

2.Problem Statement

3.Dataset Information

4.Technologies Used

5.Workflow

6.Model Evaluation

7.Project Highlights

8.Conclusion

## Problem Statement
Diabetes is a chronic condition that affects millions of people globally. Early detection can prevent complications and reduce healthcare burdens. The aim of this project is to build a reliable prediction model to identify diabetic patients based on key medical attributes.

## Dataset Information
The dataset contains patient-level information such as:

Pregnancies

Glucose level

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Outcome (0 = No Diabetes, 1 = Has Diabetes)

There are no missing values in the dataset, and all features are numerical.

## Technologies Used
1.Python

2.Pandas, NumPy

3.Scikit-learn

4.Matplotlib, Seaborn (for visualization)

5.Jupyter Notebook / Google Colab

## Workflow
Data Exploration – Understand feature distributions and data types

Preprocessing – No categorical variables, but StandardScaler is applied

Train-Test Split – Dataset is split to avoid overfitting

Model Training – Logistic Regression is used for binary classification

Prediction – The model predicts whether a patient has diabetes

Evaluation – Accuracy, confusion matrix, and classification report are used

## Model Evaluation
Achieved an accuracy of 72%

Evaluated using confusion matrix and classification metrics

Developed a custom logic to convert prediction results into human-readable format (e.g., “Has Diabetes” or “No Diabetes”)

## Project Highlights
Built a clean and interpretable model using a simple yet effective algorithm

Implemented proper feature scaling to improve model performance

Developed a reusable prediction function for future use

Ensured no data leakage or imbalance issues during model training

## Conclusion
This project demonstrates the effectiveness of Logistic Regression in medical diagnosis problems like diabetes prediction. While simple, the model performs reasonably well and serves as a strong baseline for future improvements using more complex algorithms or ensemble techniques.
