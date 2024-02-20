# Customer Segmentation Analysis

## Overview

This project aims to perform customer segmentation analysis using data sourced from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). The analysis involves steps such as data cleaning, feature engineering, dimensionality reduction, clustering, and evaluation of the formed clusters.

## Steps in the Analysis

### Data Cleaning

- Missing values: Dropping rows with missing income values.
- Feature Engineering:
  - Creating a feature indicating the number of days a customer is registered in the firm's database relative to the most recent customer.
  - Extracting age from birth year.
  - Creating features such as "Spent", "Living_With", "Children", "Family_Size", and "Is_Parent".
  - Simplifying and categorizing the "Education" feature.
- Handling discrepancies and outliers.

### Data Preprocessing

- Label encoding categorical features.
- Scaling features using standard scaler.
- Creating a subset dataframe for dimensionality reduction.

### Dimensionality Reduction

- Utilizing Principal Component Analysis (PCA) to reduce dimensions to 3.
- Plotting the reduced dataframe.

### Clustering

- Determining the number of clusters using the Elbow Method.
- Performing clustering via Agglomerative Clustering.
- Examining clusters formed via scatter plot.

### Evaluating Models

- Studying cluster patterns through exploratory data analysis.
- Drawing conclusions based on cluster characteristics.

### Profiling

- Profiling clusters to understand customer traits.
- Analyzing personal traits of customers within each cluster.

## Insights from Clustering

- **Cluster 0:**
  - Likely parents with 2 to 4 family members, including single parents.
  - Mostly have teenagers at home.
  - Generally older in age.
- **Cluster 1:**
  - Not parents.
  - Typically 2 members in the family, mostly couples.
  - Represent various age groups.
  - High income earners.
- **Cluster 2:**
  - Mostly parents.
  - Families usually consist of 3 members with one child (not teenagers).
  - Generally younger.
- **Cluster 3:**
  - Definitely parents.
  - Families range from 2 to 5 members.
  - Majority have teenagers at home.
  - Older in age and lower-income group.

## Conclusion

This analysis provides insights into customer segmentation based on various personal and demographic traits. Understanding these clusters can aid marketing strategies and customer engagement efforts.

