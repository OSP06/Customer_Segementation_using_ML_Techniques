# Customer_Segementation_using_ML_Techniques
# Overview

This project applies machine learning techniques to segment customers based on their purchasing behavior. The dataset used contains transactional data, which is processed and analyzed using clustering algorithms such as K-Means, Hierarchical Clustering, and DBSCAN.

# Project Workflow

# 1.Data Preprocessing

Load dataset and clean missing values.

Compute key features: TotalSpend, NumTransactions, ItemsBought, and Recency.

Remove outliers using Z-score filtering.

Normalize data using MinMaxScaler.

# 2.Clustering Techniques

K-Means Clustering: Determines optimal K using the Elbow method and Silhouette Score.

Hierarchical Clustering: Creates a dendrogram and applies Agglomerative Clustering.

DBSCAN Clustering: Identifies clusters based on density to handle noise and outliers.

# 3.Visualization and Analysis

Scatter plots comparing different clustering methods.

Bar charts and box plots for better insights.

Comparison of refined segmentation vs. original dataset.

# 4.Export and Integration

Save refined customer segments to CSV.

Convert CSV to Tableau Hyper file for visualization.

Optionally upload to Tableau Server using API.

# Installation & Requirements

To run this project, install the required Python packages:

pip install pandas numpy matplotlib seaborn scikit-learn tableauhyperapi tableauserverclient

# Running the Project

Execute the Customer_Segmentation_using_ML.ipynb notebook.

Adjust clustering parameters if needed.

View the visualizations and analyze the customer segments.

Export the results for use in BI tools like Tableau or Power BI.
