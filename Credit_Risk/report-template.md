# Module 12 Report Template

## Overview of the Analysis


The purpose of this analysis is to build a model that can be used to identify the creditworthiness of borrowers
The financial information was gotten from historical lending activity generated from a peer-to-peer lending services company.
The dependent variables used in this analysis is the loan status and the independent variables were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
The stages of machine learning we had to go through includes spliting our data to train and test sets, defining our independent and independent variables, we the created the logistics regression model an fit it into the original data, the trained model is then used to make predicitons and the model was evaluated.
LogisticRegression models was created and then randomover was used to resample the data. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
                 precision    recall  f1-score   support

  Healthy Loans       1.00      0.99      1.00     18765
High Risk Loans       0.84      0.99      0.91       619

       accuracy                           0.99     19384
      macro avg       0.92      0.99      0.95     19384
   weighted avg       0.99      0.99      0.99     19384               Accuracy Score is 0.9918489475856377



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
                precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384                Accuracy Score is: 0.9938093272802311

## Summary
the randomly oversampled data seems to perform best only because it has a higher accuracy score, aside that the pretty much performed in like manner of predicting risky loans


