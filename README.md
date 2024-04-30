Programming Task 4; Clustering Analysis


Data Set; Dog dataset with 4 categories (includes images and edge histograms, from Task 1)

Goal; Conduct clustering analysis using algorithms and assess their performance on the dog dataset with 4 categories.

Steps to Take;

Feature Extraction;
Transform images from the dog dataset with 4 categories into edge histograms (as previously completed in Task 2).
Standardize the histogram dataset.
Dimension Reduction;
Reduce dimensions to 2 on the edge histogram dataset.
Clustering Techniques;
Apply clustering using the following methods on the 2D dataset;
K means clustering (K = 4);
(a) K means clustering (init = 'Random')
(b) KMeans, with init='k means++'
(c) Bisecting K means (init = 'Random')
(d) clustering (default settings)
DBSCAN (settings; eps, min_samples for identifying clusters)
Agglomerative clustering with 4 clusters can be performed using methods;
(a) link (MIN)
(b) Complete link (MAX)
(c) Group Average
(d) Ward’s method

To evaluate the clustering you can follow these steps, for all methods;
Calculate the Fowlkes Mallows index using sklearn.metrics.fowlkes_mallows_score.
Compute the Silhouette Coefficient using sklearn.metrics.silhouette_score.
Rank the methods based on their Fowlkes Mallows index.
Rank the methods based on their Silhouette Coefficient.

For implementing clustering algorithms and performance metrics you can use scikit learn. Visit https;//scikit learn.org/stable/modules/clustering.html for coding details.

In this repository you will find code for analyzing clustering on a dog dataset with 4 classes. Follow the instructions provided to replicate the analysis and evaluation. Make sure to have scikit learn installed by running pip install scikit learn. Refer to the links in the documentation for an implementation guide.

The code output includes results and rankings based on the Fowlkes Mallows index and Silhouette Coefficient. Remember to replace any placeholders, with values used in your implementation.
