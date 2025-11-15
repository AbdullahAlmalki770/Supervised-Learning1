
# Machine Learning Pipeline: Classification, Clustering, and Image Visualization

This project presents a complete end-to-end machine learning workflow that includes supervised learning, unsupervised learning, and image visualization.  
It demonstrates how to train, evaluate, and interpret different ML models using well-known datasets.

---

## 🚀 Project Features

### 🔹 Supervised Learning (Classification)
Implements multiple classification algorithms on two popular datasets:

- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**

Datasets used:
- **Iris dataset**
- **Digits dataset**

Each model is evaluated using:
- Accuracy  
- Mean Squared Error (MSE)  
- R² Score  

---

### 🔹 Image Visualization
Displays real handwritten digits to help understand how ML interacts with image data.

Datasets visualized:
- `sklearn.load_digits()`
- `tensorflow.keras.datasets.mnist`

---

### 🔹 Unsupervised Learning (Clustering)
Applies **K-Means** algorithm to the **Mall Customers dataset** to segment shoppers based on their:

- Annual Income  
- Spending Score  

Includes:
- **Elbow Method** for finding the optimal number of clusters  
- Cluster visualization with labeled meanings:
  - High Income – High Spending  
  - High Income – Low Spending  
  - Low Income – High Spending  
  - Low Income – Low Spending  

---

## 📁 Datasets

| Dataset | Purpose | Type |
|--------|---------|------|
| Iris | Model training & evaluation | Supervised |
| Digits | Classification + visualization | Supervised |
| MNIST | Image visualization | Supervised |
| Mall Customers | Customer segmentation | Unsupervised |

---

## 📦 Installation

Install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
