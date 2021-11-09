# Unsupervised Learning with Cryptocurrency Data

## Purpose

This project aimed to (a) use various unsupervised learning strategies and (b) determine whether select cryptocurrency data can be groups in distinct clusters.  

## Steps

* Preprocessing the data
* Dimension reduction via Principal Component Analysis (PCA)
* Use of the TNSE to further reduce data complexity
* Summarize with K-Means Cluster Analysis to determine relevant cluster

## Tools

*  Jupyter Lab
*  Opensource data from [Crypto Compare](https://min-api.cryptocompare.com/data/all/coinlist)
*  Packages: Pandas, Numbpy, matplotlib, sklearn

## Results

There were a total of 532 cryptocurrencies that did not have null values and were currently trading. 

The PCA revealed 74 principal components (out of a potential 98), which explained 90% of the variance in the data. We then used TSNE to reduce the features in the data further. TSNE revealed that there were two features in the data based on its algorithm. A plot of the features is below.   

![image](https://user-images.githubusercontent.com/82011523/140857435-6aeed1c4-a7ff-4923-8dba-de2e3aa1453a.png)

Next, we used K-Means to determine whether there could be different clusters.  Based on the elbow plot, there were no distinguishable clusters.  Based on a plot of these data, there was no elbow. See the figure below.

![image](https://user-images.githubusercontent.com/82011523/140857468-a5ee4539-e68d-4631-9007-4dd62f47ebd3.png) 
