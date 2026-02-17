# Lab 3: Exploratory Data Analysis (EDA)

**Name:** Rakan Albinsaad  
**Section:** MY02  

---

## Overview

In this lab, Exploratory Data Analysis (EDA) was performed on the Ames Housing dataset.  
The objective was to explore and understand the dataset before applying machine learning models. The analysis focused on identifying data structure, detecting missing values, examining distributions, analyzing relationships between variables, and discovering potential outliers.

The problem addressed in this dataset is a **regression problem**, where the goal is to predict:

**SalePrice** — the property's sale price.

---

## Dataset

The dataset used is the Ames Housing dataset from the Kaggle House Prices competition.  
It contains 79 explanatory variables describing residential homes in Ames, Iowa.

---

## Files Included

- [`train.csv`](./train.csv) — The training dataset used for analysis  
- [`data_description.txt`](./data_description.txt) — Official description of all dataset variables  
- [`CCSIT_ARTI308_Lab3.ipynb`](./CCSIT_ARTI308_Lab3.ipynb) — Jupyter Notebook containing the full EDA process  

---

## EDA Process

### 1. Data Inspection
- Loaded the dataset using Pandas  
- Examined dataset shape (rows and columns)  
- Reviewed column names and data types  
- Generated summary statistics  

### 2. Data Cleaning Checks
- Identified missing values  
- Checked for duplicate rows  
- Verified data types  

### 3. Univariate Analysis
- Analyzed the distribution of the target variable (SalePrice)  
- Examined distributions of important numerical features such as GrLivArea  

### 4. Bivariate Analysis
- Explored relationships between SalePrice and:
  - OverallQual  
  - GrLivArea  
  - Neighborhood  
- Visualized patterns using scatter plots and boxplots  

### 5. Correlation Analysis
- Computed correlation matrix  
- Identified features strongly correlated with SalePrice  
- Visualized correlations using a heatmap  

### 6. Time-Based Analysis
- Combined YrSold and MoSold to analyze monthly sale trends  
- Examined how average SalePrice changes over time  

### 7. Outlier Detection
- Investigated extreme values in living area and sale price  
- Identified potential outliers visually  

---

## Conclusion

The EDA provided a clear understanding of the dataset structure, key influencing variables, and potential data issues. These insights form the foundation for future preprocessing and model development stages.

---

End of Lab 3.
