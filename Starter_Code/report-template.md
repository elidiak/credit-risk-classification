# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

We preformed an analysis of the credit risk data so that we could predict if a machine learning model could tell us if a loan was risky before we exteneded the loan. The data contained a good or bad risk score, along with the loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and the borrowers total debt. We used a logistic regression model to analyze the data. To analyze the data, we imported the data into a pandas dataframe. We then split the original dataframe into two. One series contained the good or bad risk marker, the other the data we wanted to analyze. We then used a train test split, so that the model would have seen only some of the data that we would test it with. We then fit the model to the data, and tested the results. In this assignment, only Logistic regression was used. A follow up might use a neural network as a comparable model.  
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Logistic Regression: 
Accuracy: 0.99 Precision 0: 1.0 Recall 0: 0.99
Precision 1: 0.86 Recall 1: 0.94

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

As only logistic regression was tested, I would use the model. The model was 86% accurate at deciding if a loan would be risky or not. I would be interested later in comparing the data found by logistic regression vs a neural network. I would think that we are more likely to want to predict which loans may go bad.

