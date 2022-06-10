# module_12_challenge
Challenge assignment for module 12

Credit Risk Analysis

  Overview

The purpose of this analysis is to determine whether either model is worth pursuing, or if either is better than the other.  The data consisted of financial information such as loan size, interest rate, and borrower income that was fitted to the model to predict whether a loan is potentially high-risk.  In the first stage, data is split into training and testing sets.  Then the data is fed into the model and predictions are made on the data.  The methods used for the model and data were Logistic Regression and random oversampling.

Results

  Machine Learning Model 1:
*Accuracy: 0.91
*Precision: 0.99
*Recall: 0.99

  Machine Learning Model 2:
*Accuracy: 0.99
*Precision: 0.99
*Recall: 0.99


Summary


Model 2 seems to perform best.  It is better at predicting the high-risk loans, which is what the model was built for.  It's precision is slightly lower than model 1, but the recall, specificity, f-1 score, accuracy, and the geometric mean are all higher than model 1.

It's more important here to predict the 1s(high-risk loans), because the aim is to prevent giving out loans that will default.
