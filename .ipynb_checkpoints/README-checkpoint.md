# credit-risk-classification


This project aims to develop a machine learning model that predicts the creditworthiness of borrowers based on historical lending data. By classifying loans into healthy loans (0) and high-risk loans (1), the model assists financial institutions in making informed lending decisions, reducing default rates, and enhancing risk management strategies.

Purpose
The purpose of this analysis is to create a reliable machine learning model that can accurately predict loan statuses based on various borrower attributes and loan characteristics. This analysis provides insights that can help financial institutions assess borrower creditworthiness effectively.

Data Description

The dataset used in this analysis contains historical lending activity from a peer-to-peer lending services company. Key variables include:

loan_status: Indicates whether a loan is healthy (0) or high-risk (1).

Various borrower attributes, loan amounts, interest rates, and repayment histories.

Variable Distribution
- Healthy Loans (0): 15,001 instances
- High-Risk Loans (1): 507 instances

Modeling Approach
Data Loading: The dataset is loaded into a Pandas DataFrame.
Data Preprocessing: The data is cleaned and prepared by separating features and labels.
Data Splitting: The dataset is divided into training and testing sets using train_test_split.
Model Selection: A logistic regression model is chosen for binary classification.
Model Training: The logistic regression model is fitted using the training data.
Model Prediction: Predictions are made on the testing data to evaluate performance.
Model Evaluation: The model's performance is assessed using a confusion matrix and classification report.

Performance Metrics
- Accuracy: 99%
Precision:
- Healthy Loans (0): 1.00
- High-Risk Loans (1): 0.86
Recall:
- Healthy Loans (0): 0.99
- High-Risk Loans (1): 0.94
F1-Score:
- Healthy Loans (0): 1.00
- High-Risk Loans (1): 0.90

Recommendation
The logistic regression model is recommended for predicting loan statuses due to its high accuracy and strong performance metrics. While the model performs exceptionally well in identifying healthy loans, there is an opportunity to improve the precision for high-risk loans. Continuous monitoring and potential adjustments to the model will ensure its effectiveness in a dynamic lending environment.



Installation
To run this project, you will need to have Python installed along with the following libraries:

- Pandas
- NumPy
- Scikit-learn

  