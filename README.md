# Customer Segmentation

![image](https://github.com/user-attachments/assets/2b23605a-dace-415d-bae9-ccf4e6d81d3c)

This project focuses on segmenting customers based on their annual income and spending score using K-Means Clustering. The objective is to identify distinct customer groups that can be targeted with personalized marketing strategies.

## Project Overview
The project involves analyzing a dataset of mall customers to cluster them into groups based on their annual income and spending score. The K-Means algorithm is used for unsupervised learning, with the number of clusters determined using the Elbow Method.

## Workflow
1. Data Collection and Analysis
Loaded the dataset from Mall_Customers.csv and explored its structure.
Checked for missing values and summary statistics of the dataset.
2. Feature Selection
Selected two features: Annual Income and Spending Score, to cluster the customers.
3. Optimal Number of Clusters
Used the Elbow Method to determine the optimal number of clusters. The number of clusters was found to be 5 based on the Within-Cluster Sum of Squares (WCSS) graph.
4. K-Means Clustering
Applied K-Means clustering with 5 clusters, and obtained labels for each customer.

## Visualization
Plotted the customer clusters with different colors and highlighted the centroids to show how customers are grouped based on income and spending scores.



![Heatmap](https://github.com/user-attachments/assets/f30d3516-2faf-4d8b-80d4-e1be7831d287)



![Elbow_Chart](https://github.com/user-attachments/assets/b349b557-d2ec-48b1-bda4-aa05224df590)



![Customer_Groups](https://github.com/user-attachments/assets/d460fcf0-02b1-4a20-bff1-d4b60c226988)



![Centroid and Customer Segmentation](https://github.com/user-attachments/assets/99eedf9e-cafe-4e39-8892-3956e0456b99)



![3D chart](https://github.com/user-attachments/assets/eb38e454-a89b-40bb-8214-b86a399bdc5e)



![Pair_Plot](https://github.com/user-attachments/assets/47407a33-3bc2-4d2f-95ce-797feef97c1f)



![Distribution of Annual Income](https://github.com/user-attachments/assets/d4b7984f-d107-4fad-8813-0b07445f83b0)



![Distribution of Spending Score](https://github.com/user-attachments/assets/c1059775-0b68-4fb4-975d-4997c3790bee)


## Results
The model successfully segmented the customers into 5 distinct groups based on their annual income and spending score, enabling targeted strategies for each group.
