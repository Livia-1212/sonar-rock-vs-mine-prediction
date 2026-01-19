# SONAR Rock vs Mine Prediction

This project implements an end-to-end binary classification machine learning pipeline to classify sonar signals as **Rock (R)** or **Mine (M)**.

## Dataset
- SONAR dataset
    The dataset used in this project is the SONAR Rock vs Mine dataset, sourced from Kaggle:
    https://www.kaggle.com/code/mahmudulhaqueshawon/sonar-rock-vs-mine-prediction/input
- 208 samples
- 60 numerical features
- Binary labels: Rock vs Mine

## Problem Statement
Predict whether an object detected by sonar signals is a rock or a metal mine.

## ML Workflow
1. Data loading and exploration
2. Feature–label separation
3. Stratified train-test split
4. Feature scaling using StandardScaler
5. Model training (Logistic Regression, SVM)
6. Model evaluation (accuracy, confusion matrix)

## Tools & Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

## Results
The models achieve strong accuracy on unseen test data, demonstrating good generalization.

## Reference
Project implementation inspired by:
https://www.youtube.com/watch?v=fiz1ORTBGpY

