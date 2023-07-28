# Cryptocurrency Clustering 

**Overview**

This project aims to analyze and cluster cryptocurrencies based on their market performance data. The data includes various price change percentages over different time periods for a selection of cryptocurrencies. The clustering is performed using the K-Means algorithm, both with the original data and with the data reduced using Principal Component Analysis (PCA).

**Analysis**

The analysis of the cryptocurrency market data through clustering using K-Means with the original data and PCA data yields interesting insights:
* Original Data Clustering: The Elbow method suggests that the optimal number of clusters (k) is 4. However, when visualizing the clusters, there is some overlap between data points, making it challenging to clearly differentiate the clusters. This indicates that using all the original features may not fully capture the underlying patterns.
* PCA Data Clustering: The Elbow method for PCA data also suggests that the optimal number of clusters is 4. However, when visualizing the clusters with PCA data, the clusters are more well-defined and separate. This indicates that the principal components were able to capture essential information from the data while reducing its dimensionality, leading to more distinct and better-separated clusters.
* Impact of PCA: By applying PCA, the clustering process is simplified, and the interpretability of the results is improved. Reducing dimensionality helps in better understanding the market dynamics and identifying groups of cryptocurrencies with similar price change patterns.

**Conclusion**
Overall, using PCA data results in clearer and more meaningful clusters, providing valuable insights into the cryptocurrency market. The reduced complexity and improved interpretability make it easier to analyze market trends and make informed investment decisions.

