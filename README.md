# Mall Customer Segmentation using K-Means Clustering

## Project Overview

This project implements the **K-Means Clustering** algorithm to segment customers of a retail store based on their purchasing behavior. Customer segmentation helps businesses identify groups of customers with similar characteristics, enabling targeted marketing and improved customer relationship management.

---

## Objective

- Perform customer segmentation using the K-Means clustering algorithm.
- Determine the optimal number of clusters using the Elbow Method.
- Visualize customer groups based on Annual Income and Spending Score.
- Analyze the number of customers in each cluster.

---

## Dataset

**Dataset Name:** Mall Customer Dataset

The dataset contains the following attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Features used for clustering:

- Annual Income (k$)
- Spending Score (1–100)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Import required libraries.
2. Load the Mall Customer Dataset.
3. Explore the dataset.
4. Check for missing values.
5. Select relevant features.
6. Apply the Elbow Method to determine the optimal number of clusters.
7. Train the K-Means clustering model.
8. Assign cluster labels to each customer.
9. Visualize customer segments.
10. Analyze the number of customers in each cluster.

---

## Results

- Successfully segmented customers into **5 clusters**.
- Identified customer groups based on spending habits and annual income.
- Visualized customer clusters using scatter plots.
- Displayed the distribution of customers across clusters using a bar chart.

---

## Project Structure

```
Mall-Customer-Segmentation/
│
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── Customer_Segments.csv
├── README.md
└── screenshots/
    ├── dataset_head.png
    ├── elbow_method.png
    ├── clusters.png
    └── customers_per_cluster.png
```

---

## Output

- Dataset Preview
- Dataset Information
- Summary Statistics
- Elbow Method Graph
- Customer Segmentation Scatter Plot
- Customers per Cluster Bar Chart

---

## Conclusion

K-Means clustering effectively grouped customers into distinct segments based on Annual Income and Spending Score. These insights can help businesses develop targeted marketing strategies, improve customer engagement, and optimize sales performance.

---

## Author

**Sreeman**
