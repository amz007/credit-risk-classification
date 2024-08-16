## Credit Risk Classification Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose of the analysis was to develop a machine learning model that could accuractly predict he credit risk with loans. Credit risk was evaluated as either being healthy or high risk of defaulting. 

* The variables used were the borrower's: amount of loan, interest rate, income, debt to income, number of accounts, number of derogatory marks, total debt, and loan status. The project's goal was to predict the loan status where 0 shows a healthy loan and 1 shows a high risk loan. 

* A logistic regression analysis was performed to predict the outcome of the borrowers credit risk.

## Results

* Precison:
    * Healthy loans ("0"), 100% of loans predicted to be healthy loans were indeed healthy
    * High Risk loans ("1"), 85% of loans predicted as high risk were indeed high risk.
* Recall:
    * Healthy loans were correctly identified 99% in the model
    * High Risk loans were correctly identified 91% of the time
* F1-Score:
    * Healthy loans had a perfect score of 1.0 F1-score, meaning the model was extremely accurate in predicting and classifying healthy loans.
    * High Risk loans had a .88 F1-score, meaning he model is good but not extremely accurate at predicting high risk loans due to false positives (15%) leading         to misscallification of high risk loans as healthy loans.
## Summary

The model is very accurate in predicting healthy loans but the greatest weakness with this model is the lower precision rate for high risk loans. This weakness can result in borrowers being approved for loans who should have been declined or should have been approved for a lower loan amount. The model should be revised to capture a higher precision and accuracy rate for high risk credit loans. 
