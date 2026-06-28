# AI-Powered Telecom Customer Churn Prediction and Retention Strategy

## Project Overview

This project develops a Machine Learning solution for predicting customer churn in the telecom industry using **CatBoost Classifier**.

The model identifies customers likely to leave the service and classifies them into **Low**, **Medium**, and **High Risk** groups, enabling targeted customer retention strategies.

---

## Problem Statement

Customer churn significantly impacts telecom company revenue.

The objective is to predict which customers are likely to churn before they leave, allowing the business to take proactive retention actions.

---

## Dataset

* Approximately **100,000 telecom customers**
* Customer demographics
* Monthly revenue
* Voice usage
* Data usage
* Device information
* Customer behavior
* Service usage
* Target Variable: **Churn**

---

## Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
CatBoost Model
        │
        ▼
Model Evaluation
        │
        ▼
Feature Importance
        │
        ▼
Risk Segmentation
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* CatBoost

---

## Model Performance

| Metric    |     Score |
| --------- | --------: |
| ROC-AUC   | **0.702** |
| Accuracy  |      ~64% |
| Precision |      ~64% |
| Recall    |      ~64% |
| F1 Score  |      ~64% |

---

## Business Results

### Customer Risk Segmentation

| Risk   | Customers | Churn Rate |
| ------ | --------: | ---------: |
| Low    |    18,595 |      8.16% |
| Medium |    65,605 |     50.94% |
| High   |    15,800 |     92.56% |

---

## Key Insights

* High-risk customers exhibit a **92.56%** churn rate.
* Customer usage decreases as churn risk increases.
* High-risk customers still generate significant revenue.
* Usage behavior is one of the strongest churn indicators.

---

## Business Recommendations

* Immediate retention campaigns for High Risk customers.
* Personalized offers for Medium Risk customers.
* Loyalty programs for Low Risk customers.
* Continuous monitoring of customer behavior.

---

## Future Improvements

* SHAP Explainability
* Hyperparameter Optimization
* Ensemble Learning
* Real-time Prediction Dashboard
* API Deployment
* Cloud Deployment

---


## Author

**N. Saisaketh**

PES University

Machine Learning | Data Science | Artificial Intelligence
