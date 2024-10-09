# customer--segmentation2
# Customer Segmentation with K-Means Clustering

## Overview

This  Notebook demonstrates customer segmentation using the K-Means clustering algorithm applied to the "Online Retail" dataset. The goal is to group customers based on their purchasing behavior and characteristics.

## Stages

1. **Data Loading and Preprocessing:**
    - Imports necessary libraries (pandas, numpy, matplotlib, seaborn, sklearn).
    - Loads the "Online Retail.xlsx" dataset into a pandas DataFrame.
    - Handles missing values by removing rows with missing 'CustomerID'.
    - Performs feature engineering to create relevant features for segmentation, including:
        - Invoice frequency (monthly, yearly, daily, hourly).
        - recency
        - Total amount
        - Time between purchases.
        - Total invoice amounts.
        - Customer activity (invoice count).
        - Country (one-hot encoded).
2. **Data Normalization:**
    - Applies StandardScaler to normalize the selected features, ensuring that they have zero mean and unit variance.
3. **Model Building and Evaluation:**
    - Uses the K-Means clustering algorithm to group customers.
    - Determines the optimal number of clusters using the Elbow method. in this plot the elbow appears to be around 4 clusters making  4 a good choice for the number of clusters. 
    - Evaluates the clustering performance using the Silhouette score.
4. **Cluster Analysis:**
   - Visualizing the clusters using PCA and scatter plots.
   - Analyzing cluster profiles based on mean values of key features.
   - Investigating feature distributions within clusters using box plots.


## Results

- The analysis identifies distinct customer segments with varying purchasing patterns.
- The clusters are visualized and their characteristics are explored.
- The notebook provides insights into customer behavior and potential strategies for targeted marketing.




## Conclusion

This notebook provides a basic framework for customer segmentation using K-Means clustering.
