# Classification Problem Solver

This project aims to solve a classification problem using machine learning techniques, specifically GridSearchCV with Gradient Boosting and Random Forest Classifier.

## Problem Statement

Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

1. They first identify a set of employees based on recommendations/ past performance
2. Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
3. At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion

For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

![checkpoint](checkpoint%20image.jpg)

## Data

### Data Cleaning

The dataset required minimal cleaning, as it contained a small percentage of null values. Missing values were imputed with the most frequently occurring value in each respective column.

### Categorical Feature Encoding

Categorical features in the dataset were encoded using the Pandas `get_dummies` method. This process transformed categorical variables into binary columns, making them suitable for machine learning models.

