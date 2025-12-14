# User Churn Prediction Using LightGBM & CatBoost

Predicting customer churn is a critical business problem where the objective is to identify users who are likely to stop using a service. This project builds a robust **end-to-end churn prediction pipeline** using **tree-based gradient boosting models**, with a strong focus on **business-oriented evaluation metrics** and **model interpretability**.

---

##  Project Highlights

- End-to-end **machine learning pipeline** for churn prediction
- Advanced models: **LightGBM** and **CatBoost**
- Business-focused evaluation beyond accuracy (ROC-AUC, PR-AUC, MCC)
- Handles **class imbalance** effectively
- Model explainability using **SHAP**
- Production-ready, modular, and reproducible code

---

##  Dataset

**Dataset:** Telco Customer Churn  
**Source:** Kaggle / Public Telecom Dataset  

### Key Characteristics
- Customer demographics
- Subscription details
- Service usage patterns
- Billing and contract information
- Binary target variable: **Churn (Yes / No)**

---

##  Problem Statement

> *Can we predict whether a customer will churn based on historical usage and subscription data?*

Churn prediction helps businesses:
- Reduce revenue loss
- Design targeted retention strategies
- Improve customer lifetime value (CLV)

---

##  Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**
  - NumPy, Pandas
  - Scikit-learn
  - LightGBM
  - CatBoost
  - SHAP
  - Matplotlib, Seaborn

---

##  Workflow

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling (where required)

2. **Feature Engineering**
   - Contract-based features
   - Tenure-related patterns
   - Usage intensity indicators

3. **Model Training**
   - Logistic Regression (baseline)
   - LightGBM
   - CatBoost

4. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - ROC-AUC
   - PR-AUC
   - Matthews Correlation Coefficient (MCC)

5. **Explainability**
   - SHAP value analysis
   - Feature importance interpretation

---

##  Model Performance

### LightGBM
- Accuracy: **0.7555**
- Precision: **0.5342**
- Recall: **0.6257**
- F1-Score: **0.5764**
- ROC-AUC: **0.8109**
- PR-AUC: **0.6021**
- MCC: **0.4085**

### CatBoost
- Accuracy: **0.7505**
- Precision: **0.5216**
- Recall: **0.7433**
- F1-Score: **0.6130**
- ROC-AUC: **0.8246**
- PR-AUC: **0.6350**
- MCC: **0.4521**

 **Observation:**  
CatBoost shows stronger **recall, PR-AUC, and MCC**, making it more suitable for churn-sensitive business use cases where **missing a churner is costly**.

---

## Model Interpretability (SHAP)

- Identifies **key churn drivers**
- Explains **individual predictions**
- Improves trust for business stakeholders
- Enables actionable insights for retention teams

---
