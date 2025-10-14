# Mall Customer Segmentation Project 🛍️

This project aims to segment mall customers based on their annual income and spending score using **K-Means clustering**.

## 📊 Dataset
- Source: Mall_Customers.csv
- Columns: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100)

## 🎯 Objectives
- Identify different customer groups based on spending behavior.
- Provide insight for targeted marketing strategies.

## 🧠 Methods
- Data cleaning and preprocessing using `pandas` and `sklearn`.
- Determined optimal number of clusters using the **Elbow Method**.
- Applied **K-Means clustering** with 5 clusters.
- Visualized using `matplotlib` and `seaborn`.

## 📈 Results
| Cluster | Description |
|----------|--------------|
| 0 | High income, low spending (conservative buyers) |
| 1 | High income, high spending (target customers) |
| 2 | Moderate income, high spending |
| 3 | Low income, low spending |
| 4 | Low income, high spending |

## 🧩 Tools Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- GitHub

## 🏁 Conclusion
Customers can be grouped into five segments. The best potential for marketing campaigns lies in clusters 1 and 2, which show strong spending patterns.

---

📌 Author: **Fauzand Mestakindo E.**  
📧 Contact: mestakindo@gmail.com

