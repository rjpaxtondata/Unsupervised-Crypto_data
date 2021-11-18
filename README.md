# Using Unsupervised Learning for Cryptocurrency Data

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

There were a total of 532 cryptocurrencies with complete data that were trading when the data was uploaded.  

The PCA revealed 74 principal components (out of a potential 98), which explained 90% of the variance in the data. We then used TSNE to reduce the features in the data further. TSNE revealed that there were two features in the data based on its algorithm. A plot of the features is below.   

![image](https://user-images.githubusercontent.com/82011523/140857435-6aeed1c4-a7ff-4923-8dba-de2e3aa1453a.png)

Next, we used K-Means to determine whether we could reveal clusters in the data not otherwise obtained from the PCA output data. Based on the elbow plot, there were no distinguishable clusters.  As you can see in the figure below, there is no distinguishable elbow.

![image](https://user-images.githubusercontent.com/82011523/140857468-a5ee4539-e68d-4631-9007-4dd62f47ebd3.png) 
