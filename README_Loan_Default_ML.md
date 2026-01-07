# Loan Default Prediction Using Machine Learning

This project presents a comparative analysis of multiple classification models to predict loan default risk using borrower demographic, financial, and credit-related data. The analysis emphasizes both predictive accuracy and interpretability to support real-world credit risk management decisions.

## Project Overview
The project builds an end-to-end machine learning pipeline covering exploratory data analysis, feature engineering, multicollinearity management, and systematic model evaluation for loan default prediction.

## Objectives
- Predict loan default status (binary classification)
- Compare linear, regularized, and tree-based models
- Identify key risk drivers influencing loan rejection
- Balance predictive performance with interpretability

## Repository Structure
- Classification_Models.ipynb – Main analysis notebook  
- loan_data.csv – Loan dataset  
- Presentation.pdf – Business presentation  
- Report.pdf – Detailed report  
- README.md – Documentation  
- requirements.txt – Dependencies  

## Models Used
- Logistic Regression (Baseline)
- L1 & L2 Regularized Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost

## Key Insights
- Tree-based ensemble models outperform linear models in ROC–AUC and recall
- XGBoost delivers the strongest overall performance
- Logistic regression remains valuable for regulatory transparency

## Tools
Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Statsmodels, Matplotlib, Seaborn

## Author
Pragya Gupta
