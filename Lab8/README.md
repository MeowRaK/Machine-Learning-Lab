# Lab 8 – K-Nearest Neighbors (KNN)

This lab focuses on implementing and evaluating the K-Nearest Neighbors (KNN) algorithm on a synthetic dataset. The goal is to understand how distance-based classification works, why feature scaling matters, and how to choose an optimal value for K.

## Files

* [KNN_Project_Data](./KNN_Project_Data)
* [02_K_Nearest_Neighbors_Assignment.ipynb](./02_K_Nearest_Neighbors_Assignment.ipynb)

## Overview

### Data Loading

The dataset is loaded into a pandas DataFrame. It consists of multiple numerical features and a binary target column labeled `TARGET CLASS`.

### Exploratory Data Analysis (EDA)

A seaborn pairplot is used to visualize relationships between features and observe how the target classes are distributed.

### Feature Scaling

StandardScaler is applied to normalize the feature values. This step is essential because KNN relies on distance calculations, and unscaled features can distort results.

### Train-Test Split

The data is split into training and testing sets using a 70/30 ratio.

### Model Training

A KNN model is first trained using K = 1 to establish a baseline.

### Evaluation

Model performance is evaluated using:

* Confusion matrix
* Classification report (precision, recall, F1-score)

### Choosing K

The elbow method is used by testing multiple K values (1–39) and plotting error rate against K to find the optimal value.

### Final Model

The model is retrained using the optimal K (around 30), resulting in improved and more stable performance.

## Key Takeaways

* Feature scaling is critical for KNN performance
* Small K values can lead to overfitting
* Large K values can smooth predictions but risk underfitting
* Selecting the right K significantly improves accuracy and balance
