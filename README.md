# E-commerce Customer Analysis and Prediction

## Overview
This project analyzes e-commerce customer data to predict future purchases and derive business insights. The model predicts whether a customer will make a purchase in the next 6 months based on historical data.

## Dataset
The dataset includes customer information:
- CustomerID: Unique identifier
- Age: Customer age
- Gender: Customer gender
- Income: Annual income ($)
- Tenure: Years with company
- LastPurchase: Days since last purchase
- TotalPurchases: Total number of purchases
- TotalSpend: Total amount spent ($)
- IsReturning: Binary (0/1) for repeat purchases
- EngagementScore: Customer engagement metric
- NextPurchase: Target variable (0/1) for purchase in next 6 months

## Requirements
```python
pip install xgboost scikit-learn pandas numpy seaborn matplotlib
```

## Usage
1. Upload your CSV file when prompted
2. The script will:
   - Perform data preprocessing
   - Train multiple models (Logistic Regression, Random Forest, XGBoost)
   - Generate visualizations
   - Export best model and summary report

## Features
- Automated data preprocessing
- Multiple model comparison
- ROC curve visualization
- Feature importance analysis
- Business insights generation
- Model export functionality

## Output Files
- best_model.pkl: Serialized best-performing model
- summary_report.txt: Analysis results and business recommendations

## Performance Metrics
- Cross-validation scores
- ROC-AUC curves
- Feature importance rankings
- Classification reports

## Project Structure
```
Main Analysis Script
   ├── Data Preprocessing
   ├── Model Training
   ├── Evaluation
   └── Insights Generation
```

