# Nature-Image-Clustering1
Here is a well-structured `README.md` text for your GitHub repository:

---

# 🌿 Nature Image Clustering using Visual Features

**Academic Project – Intelligent Computing Fundamentals**
**Ferdowsi University of Mashhad**

## 📌 Overview

This project focuses on unsupervised clustering of satellite images representing natural landscapes (e.g., desert, forest, beach, etc.) based on handcrafted visual features. It was developed entirely from scratch without using pre-trained models or built-in clustering evaluators.

## 🚀 Key Features

* **Feature Extraction**

  * Dominant color detection
  * Texture and edge density analysis
  * Statistical descriptors (mean, variance, etc.)

* **Feature Selection**

  * Correlation matrix computation
  * Threshold-based filtering to reduce redundancy

* **Clustering Algorithms**

  * KMeans
  * DBSCAN
  * Agglomerative Clustering
  * MeanShift
  * All tuned manually for optimal performance

* **Evaluation**

  * Self-implemented precision, recall, F1-score
  * Silhouette Score

* **Visualization**

  * Cluster heatmaps
  * Dimensionality reduction (e.g., PCA, t-SNE) for 2D plotting

* **Test Prediction**

  * Classifies unseen data into trained clusters
  * Saves output as CSV
