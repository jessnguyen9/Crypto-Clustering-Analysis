# Crypto Clustering Analysis

## Overview
In this project, the goal was to group different cryptocurrencies based on their market data to uncover hidden patterns and trends. By using a method called K-Means clustering, we were able to divide the cryptocurrencies into distinct groups, which helped us identify similarities and differences among them. These insights can be helpful for decision-making, such as making investment choices or crafting targeted marketing strategies.

We used two different methods to perform this clustering: one that kept all the data features (original data) and one that simplified the data by reducing the number of features (through PCA, a method for simplifying complex data). We compared these two methods to understand how using fewer features affects the clustering results.

## Techniques & Tools Used
**K-Means Clustering:** To group cryptocurrencies based on their market data.

**Principal Component Analysis (PCA):** A method used to simplify the data by reducing the number of features (or characteristics) while keeping the most important information.

**Python Libraries:** Pandas, NumPy, Matplotlib, and Scikit-learn for data manipulation and analysis.

**Data Visualization:** HVPlot for interactive visualizations, including scatter plots and elbow curves.

## Impact of Using Fewer Features for Clustering
When we reduced the number of features (or characteristics) that we used to group the cryptocurrencies, we noticed two key things:

1. **Easy to Understand:** With fewer features, the results were simpler and easier to visualize. The charts and graphs became less crowded, making it easier to see how the cryptocurrencies grouped together. This is especially helpful if you're trying to get a quick overview without getting lost in too many details.
2. **Less Detail in the Clusters:** On the flip side, using fewer features also meant that the clusters might not have been as precise. With less information to work with, the algorithm grouped some cryptocurrencies together that might have been more distinct if we had kept all the original features. So, while the results were easier to interpret, they may not have been as accurate in fully capturing the differences between each cryptocurrency.

In this analysis, we compared how the clusters looked when using fewer features (via PCA) and the original data. This allowed us to see how simplifying the data impacted the accuracy of the clusters, and to decide whether simplicity or precision was more important for our goals.

**K-Means Clustering: Cryptocurrency Price Change Patterns**

![Crypto Price Change Scatter Plot](https://github.com/user-attachments/assets/bff801b8-830a-4f23-bef8-6159661174a3)

**PCA Clustering: Dimensionality-Reduced Cryptocurrency Price Trends**

![Crypto Clustering Scatter Plot_pca](https://github.com/user-attachments/assets/775075dc-f5a3-4cd5-aa8c-0e91505ce45c)

## Cluster Analysis Results
**Choosing the Best Number of Clusters (k)**

To determine how many groups (or clusters) we should have, we used something called the Elbow Method. This method helped us visually find the best number of clusters. The result showed that k=4 was the best number, meaning that the data was best divided into four groups.

![Elbow Curve](https://github.com/user-attachments/assets/dabbc88c-94fe-490b-98b7-05b173789e36)

**Visualization of Results**

We used a scatter plot to show how the cryptocurrencies were grouped based on their two most important features (Principal Components). This helped us easily see the clusters and how the cryptocurrencies within each group were similar to one another.

## Conclusion
In this project, we used K-Means clustering to group cryptocurrencies into different categories based on market data. By comparing results from clustering with all features versus fewer features, we gained insights into how simplifying the data affects the interpretation of the results. Ultimately, this analysis provides valuable information for businesses looking to better understand cryptocurrency trends and make more informed decisions in areas like investment and marketing.
