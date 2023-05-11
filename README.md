# Unsupervised Learning Analysis of Crypto Currencies: 'CryptoClustering'

This code applies K-Means and Principal Component Analysis (PCA) to cluster cryptocurrencies based on performance over 7 different holding periods. The analysis could be replicable to other financial series, with large amount of data thanks to the use of PCA, which reduces the dimensionality of the data. The analysis found the same number and composition of clusters (4) when using the original standardized data of 7 series of returns than when using its 3 principal components. These three principal components explained 90% of the variance of the cryptocurrencies' returns.

## Technologies
Technologies used in the analysis are:
Scikit-learn machine learning tools for the unsupervised data analysis. Tools such as Cluster, StandardScaler, Preprocessing, Decomposition, Data Standardization, and Principal Component Analysis.

Pandas, NumPy and Path libraries for general coding,
hvPlot, Plotly Express, Holoviews for visualizations


