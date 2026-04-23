# Lab 9 – Decision Trees & Random Forest

This lab focuses on building and comparing **Decision Tree** and **Random Forest** models using LendingClub loan data. The objective is to predict whether a borrower will fully repay their loan based on financial and credit-related features.

## Files

* [02_Decision_Trees_and_Random_Forest_Project.ipynb](./02_Decision_Trees_and_Random_Forest_Project.ipynb)
* [loan_data.csv](./loan_data.csv)

## Overview

### Data Loading

The dataset is loaded into a pandas DataFrame. It includes borrower information such as credit score, income, debt ratio, and loan purpose, along with the target variable `not.fully.paid`.

### Exploratory Data Analysis (EDA)

* Histograms used to compare FICO scores across different groups
* Countplots used to analyze loan purposes vs repayment status
* Jointplots and lmplots used to explore relationships between FICO score and interest rate

### Feature Engineering

* The categorical `purpose` column is converted into dummy variables using `pd.get_dummies`
* This allows models to process categorical data properly

### Train-Test Split

The dataset is split into training and testing sets (70/30) to evaluate model performance.

### Decision Tree Model

* A Decision Tree classifier is trained on the data
* Performance is evaluated using a confusion matrix and classification report
* Results show decent performance but signs of overfitting and class imbalance

### Random Forest Model

* A Random Forest classifier with multiple trees (n=600) is trained
* Predictions are generated and evaluated using the same metrics

### Model Comparison

* Random Forest outperforms the Decision Tree overall
* It generalizes better and reduces overfitting
* However, class imbalance still affects recall for the minority class

## Key Takeaways

* Decision Trees are simple but prone to overfitting
* Random Forest improves performance by combining multiple trees
* Feature engineering (especially encoding categorical variables) is essential
* Imbalanced data can significantly impact model performance
