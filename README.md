# CryptoClustering

Unsupervised Learning model used to cluster groups of crypto currencies based on a vast array of market data to detect best-of-class assets.

# Steps:

* Found best value for k Using the Original Scaled DataFrame.
* Plotted elbow curve.
 <img width="720" alt="Screen Shot 2023-06-14 at 2 05 13 AM" src="https://github.com/Phil-Mart/CryptoClustering/assets/120279988/1cbfbc41-fe46-4068-9e09-e0b3648b7a7a">

* Clustered Cryptocurrencies with K-means using originaly scaled data.
* Fitted the model to make precitions based on best elbow value.
* Created a scatter plot: x-axis = price change percentage in 24 hours; y-axis = the price change percentage in 7 days. 
* Colorred the points with the labels found using K-means and add the "coin_id" as a hover column.
<img width="720" alt="Screen Shot 2023-06-14 at 2 05 39 AM" src="https://github.com/Phil-Mart/CryptoClustering/assets/120279988/da50fde8-ed7e-4749-b2a5-607ad8a1a9a0">


* Optimized clusters with Principal Component Analysis.
* Plotted and overlapped both models to compare effiencies of models and elbow curves. 
<img width="720" alt="Screen Shot 2023-06-14 at 2 06 08 AM" src="https://github.com/Phil-Mart/CryptoClustering/assets/120279988/cdf5e68b-4c5f-431b-a174-807b54061b63">
<img width="720" alt="Screen Shot 2023-06-14 at 2 06 50 AM" src="https://github.com/Phil-Mart/CryptoClustering/assets/120279988/a484cecb-81de-4e12-8273-e472c730691f">



# Conclusion

After visually analyzing the cluster analysis results, the impact of using fewer features to cluster the data using K-Means in a PCA model resulted in two distinct clusters that are closer to each other than the original model. Only one coin represents group 2 & 3's clusters in the PCA scatter plot.

# [Linkedin Profile](linkedin.com/in/phil-mart) 
