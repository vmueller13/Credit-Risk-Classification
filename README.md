# Module 20 Challenge: Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis was to predeict the healthy and high-risk loan labels. The financial information provided for this project was a CSV with all the information about loan size, interest rate, borrower income and total debt. I needed to use this information to predict whether the loans issued would be high risk or healthy loans. In total, there were 75036 healthy loans and 2500 high-risk loans. In order to complete this prediction, I used the machine learning process to split the data, train and test the model. I used the `LogisticRegression` module from `SKLearn` to train the model. After this, I saved the predicitons on the testing data labels by using the testing feature data (`X_test`) and the fitted model. Lastly, I evaluated the model's performance using an accuracy score, confusion matrix adn classification report. I would have continued on to reample the data, but I ran into issues importing the `imblearn` module.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
