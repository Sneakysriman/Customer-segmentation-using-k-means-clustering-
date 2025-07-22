# 🧠 Customer Segmentation using K-Means Clustering (Python + Power BI)

## 📌 Project Overview

This project performs **customer segmentation** using **K-Means Clustering** on mall customer data, aiming to group customers based on their behavior and spending patterns. The segmentation results are visualized through an interactive **Power BI dashboard** to provide business-friendly insights for marketing strategies and decision-making.

The project is split into two key parts:
1. **Clustering with Python**: Data pre-processing and clustering logic using scikit-learn.
2. **Power BI Dashboard**: Visual representation of clustered customer groups via scatter plots, bar charts, and data tables.

---

## 🎯 Project Objectives

- Apply **unsupervised machine learning (K-Means)** to segment customers.
- Identify customer groups based on annual income and spending score.
- Use **Power BI** to present the segmented data visually and interactively.
- Help businesses target customer groups more efficiently through data insights.

---

## 🗂️ Project Structure

| File | Description |
|------|-------------|
| `mall_customer_data.csv` | Original dataset used for clustering |
| `segmented_customer_data.csv` | Output data with cluster labels |
| `customer_segmentation.pbix` | Power BI dashboard with visualizations |
| `cluster_plot_1.png` | Cluster scatter plot from Power BI |
| `cluster_plot_2.png` | Bar chart visualization |
| `cluster_table.png` | Segmented data table |
| `README.md` | Project documentation (this file) |

---

## 📊 Dashboard Visualizations (Power BI)

- ✅ **Scatter Plot**: Customers segmented by spending score vs. income.
- ✅ **Bar Chart**: Average income/spending per segment.
- ✅ **Data Table**: Full view of customers with cluster labels.
- ✅ **Interactive Filters**: Slice by gender, age group, and cluster.

> 📷 Sample Screenshots:

![Cluster Plot](cluster_plot_1.png)
![Bar Chart](cluster_plot_2.png)
![Segment Table](cluster_table.png)

---

## 🛠 Tools & Technologies

- **Python 3.9+**
  - Pandas
  - Scikit-learn
- **Power BI**
- Dataset: `mall_customer_data.csv`

---

## 📌 How It Works

### 🔹 1. Clustering in Python

- Read customer data
- Normalize features (Annual Income, Spending Score)
- Apply K-Means with `k=5` (elbow method)
- Export clustered dataset as `segmented_customer_data.csv`

### 🔹 2. Dashboard in Power BI

- Load segmented CSV
- Create visuals:
  - Scatter Plot → Clusters
  - Bar Chart → Avg metrics per cluster
  - Table → Customer info + segment
- Add slicers and format the report

---

## 🔍 Business Use Case

Customer segmentation allows businesses to:
- Personalize marketing campaigns per group
- Improve customer retention by understanding behavior
- Identify high-value and low-engagement segments

---

## ✨ Project Purpose (Professional)

This project showcases how **machine learning** and **data visualization** can work together to produce real-world business insights. It simulates a practical retail scenario where customer segmentation supports data-driven decision-making in marketing, sales, and customer engagement.

It also demonstrates core skills in:
- Data preprocessing and clustering in Python
- Visual storytelling in Power BI
- Dashboard design with KPIs and interactivity

Ideal for showcasing in **data analyst, BI developer, or junior data science** portfolios.

---

## 📎 How to Use

1. Clone or download the repository
2. Open the Power BI `.pbix` file to explore the dashboard
3. Use the `.csv` files to test or retrain clusters in Python
4. Use visuals/screenshots for your data portfolio or presentation

---
