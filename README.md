# DataMining_Homework4

# Problem 1: Auto MPG
I loaded the Auto MPG dataset from UCI, selected only continuous features, and filled missing values with column means. After standardizing the data, I applied Agglomerative Clustering with average linkage and Euclidean distance, targeting 3 clusters. The resulting cluster means and variances were compared with the 'origin' labels, revealing some overlap but no strong one-to-one correspondence.

# Problem 2: Boston Housing
I loaded and standardized the Boston dataset, then performed KMeans clustering with k ranging from 2 to 6. Using the Silhouette score, I identified k=2 as optimal. Cluster-wise feature means showed clear differences, and the inverse-transformed centroids closely matched those means, indicating well-defined and interpretable clusters.

# Problem 3: Wine Dataset
I used the sklearn wine dataset, standardized the features, and clustered the data into 3 groups using KMeans. Comparing with the true class labels, I computed a homogeneity score of 0.8788 and completeness score of 0.8730, showing that the clustering result strongly aligned with the actual class structure.
