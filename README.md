# Unsupervised Machine Learning Algorithms

This README gives a brief description, a one-line definition, and a one-line typical use for common unsupervised machine learning algorithms.

## K-Means
Definition: Partition-based clustering that assigns points to K centroids by minimizing within-cluster variance.  
Use: Fast clustering for balanced, spherical clusters and vector quantization.

## Hierarchical Clustering (Agglomerative)
Definition: Builds a tree (dendrogram) of nested clusters by iteratively merging the closest pair of clusters.  
Use: Exploratory analysis to visualize cluster structure and choose different cluster granularities.

## DBSCAN
Definition: Density-based clustering that groups points that are closely packed and marks sparse points as noise.  
Use: Discovering arbitrarily shaped clusters and detecting outliers in spatial data.

## Gaussian Mixture Models (GMM)
Definition: Probabilistic clustering modeling data as a mixture of Gaussian distributions using EM.  
Use: Soft clustering where cluster membership is probabilistic and clusters may overlap.

## Principal Component Analysis (PCA)
Definition: Linear dimensionality reduction that projects data onto orthogonal axes of maximal variance.  
Use: Feature reduction, noise filtering, and visualization of high-dimensional data.

## Independent Component Analysis (ICA)
Definition: Decomposes multivariate signals into statistically independent non-Gaussian components.  
Use: Source separation (e.g., blind signal separation, artifact removal in signals).

## t-SNE
Definition: Nonlinear dimensionality reduction that preserves local structure for visualization in 2–3 dimensions.  
Use: Visual exploration of high-dimensional data manifolds and cluster structure.

## UMAP
Definition: Nonlinear manifold learning technique for faster, scalable dimensionality reduction preserving both local and global structure.  
Use: Visualization and pre-processing for downstream tasks with better run-time than t-SNE on large datasets.

## Autoencoders
Definition: Neural-network-based dimensionality reduction learning compact latent representations via reconstruction.  
Use: Nonlinear feature learning, compression, denoising, and anomaly detection.

## Isolation Forest
Definition: Ensemble method that isolates anomalies by randomly partitioning features and measuring path lengths.  
Use: Unsupervised anomaly/outlier detection in high-dimensional data.

## One-Class SVM
Definition: Boundary-based anomaly detection that learns a decision function for the normal class using support vectors.  
Use: Identifying novelties when only "normal" data is available for training.

---

For each algorithm, choose preprocessing, hyperparameters, and evaluation metrics appropriate to the data and task (e.g., scaling for distance-based methods, perplexity for t-SNE, number of components for PCA).