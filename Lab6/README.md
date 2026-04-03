# Overview
This repository contains the submission for ARTI 308 – Lab 6, which focuses on applying regression techniques to an Ecommerce Customers dataset.

The objective of this lab is to build a machine learning model capable of predicting the yearly amount spent by a customer based on their behavior:

- Avg. Session Length  
- Time on App  
- Time on Website  
- Length of Membership  

Since the dataset is already clean (no missing values or inconsistencies), the main focus of this lab is on data exploration, feature selection, and building a regression model.

---

# Lab Objectives
The notebook performs the following steps:

- Load the dataset into a DataFrame  
- Explore the data using head, info, and describe  
- Perform basic data cleaning  
- Remove irrelevant columns (Email, Address, Avatar)  
- Define the target variable (Yearly Amount Spent)  
- Select appropriate features for modeling  
- Split the data into training and testing sets  
- Train a Linear Regression model  
- Evaluate model performance using regression metrics  

---

# Student Tasks
Task 1:  
Load the Ecommerce Customers dataset and explore its structure using head, info, and describe.

Task 2:  
Perform basic data cleaning and explain why non-relevant columns were removed.

Task 3:  
Prepare the dataset for modeling by defining features (X) and target variable (y), and splitting the data.

Task 4:  
Train a Linear Regression model and evaluate its performance using MAE, MSE, RMSE, and R².

---

# Repository Files
- [`ARTI308_Lab6_Ecommerce_Dataset.ipynb`](./ARTI308_Lab6_Ecommerce_Dataset.ipynb)  
  The main notebook containing the full workflow including data exploration, preprocessing, model training, and evaluation.

- [`Ecommerce Customers`](./Ecommerce%20Customers)  
  The dataset used for the regression task, containing customer behavior and spending data.

- [`README.md`](./README.md)  
  Documentation for this lab submission.

---

# Summary
This lab demonstrates how Linear Regression can be used to predict customer spending based on behavioral data. The model achieves strong performance, with a high R² score indicating that the selected features effectively explain the variation in yearly spending. The results show that Length of Membership and Time on App are key factors influencing customer spending.
