# Module 20 Challenge: Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis was to predeict the healthy and high-risk loan labels. The financial information provided for this project was a CSV with all the information about loan size, interest rate, borrower income and total debt. I needed to use this information to predict whether the loans issued would be high risk or healthy loans. In total, there were 75036 healthy loans and 2500 high-risk loans. In order to complete this prediction, I used the machine learning process to split the data, train and test the model. I used the `LogisticRegression` module from `SKLearn` to train the model. After this, I saved the predicitons on the testing data labels by using the testing feature data (`X_test`) and the fitted model. Lastly, I evaluated the model's performance using an accuracy score, confusion matrix and classification report. I continued this analysis by refitting the training data using `RandomOverSampler` and rerunning the logisitic regression model.

## Results

* Machine Learning Model 1:
  * Accuracy-- 0.99
  * Precision--Healthy: 1.00 High-Risk: 0.85
  * Recall--Healthy: 0.99 High-Risk: 0.91
  * F-1--Healthy: 1.00 High-Risk: 0.88

* Machine Learning Model 2: 
  * Accuracy-- 0.99
  * Precision--Healthy: 1.00 High-Risk: 0.84
  * Recall--Healthy: 0.99 High-Risk: 0.99
  * F-1--Healthy: 1.00 High-Risk: 0.91
  
## Summary

Both of these machine learning models predict the loan labels to a fairly high degree of accuracy, however, I would recommend the second model. I make this recommendation based off of two observations of the results. Firstly, that the accuracy of both models is the same and this therefore cannot be the only determining factor to recommending a model.
Secondly, the recall is higher for the second model and since the cost of false negatives is high for loan prediction, I want to minimize the number of high-risk loans that are incorrectly classified as healthy (minimize missed high-risk loans). Utilizing the second model with higher recall means that the model can effectively identify most of the actual high-risk loans.