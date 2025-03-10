# Crypto Clustering Analysis

## Overview
This analysis focuses on clustering cryptocurrencies based on key metrics such as price, market capitalization, trading volume, and volatility. By utilizing machine learning techniques, specifically K-means clustering, the goal was to group cryptocurrencies with similar characteristics, offering insights into market behavior. These insights are intended to guide investors, traders, and analysts in understanding cryptocurrency trends, identifying potential investment opportunities, and evaluating market risks.

## Techniques & Tools Used
**Data Preprocessing:** Pandas was used to clean the dataset, handling missing values and outliers. Data was transformed and scaled using StandardScaler to ensure fair comparisons between cryptocurrencies.

**Clustering Algorithm:**
- **K-means clustering** was implemented to group cryptocurrencies into clusters based on similarities across multiple features such as market cap, price, and volatility.
- The optimal number of clusters was determined using the **Elbow Method** and **Silhouette Score**, ensuring that the clusters were both meaningful and interpretable.

**Demensionality Reduction:** **PCA (Principal Component Analysis)** was used to reduce the dimensionality of the dataset, visualizing the clusters in two dimensions while retaining key variance across features.
