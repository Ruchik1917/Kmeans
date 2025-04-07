# MNIST KMeans Clustering using Cosine Similarity

In this project, we implemented the K-Means clustering algorithm from scratch. Instead of using Euclidean distance, we used Cosine Similarity as the distance metric.

## Steps

1. Loaded the MNIST handwritten digit dataset.
2. Performed clustering for 3 different numbers of clusters:
   - 10 clusters
   - 7 clusters
   - 4 clusters
3. Visualized the images grouped into each cluster.
4. Analyzed the characteristics of each cluster.
5. Bonus: Created a function to find the optimal number of clusters.

## Files

- `kmeans_cosine.ipynb` – Main notebook with clustering code and visualizations
- `kmeans_utils.py` – Utility functions or classes for clustering
- `optimal_k.py` – Bonus function to find the best number of clusters
- `README.md` – This file with project explanation

## Visualizations

The notebook displays sample images from each cluster to help understand which digits were grouped together.

## Conclusion

Using Cosine Similarity instead of Euclidean distance gave better results for high-dimensional data like MNIST. The analysis showed that visually similar digits (like 3 and 8) often ended up in the same cluster.
