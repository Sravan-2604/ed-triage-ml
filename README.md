# ED-Triage-ML  
**Comparative Study of Machine Learning Models for Emergency Department (ED) Triage**  

This repository contains the implementation of a comparative study on machine learning (ML) models for predicting triage acuity levels in adult Emergency Departments (EDs). The project emphasizes **predictive performance**, **fairness**, and **interpretability**, aligning with principles of **human-centered AI in healthcare**.  

---

## 📌 Overview
Emergency department triage is a critical decision-making process where clinicians prioritize patients under time and resource constraints. Traditional triage tools (e.g., ESI, CTAS) are often subjective and inconsistent.  
This work investigates how different ML models can improve triage prediction while ensuring fairness, transparency, and reliability.  

---

## ⚙️ Models Implemented
- **Logistic Regression** – Interpretable baseline model  
- **Random Forest** – Robust ensemble method  
- **XGBoost** – Gradient boosting for structured data  
- **Neural Network (MLP)** – Exploring deep learning potential  

---

## 📊 Evaluation Metrics
The models were compared using:  
- **Predictive Performance**: Accuracy, Precision, Recall, F1-score, AUROC  
- **Fairness**: Subgroup analysis by gender, race, and language  
- **Transparency Metrics**: Sparsity, Feature Importance Stability (FIS), SHAP explanations  
- **Calibration & Reliability**: Expected Calibration Error (ECE), Brier Score  

---

## 📂 Repository Structure
