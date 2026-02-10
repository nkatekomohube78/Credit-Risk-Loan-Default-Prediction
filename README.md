# Credit-Risk-Loan-Default-Prediction
Predictive model that estimates borrower default probability and ranks applicants by credit risk

## Overview
Built a machine learning model to predict whether a borrower will default on a loan (binary classification) and generated a probability-based risk score.

## Dataset
Public credit risk dataset (source: [Kaggle]).
Target: `loan_status` (0 = non-default, 1 = default)

## Approach
- Cleaned data (handled missing values by dropping rows)
- Train/test split with stratification
- Standardized features
- Trained Logistic Regression model
- Evaluated with ROC AUC and  classification report
- Produced default probability “risk score” 

## Results
- ROC AUC: 0.86( to the nearest two decimal places)
- Output: default probability per borrower (risk score)

##Conclusion
The model achieved ROC AUC = 0.86, showing strong separation between default and non-default borrowers. The resulting risk scores provide a practical way to rank applicants and choose approval thresholds based on risk appetite.


