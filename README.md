# 🛍️ Mall_Customer_Kmeans


# Overview

This project uses the K-Means clustering algorithm to segment mall customers based on spending behavior and annual income. By grouping customers into distinct clusters, businesses can tailor marketing strategies, optimize promotions, and improve customer engagement.

The dataset includes features such as Age, Annual Income, and Spending Score, which help identify high-value customers, understand spending patterns, and design personalized marketing campaigns.

# Dataset

The dataset consists of the following columns:

CustomerID		Unique identifier for each customer (not used for clustering)

Gender	Male/Female (can be encoded as 0/1 for ML)

Age		Age of the customer in years

Annual Income (k$)	Customer's annual income in thousands of dollars

Spending Score (1-100)		Score assigned based on customer spending behavior (higher = more spending)


# Workflow

1.Data Preprocessing

  Encode categorical features (e.g., Gender → 0/1)

  Drop irrelevant columns (CustomerID)

  Feature scaling (optional for better clustering performance)

2.Exploratory Data Analysis (EDA)

  Analyze distributions of Age, Income, and Spending Score

  Visualize relationships and trends

3.K-Means Clustering

  Determine the optimal number of clusters using the Elbow Method

  Fit the K-Means model on selected features

  Assign cluster labels to each customer

4.Visualization and Interpretation

  Plot clusters using scatter plots

  Analyze characteristics of each segment

# Key Insights

Each cluster represents a customer segment with similar spending patterns and income.

Typical segments include:

High-income, high-spending → Premium customers

Young, low-spending → Potential for targeted campaigns

Middle-aged, moderate-spending → Loyal customers

Older, low-spending → Cost-sensitive segment

Other niche segments
