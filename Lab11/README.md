# Credit Card Customer Segmentation — Lab 11

This repository contains the completed implementation of **Lab 11: Credit Card Customer Segmentation** using unsupervised machine learning techniques.

The lab focuses on analyzing customer behavior from credit card usage data and grouping customers into meaningful segments using **K-Means Clustering**.

---

# 📌 Lab Overview

In this lab, we performed customer segmentation on the `CC_GENERAL.csv` dataset using clustering techniques. The goal was to identify different types of credit card users based on their financial behavior and transaction patterns.

The notebook includes:

- Data preprocessing
- Handling missing values
- Exploratory Data Analysis (EDA)
- Feature scaling
- K-Means clustering
- Elbow method
- Silhouette score analysis
- Cluster visualization using PCA
- Customer segment interpretation

---

# 📂 Files

- [02-Credit_Card_Customer_Segmentation_Assignment.ipynb](./02-Credit_Card_Customer_Segmentation_Assignment.ipynb)
- [CC_GENERAL.csv](./CC_GENERAL.csv)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📊 Tasks Performed

## 1. Data Loading and Exploration
- Loaded the dataset using Pandas
- Displayed dataset shape, info, and summary statistics
- Inspected the first rows of the dataset

## 2. Data Cleaning
- Removed the `CUST_ID` column
- Checked for missing values
- Applied mean imputation to handle missing data

## 3. Exploratory Data Analysis (EDA)
- Created histograms for numerical features
- Generated a correlation heatmap
- Visualized relationships between:
  - `BALANCE` vs `PURCHASES`
  - `BALANCE` vs `CASH_ADVANCE`

## 4. Feature Scaling
- Standardized all numerical features using `StandardScaler`
- Prepared scaled data for clustering

## 5. K-Means Clustering
- Applied the Elbow Method to determine optimal K values
- Calculated silhouette scores for cluster evaluation
- Selected the final number of clusters
- Trained the final K-Means model

## 6. Cluster Analysis
- Added cluster labels to the dataset
- Created a cluster summary table using group averages
- Analyzed customer behavior patterns for each segment

## 7. PCA Visualization
- Reduced dimensions using PCA
- Visualized customer clusters in 2D space

---

# 🎯 Final Customer Segments

The final clustering model identified four major customer groups:

- Regular Active Purchasers
- High-Value Premium Spenders
- Cash Advance Dependent Customers
- Low Activity / Passive Users

These segments can help companies improve marketing strategies, customer retention, and financial product recommendations.

---

# 📈 Machine Learning Concepts Used

- Unsupervised Learning
- K-Means Clustering
- Standardization
- Elbow Method
- Silhouette Score
- Principal Component Analysis (PCA)

---

# 🚀 Goal of the Lab

The objective of this lab is to understand how unsupervised machine learning can be used to discover hidden customer behavior patterns and create meaningful customer segments for business decision-making.
