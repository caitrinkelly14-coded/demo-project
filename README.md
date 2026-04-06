# 🏥 Predicting Healthcare Staff Attrition

**ISOM 835: Predictive Analytics & Machine Learning - Term Project**

## 📌 Project Overview
Turnover in the healthcare sector creates significant financial and operational burdens, directly impacting patient care. This project applies an end-to-end predictive analytics pipeline to a dataset of 1,676 healthcare professionals to predict the likelihood of employee attrition. By identifying at-risk employees early and understanding the core drivers of burnout, HR can implement targeted retention strategies.

**[View the Interactive Portfolio Website Here](https://caitrinkelly14-coded.github.io/demo-project/)**

## 🎯 Objectives
1. **Identify Retention Drivers:** Determine which factors (e.g., Overtime, Monthly Income, Distance from Home) most strongly influence staff turnover.
2. **Departmental Risk Analysis:** Assess turnover risk across Maternity, Cardiology, and Neurology departments.
3. **Predictive Modeling:** Build and evaluate machine learning models to accurately classify high-risk employees.
4. **Algorithmic Interpretability:** Utilize SHAP (Shapley Additive exPlanations) values to ensure the model's predictions are transparent and free from hidden demographic biases.

## 📊 The Dataset
* **Source:** Modified Watson Healthcare Employee Attrition Dataset
* **Instances:** 1,676 employees
* **Features:** 35 variables (including Age, Department, Job Satisfaction, OverTime, and Attrition)
* **Target Variable:** `Attrition` (Yes/No) - *Note: Imbalanced class with an 11.8% baseline attrition rate.*

## 🛠️ Tools & Libraries Used
* **Environment:** Google Colab / Jupyter Notebook
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **Visualizations:** `matplotlib`, `seaborn`, `shap`

## 🚀 How to View the Code
The complete data exploration, preprocessing, and modeling pipeline is hosted on Google Colab. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](INSERT_YOUR_COLAB_LINK_HERE)

*(Instructions: Click the badge above to open the notebook. You can run the cells directly in your browser without installing any local software.)*

## 📁 Repository Structure
```text
├── data/
│   ├── watson_healthcare_modified.csv
│   └── watson_shap_values_for_testset.csv
├── notebooks/
│   └── ISOM835_Healthcare_Attrition.ipynb
├── assets/
│   └── shap_summary_plot.png
├── index.html        <- Portfolio Website Code
├── README.md         <- Project Documentation
└── .gitignore
