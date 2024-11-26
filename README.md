# Telecom-churn-prediction
Machine learning project to predict customer churn in the telecom industry.
# Telecom Churn Prediction Project 📊

## 🔍 Project Overview
This project aims to predict customer churn in the telecom industry using machine learning. The goal is to identify high-value customers at risk of leaving, helping telecom companies implement proactive retention strategies.

## 🎯 Objectives
- Predict churn for high-value prepaid customers.
- Identify key factors contributing to churn.
- Provide actionable insights for reducing customer attrition.

## 📊 Data Description
The dataset contains customer-level data over four months (June to September). Key features include:
- **Call Data:** Total incoming and outgoing minutes.
- **Recharge Data:** Monthly recharge amounts.
- **Internet Usage:** 2G and 3G data consumption.

### Churn Definition
A customer is considered churned if they:
- Have no outgoing calls.
- Do not use mobile internet in the last month (September).

## 🛠️ Project Workflow
1. **Data Preprocessing:** Cleaning and filtering data, handling missing values.
2. **Exploratory Data Analysis (EDA):** Analyzing customer behavior patterns.
3. **Feature Engineering:** Creating new features based on business insights.
4. **Model Building:** Training machine learning models (Random Forest, Logistic Regression).
5. **Evaluation:** Assessing models using metrics like ROC-AUC and F1-Score.

## ⚙️ How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/telecom-churn-prediction.git
   cd telecom-churn-prediction
