# credit-risk-classification

## Overview

The purpose of the analysis is to perdict the credit risk of loan applicants to see if they are are a high-risk or low-risk borrower.

The inanciinformation of the data are loan size, interest rate, borrower income, debt-to-income, number of accounts, derogatory marks, and total debt. 
We use these factors to predict if the applicant is a healthy loan or a high-risk loan.

The loan status variables on the original database have value counts of healthy loan having 75,036 data points and high-risk having 2,500 data points. On the resampled database they both had 56,271 value counts

The data was separted then split into traing and testing datasets using train_test_split. Then created a Logistic Regression Model with both the original model and the resampled model. Finally both made predictions and a classification report to compare them to one another.

Model 1:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

Model 2:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

The model using the resampled data show high accuracy in all aspects of the test proving itself useful and reliable when make a prediction for loan applicants.