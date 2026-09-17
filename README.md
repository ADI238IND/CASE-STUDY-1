# CASE-STUDY-1
# Hospital Readmission Prediction

A machine learning case study for predicting whether a patient will be readmitted within 30 days.

## Problem Statement

Predict 30-day hospital readmission risk using patient and hospitalization information with Logistic Regression and L2 regularization.

## Dataset

- Source: Kaggle
- Dataset: Hospital Readmission Prediction (Synthetic Dataset)
- Records: 30,000
- Type: Synthetic dataset
- Target: `readmitted_30_days`

Target values:

- `Yes` → 1
- `No` → 0

### Features Used

- Age
- Gender
- Blood Pressure
- Cholesterol
- BMI
- Diabetes
- Hypertension
- Medication Count
- Length of Stay
- Discharge Destination

Kaggle dataset:

https://www.kaggle.com/datasets/siddharth0935/hospital-readmission-predictionsynthetic-dataset

## Machine Learning Workflow

```text
Dataset
   ↓
EDA
   ↓
Data Preparation
   ↓
Train/Test Split
   ↓
Feature Scaling
   ↓
One-Hot Encoding
   ↓
Logistic Regression
   ↓
L2 Regularization
   ↓
Class Weight Balancing
   ↓
Model Evaluation
   ↓
Prediction CSV

