# Clustering Across Datasets

This project explores the use of unsupervised learning techniques, particularly clustering, across three distinct types of datasets: synthetic 2D data, smartphone motion sensor data, and scientific research articles. The goal is to compare how clustering algorithms perform across structured, time-series, and unstructured text data.

---

## 📌 Objective

To investigate the behavior and effectiveness of clustering algorithms such as **K-Means** and **Hierarchical Clustering** across various real-world and synthetic datasets using dimensionality reduction and purity evaluation techniques.

---

## 🧪 Experiments Overview

### 🟢 Experiment 1: Clustering on Synthetic 2D Data
- **Data:** Geometrically distributed points (blobs, chameleon, elliptical)
- **Techniques:** K-Means, Agglomerative Clustering, Elbow Method
- **Goal:** Understand clustering behavior on ideal vs irregular shapes

### 🟡 Experiment 2: Smartphone Human Activity Recognition (HAR)
- **Data:** Samsung motion sensor data (accelerometer and gyroscope)
- **Techniques:** PCA for dimensionality reduction + K-Means
- **Goal:** Cluster similar human activities and evaluate with purity

### 🔵 Experiment 3: COVID-19 Scientific Articles (CORD-19)
- **Data:** Titles, abstracts, and body text from CORD-19 dataset
- **Techniques:** Text preprocessing (TF-IDF), PCA, clustering
- **Goal:** Automatically group research articles into thematic clusters

---

## 🛠️ Tools & Libraries

- Python, Jupyter Notebook
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` (KMeans, Agglomerative Clustering, PCA)
- `nltk`, `scikit-learn.feature_extraction.text` (TF-IDF for text)

---

## 📊 Evaluation Metrics

- **Purity Score** (for HAR activity clustering)
- **Elbow Method** (for determining number of clusters)
- **Visual inspection** via scatterplots and heatmaps




