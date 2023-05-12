# CryptoClustering

## Overview

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Also, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

## Steps

- Load and preprocess the data.
- Scale the data using StandardScaler.
- Find the best value for k using the elbow method.
- Cluster cryptocurrencies with K-means using the original scaled data.
- Perform PCA to reduce the features to three principal components.
- Find the best value for k using the PCA data.
- Cluster cryptocurrencies with K-means using the PCA data.
- Visualize and compare the results using hvPlot.

Results
The project includes the following visualizations:

Elbow curve for the original data.

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/26535af3-0295-46ea-95e9-0f10c54d17a3)

Scatter plot of cryptocurrency clusters based on the original data:

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/e80223e1-b81d-4436-a5b2-35ebd06cb908)

Elbow curve for the PCA data.

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/200e4835-75aa-4641-91cb-d09846a82e49)

Scatter plot of cryptocurrency clusters based on the PCA data.

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/41bf61de-dea9-429c-8a6c-e53a305c0da6)

Combined Elbow curves ( with original data and PC data)

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/f429353e-7be6-40ae-8c8f-2ef74a86f03f)

Scatter plot of cryptocurrency clusters based on original data and PC data

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/7fb76c86-7278-44f2-bed4-f18ca80b1c76)

![image](https://github.com/Swetavirani/CryptoClustering/assets/102982635/c5701e99-8a8a-4e35-a926-f62363e58e4b)


Conclusion
The project analyzes the impact of using fewer features on clustering the data using K-means. Using fewer features in the clusters had no major changes to the cluster analysis results. However, the cluster were closer together using fewer features as compared to all features
