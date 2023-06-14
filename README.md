# CryptoClustering

Unsupervised Learning model used to cluster groups of crypto currencies based on a vast array of market data to detect best-of-class assets.

# Steps:

* Found best value for k Using the Original Scaled DataFrame.
* Plotted elbow curve.
* Clustered Cryptocurrencies with K-means using originaly scaled data.
* Fitted the model to make precitions based on best elbow value.
* Created a scatter plot: x-axis = price change percentage in 24 hours; y-axis = the price change percentage in 7 days. 
* Colorred the points with the labels found using K-means and add the "coin_id" as a hover column.
* Optimized clusters with Principal Component Analysis.
* Plotted and overlapped both models to compare effiencies of models and elbow curves. 
