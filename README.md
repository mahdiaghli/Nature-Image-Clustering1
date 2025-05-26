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

## 📁 Structure

```
├── data/                # Dataset of satellite images
├── features/            # Extracted features and selected feature vectors
├── clustering/          # Implementation of all clustering algorithms
├── evaluation/          # Custom evaluation metrics
├── visualization/       # Heatmaps and reduced-dimensional plots
├── prediction/          # Test image handling and prediction
├── main.py              # Pipeline integration and execution
└── README.md
```

## 🛠️ Requirements

* Python 3.x
* NumPy, OpenCV, matplotlib, pandas, scikit-learn

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 📊 Sample Results

* **Cluster Interpretability**: Forest-dominated clusters show high green channel means and dense texture patterns
* **Silhouette Score**: Achieved \~0.52 using optimized KMeans
* Test Accuracy**: Clusters show high internal consistency across various metrics

## 👨‍💻 Authors

* Mahdi Achli
* Instructor: Dr. Sayed Kamaledin Ghiasi Shirazi

---

Let me know if you'd like badges (e.g., for license, Python version), example images, or Colab integration.
