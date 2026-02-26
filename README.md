## Project Title

Heart Attack Risk Prediction using Machine Learning

---

## Overview

This project builds an end-to-end machine learning pipeline to predict cardiovascular risk using demographic, clinical, and lifestyle data.

The goal is to identify high-risk individuals early and support preventive healthcare decisions.

---

## Dataset

* 8,763 patient records
* 26 features
* Binary classification problem

Target:
Heart Attack Risk (Low / High)

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Training
5. Hyperparameter Tuning
6. Performance Evaluation
7. Explainability using SHAP

---

## Models Used

* Decision Tree
* Random Forest
* Gradient Boosting
* LightGBM
* CatBoost
* XGBoost

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Cross Validation

---

## Best Model

Gradient Boosting (Tuned)

* ROC-AUC: 0.532
* Recall: 19.75%

Chosen due to better identification of high-risk patients.

---

## Key Insights

* Exercise levels are the strongest predictor
* Sedentary behavior significantly increases risk
* Lifestyle factors outweigh age
* Income indirectly influences health outcomes

---

## Explainability

SHAP was used to interpret individual predictions and understand contributing risk factors.

---

## Tech Stack

Python
Scikit-Learn
XGBoost
LightGBM
CatBoost
SHAP
Matplotlib
Seaborn

---

## Outcome

Developed a medically interpretable ML system capable of identifying cardiovascular risk patterns in high-risk populations.

---

