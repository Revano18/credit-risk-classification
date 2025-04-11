# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The Goals of this analysis was to predict whether a loan would be fully paid (0) or not fully paid (1) based on financial data. The dataset includes features like loan size, interest rate, borrower income, debt-to-income ratio, and others. Target variable is loan_status, where:

* 0 = healthy loan (fully paid)
* 1 = high-risk loan (not fully paid)

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

    * Description of Model 1 Accuracy, Precision, and Recall scores.

* Machine Learning Model 2:

    * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The Logistic Regression model performs excellently, with an accuracy of 99%. It is highly effective at predicting healthy loans (Class 0), with nearly perfect precision and recall. For high-risk loans (Class 1), the model achieves a good recall of 94%, but precision is a bit lower at 86%, meaning there are some healthy loans misclassified as high-risk loans.

Given the high performance, Logistic Regression is a solid choice for predicting loan status, especially since the goal is to identify high-risk loans.

If you do not recommend any of the models, please justify your reasoning.
