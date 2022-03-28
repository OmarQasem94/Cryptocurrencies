# Cryptocurrencies


## Overview of the Analysis

The purpose of this project was to use unsupervised machine learning to analyze a databse of cryptocurrencies and create a report that identifies the traded cryptocurrencies. The cruptocurrencies were classified based on their features. This classification report can be an utilized by investment banks to propose a new cryptocurrency investment portfolio to its clients.


## Results

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

The figure below is of a table that depicts all the tradable cryptocurrencies.

![Trips_by_Gender_WpH](https://github.com/OmarQasem94/bikesharing/blob/main/Resources/Trips_by_Gender_WpH.PNG)

* The majority of the cryptocurrencies belong to clsuters 0 and 1.
* BitTorrent is the only cryptocurrency that belongs to cluster 3. 

### Clustering Cryptocurrencies using K-Means - Elbow Curve

In this porion of the analysis the Elbow curve was utilized to determine the best number of clusters to use in the KMneas analysis. Upon analyzing the graph it was determined that the best number of clusters to categorize the cryptocurrencies was 4 (k=4).

![Client_Statistics](https://github.com/OmarQasem94/bikesharing/blob/main/Resources/Client_Statistics.PNG)

### Visualizing Cryptocurrencies Results

#### 3D Scatter Plot

The 3D scatter plot was obtained using the Princial Component Analysis (PCA) algorithm to reduce the dimensionality of the model to three principal components. The graph clearly shows all four clusters with the majority belonging to clusters 0 and 1. while cluster 3 consists of one outlier BitTorrent Crypto.

![Checkout_Times_for_Users](https://github.com/OmarQasem94/bikesharing/blob/main/Resources/Checkout_Times_for_Users.PNG)

#### 2D Scatter Plot

The 2D scatter plot was also obtained using the Princial Component Analysis (PCA) algorithm to reduce the dimensionality of the model to two principal components. The same inferences drawn from the 3d plot can be deduced from the 2d plot.

![Chechout_Times_by_Gender](https://github.com/OmarQasem94/bikesharing/blob/main/Resources/Checkout_Times_by_Gender.PNG)

## Summary

The objective of unsupervised machine learning models is to discover patterns or groups of data when there is no known output. That being said, this analysis was successful at grouping cryptocurrencies into 4 clusters. If we were to create a crypto investment portfolio we would need to further analyze the clusters and what belonging to each cluster means about the individual cryptocurrencies. 
