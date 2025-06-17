# 📉 Customer Churn Prediction + MLOps Monitoring

This project predicts customer churn and simulates an end-to-end machine learning workflow—including training, inference, and monitoring—to reflect real-world MLOps practices.

## 🧠 Problem

Subscription-based businesses lose millions in revenue due to churn. This project aims to forecast which customers are at risk of churning and monitor model performance over time to ensure ongoing reliability and value.

## 🔧 Tools & Technologies

- **Python**, **pandas**, **scikit-learn**
- **Streamlit** for dashboard visualization
- **EvidentlyAI** for model monitoring (input/output drift)
- **Google Colab** for prototyping
- (Optional) **Vertex AI**, **MLflow**, **BigQuery**

## 📊 Workflow Overview

1. **EDA & Feature Engineering** – Identify key behavioral signals from customer data  
2. **Model Training** – Logistic Regression baseline, evaluated via AUC & confusion matrix  
3. **Inference Simulation** – Score mock daily batches and store results  
4. **Model Monitoring** – Detect input drift or accuracy drops using EvidentlyAI  
5. **Dashboard & Storytelling** – Present insights and business implications

## 📈 Key Results

- AUC: 0.87 (validation set)
- Top predictors: Contract Type, Monthly Charges, Tenure
- Dashboard identifies high-risk cohorts for retention targeting
- Simulated monitoring shows input drift after 30 days

## 🖼️ Screenshots

![Feature Importance](images/feature_importance.png)
![Dashboard](images/dashboard_screenshot.png)

## 🔗 Links

- [Presentation or walkthrough PDF (TBD)]()
- [Live dashboard (optional Streamlit Cloud)]()
- [Evidently monitoring report (optional)]()

---

## 📁 Project Structure

