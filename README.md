Author:

# Ilana Greenberg

Link to Notebook: [Notebook](https://colab.research.google.com/drive/1_8d5Bb3CyKQOSCclv-zLiCet21noeCi2?authuser=1#scrollTo=48uOnS-q__ue)

Link to Slideshow Presentation: [Slideshow](./IlanaPowerpoint.pdf)

## Problem Statement
With the rise of social media, targeted advertising has become an increasing interest among large-scale coorporations. This project seeks to compare classification methods for targeted advertising, by analyzing whether a user's decision to buy a product after viewing an advertisement can be predicted from their personal attributes of age, gender and salary. The results could be valuable for recomending a future model, and advising advertizers in the favorability of one model over another depending on thier needs. 

## Description of Dataset
This project uses a Kaggle dataset with information collected from 400 users and their purchase decisions when viewing advertizements.  The data includes the user's ID, age, estimated salary, and gender, as well as their decision to purchase a product (with 0 representing not purchased, and 1 representing purchased).  The user's age, salary and gender were chosen as features to predict whether the product would be purchased. 

## Data Dictionary for [advertisements.csv](./advertisments.csv)

|Feature|Type|Description|
|---|---|---|
|**User ID**|*int64*|ID of the Person|
|**Gender**|*object*|Male or Female|
|**Age**|*int64*|age of the person|
|**EstimatedSalary**|*int64*|Estimated Salary |
|**Purchased**|*int64*|if the person bought the advertisment or not|

## Executive Summary
- Exploratory Data Analysis was connducted and revealed that User ID column should be dropped
- Categorical variable of Gender was encoded numerically using dummy variables
- Logistic regression was performed on the dataset 
- Logistic regression was performed on the dataset after applying a Standard Scaler
- A Support Vector Classifier algorithm was performed after applying a Standard Scaler
- A Stochastic Gradient Descent algorithm was performed
- For each classification algorithm, a confusion matrix, regression score and ROC curve were used to evaluate and compare the effectiveness of the model 

## Conclusion 

Based on the results of the analysis, the Support Vector Classifier perfomed the best.  
