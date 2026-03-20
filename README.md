# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project implements **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers of a retail store based on their purchasing behavior.

The goal is to group customers into distinct clusters to help businesses better understand customer patterns and improve marketing strategies.

---

## 🚀 Key Features

* 📊 Data preprocessing and feature selection
* 📈 Elbow Method to determine optimal number of clusters
* 🧠 K-Means clustering implementation
* 📉 Visualization of clusters
* 📦 Automatic output generation

---

## 🧠 Machine Learning Technique

* **Algorithm:** K-Means Clustering
* **Type:** Unsupervised Learning
* **Objective:** Group similar customers based on income and spending behavior

---

## 📊 Dataset

* Source: Kaggle – Mall Customer Segmentation Dataset
* Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Features used:

* Annual Income (k$)
* Spending Score (1-100)

---

## 📁 Project Structure

```id="struct_final"
SCT_ML_2/
│
├── data/
│   └── Mall_Customers.csv
│
├── output/
│   ├── elbow_plot.png
│   ├── clusters.png
│
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```id="clone_final"
git clone https://github.com/hasinib729/SCT_ML_2.git
cd SCT_ML_2
```

### 2️⃣ Install dependencies

```id="install_final"
pip install -r requirements.txt
```

### 3️⃣ Add dataset

Place the dataset in:

```id="data_final"
data/Mall_Customers.csv
```

---

## ▶️ Run the Project

```id="run_final"
python main.py
```

---

## 📊 Methodology

### 🔹 Step 1: Data Selection

Selected relevant features:

* Annual Income
* Spending Score

### 🔹 Step 2: Elbow Method

Used to determine optimal number of clusters by analyzing WCSS values.

### 🔹 Step 3: Model Training

Applied K-Means clustering algorithm to group customers.

### 🔹 Step 4: Visualization

Plotted clusters and centroids for better understanding.

---

## 📈 Output

* 📉 Elbow Graph → Helps identify optimal K
* 📊 Cluster Plot → Visual representation of customer segments

---

## 💼 Resume Description

Developed a customer segmentation model using K-Means clustering on retail dataset. Implemented Elbow Method to determine optimal clusters and visualized customer groups based on income and spending patterns.

---

## 🔮 Future Improvements

* Use advanced clustering (DBSCAN, Hierarchical)
* Add 3D visualization
* Build a dashboard for business insights

---

## 📚 Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🙌 Acknowledgements

* Kaggle Dataset: Mall Customer Segmentation
* Scikit-learn documentation

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
