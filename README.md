# Credit Risk Classification Challenge

## Overview
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Directory
- `Credit_Risk` contains all the files used to run the analysis

## Analysis
The purpose of this analysis is to train and evaluate a machine learning model based on loan risk data for a company to give to clients.
- Machine Learning Model 1
    - The accuracy of the model is 95%.
    - The precision of the model is 1.00 for healthy loans and .85 for high-risk loans.
    - The recall is .99 for healthy loans and .91 for high-risk loans.
- Machine Learning Model 2
    - The accuracy of the model is 99%.
    - The precision of the model is 1.00 for healthy loans and .84 for high-risk loans.
    - The recall is .99 for healthy loans and .99 for high-risk loans.
## Summary
- We would recommend Machine Learning Model 2 with random oversampling since it seems to perform better overall with its higher balanced accuracy and significantly less false negatives.
- The reason Machine Learning Model 2 performs better is due to the type of data provided. It's better at reducing false positives, therefore the company would find it more valuable to better identify high-risk loans