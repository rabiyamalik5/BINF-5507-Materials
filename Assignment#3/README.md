This project compares three clustering algorithms—DBSCAN, k-Means, and Hierarchical Clustering—on various datasets and also shows where DBSCAN excels and struggles.
All datasets are generated using sklearn.datasets:
make_moons(n_samples=300, noise=0.05) – non-spherical clusters with noise (DBSCAN performs well)
make_blobs(n_samples=300, centers=3, cluster_std=[1.0, 2.5, 0.5]) – varying densities (DBSCAN struggles)
make_circles(n_samples=300, factor=0.5, noise=0.05) – nested circular clusters (DBSCAN works well)

How to Run
Clone the repository
git clone https://github.com/your-username/DBSCAN-Clustering-Comparison.git
cd DBSCAN-Clustering-Comparison

Install dependencies
pip install -r requirements.txt

Open the notebook
jupyter notebook clustering_analysis.ipynb
Run all cells to generate visualizations and compare results