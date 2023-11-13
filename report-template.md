# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
A logistic regression model was used, which provided the following scores:
    * Accuracy 0.99
    * Precision 0.85 for high risk and 1.00 for healthy
    * Recall 0.91 for high risk and 0.99 for healthy


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Model 1 works well (logistic regression model) as the accuracy shows that 99 per cent of the time it could predict accurately. The other scores show that this model was more effective for analysing healthy risk scores compared to high risk, but there is still a high predictability with high risk so I would still recommend using this model. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) I would say that it is more important to predict the high-risk loans compared to healthy loans, but it is also better to have this model than relying on human decisions. 

If you do not recommend any of the models, please justify your reasoning.

The purpose of the analysis is to identify what potential clients are a low or a high risk for loans using the information in the dataset - being loan size, interest rate, the income and debt to income of the borrower. 