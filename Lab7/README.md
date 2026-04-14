# Lab 7 - Logistic Regression

This lab focuses on building a Logistic Regression model to predict whether a user clicks on an advertisement based on behavioral and demographic data.

## 📂 Files

- [advertising.csv](./advertising.csv) — Dataset used for training and testing the model  
- [02_Logistic_Regression_Assignment.ipynb](./02_Logistic_Regression_Assignment.ipynb) — Jupyter Notebook containing the full implementation  

---

## 📊 What Was Done

- Loaded and explored the dataset  
- Performed exploratory data analysis (EDA):
  - Histogram of Age  
  - Jointplots to analyze relationships between features  
  - Pairplot with class separation based on target variable  
- Selected relevant features for modeling:
  - Daily Time Spent on Site  
  - Age  
  - Area Income  
  - Daily Internet Usage  
  - Male  
- Split the dataset into training and testing sets  
- Trained a Logistic Regression model  
- Generated predictions on the test set  
- Evaluated the model using:
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-score)  

---

## 📈 Results

- Model achieved approximately **91% accuracy**  
- Strong separation between classes based on user behavior features  

---

## 📌 Notes

- Dataset is clean with no missing values  
- Logistic Regression performs effectively due to clear feature patterns  
