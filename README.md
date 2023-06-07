# Cryptocurrency-Cluster-Analysis-with-Unsupervised-Machine-Learning

This is an assignment that I completed for the George Washington University Data Analytics Bootcamp, focused on analysis using Unsupervised Machine learning. Specifically utilizing K Means, PCA, and StandardScaler.

## Background
In this project I am analyzing 42 cryptocurrencies in order to determine the effect of price changes over different periods of time.

## Organization
Inside of this repository is a readme file and a file labeled 'Code'. Inside of the folder is a Jupyter Notebook file named 'Crypto_Clustering_Jupyter.ipynb' which contains my analytical code. There is also a folder marked 'Resources' which contains a single csv data file named 'crypto_market_data.csv'.

## Overview
First I scaled all of the data in the imported dataframe. Then I determined the ideal K value for K Means using the elbow method. Next I clustered all of the values using K Means with k value determined previously.
Next I optimized clusters with Principal COmponent Analysis (PCA). I used these new values to calculate a new optimal value of K, and then I clustered the cryptocurrencies with K Means using the PCA data.

## Discussion
We found that with the scaled data and PCA data, that four clusters was the optimal configuration. However, cluster distribution was much clearer with the PCA method. This model showed a clear demarkation of clusters and a more distinct change in the slope of the elbow curve.

