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
        - Time between purchases.
        - Total invoice amounts.
        - Customer activity (invoice count).
        - Country (one-hot encoded).
2. **Data Normalization:**
    - Applies StandardScaler to normalize the selected features, ensuring that they have zero mean and unit variance.
3. **Model Building and Evaluation:**
    - Uses the K-Means clustering algorithm to group customers.
    - Determines the optimal number of clusters using the Elbow method.
    - Evaluates the clustering performance using the Silhouette score.
4. **Cluster Visualization:**
    - Employs Principal Component Analysis (PCA) to reduce the dimensionality of the data for visualization purposes.
    - Creates a scatter plot to visualize the clusters in a two-dimensional space.




## Usage

1. Install the required libraries.
2. Download the "Online Retail.xlsx" dataset and place it in the same directory as the notebook.
3. Open the notebook and execute the cells sequentially.


## Conclusion

This notebook provides a basic framework for customer segmentation using K-Means clustering. Further analysis and interpretation of the clusters can be performed to gain insights into customer behavior and develop targeted marketing strategies.
