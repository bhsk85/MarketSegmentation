# Market Segmentation in Insurance

## Objective:
This case requires developing a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. for target customer groups.

![Image](https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png)

## Data Description:
The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

## Data:
You can download the dataset using the following link: [Clustered_Customer_Data.csv]([https://github.com/pik1989/MarketSegmentation/blob/main/Clustered_Customer_Data.csv](https://github.com/bhsk85/MarketSegmentation/blob/main/Clustered_Customer_Data.csv))

## Algorithms Used:
In this dataset, we have used five clustering algorithms to perform segmentation. These algorithms are as follows:

- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [Spectral Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [Gaussian Mixture Model-based Clustering](https://en.wikipedia.org/wiki/Mixture_model)

## Final Model:
We have created a Streamlit Application based on these clustering techniques, where we take customer details and identify which cluster the customer belongs to.

This project was made by Team Leader Baba, along with Team Members Greeshma and Shiny.
