# 🛍️ Mall_Customer_Kmeans


# Overview

This project uses the K-Means clustering algorithm to segment mall customers based on spending behavior and annual income. By grouping customers into distinct clusters, businesses can tailor marketing strategies, optimize promotions, and improve customer engagement.

The dataset includes features such as Age, Annual Income, and Spending Score, which help identify high-value customers, understand spending patterns, and design personalized marketing campaigns.

# Dataset

| Feature                | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| CustomerID             | Unique identifier for each customer (not used for clustering)      |
| Gender                 | Male/Female (can be encoded as 0/1 for ML)                         |
| Age                    | Age of the customer in years                                       |
| Annual Income (k\$)    | Customer's annual income in thousands of dollars                   |
| Spending Score (1-100) | Score assigned based on spending behavior (higher = more spending) |

# Why K-Means?

K-Means is an unsupervised learning algorithm used for clustering:

  Groups data points into k clusters based on similarity
  Minimizes intra-cluster variance (distance from cluster center)
  Useful for discovering patterns without labeled data
  Helps businesses target specific customer segments effectively

# Project Workflow

1.Data Preprocessing

  Encode categorical features (e.g., Gender → 0/1)

  Drop irrelevant columns (CustomerID)

  Feature scaling (optional, improves clustering performance)

2.Exploratory Data Analysis (EDA)

  Analyze distributions of Age, Annual Income, and Spending Score

  Visualize relationships and trends using histograms, boxplots, and scatter plots

3.K-Means Clustering

  Determine the optimal number of clusters using the Elbow Method

  Fit the K-Means model on selected features (Annual Income & Spending Score)

  Assign cluster labels to each customer

4.Visualization and Interpretation

  Scatter plots of clusters to visualize segmentation

  Analyze characteristics of each segment to identify actionable insights
