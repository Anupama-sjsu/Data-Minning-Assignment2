# Data-Minning-Assignment2

### PCA - From the graph we can see the two components definitely hold some information, especially for mnist digits, but clearly not enough to set all of them apart. It fails to model nonlinear relationships because it is linear.

### t-SNE - it is particularly well suited for the visualization of high-dimensional datasets. PCA it is not a mathematical technique but a probablistic one. The way it does this is computationally quite heavy and therefore has limitations. In case of very high dimensional data, best to apply another dimensionality reduction technique before using t-SNE. Since t-SNE scales quadratically in the number of objects N, its applicability is limited to data sets with only a few thousand input objects,after that, learning becomes too slow to be practical. We can see that the mnist digits are very clearly clustered in their own sub groups here.

### UMAP - We can clearly see that the UMAP does a great job in separating the data points compared to t-SNE and PCA in terms of separation. It outperforms t-SNE and PCA. By looking at the plots, we can see mini-clusters that are being separated well. It is very effective for visualizing clusters or groups of data points and their relative proximities. UMAP is much faster than t-SNE.

### ISOMAP - tries to preserve geodesic distance, or distance measured not in Euclidean space but on the curved surface of the manifold.Isomap performs better than PCA.

### LLE - Better computational time as it tends to accumulate sparse matrices, it is more efficient than the other algorithms in terms of computational space and time. In terms of consideration of the non-linearity of the structure, LLE goes beyond density modeling techniques such as local PCA. Similarly, other methods like Kernel PCA, Isomap are also unable to detect the features which are detected by LLE.

### SVD - It clearly shows how the reconstructed image quality varies with different values of K. As we increase or decrease the k with the slider, the quality increases or decreases.
