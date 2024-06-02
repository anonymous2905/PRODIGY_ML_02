Prodigy Infotech Task-2


Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

This Python script demonstrates customer segmentation using K-means clustering. It loads a dataset containing basic information about customers (such as age, gender, annual income, and spending score), preprocesses the data, and performs K-means clustering to segment customers into distinct groups. The results are visualized using PCA for dimensionality reduction.

Getting Started
Prerequisites
Make sure you have Python installed on your system. You'll also need to install the following libraries:

pandas
matplotlib
seaborn
scikit-learn
You can install these libraries using pip:

pip install pandas matplotlib seaborn scikit-learn
Usage
Place your customer_data.csv file in the root directory of the project. This file should contain the following columns:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousand dollars
Spending Score (1-100): Spending score assigned to the customer (1-100)
Run the Python script to perform customer segmentation:


The script performs the following steps:


Data Preprocessing:

Encodes the Gender column using Label Encoding.
Scales the features using StandardScaler.
Optimal Number of Clusters:

Uses the Elbow Method to determine the optimal number of clusters.
K-means Clustering:

Applies K-means clustering with the chosen number of clusters.
Visualization:

Reduces dimensions using PCA for visualization.
Generates a scatter plot to visualize the customer segments.
Results
The output of the script includes:

Elbow Method Plot: Helps determine the optimal number of clusters by plotting the Sum of Squared Errors (SSE).
Customer Segments Visualization: Visualizes the customer segments based on the first two principal components.
