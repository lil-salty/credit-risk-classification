# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis was to create a model that uses machine learning that analyses credit and loan data to predict if a loan is high or low risk. 

The data used to train the machine learning model contained over 70,000 rows of data pertaining to: 
* loan size
* interest rate
* borrower income
* dept to income rate
* total debt
* number of loans
* derogatory marks
* loan status

The variables this machine learning model aimed to predict were loans labeled as either healthy loans with a value of 0 or labeled as high risk loans with a value of 1. These values are loacated in the 'loan_status' column.

To create this machine learning model the csv file with loan data was loaded into a DataFrame where a subset of the data was isolated. This subset was then used to train the machine learning logistic regression model before the model was compared to the original data to see how well its predictions held up against the known results.



## Results

Machine Learning Model 1:

    * Precision Scores:
        * Healthy Loan: 100%
        * High-Rish Loan: 87%
    * Recall Scores:
        * Healthy Loan: 100%
        * High-Risk Loan: 95%
    * Accuracy Score:
        * 99%

## Summary

This logistic regression machine learning model preformed with a high accuracy for predicting both high risk and healthy loans. While the healthy loan model preformed best because of its higher accuracy, both models preformed very well and would be recommended for use in determining if a loan is healthy or high-risk.