Dataset link - https://www.kaggle.com/kondapuramshivani/mall-customerscsv

# Hierarchical Clustering

In hierarchical clustering, this new step also consists of finding the optimal number of clusters. Only this time we’re not going to use the elbow method. We are going to use the dendrogram.

Using the dendrogram to find the optimal numbers of clusters.  First thing we're going to do is to import scipy library. scipy is an open source Python library that contains tools to do #hierarchical clustering and building dendrograms. Only import the tool.

Lets create a dendrogram variable linkage is actually the algorithm itself of hierarchical clustering and then in linkage we have to specify on which data we apply and engage. This is X dataset.

Ward method is actually a method that tries to minimize the variance within each cluster. In K-means when we were trying to minimize the wcss to plot our elbow method chart, here it’s almost the same the only difference is that instead of minimizing wcss we are minimizing the within-cluster variants. That is the variance within each cluster. Below is the dendrogram diagram.





The x-axis consists of the customers and y-axis consists of the Euclidean distance between the clusters. How do we determine the optimal number of clusters from this diagram? We look for the largest distance that we can vertically without crossing any horizontal line and this one is the red framed line on the above diagram. Let's count the number of lines on the diagram and determine the optimal number of clusters. Cluster number will be 5 for this dataset.

# Hierarchical-Clustering
Unsupervised Machine Learning




