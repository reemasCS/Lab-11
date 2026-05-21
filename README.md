# Lab 11: K-Means Clustering

This repository contains Lab 11 for the Machine Learning course. The lab focuses on using the K-Means algorithm to group credit card customers based on their spending and usage habits.

## Lab Summary
Since the dataset does not have any predefined target labels, this is an Unsupervised Learning problem. The goal is to find hidden patterns and cluster similar customers together.

## Dataset
We used the `CC_GENERAL.csv` dataset, which contains credit card usage data like:
* BALANCE: Account balance.
* PURCHASES: Total purchases made.
* CASH_ADVANCE: Cash withdrawals.
* CREDIT_LIMIT: Maximum credit limit.

## Steps Done
1. Cleaned the data by removing `CUST_ID` and filling missing values with the mean.
2. Explored the data using histograms and a correlation heatmap.
3. Scaled the features using `StandardScaler`.
4. Found the optimal number of clusters using the Elbow Method and Silhouette Score.
5. Trained the K-Means model with K = 4.
6. Visualized the clusters in 2D using PCA.

## Customer Groups Identified
* Cluster 0: Average users with normal balances and spending.
* Cluster 1: Active buyers who make frequent purchases.
* Cluster 2: Customers who maintain high balances and mostly use cash advances.
* Cluster 3: VIP customers with high credit limits and big spending.

## Tools Used
* Python 3
* Google Colab
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-Learn
