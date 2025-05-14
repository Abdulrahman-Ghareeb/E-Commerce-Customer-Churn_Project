# 🛍️ E-Commerce Customer Churn Analysis

An end-to-end machine learning project to analyze and predict customer churn in an e-commerce environment. It leverages data science to identify high-risk customers and uncover actionable insights for improving customer retention.

---

## 📌 Objective

To develop a predictive model that accurately identifies customers at risk of churning. The goal is to empower marketing and support teams with data-driven insights for proactive intervention.

---

## 📊 Key Features

- 📥 **Data Handling**: Missing value imputation (KNN), outlier treatment, and SMOTE oversampling.
- 📊 **EDA & Visualization**: Insightful charts and distribution analysis using Seaborn, Plotly, and Matplotlib.
- 🧠 **Feature Engineering**:
  - Feature selection via RFE, PCA, Chi-square, and SelectKBest.
  - Categorical encoding with OneHot, Binary, and Ordinal methods.
- 🤖 **Modeling Approaches**:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - CatBoost Classifier
  - XGBoost Classifier
- 🧪 **Evaluation Metrics**: Accuracy, ROC-AUC, Confusion Matrix, Classification Report.
- 🛠️ **Hyperparameter Tuning** with GridSearchCV.
- 💾 **Model Saving** using `joblib`.

---

## 📈 Results

**Best Model: Support Vector Machine (RBF Kernel)**  
**Accuracy:** 97%  
**F1-Score:** 97%  
**ROC-AUC Score:** 99%

The SVM model demonstrated exceptional performance, with near-perfect training accuracy and excellent generalization on the test set. It outperformed other models including XGBoost, Random Forest, and CatBoost in terms of ROC-AUC and F1-Score.

---
