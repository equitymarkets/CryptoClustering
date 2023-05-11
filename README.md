# CryptoClustering

<img width="100%" alt="crypto" src="https://user-images.githubusercontent.com/49753517/236657720-d696e37e-ad4d-4d61-83d0-c426c23f7356.png">



Let's analyze some cryptocurrencies!
Given an unsupervised learning environment, k-means clustering and Principal Component Analysis, or PCA, are two ways in which we can try to predict unknown values. First, we must run the calculation for the elbow curve to determine where increasing k (x) would bring little decrease in inertia (y), and in both cases here k = 4 gives us this outcome. In the first section we develop ten clusters then test the data. In the second section we use the elbow method to determine that we will test four clusters in the original data. 
PCA can capture as much as possible while minimizing noise in the output. It is often used to smooth the data before applying k-means tests. In the third section we again test ten clusters to run an elbow test and determine an optimal k value of four. In the fourth section we then run the four-cluster k-means on the PCA-adjusted data. 
You can see differences in theh data when comparing the plots side-by-side. 
