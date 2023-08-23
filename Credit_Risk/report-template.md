# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

- The purpose of this analysis is to train and evaluate a machine learning model based on loan risk data for a company to give to clients. 
- The financial information data was based on features like interest_rate,borrower_income, and debt_to_income. Using this data, we attempt to predict the loan risk of each client.
- When creating the model, we had to test using a KMeans supervised model and then tried out an alternative model through random oversampling.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - The accuracy of the model is 95%.
  - The precision of the model is 1.00 for healthy loans and .85 for high-risk loans.
  - The recall is .99 for healthy loans and .91 for high-risk loans.



* Machine Learning Model 2:
    - The accuracy of the model is 99%.
    - The precision of the model is 1.00 for healthy loans and .84 for high-risk loans.
    - The recall is .99 for healthy loans and .99 for high-risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  - The Machine Learning Model 2 with random oversampling performs best. We know this since it seems to perform better overall with its higher balanced accuracy and significantly less false negatives.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  - Yes, performance depends on the problem we are trying to solve. It's more important to the customer to predict the `1`'s since they'd rather be able to more accurately predict high-risk loans and limit the amount of false positives they recieve.

If you do not recommend any of the models, please justify your reasoning.
