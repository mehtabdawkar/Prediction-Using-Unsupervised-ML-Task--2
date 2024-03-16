# Prediction-Using-Unsupervised-ML-Task--2
Objective-Clustering of Iris Dataset
From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually.
Alogrithm Used - K-Means
K-means is a centroid-based algorithm, or a distance-based algorithm, where we calculate the distances to assign a point to a cluster. In K-Means, each cluster is associated with a centroid.
Workflow behind Implemention of K-Means Clustering:
Determine the desired number of clusters, denoted as 'k'.
Randomly select 'k' data points from the dataset to serve as initial cluster centroids.
Assign each data point to the nearest cluster centroid based on their distances.
Update the centroids of the clusters by computing the mean of all data points assigned to each cluster.
Repeat steps 3 and 4 until convergence is achieved, i.e., when the centroids no longer change significantly or a specified number of iterations is reached.
