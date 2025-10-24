# Flexisaf-internship-deliverable1-Advance-machine-techniques-
# Flexisaf Internship Assignment – Advanced Machine Learning Techniques

This repository contains my internship deliverable for Flexisaf, focused on applying and demonstrating advanced machine learning techniques using the Breast Cancer Wisconsin Diagnostic Dataset.

## 📌 Objective
To train and evaluate two machine learning models that showcase advanced concepts covered in the Microsoft Learn path on machine learning. The models are designed to classify tumors as **malignant** or **benign**.

## 🧠 Models Implemented

### 1. Random Forest Classifier
- Ensemble method using multiple decision trees
- No feature scaling required
- Evaluated using confusion matrix and classification report
- Feature importance analysis included

### 2. Logistic Regression
- Linear model for binary classification
- Requires feature scaling
- Evaluated using ROC curve and AUC score
- Probability-based interpretation

## 📊 Dataset
- **Source**: `sklearn.datasets.load_breast_cancer`
- **Features**: 30 numerical attributes derived from digitized images of breast mass samples
- **Target**: Binary classification – Malignant (0) or Benign (1)

## 📁 Files
- `Model1_RandomForest_BreastCancer.ipynb`: Implementation and evaluation of Random Forest
- `Model2_LogisticRegression_BreastCancer.ipynb`: Implementation and evaluation of Logistic Regression

## 📝 Summary
This project demonstrates how different machine learning models approach the same classification task. Random Forest offers robustness and feature insights, while Logistic Regression provides interpretability and probability-based evaluation. Both models were trained, tested, and analyzed to highlight their strengths and limitations.


