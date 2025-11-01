# Customer-Churn-Prediction-ML-Project

## Project Overview
This project predicts whether a customer will churn (leave a service) using machine learning.  
It demonstrates end-to-end classification — from data preprocessing and EDA to model building and interpretation.

## Objectives
- Analyze customer behavior and service usage patterns  
- Handle class imbalance using SMOTE  
- Build and compare Logistic Regression, Random Forest, and XGBoost models  
- Identify factors influencing churn for actionable business insights  

## Technologies Used
- Python, Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-Learn, XGBoost, Imbalanced-Learn  
- Google Colab / Jupyter Notebook  

## Workflow
1. **Data Cleaning & Preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering & SMOTE**  
4. **Model Building (LogReg / RF / XGB)**  
5. **Model Comparison & ROC Analysis**  
6. **Feature Importance & Business Insights**  

## Results
| Model | Accuracy | Precision | Recall | F1 | AUC |
|--------|-----------|-----------|--------|----|-----|
| Logistic Regression | ~0.80 | 0.78 | 0.72 | 0.75 | 0.83 |
| Random Forest | ~0.86 | 0.82 | 0.80 | 0.81 | 0.90 |
| XGBoost | **~0.88** | **0.84** | **0.83** | **0.84** | **0.92** |

## Key Insights
- **Tenure**, **Monthly Charges**, and **Contract Type** are key churn drivers.  
- Short-term, high-charge customers are more likely to churn.  
- Targeted retention campaigns for early-stage customers can reduce churn.

## Contact

📧 Email: [singhbulbul485@gmail.com]  
🌐 LinkedIn: [https://www.linkedin.com/in/bulbul-singh-77b3a6201/] 
