# Understanding-Mall-Shoppers-K-Means-Clustering-for-Customer-Insights

K-Means Clustering
•	This Python script performs K-Means clustering on a dataset of mall customers to segment them based on their annual income and spending scores.
Description:

The script follows these steps:

•	Importing the Libraries: Imports necessary libraries including NumPy, Matplotlib, and Pandas.

•	Importing the Dataset: Reads the dataset containing information about mall customers. It assumes the dataset is stored in a CSV file named 'Mall_Customers.csv'.

•	Using the Elbow Method: Determines the optimal number of clusters using the elbow method. 

•	This involves fitting the K-Means algorithm with different numbers of clusters and plotting the within-cluster sum of squares (WCSS) against the number of clusters.

•	Training the K-Means Model: Trains the K-Means model with the optimal number of clusters determined from the elbow method.

•	Visualizing the Clusters: Plots the clusters along with their centroids to visualize the segmentation of mall customers based on their annual income and spending score.

