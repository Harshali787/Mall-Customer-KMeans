# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers of a retail store based on their **Annual Income** and **Spending Score**.

It helps businesses identify different customer groups for **better marketing strategies** and **targeted promotions**.

---

## 📂 Dataset
Dataset used: **Mall_Customers.csv**

### Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Steps Performed
1. Imported dataset
2. Checked missing values and dataset info
3. Selected important features:
   - Annual Income
   - Spending Score
4. Scaled the data using StandardScaler
5. Used the **Elbow Method** to find the optimal number of clusters
6. Applied **K-Means Clustering**
7. Visualized customer segments
8. Added cluster labels and names
9. Saved final clustered dataset

---

## 📈 Output
- Elbow Method Graph
- Customer Cluster Scatter Plot
- Cluster Count Plot
- Income Distribution by Cluster
- Spending Score Distribution by Cluster

---

## 🧠 Cluster Labels
- Standard Customers
- Careful Customers
- Target Customers
- Spending Customers
- Sensible Customers

---

## 📁 Final Output File
`Mall_Customers_Clustered_Final.csv`

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
python mall_customer_kmeans.py
