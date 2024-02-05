# README: CREDIT CARD FRAUD DETECTION 

## Author: Sunny Singh 

## Domain: Data Science

## Aim
The aim of this project is to build a machine learning model to identify fraudulent credit card transactions .

## Dependencies Used
- numpy
- pandas
- train_test_split from sklearn
- LogisticRegression from sklearn
- accuracy_score from sklearn.metrics

## Data set - 
used the credit card detection data set from kaggle and loaded dataset to the pandas data frame .

## Data Exploration and Preprocessing 
- to get the information about the data we used info() function that gives the basic info about the data and the data types .
- Also checking the number of missing values in each column using-  credit_card_data.isnull().sum() .
- After checking the missing values we handle the missing values by taking the mean of each column and replace it with the mean .
- we also check the statistical measures of the data by using - legit.Amount.describe() .
- after that we split the data into train and test by using the train_test_split() function from sklearn .

## Model Training -
- we train our model by using logistic Regression algorithm from sklearn.linear_model

## Model Evaluation - Accuracy score 
