Task 12: Customer Segmentation using KMeans Clustering
Objective

The objective of this task is to perform customer segmentation using KMeans clustering to group shopping mall customers based on their annual income and spending behavior. This task helps in understanding unsupervised learning and customer behavior analysis.

Dataset

Dataset Name: Shopping Mall Customer Segmentation Dataset

File: Shopping Mall Customer Segmentation Data .csv

Features Used:

Annual Income

Spending Score

Tools and Libraries Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Steps Performed

Loaded the shopping mall customer dataset using Pandas.

Explored dataset structure and column names.

Removed irrelevant columns such as Customer ID and Gender.

Selected Annual Income and Spending Score for clustering.

Applied StandardScaler for feature scaling.

Used the Elbow Method to determine the optimal number of clusters.

Trained the KMeans clustering model.

Assigned cluster labels to each customer.

Visualized customer segments using scatter plots.

Interpreted each customer cluster.

Saved the segmented dataset for future use.

Model Evaluation

Evaluation Method: Elbow Method (Inertia)

The optimal number of clusters was selected based on the elbow point.

Cluster visualization helped in understanding customer groups.

Cluster Interpretation

Cluster 0: Low income, low spending – Budget customers

Cluster 1: High income, high spending – Premium customers

Cluster 2: Low income, high spending – Impulsive buyers

Cluster 3: High income, low spending – Careful customers

Cluster 4: Average income and spending – Standard customers

Deliverables

Jupyter Notebook (.ipynb)

Elbow Method plot

Cluster visualization plot

Segmented customer dataset (.csv)

Final Outcome

The intern successfully applied KMeans clustering to segment shopping mall customers, identified the optimal number of clusters using the Elbow method, and derived meaningful business insights from customer behavior patterns.

Key Learnings

Understanding unsupervised learning

Importance of feature scaling in KMeans

Using the Elbow Method for optimal cluster selection

Interpreting clustering results for business insights
