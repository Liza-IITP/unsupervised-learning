# 🧠 UNSUPERVISED LEARNING
---

## 📌 CONTENTS
- **Dimensionality Reduction**
  - Principal Component Analysis (PCA)
- **Clustering**
  - K-Means Clustering  
  - Hierarchical Clustering  
  - DBSCAN Clustering  
  - Silhouette Score for Cluster Evaluation
- **Anomaly Detection**
  - Isolation Forest  
  - DBSCAN Outlier Detection  
  - Local Outlier Factor (LOF)

---

# 📉 Dimensionality Reduction — PCA

**Principal Component Analysis (PCA)** reduces data to lower dimensions while preserving maximum variance.

### What this section includes:
- Eigenvalues & eigenvectors computation  
- Explained variance ratio  
- 2D visualization  
- PCA as preprocessing before clustering  

---

# 📍 K-Means Clustering

K-Means partitions data into **K clusters** using centroid minimization.

### Included:
- Random initialization + K-Means++  
- Inertia (WCSS)  
- Elbow Method  
- Cluster visualization  
- Real dataset examples  

---

# 🌳 Hierarchical Clustering

Hierarchical clustering builds nested clusters without requiring K beforehand.

### Included:
- Agglomerative clustering  
- Linkage criteria (single, complete, average, ward)  
- Dendrogram visualization  
- Distance matrix explanation  

---

# 🧩 DBSCAN Clustering

**DBSCAN (Density-Based Spatial Clustering)** groups dense regions and labels sparse points as noise.

### Key Parameters:
- `eps`: neighborhood radius  
- `min_samples`: minimum neighbors to form core point  

### Features:
- Finds arbitrary-shaped clusters  
- Automatically detects outliers  
- Does not require number of clusters  

---

# 📏 Silhouette Scoring

Silhouette score evaluates cluster quality.

\[
S(i) = \frac{b(i) - a(i)}{\max(a(i), b(i))}
\]

Where:  
- **a(i)** = avg. distance to same cluster  
- **b(i)** = avg. distance to nearest other cluster  

Range:  
- **+1** → well-formed clusters  
- **0** → overlapping clusters  
- **−1** → misclassified points  

Included:
- Silhouette score for K-Means  
- Silhouette score for DBSCAN  
- Silhouette plots  

---

# 🚨 ANOMALY DETECTION

## 1️⃣ Isolation Forest
## 2️⃣ DBSCAN Outlier Detection
## 3️⃣ Local Outlier Factor (LOF)
