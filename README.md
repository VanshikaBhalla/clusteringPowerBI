# 🩺 WHO Health Expenditure Clustering (2000–2017)

This project performs **K-Means Clustering** on the **World Health Organization’s Global Health Expenditure** dataset, analyzing how over 200 countries spent on health (% of GDP) between 2000 and 2017.  
The objective is to identify meaningful groups (clusters) of countries based on their expenditure patterns.

---

## Dataset

- **Source:** [clustering.csv](https://github.com/pycaret/powerbi-clustering/blob/master/clustering.csv)
- **Description:** Health expenditure as a percentage of GDP for each country from 2000 to 2017.

---

## Methods Used

- **Data Cleaning** and Reshaping
- **Standardization** using `StandardScaler`
- **K-Means Clustering** with `k=3` (chosen using the Elbow method)
- **Visualization** using:
  - Violin plots (distribution across clusters)
  - Line plots (trend per cluster)
  - Choropleth maps (assess regional/geographic patterns)

---

## Microsoft Power BI Dashboard

Below is a snapshot of the interactive dashboard built in **Power BI** to visualize the clustering results:

![image](https://github.com/user-attachments/assets/44b4feb2-a7c0-44df-bdfd-6a2cb66ecfda)

---

## Dashboard Insights

The Power BI dashboard offers a comprehensive view of the health expenditure (% of GDP) patterns across over 200 countries from 2000 to 2017. Below are some key insights derived from the clustered data:

- 🏆 **Top 5 Countries with Highest Health Expenditure**:
  - Marshall Islands (3.0%), United States (2.8%), Tuvalu (2.8%), Nauru (2.3%), Sierra Leone (2.2%).

- 🎻 **Violin Plot of Cluster Distributions**:
  - **Cluster 0**: Countries with **moderate** and slightly increasing health expenditure.
  - **Cluster 1**: Countries with **low and stable** expenditure patterns.
  - **Cluster 2**: Countries with **high and fluctuating** expenditure, often including small island nations and developed economies.

- 🗺️ **Geographical Distribution (Choropleth Map)**:
  - **Cluster 0** dominates **North America, Europe**, and parts of **Asia**.
  - **Cluster 1** appears in **developing regions** with lower expenditure.
  - **Cluster 2** is seen in **outliers** with high or erratic expenditure patterns.

- 📈 **Average Health Expenditure Over Time**:
  - **Cluster 0** shows a steady increase from 2000 to 2017.
  - **Cluster 1** remains flat with minimal change.
  - **Cluster 2** starts high and stays relatively stable.

- 🔁 **GDP Change vs Volatility Scatterplot**:
  - Cluster 0 and 2 countries exhibit higher **volatility** in expenditure trends.
  - Cluster 1 countries show **low change and low volatility**, indicating conservative health budgets.

---
