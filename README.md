# Credit Risk Modelling

## Introduction
Classification predictive modelling is a supervised machine learning approach that can be used to identify the creditworthiness of borrowers. Binary classification where the classification has only two possible outcomes, for example either true or false, is the focus of this exercise. We examine two models for credit risk modelling:
* Model 1 - Logistic regression model with original data, and
* Model 2 - Logistic regression model with resampled training data.

We then evaluate the performance of each model using metrics such as accuracy score, precision rate and recall rate.

## Data and Assumption
A peer-to-peer lending services has provided their historical lending activity for the modelling. This set of data has 77,526 records and contains the following variables:
* size of the loan
* loan interest rate
* borrower's income
* borrower's debt to income ratio
* number of loan accounts
* an indicator of derogatory marks
* total debt amount

Variables are assumed to be independent of each other. <br>

Each record also has the loan status marked with 0 or 1, where value of 0 means the loan is health and value of 1 means the loan has a high risk of defaulting. From the historical data, 3% (or 2500) is of high risk of defaulting. The disproportionate ratio of healthy and high-risk defaulting loans can make training efficient learning models difficult. Next section will discuss the technique used to handle this imbalance.

## Machine Learning Process


* In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Methodology


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Recommendation

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.