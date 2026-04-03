# ARTI308 Lab 6 – Ecommerce Customers

## Overview
This lab applies machine learning concepts on a new dataset: **Ecommerce Customers**.  
The goal is to build a predictive model to estimate how much a customer spends yearly based on their behavior.

---

## Files Included
- [`Ecommerce Customers`](./Ecommerce%20Customers)  
  Dataset containing customer information and spending behavior.

- [`ARTI308_Lab6_Ecommerce_Dataset.ipynb`](./ARTI308_Lab6_Ecommerce_Dataset.ipynb)  
  Jupyter Notebook with the full workflow: data exploration, preprocessing, modeling, and evaluation.

---

## Tasks Completed
- Loaded the dataset into a DataFrame  
- Explored the data using:
  - `head()`
  - `info()`
  - `describe()`  
- Performed basic data cleaning:
  - Checked for missing values
  - Removed irrelevant columns (`Email`, `Address`, `Avatar`)  
- Applied feature selection (no complex feature engineering required)  
- Prepared the data for modeling:
  - Defined features (X) and target (y)
  - Split into training and testing sets  
- Trained a **Linear Regression** model  
- Evaluated model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score  

---

## Model Performance
The Linear Regression model performed very well:
- R² Score ≈ **0.98**
- Low prediction error (RMSE ≈ 10)

---

## Key Insights
- **Length of Membership** is the strongest predictor of spending  
- **Time on App** has more impact than **Time on Website**  
- The dataset required minimal preprocessing  
