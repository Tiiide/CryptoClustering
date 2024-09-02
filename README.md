# CryptoClustering
Homework for Module 19 - Unsupervised Learning

This project involves the analysis and clustering of cryptocurrency data using K-Means clustering and Principal Component Analysis (PCA).

The goal is to identify the optimal number of clusters and to compare the clustering results using the original data and the PCA-reduced data.

We import data from a csv file and convert into Pandas DataFrames to analyze the ideal K-Means value for the K-Means clustering and PCA clustering by generating an Elbow Chart to visually identify where the inertia in the data drops. The distinct point in the curve (the elbow) here notes that our ideal k value is 3.

PCA Analysis effectively reduces the dimensionality of our data which provides more clear clustering results.