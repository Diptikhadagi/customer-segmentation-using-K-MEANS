
CUSTOMER SEGMENTATION USING K-MEANS

This project is based on customer segmentation using the K-Means clustering algorithm. The main goal of this task is to group customers based on their spending behavior and income so that different marketing strategies can be applied to different types of customers.

DATASET USED
The dataset used in this project is Mall\_Customers.csv which contains details like Age, Annual Income (k\$), and Spending Score (1–100).

STEPS PERFORMED IN THE PROJECT

1. Loaded the dataset and removed any missing values
2. Selected useful features for clustering
3. Scaled the features using StandardScaler
4. Applied the Elbow method to find the optimal value of k
5. Used KMeans clustering algorithm to assign each customer to a cluster
6. Calculated the silhouette score for accuracy checking
7. Visualized the customer segments using scatter plots
8. Exported the final data with cluster labels

TOOLS AND LIBRARIES USED
Python
pandas
matplotlib
seaborn
scikit-learn

HOW TO RUN THE PROJECT
Open the kmeans\_clustering.ipynb file in Jupyter Notebook.
Make sure the Mall\_Customers.csv file is in the same folder.
Run all the cells step by step.
The output will be shown in the form of plots and a new CSV file will be saved.

OUTPUT FILES GENERATED

1. segmented\_customers.csv – contains the customer data with their cluster labels
2. kmeans\_clustering.ipynb – notebook with all steps
3. output\_report.pdf – optional report with charts and summary

INSIGHTS FROM CLUSTERS
Cluster 0 – High income and high spending customers – best for premium offers
Cluster 1 – Low income and low spending – basic level
Cluster 2 – Medium income and high spending – loyal shoppers
Cluster 3 – High income but low spending – need targeted marketing

SUBMITTED BY
Dipti Khadgi
Credora Internship – Machine Learning Task 02

---

🟢 Ye version bilkul internship submission ke format jaisa hai — **neat, professional, readable**.

Agar chaho to isi content ka **PDF** ya **ready file** bhi de sakta hoon. बस बोलो 😊
