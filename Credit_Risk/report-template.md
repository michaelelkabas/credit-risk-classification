# Module 20 Report 

## Overview of the Analysis

The purpose of this analysis is to develop a machine learning model that can predict the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. By accurately predicting whether a loan will be healthy (low risk) or high-risk, the company can make more informed lending decisions, potentially reducing defaults and improving overall financial stability.

## Results

Results
The logistic regression model developed in this analysis was evaluated using various performance metrics on a test dataset. The key results are:

Accuracy Score: 99.2%
Class 0 (Healthy Loans)
Precision: 100%
Recall: 99%
F1-Score: 100%

Class 1 (High-Risk Loans)
Precision: 85%
Recall: 91%
F1-Score: 88%

Summary: The logistic regression model demonstrates strong performance with an overall accuracy of 99.2%. The key metrics for both classes are as follows:

Class 0 (Healthy Loans)
Precision: The model correctly predicts 100% of healthy loans as healthy, indicating no false positives.
Recall: The model correctly identifies 99% of all actual healthy loans, showing very few false negatives.
F1-Score: The harmonic mean of precision and recall is 100%, reflecting excellent performance.

Class 1 (High-Risk Loans)
Precision: The model correctly predicts 85% of high-risk loans as high-risk, indicating a moderate level of false positives.
Recall: The model correctly identifies 91% of all actual high-risk loans, showing a high level of true positives.
F1-Score: The harmonic mean of precision and recall is 88%, reflecting strong performance in identifying high-risk loans.

Justification for Recommendation
Based on the results, I recommend the use of this logistic regression model for the following reasons:

High Accuracy: The model's overall accuracy of 99.2% means it correctly classifies the vast majority of loans.
Reliable Predictions for Both Classes: The model performs exceptionally well in predicting both healthy and high-risk loans, ensuring balanced and robust performance.

## Summary

Effective Risk Identification: With a precision of 85% and a recall of 91% for high-risk loans, the model effectively identifies high-risk loans, which is critical for minimizing defaults and financial losses.
The model's high performance suggests that it will be a valuable tool for the company in making informed lending decisions, improving risk management, and enhancing financial stability. If further refinements are needed, additional techniques such as hyperparameter tuning, feature engineering, and exploring other machine learning algorithms can be considered to enhance the model's performance even more.

