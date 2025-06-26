# Clustering Algorithm Comparison
This project compares three clustering algorithms—DBSCAN, k-Means, and Hierarchical Clustering—on various datasets and also shows where DBSCAN excels and struggles.

# How to Run
1. Open 'Main.ipynb' in Jupyter.
2. Run all cells to generate graphs.
All datasets are generated using sklearn.datasets:
make_moons(n_samples=300, noise=0.05) – non-spherical clusters with noise (DBSCAN performs well)
make_blobs(n_samples=300, centers=3, cluster_std=[1.0, 2.5, 0.5]) – varying densities (DBSCAN struggles)
make_circles(n_samples=300, factor=0.5, noise=0.05) – nested circular clusters (DBSCAN works well)

# Requirements
- Python
- sklearn