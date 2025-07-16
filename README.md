🛍️ Mall Customer Segmentation using K-Means Clustering
📌 Project Overview
This project implements a K-Means clustering algorithm to segment customers of a retail mall based on their Annual Income and Spending Score. The goal is to understand customer behavior and enable businesses to target customer groups more effectively with personalized strategies.

📁 Dataset
Dataset Name: Mall_Customers.csv

Source: Kaggle Mall Customers Dataset

Features:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

🎯 Objective
Cluster customers into distinct groups based on purchase behavior using unsupervised machine learning. This helps identify:

High-value customers

Budget shoppers

Average spenders

Target segments for promotions

🧠 Algorithms Used
K-Means Clustering

Elbow Method to find optimal number of clusters

🛠️ Technologies Used
Python

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn

🚀 How it Works
Load and explore the dataset

Select relevant features (Annual Income, Spending Score)

Standardize the data using StandardScaler

Determine optimal clusters using the Elbow Method

Train KMeans and predict clusters

Visualize clusters using scatter plots

Analyze customer segments and generate insights

📈 Results
5 distinct clusters of customers identified

Visual separation between high-spenders, average buyers, and low-income groups

Useful insights for personalized marketing

📊 Visualization

Clusters are plotted based on income and spending score, with distinct colors representing each group.

▶️ Run Locally

# Step 1: Clone the repo
git clone https://github.com/your-username/mall-customer-segmentation.git

# Step 2: Change directory
cd mall-customer-segmentation

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the script
python mall_kmeans.py

📬 Contact
Built with 💻 by Krrish Yaduka
📩 Connect on LinkedIn for collaboration!
