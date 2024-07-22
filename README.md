# Credit-Risk-challenge-20


### Train and evaluate a model based on loan risk,using historical lending activity that can identify the crediworthiness of borrowers ###

Read data from a csv file into a Pandas DataFrame. Split data into training and testing datasets. Created a logistic regression model with original data. Fit the logistic regression model by using the training data x_train and y_train. Saved the predictions for the testing data labels by using the testing feature data x_test and the fitted model. Evaluated the model's performance by generating a confusion matrix and printin a classificationa report.

* Credit Risk Analysis Report

## Analysis Overview ##

  The objective of the analysis is to give a model or train a model that can help predicting between a good loan (0), or a bad loan (1).

## Results ##

  - accuracy           0.99
  - precision (0), 1.00 / (1), 0.85
  - recall    (0), 0.99 / (1), 0.91


## Summary 
 The model gave a really precision on the healthy loans but when it came to the unhealthy loans it was better at dealing with the false negatives than the false positives. As is the model is doing well, however the client might want a better  precision or a better recall. Then, if thats the case the client would have to tell you to adjust your model to meet their objectives. Overall , being that the model only had %3.2 of unhealthy loan data to work with, it did an amazing job.

### Libraries/Modules Used
numpy, pandas, pathlib,sklearn.metrics, confusion matrix, classification report

### Resources
 
