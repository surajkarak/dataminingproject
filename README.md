# Google Analytics Customer Clustering

## Overview

This repository contains the code and analysis for clustering visitors to the Google Merchandise store using the Google Customer Revenue Prediction dataset from Kaggle. The goal is to gain insights into visitor behavior and segment them based on various features.

## Data Exploration

- **Channels and Affiliates:** Explored the distribution of visitors across different channels and affiliates to understand the sources of traffic.

- **Visitor Clustering:** Utilized k-means clustering to segment visitors based on features such as Channel Grouping, device category, and datetime variables.


## Data Preprocessing and Feature Engineering

- **Scaling Numerical Variables:** Used the StandardScaler to scale numerical variables such as visitNumber, totals.pageviews, etc.

- **One-Hot Encoding:** Encoded categorical variables to facilitate clustering.

## Clustering and Visualization

- **K-Means Clustering:** Applied k-means clustering to group visitors into distinct clusters.

- **Visualization:** Created visualizations to understand the distribution of visitors within each cluster, specifically focusing on the distribution of categorical variables.

## Results and Insights

- **Cluster Interpretation:** Analyzed the characteristics of each cluster to derive actionable insights into different visitor segments.

- **Categorical Variable Analysis:** Explored how categorical variables contribute to the clustering and identified patterns within each cluster.

## Instructions

1. **Data Setup:** Ensure you have the Google Customer Revenue Prediction dataset available.

2. **Run the Code:** Execute the provided Python code to reproduce the analysis and visualizations.

3. **Explore Results:** Refer to the generated visualizations and analysis in Jupyter notebooks or other relevant files.

## Dependencies

- Python 3.x
- Jupyter Notebooks
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Feel free to reach out if you have any questions or suggestions!
