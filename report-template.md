# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this module is to analyze the credit risk of customer, therefore the company can based on the credit healty to approve if the customer is qualify for the loan.
* The data columns includes loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status. 
* The module will based on X variables, include all columns except loan_status, to predict customer's credit health. 
* Because the module we applied and the result is continous data based on the X variables, this module will be using Regression model to analyze. The satges of the machine learning process it went through include import the train_test_learn module, split the data using train_test_split, instantiate the Logistic Regression model, fit the model using training data, make prediction using the testing data, and generate accuracy_score, confusion matrix, classification report for the model.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Module 1 accuracy_score is 0.9924. Based on this score, we can tell the accuracy is very high and result should be pretty accurate.
  * Module 1 recall score is also around 0.99, which means that nearly no non-spam message is wrongly labeled as spam.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Module 2 accuracy, precision, and recall are all 1.00.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* I recommend to use Logistic Regression model.

If you do not recommend any of the models, please justify your reasoning.
