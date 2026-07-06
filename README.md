# DBSCAN Clustering Analysis

This project applies **DBSCAN** to perform clustering on numerical data and identify groups of similar observations based on density.  
Unlike K-Means, DBSCAN does not require specifying the number of clusters in advance and can also detect **noise points / outliers**.

The workflow includes:
- loading and preparing the dataset
- training an initial **DBSCAN** model
- examining the generated cluster labels
- evaluating clustering quality using **Silhouette Score**
- tuning **`eps`** and **`min_samples`** to improve the clustering result

This project demonstrates how **density-based clustering** can be used to discover natural patterns in data and evaluate the quality of the resulting clusters.
