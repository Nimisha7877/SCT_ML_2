# SCT_ML_2
A machine learning project that performs customer segmentation using K-Means clustering on the Mall Customer Dataset. Customers are grouped based on their annual income and spending behavior to identify marketing-friendly clusters. | Internship @ SkillCraft Technologies

# 🛍️ Mall Customer Segmentation using K-Means

This project uses **K-Means Clustering** to segment mall customers into distinct groups based on their **Annual Income** and **Spending Score**. The goal is to understand customer behavior for personalized marketing strategies and better business decisions.

---

## 📌 Objective

🔍 Cluster customers based on purchasing behavior to identify:
- High-value customers
- Budget-conscious shoppers
- Strategic customer groups for targeted promotions

---

## 🧾 Dataset Details

- **File Used:** `Mall_Customers.csv`
- **Source:** [Kaggle - Mall Customer Segmentation Data]https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

| Column Name             | Description                         |
|-------------------------|-------------------------------------|
| `CustomerID`            | Unique customer identifier          |
| `Gender`                | Male or Female                      |
| `Age`                   | Age of the customer                 |
| `Annual Income (k$)`    | Customer's income in $1000s         |
| `Spending Score (1-100)`| Customer spending score (1 = low)   |

📌 Only `Annual Income (k$)` and `Spending Score (1-100)` were used for clustering.

---

## 🧠 Techniques Used

- K-Means Clustering (Unsupervised ML)
- Elbow Method for optimal cluster selection
- Data scaling using StandardScaler
- Visualizations using Matplotlib

---
## 📊 Output Example

### 🔹 Final Clusters (K=5)

The K-Means model identified 5 distinct customer segments based on annual income and spending score.

![Customer Segments](images/output_plot.png)


## 🚀 How to Run the Project

You can run this project in **two ways**:

---

### 🔹 Option 1: Run on Google Colab (Recommended)

If you're using Google Colab:

1. Open the `kmeans_clustering.ipynb` or copy the code into [Colab](https://colab.research.google.com/)
2. Upload `Mall_Customers.csv` when prompted
3. Run all cells to view output and clustering graph

---

### 🔹 Option 2: Run Locally in VS Code

1. Make sure you have Python installed
2. Install required libraries:
```bash
pip install pandas matplotlib scikit-learn


