## Customer_Segmentation using K-Means Clustering
**Project Goal
The aim of this project is to perform market basket analysis by segmenting customers of a mall into distinct groups. This helps businesses understand customer behaviour and create targeted marketing strategies.
# Detailed workflow
**Data Preprocessing:
Loaded the "Mall Customers" dataset and checked for missing values to ensure data integrity.
**Feature Selection:
Focused on 'Annual Income' and 'Spending Score' as primary features for clustering.
**Elbow Method:
Used the Elbow Method to find the ideal number of clusters (k), which was determined to be 5.
**Model Training:
Applied the kmeans algorithm to the data to create 5 distinct customer segments.
**Visualization:
Created a colorful scatter plot showing the clusters and their centroids to represent the different customer types.
#Bonus Analysis: Cluster insight
I performed an additional analysis to understand each group better:
**Group 1 :
High income, High spending, (Target cuatomers).
**Group 2 :
Low income, Low spending.
**Group 3 :
Average Income, Average spending.
**Group 4 :
High Income, Low spending
##Technologies used:
Language : # Python
Data Processing : # Pandas and Numpy
K-Means Clustering model : #Scikit_learn
Cluster Visualization : #Matplotlib and Seaborn

