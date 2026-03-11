# ARTI 308 – Lab 5: Feature Engineering for Order Status Prediction

## Overview
This repository contains the submission for **ARTI 308 – Lab 5**, which focuses on applying **feature engineering techniques to a classification problem** using a Talabat-style food delivery dataset.

The objective of this lab is to build a **baseline machine learning model** capable of predicting the status of an order:

- Delivered  
- Cancelled  
- In Transit  

Since the dataset provided is already clean (no missing values, duplicates, or inconsistent data types), the main focus of this lab is on **creating meaningful engineered features and evaluating their impact on model performance**.

---

## Lab Objectives
The notebook performs the following steps:

- Load and inspect the dataset  
- Define the target variable (`Order_Status`)  
- Select appropriate predictors while avoiding data leakage  
- Engineer new features including:
  - Time-based features
  - Price-based features
  - Distance-based features
- Reduce high-cardinality categorical variables  
- Encode categorical features  
- Train a **baseline Random Forest classifier**  
- Evaluate model performance  
- Analyze **feature importance**

---

## Student Tasks

**Task 1:**  
Create a new engineered feature and justify why it may help predict the order status.

**Task 2:**  
Test a different rule for identifying **peak order hours** and discuss whether the model performance changes.

**Task 3:**  
Experiment with different values of `top_k` when reducing item categories (e.g., 10, 30, 50) and compare model accuracy and feature importance.

**Task 4:**  
Run the optional **feature selection section** and explain whether it improved the model performance.

---

## Repository Files

- [ARTI308 Lab5.ipynb](ARTI308%20Lab5.ipynb)  
  The main notebook containing the complete workflow including data inspection, feature engineering, model training, evaluation, and the student task solutions.

- [talabat_enhanced_orders.csv](talabat_enhanced_orders.csv)  
  The dataset used for the classification task, containing order, driver, restaurant, and delivery information.

- [README.md](README.md)  
  Project description and documentation for this lab submission.

---

## Summary
This lab demonstrates how **feature engineering can significantly impact machine learning performance**. By creating time-based, price-based, and distance-based features and reducing categorical complexity, the model is better able to capture patterns that influence delivery outcomes. Feature importance analysis also provides insights into which variables contribute most to predicting order status.
