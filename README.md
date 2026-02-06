# KMeans Clustering Using Python

## 📌 Project Overview
This project demonstrates **KMeans clustering** using Python and Scikit-learn. A built-in dataset is used to perform unsupervised learning, identify natural groupings, and visualize clusters.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📂 Dataset
- Dataset Used: Iris Dataset (from Scikit-learn)
- Features: Sepal length, sepal width, petal length, petal width

---

## ⚙ Steps Performed
1. Loaded dataset using `load_iris()`
2. Converted data into Pandas DataFrame
3. Selected two features for clustering
4. Applied feature scaling using `StandardScaler`
5. Used Elbow Method to find optimal number of clusters
6. Applied KMeans clustering
7. Visualized clusters
8. Saved clustered dataset as CSV

---

## 📊 Output Files
- `segmented_customers.csv` – Clustered dataset
- Elbow plot
- Cluster visualization plot

---

## ▶ How to Run
```bash
pip install pandas matplotlib scikit-learn
python kmeans.py
