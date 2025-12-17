# Explainable-AI-Framework-for-Trust-Prediction-in-Financial-Advisory-Systems
End-to-end machine learning framework for predicting consumer trust in AI-based fintech advisory systems using behavioural data and explainable models.



## Overview
This repository contains the complete implementation of a machine learning framework for **predicting and analysing consumer trust** in AI-based financial advisory (fintech) systems.  
Trust is modelled as a **behavioural, data-driven outcome**, derived from real user interaction patterns rather than survey-based perceptions.

The project follows an **end-to-end, reproducible pipeline** covering data preprocessing, feature engineering, supervised learning, model evaluation, and explainable AI analysis.

---

## Research Objective
The primary goals of this project are to:

- Predict consumer trust in AI-driven financial advisory platforms  
- Identify behavioural and engagement-based trust drivers  
- Compare multiple supervised machine learning models  
- Explain model decisions using explainable AI techniques  

Trust is treated as a **computational variable**, not a subjective perception.

---

## Dataset
- **Source:** Public Kaggle Fintech Users Dataset  
- **Records:** 26,542 (after duplicate removal and cleaning)  
- **Features:**  
  - Demographic attributes  
  - Financial behaviour indicators  
  - Platform and engagement metrics  
- **Target Variable:** Binary trust label (Trusted / Not Trusted), engineered from behavioural data  

No personally identifiable information (PII) is used.

---

## Methodology
The project implements a structured machine learning pipeline:

1. Data loading and exploratory analysis  
2. Data cleaning and duplicate removal  
3. Missing value analysis and imputation  
4. Trust target variable construction  
5. Feature engineering and preprocessing  
6. Stratified train–test split  
7. Model training and benchmarking  
8. Model evaluation using multiple metrics  
9. Explainable AI analysis (global and local)  
10. Prediction confidence and reliability analysis  

All evaluations are performed on a held-out test dataset.

---

## Machine Learning Models
The following models are implemented and compared:

- Logistic Regression (baseline)
- Support Vector Machine (Linear)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- CatBoost

**Best-performing models:**  
- **XGBoost**
- **CatBoost**

These models demonstrate superior performance on heterogeneous fintech data and strong recall for trusted users.

---

## Explainable AI
Explainability is a core component of this project.

- **Framework:** SHAP (SHapley Additive exPlanations)
- **Global explanations:** Identify system-level trust drivers
- **Local explanations:** Explain individual trust predictions

Explainability is used as an **analytical tool**, not merely for compliance.

---

## Key Findings
- Trust is primarily driven by **behavioural and engagement variables**
- Financial incentives and sustained activity strongly influence trust
- Churn shows a near-perfect negative association with trust
- Boosted ensemble models outperform linear and tree-based models
- Explainable AI provides clear and actionable insights into trust formation

---
