# PRODIGY_ML_02

📌 Project Overview
Create a K-means clustering algorithm to group customers of a retail store based on theory purchase history.

📁 Dataset
The dataset contains the following features:

---CustomerID

---Gender

---Age

---Annual Income (k$)

---Spending Score (1-100)

---For clustering, we used:

---Annual Income (k$)

---Spending Score (1-100)
🧠 Machine Learning Approach

We implemented:

Data preprocessing

Feature scaling using StandardScaler

Elbow Method to determine optimal number of clusters

K-Means clustering algorithm
📈 Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

Optimal K = 5


🎯 Customer Segments Identified
Cluster	Description
0	High Income – High Spending (VIP Customers)
1	Low Income – Low Spending
2	High Income – Low Spending
3	Low Income – High Spending
4	Average Customers

📊 Results

The model successfully segmented customers into meaningful groups based on income and spending patterns.

These insights can help businesses:

Target high-value customers

Design personalized offers

Improve marketing efficiency

Increase overall profitability

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

📌 Future Improvements

Include Age and Gender encoding

Apply PCA for visualization

Compare with DBSCAN clustering

Deploy as a web app
👩‍💻 Author

Tehreem-Un-Nisa
Machine Learning Enthusiast | Mathematics Background | AI Research Aspirant
