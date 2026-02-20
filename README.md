# Task-2---Mall-Customers
This project uses K-Means clustering to group customers based on annual income and spending score, helping businesses identify distinct customer segments for targeted marketing.
Project Overview

This project implements the K-Means clustering algorithm to segment customers of a retail store based on their purchasing behavior. The objective is to group customers into distinct clusters using their Annual Income and Spending Score, enabling better marketing strategies and business decision-making.

The Mall Customer Dataset is used for this analysis.

Dataset Description

The dataset contains the following attributes:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

For clustering, the following features were selected:

Annual Income (k$)

Spending Score (1–100)

Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Methodology

Load and explore the dataset.

Select relevant features for clustering.

Scale features using StandardScaler.

Determine the optimal number of clusters using the Elbow Method.

Apply the K-Means clustering algorithm.

Visualize clusters and centroids.

Assign cluster labels to each customer.

Results

Using the Elbow Method, the optimal number of clusters was identified (typically 5 for this dataset). The model grouped customers into meaningful segments such as:

High Income – High Spending

High Income – Low Spending

Low Income – High Spending

Low Income – Low Spending

Moderate Income – Moderate Spending

These segments provide insights for targeted marketing, customer retention strategies, and revenue optimization.

How to Run

Install required libraries:

pip install pandas numpy matplotlib scikit-learn


Place Mall_Customers.csv in the project directory.

Run the script:

python kmeans_clustering.py

Project Structure
Mall_Customers.csv
kmeans_clustering.py
README.md

Future Improvements

Evaluate clustering using Silhouette Score

Extend clustering to include Age (3D visualization)

Deploy as a web-based application

Automate cluster interpretation

Conclusion

K-Means clustering effectively segments customers based on purchasing behavior. The insights derived from clustering can help businesses improve decision-making, enhance customer targeting, and increase overall profitability.
