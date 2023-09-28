# Social Media Engagement Analysis

## Overview
This project aims to analyze and cluster social media content based on user engagement. It involves preprocessing, clustering, and visualizing social media data to gain insights into how different types of content perform in terms of user reactions, comments, and shares.

## Description
In today's digital age, understanding user engagement with social media content is crucial for individuals and businesses alike. This project offers a comprehensive analysis of social media data, particularly focusing on the types of content (e.g., videos, photos, links, statuses) and their corresponding engagement metrics (e.g., reactions, comments, shares).

## Key Steps:
Data Preprocessing: The project begins with loading a dataset containing social media posts. We perform initial exploratory data analysis (EDA) to understand the dataset's structure, check for missing values, and eliminate unnecessary columns.

Data Encoding: Categorical variables, such as "status_type" (content type), are encoded into numerical values using Label Encoding to make them suitable for clustering algorithms.

Feature Scaling: We normalize the data using Min-Max scaling to ensure that each feature contributes equally to the clustering process.

Cluster Analysis: The main analysis involves clustering the data using the K-Means clustering algorithm. We use the "elbow method" to determine the optimal number of clusters, and then perform the clustering.

Cluster Visualization: The clusters are visualized in two ways. First, we plot the clusters against the "num_reactions" and "status_type" features to understand how different content types perform. Second, we visualize the clusters against the "num_comments" and "status_type" features.

Correlation Analysis: We explore the correlations between the features using a heatmap to identify potential patterns in user engagement.

Distribution Analysis: We visualize the distribution of "num_reactions" to understand how engagement varies across different content types.

## Results
This project provides insights into how different types of social media content drive user engagement. It helps users and businesses understand which content types are more likely to receive reactions, comments, and shares, allowing for more effective content strategies.
