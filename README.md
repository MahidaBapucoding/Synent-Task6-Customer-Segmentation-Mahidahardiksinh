# Synent-Task6-Customer-Segmentation-Mahidahardiksinh
Customer Segmentation using the Mall Customer Dataset to group customers based on purchasing behavior using K-Means Clustering and data visualization techniques as part of my sysnent data science internship


# Customer Segmentation

## Objective

The objective of this project is to perform customer segmentation using the Mall Customer Dataset. Customers are grouped based on their annual income and spending behavior using K-Means Clustering to identify meaningful customer segments.

## Dataset

Dataset: Mall Customer Dataset

File Used: Mall_Customers.csv

Number of Rows: 200

Number of Columns: 5

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* VS Code
* Jupyter Notebook

## Steps Performed

### 1. Data Loading

The Mall Customer dataset was loaded using Pandas.

### 2. Data Inspection

Dataset structure, data types, and missing values were examined.

### 3. Data Preprocessing

Relevant features for clustering were selected:

* Annual Income (k$)
* Spending Score (1-100)

### 4. Elbow Method

The Elbow Method was applied to determine the optimal number of clusters.

### 5. K-Means Clustering

K-Means Clustering was applied to group customers into segments.

### 6. Cluster Visualization

Customer groups were visualized using scatter plots.

### 7. Customer Insights

Cluster-wise analysis was performed to understand customer behavior patterns.

## Visualizations Created

* Elbow Method Graph
* Customer Cluster Visualization
* Cluster Insights Chart

## Results

* Customers were successfully divided into five segments.
* Distinct spending and income patterns were identified.
* High-income and high-spending customers were recognized as valuable customers.
* High-income and low-spending customers represent potential growth opportunities.
* Customer segmentation can help businesses improve marketing strategies.

## Project Structure

├── Mall_Customers.csv

├── task6.ipynb

├── requirements.txt

├── report.pdf

├── screenshots/

│   ├── elbow_method.png

│   ├── customer_clusters.png

│   └── cluster_insights.png

└── README.md

## Conclusion

Customer segmentation using K-Means Clustering successfully grouped customers based on their spending behavior and annual income. These insights can assist businesses in designing targeted marketing campaigns and improving customer relationship strategies.
