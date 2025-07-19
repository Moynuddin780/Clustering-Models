# Clustering-Models
# Iris Clustering Analysis

## Overview
This Jupyter Notebook  performs an unsupervised clustering analysis on the Iris dataset, a well-known dataset in machine learning consisting of measurements of sepal and petal dimensions for three species of iris flowers. The notebook demonstrates the application of multiple clustering algorithms, including K-Means, DBSCAN, and Agglomerative Clustering, to explore patterns within the data. It also includes data preprocessing, visualization, and evaluation steps to provide insights into the clustering results.

## Dataset
The Iris dataset is sourced from `sklearn.datasets.load_iris` and includes:
- **Features**: Sepal length, sepal width, petal length, and petal width (4 numerical features).
- **Target**: Three classes of iris species (Setosa, Versicolor, Virginica), used for evaluation but not for clustering.
- **Size**: 150 samples, with no missing values.

## Objectives
- Perform exploratory data analysis (EDA) to understand the dataset's structure and characteristics.
- Apply and compare different clustering algorithms to identify natural groupings in the data.
- Visualize the clustering results using PCA for dimensionality reduction.
- Evaluate the clustering performance using metrics like Adjusted Rand Score.

## Dependencies
The following Python libraries are used in the notebook:
- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `matplotlib.pyplot`: For creating visualizations.
- `seaborn`: For enhanced statistical visualizations.
- `sklearn`: For loading the Iris dataset, preprocessing, clustering algorithms, PCA, and evaluation metrics.
- `scipy.cluster.hierarchy`: For hierarchical clustering and dendrogram visualization.
- `kneed`: For determining the optimal number of clusters using the elbow method.
- `warnings`: To suppress unnecessary warnings for cleaner output.

To install the required libraries, run:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn kneed
