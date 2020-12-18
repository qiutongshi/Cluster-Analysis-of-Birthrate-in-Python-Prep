# clusteranalysis_birthrate_python

## What this project is doing?

1. Clean data sets to prepare for cluster analysis and final project
2. Using different cluster analysis in Python and plot the results to see whether cluster analysis is necessary for final project. 

## Why is this project necessary?

1. Data file needs to be cleaned from raw.
2. Cluster analysis is only necessary to do later in the final project when different clustering methods' results are graphed with color plot.
3. Cluster analysis in python can work without initial guess of number of groups that imply reasonable guesses of group used later in Excel for final project.

## Results
1. Among the results of clusering methods, KMeans, BIRCH clustering, and agglomerative clustering suggest using 3 cluster groups is a good idea. Mean Shift clustering suggests 4. DBSCAN suggests 1. Affinity propagation suggests 1.

2. Color plots seemed to have reasonable groups of data points. This also suggests that cluster analysis is applicable for this datasets.

3. Note that some clustering method tests(unrelevant to this project) such as Kmeans.inertia_ suggests the performance of cluster analysis is not ideal on this datasets. It is possible that there are not enough numbers in the data that help the data training process.
