# HierarchialClustering

**Hierarchical clustering**, also known as hierarchical cluster analysis, is an algorithm that groups similar objects into groups called clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, and the objects within each cluster are broadly similar to each other.

**Clustering** is the task of dividing the population or data points into several groups such that data points in the same groups are more similar to other data points in the same group than those in other groups. In simple words, the aim is to segregate groups with similar traits and assign them into clusters.

**Agglomerative clustering** is a bottom-up approach. It starts clustering by treating the individual data points as a single cluster then it is merged continuously based on similarity until it forms one big cluster containing all objects. It is good at identifying small clusters. 

The steps for agglomerative clustering are as follows:

  1. Compute the proximity matrix using a distance metric.  
  2. Use a linkage function to group objects into a hierarchical cluster tree based on the computed distance matrix from the above step.  
  3. Data points with close proximity are merged together to form a cluster.  
  4. Repeat steps 2 and 3 until a single cluster remains.

**Input data set is also attached in this Repository**
