# Customer Segmentation Using K-Means
## Overview
This project applies K-Means clustering to mall customer data to group customers with similar annual income and spending scores.

## Dataset
- 200 customer records and 5 columns
- No missing values or duplicate rows
- Features used for clustering: Annual Income (k$) and Spending Score (1–100)

## Tools
- Python,
- Pandas,
- Matplotlib, and
- Scikit-learn.

## Methodology
The dataset was inspected and two features were selected for clustering. The Elbow Method was used to choose five clusters. K-Means was then fitted with n_clusters=5, random_state=42, and n_init=10. The resulting groups were visualized and compared using average age, income, and spending score.

## Cluster Summary
- Cluster 0: 81 customers; average income and spending
- Cluster 1: 39 customers; high income and high spending
- Cluster 2: 22 customers; low income and high spending
- Cluster 3: 35 customers; high income and low spending
- Cluster 4: 23 customers; low income and low spending

## Outputs
The notebook saves the segmented customer data as segmented_Mall_Customers.csv and charts as Elbow_Method.png and Customer_Segmentation.png in the output and charts folders.

## Conclusion
The project identifies five customer groups and provides a starting point for understanding customer patterns and planning customer-focused business activities.
