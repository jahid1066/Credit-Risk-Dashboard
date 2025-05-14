Credit Risk Analysis Dashboard (German Dataset)

# Project OverviewThis project is a comprehensive Credit Risk Analysis Dashboard for the German Credit dataset. It uses multiple machine learning models to assess the creditworthiness of borrowers. The primary goal is to help financial institutions make data-driven decisions on loan approvals and risk management.

# Key Features

Data preprocessing and feature engineering for accurate modeling.

Model training with Logistic Regression, Random Forest, and XGBoost.

Model evaluation using AUC-ROC, confusion matrix, and classification reports.

Interactive dashboard for exploring model performance.

# Model Performance

Model

AUC Score

Random Forest

0.828

Logistic Regression

0.816

XGBoost

0.799

Confusion Matrix (Random Forest)

[[ 31  28]
 [ 11 130]]

Confusion Matrix (XGBoost)

[[ 31  28]
 [ 14 127]]

Classification Report (XGBoost)

              precision    recall  f1-score   support

           0       0.69      0.53      0.60        59
           1       0.82      0.90      0.86       141

    accuracy                           0.79       200
   macro avg       0.75      0.71      0.73       200
weighted avg       0.78      0.79      0.78       200

# Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Machine Learning (scikit-learn, XGBoost)

Data Visualization (Matplotlib, Seaborn)