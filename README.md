# Vishwani-Bodapatla-Chicago-Healthy-Schools-Certification-Prediction


# Healthy Schools Certification Prediction

This project aims to predict whether a school is **Healthy Schools Certified** based on various academic, attendance, behavioral, and climate-related indicators. The goal is to support decision-making and highlight which factors most influence certification.

## 📊 Project Overview

This project includes:
- **Data Preprocessing**
  - Handling missing values using **KNN imputation**
  - Encoding ordinal and categorical variables (e.g., school climate, ratings)
  - Creating missingness indicator flags
  - Feature scaling (standardization)

- **Imbalanced Data Handling**
  - Addressing class imbalance using **SMOTE** (Synthetic Minority Oversampling Technique)

- **Modeling**
  - Training and evaluating multiple classification models:
    - Random Forest (with GridSearchCV hyperparameter tuning)
    - Logistic Regression
    - Support Vector Machine (SVM)
    - XGBoost Classifier
  - Evaluation using:
    - **Accuracy**, **Classification Reports**
    - **Confusion Matrices**
    - **ROC Curves & AUC Scores**

## 🧠 Key Features Used

- Student & teacher attendance
- Suspension metrics
- Behavioral misconducts
- Survey-based ratings (e.g., Safe, Supportive Environment, Involved Family)
- Dropout rate
- Climate & leadership effectiveness scores

## ⚙️ Technologies & Libraries

- Python 3.x
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib, seaborn
- xgboost

## 📁 Project Structure

project/
│
├── data/ # Source datasets (not included here)
├── notebooks/ # Jupyter notebooks (EDA, modeling, tuning)
├── models/ # Saved models (optional)
├── visuals/ # Output plots (confusion matrices, ROC curves)
├── src/ # Source Python scripts (if modularized)
└── README.md # This file

