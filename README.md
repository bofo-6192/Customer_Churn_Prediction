# Customer Churn Prediction

This project uses **Logistic Regression** to predict customer churn from the Telco dataset. It includes full steps: data cleaning, EDA, preprocessing, modeling, evaluation (accuracy, F1, ROC-AUC), and feature importance analysis — all built in Python with a focus on clarity and reproducibility.

## Dataset
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Source: IBM Sample Data
- Rows: 7,000+ customers
- Features: Demographics, services used, billing, churn status

## Tech Stack
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (Logistic Regression, Metrics)
- Jupyter Notebook

## EDA & Preprocessing
- Handled missing values (`TotalCharges`)
- Converted categorical to numerical
- Visualized churn distribution across:
  - InternetService, Contract, PaymentMethod, etc.
  - Tenure, MonthlyCharges, TotalCharges

## Model
- Logistic Regression (with class weights to handle imbalance)
- Metrics:
  - Accuracy
  - Precision / Recall / F1-score
  - ROC-AUC
  - Confusion Matrix
- Feature Importance (Top 10)

## How to Use
1. Clone the repo
2. Open the notebook
3. Run cells in order — all code is commented

## Key Insights
- Longer tenure & 2-year contracts = less likely to churn
- Month-to-month customers, high charges = more likely to churn
