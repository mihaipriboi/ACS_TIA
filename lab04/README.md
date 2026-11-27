# Lab 04 – Unsupervised Learning (K-Means)

Requirements: [331 AA.pdf](331%20AA.pdf)

Notebook: [lab04.ipynb](lab04.ipynb)

## Tasks

1. **Data analysis and visualization** – check the dataset; check the distribution of the clusters (species); histograms of each feature split by label.
2. **K-Means** – dendrogram of hierarchical clustering (Ward linkage); choose the number of clusters k (dendrogram, backed by the Elbow method and Silhouette coefficient); train K-Means for that k; scatter plot of the clusters on two features with the centroids; scatter plot of the true clusters.

## Dataset

[iris.csv](iris.csv) – 150 iris flowers (50 per species), with an unnamed index column followed by:

| Column | Description |
|--------|-------------|
| `sepal_length` | Sepal length (cm) |
| `sepal_width` | Sepal width (cm) |
| `petal_length` | Petal length (cm) |
| `petal_width` | Petal width (cm) |
| `species` | `Iris-setosa`, `Iris-versicolor` or `Iris-virginica` (used only for evaluation) |
