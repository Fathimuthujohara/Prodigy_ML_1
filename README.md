## Customer Segmentation with K-Means Clustering

This project demonstrates how to group customers of a retail store based on their purchase history using the K-means clustering algorithm. By understanding customer segments, businesses can tailor marketing strategies, improve customer satisfaction, and boost sales.

## Overview

In this project, we apply the K-means clustering algorithm to segment customers based on their demographic and purchasing information. The key steps include data preprocessing, exploratory data analysis (EDA), feature scaling, clustering, and visualization.

## Dataset

The dataset used in this project contains information about customers such as:
- Customer ID
- Age
- Gender
- Annual Income (k$)
- Spending Score (1-100)

Spending Score is assigned based on customer behavior and purchasing data.

## Exploratory Data Analysis

In the exploratory data analysis (EDA) phase, we thoroughly examine the dataset to gain insights and understand its structure. This involves checking for any missing values and handling them appropriately to maintain data integrity. We summarize the dataset using basic statistical measures to grasp the central tendencies, dispersion, and overall distribution. Additionally, we visualize the distribution of key features such as 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)' using histograms and KDE plots. These visualizations help us identify patterns and anomalies, providing a solid foundation for subsequent analysis.

## Clustering

The core of this project is the application of the K-means clustering algorithm to segment customers based on their demographic and purchasing behavior. We begin by selecting relevant features for clustering, specifically 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'. These features are standardized to ensure they are on the same scale, which is crucial for the accuracy of the K-means algorithm. To determine the optimal number of clusters, we use the Elbow Method, which involves plotting the within-cluster sum of squares (WCSS) for various numbers of clusters and identifying the "elbow point" where the rate of decrease sharply slows down. This optimal number of clusters is then used to perform the K-means clustering, resulting in distinct customer segments.

## Visualization

Visualizing the clusters helps us understand the characteristics of each customer segment. We use various plots to analyze the clusters in detail. For instance, a 3D scatter plot shows the distribution of customers based on their age, annual income, and spending score, color-coded by cluster. Additionally, we apply Principal Component Analysis (PCA) to reduce the dimensionality of the data and visualize the clusters in a 2D space.

## Cluster Analysis

To understand the distinct characteristics of each cluster, we compute the mean values of the features within each cluster. This analysis provides insights into the demographics and purchasing behavior of different customer segments, enabling businesses to tailor their strategies accordingly.

## Additional Visualizations

We further analyze the clusters using additional visualizations such as pair plots and box plots. Pair plots help us visualize the pairwise relationships between features within each cluster, while box plots show the distribution of features within each cluster, highlighting the variations and central tendencies.

