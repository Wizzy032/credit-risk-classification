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

The model is recommended for use by the company for the following reasons:

1.	High Overall Accuracy (99%)
	•	The model correctly classifies 99% of the loans, which means it is highly reliable for predicting both healthy and high-risk loans.
	•	A high accuracy score indicates that the model can effectively be a useful tool for initial loan risk assessments.

2. Strong Performance on Healthy Loans
	•	We could see that the precision of the model on healthy loans is 100%. This means that when the model predicts a loan as healthy, it is always correct.
	•	Recall (100%)- The model correctly identifies all healthy loans.
	•	F1-score (100%)- A perfect balance between precision and recall.
	This ensures that safe borrowers are not mistakenly flagged as high risk, which is crucial for approving loans efficiently.

3. Reliable Identification of High-Risk Loans
	•	Precision (87%)- When the model flags a loan as high risk, it is correct 87% of the time.
	•	Recall (95%)- The model identifies 95% of actual high-risk loans, meaning it catches most borrowers that are likely to default.
	•	F1-score (91%)- A good balance between precision and recall, making the model dependable for risk assessment.
	This means that the model is effective at identifying risky loans, which helps the company reduce financial losses by minimizing loan defaults.

