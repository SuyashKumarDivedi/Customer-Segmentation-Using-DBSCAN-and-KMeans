# 🎯 Customer Segmentation using K-Means & DBSCAN

### 📊 An Unsupervised Machine Learning Project

This project explores customer segmentation using **K-Means and DBSCAN clustering algorithms** on marketing campaign data. The goal is to identify meaningful customer groups based on their demographics, income, and purchasing behaviour using unsupervised learning techniques.

---

## 🛠️ Tech Stack & Tools

| Technology          | Purpose                       |
| ------------------- | ----------------------------- |
| 🐍 Python           | Core Programming Language     |
| 📊 Pandas           | Data Manipulation             |
| 🔢 NumPy            | Numerical Computation         |
| 📈 Matplotlib       | Data Visualization            |
| 🤖 Scikit-learn     | Machine Learning & Clustering |
| 📓 Jupyter Notebook | Development Environment       |

---

## 🧠 Algorithms Implemented

### 1. K-Means Clustering

* Partitions customers into a predefined number of clusters.
* Uses the Elbow Method to determine the optimal number of clusters.
* Evaluates clustering using the Silhouette Score.

### 2. DBSCAN (Density-Based Spatial Clustering)

* Identifies clusters based on data density.
* Detects noise and outliers.
* Does not require specifying the number of clusters beforehand.

---

## ⚙️ Project Workflow

* 📥 **Data Loading:** Importing the marketing campaign dataset.
* 🧹 **Data Cleaning:** Handling missing values, duplicates, and irrelevant features.
* 🔧 **Feature Engineering:** Extracting meaningful customer information.
* 📏 **Feature Scaling:** Standardizing numerical features.
* 🔠 **Encoding:** Converting categorical features into numerical representations.
* 🤖 **Model Training:** Implementing K-Means and DBSCAN.
* 📊 **Evaluation:** Analysing clustering performance.
* 🎨 **Visualization:** Representing clusters using dimensionality reduction techniques.

---

## 📉 Data Visualization

The project uses:

* **PCA (Principal Component Analysis):** Reduces high-dimensional data into two dimensions for visualization.
* **t-SNE:** Helps visualize complex relationships and cluster structures in high-dimensional data.

---

## 📂 Project Structure

```text
Customer-Segmentation/
│
├── 📓 Model Training Usind DBSCAN.ipynb
├── 📊 marketing_campaign.csv
└── 📄 README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Customer-Segmentation
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook
```

Open the notebook and execute the cells sequentially.

---

## 🎯 Project Objectives

* Understand unsupervised machine learning.
* Explore different clustering approaches.
* Identify customer segments from marketing data.
* Understand density-based clustering and outlier detection.
* Visualize high-dimensional datasets.

---

## 🔮 Future Improvements

* Optimize DBSCAN parameters using the k-distance graph.
* Explore additional clustering evaluation metrics.
* Perform detailed customer segment profiling.
* Develop targeted marketing strategies based on clustering results.

---

## 👨‍💻 Author

**Suyash Kumar Divedi**

B.Tech CSE (AI & ML)

---

⭐ If you find this project interesting, consider giving the repository a star!
