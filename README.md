# Loan Eligibility Prediction - HexSoftwres Internship
This project predicts loan eligibility using machine learning models (Logistic Regression, Decision Tree, Random Forest) for my HexSoftwres internship.

## Files
- `Loan_Eligibility_Prediction.ipynb`: Main code (data loading, cleaning, EDA, models, deployment)
- `loan_data.csv`: Dataset
- `correlation_heatmap.png`, `loan_status_distribution.png`, `loan_amount_vs_income.png`: Visualizations
- `logistic_regression_model.pkl`, `decision_tree_model.pkl`, `loan_model_v1.0.pkl`: Trained models
- `preprocess_config.json`, `deployment_package.json`: Deployment configs

## How to Run
1. Upload `loan_data.csv` to Google Colab.
2. Run `Loan_Eligibility_Prediction.ipynb`.
3. Outputs: Visualizations, trained models, and deployment files.

## Results
- Logistic Regression Accuracy: ~75%
- Decision Tree Accuracy: ~50%
- Key Insight: Credit_History strongly correlates with loan approval.
