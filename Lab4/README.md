
# Lab 4: Data Quality Assessment & Preprocessing

**Name:** Rakan Albinsaad  
**Section:** MY02  

---

## Overview

In this lab, data preprocessing techniques were applied to the Ames Housing dataset to improve data quality and prepare the dataset for machine learning modeling. The lab focused on identifying data quality issues, handling missing values, detecting and removing outliers, normalizing numerical features, and applying Principal Component Analysis (PCA) for dimensionality reduction.

The dataset represents a **regression problem**, where the target variable is:

**SalePrice** — The property's sale price.

---

## Dataset

The dataset used is the Ames Housing dataset (Kaggle House Prices competition).

---

## Files Included

- [`train.csv`](./train.csv) — The dataset used for preprocessing  
- [`CCSIT_ARTI308_Lab4.ipynb`](./CCSIT_ARTI308_Lab4.ipynb) — Jupyter Notebook containing the full Lab 4 implementation  

---

## Tasks Completed

### Task 1: Identify Data Quality Issues
- Checked for missing values
- Checked for duplicate rows
- Examined data types
- Identified numerical and categorical features

### Task 2: Handle Missing Values
- Applied **median imputation** to numerical columns
- Median was chosen because it is robust to outliers and suitable for skewed distributions

### Task 3: Detect and Handle Outliers (IQR Method)
- Used the Interquartile Range (IQR) method
- Calculated lower and upper bounds
- Removed extreme values outside the acceptable range

### Task 4: Normalize Numerical Features
Applied two normalization techniques:

- **Min-Max Scaling**
  - Scales values between 0 and 1

- **Z-Score Normalization (Standardization)**
  - Mean = 0
  - Standard Deviation = 1

### Task 5: Apply PCA
- Applied Principal Component Analysis (PCA) on standardized numerical features
- Plotted cumulative explained variance
- Analyzed how many components are needed to retain most of the dataset variance

---

## Conclusion

This lab demonstrated essential preprocessing techniques required before building machine learning models. The dataset was cleaned, normalized, and transformed using PCA to prepare it for future modeling tasks.

---

End of Lab 4.
