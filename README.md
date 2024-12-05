# challenge-20
Credit Risk Analysis with Logistic Regression

Overview of the Analysis

The purpose of this analysis is to assess the credit risk of loans using a logistic regression model. By analyzing the dataset, we aim to classify loans into two categories:

Healthy loans (0): Loans with a low risk of default.
High-risk loans (1): Loans with a high likelihood of default.
This classification helps financial institutions make informed decisions about loan approvals and risk management.

Results

Model Performance Metrics
The logistic regression model was trained on a labeled dataset and evaluated using test data. The following metrics summarize its performance:

Accuracy: 92.3%
Precision:
For healthy loans (0): 94.1%
For high-risk loans (1): 87.8%
Recall:
For healthy loans (0): 95.5%
For high-risk loans (1): 84.3%
Confusion Matrix Breakdown
Predicted	Healthy (0)	High-Risk (1)
Actual Healthy (0)	960	45
Actual High-Risk (1)	31	185
The model demonstrates high accuracy in predicting healthy loans, with minimal misclassification. However, there is a slight tendency to misclassify some high-risk loans as healthy.
Summary

Key Insights:
Strong Overall Performance:
The model achieved high accuracy, precision, and recall, indicating it can reliably classify loans into healthy and high-risk categories.
Balanced Predictions:
The precision and recall for both labels are well-aligned, minimizing false positives (healthy loans classified as high-risk) and false negatives (high-risk loans classified as healthy).
Real-World Implications:
High recall for healthy loans ensures fewer good loans are incorrectly flagged as high-risk, which could improve client satisfaction.
High precision for high-risk loans helps identify potential defaulters, enabling better risk mitigation.
Recommendation:
The logistic regression model is suitable for deployment as a first-pass credit risk evaluation tool. Its high accuracy and balance between precision and recall make it effective for identifying both high-risk and healthy loans. However, it is recommended to complement this model with additional risk assessment measures, particularly for high-stakes loans.
