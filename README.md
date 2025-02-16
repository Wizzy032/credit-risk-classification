# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis was to evaluate the risk of loan default using a machine learning model. The dataset provided financial information about borrowers, including loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict whether a loan was high risk (1) or healthy (0) based on these features.

Machine Learning Process
	1.	Data Preprocessing: The dataset was loaded, and the target variable (loan_status) was separated from the features.
	2.	Data Splitting: The dataset was split into training and testing sets.
	3.	Model Selection: A Logistic Regression model was chosen for classification.
	4.	Model Training: The model was trained using the training dataset.
	5.	Evaluation: The model’s performance was assessed using a confusion matrix and classification report.

## Results

  • Accuracy: The model correctly classified 99% of loans.
	•	Precision for High-Risk Loans (1): 87%-when the model predicts high risk, it is correct 87% of the time.
	•	Recall for High-Risk Loans (1): 95%-it correctly identifies 95% of actual high-risk loans.

## Summary

The model performed exceptionally well in identifying healthy loans, with 99% accuracy. However, for high-risk loans, while the recall is 95%, the precision is 87%, meaning some healthy loans might be incorrectly classified as high-risk.

## Recommendation
I would recommend to use this model as an initial screening tool for credit risk assessment.
	
