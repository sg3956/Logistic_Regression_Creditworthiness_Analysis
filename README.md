
## Overview of the Analysis

* In this project, we will be utilizing different techniques to train and assess models that deal with imbalanced classes. Our aim is to construct a model that can accurately identify the creditworthiness of borrowers, using a dataset of past lending activity from a peer-to-peer lending services company.


* We examined financial data and variables including the loan amount, interest rate, and the borrower's income, debt-to-income ratio, total debt, number of accounts, as well as any negative marks on their credit history. 

* In the next step, we aimed to predict `value_counts` including the number of loans that were expected  to be either healthy or high risk loans. In doing so, we evaluated different variables such as the accuracy, precision, recall, and F1 scores. 


* Using the original dataset, we performed  a `LogisticRegression` analysis upon splitting the data into training and testing sets to properly train the model for future predictions. We then used  a resampled dataset and conducted the Random OverSampler technique to improve the accuracy and identify the model with the best perfoming features including accuracy, precision, and recall.


## Results

* Machine Learning Model 1:


  * The model derived from the original data shows excellent accuracy of 0.99 which means the model has been accuarte 99% of time.
  The model reflects a precision of 1.00 or 100% for healthy loans and .85 or 85% for high risk loans. In other words, the model provides 100% confidence in predicting healthy loans and 85% confidence is predicting high risk loans.
  Considering the recall variable, the model identified 99% of healthy loans and 91% of high risk loans.




* Machine Learning Model 2:


  * The model derived from resampled data also shows excellent accuracy of 0.99 which means the model has been accuarte 99% of time.
  The model reflects a precision of 1.00 or 100% for healthy loans and .84 or 84% for high risk loans. In other words, the model provides 100% confidence in predicting healthy loans and 84% confidence is predicting high risk loans.
  Considering the recall variable, the model identified 99% of healthy loans and 99% of high risk loans.



## Summary


* Comparaing the two models and looking at accuracy, precision, and recall for each model, model 2 appears to perform slightly better in  predicting the risky loans, therefore, I would selecr model 2 with resampled data.

