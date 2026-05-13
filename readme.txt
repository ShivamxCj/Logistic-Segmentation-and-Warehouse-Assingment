Logistic Segmentation & Warehouse Assignment System

Overview

This project is an end-to-end logistics optimization system that uses Machine Learning and Geo-Spatial Analysis to intelligently assign customer orders to the nearest optimal warehouse based on geographic demand patterns.

Using customer order latitude and longitude data, the system applies K-Means Clustering to identify high-demand zones and optimize warehouse assignment for efficient delivery operations.

The project simulates how large-scale e-commerce companies like Amazon and Flipkart optimize delivery networks and warehouse allocation.

Features ✨
Geo-spatial customer segmentation using K-Means clustering
Warehouse assignment based on nearest cluster centroid
Distance-based logistics optimization
Demand zone identification
Warehouse load distribution analysis
Silhouette Score evaluation for cluster quality
End-to-end logistics simulation pipeline
Tech Stack 🛠️
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Geo-Spatial Analysis
Machine Learning
Problem Statement 📌

In large-scale logistics systems, assigning customer orders to inefficient warehouses increases:

Delivery time
Fuel cost
Operational overhead
Warehouse imbalance

The goal of this project is to:

Identify customer demand zones using clustering
Assign each zone to the most optimal warehouse
Reduce delivery distance and improve logistics efficiency
Project Workflow 🔄
1. Data Collection

Customer order data containing:

Latitude
Longitude
Order ID
Warehouse locations
2. Data Preprocessing
Removed missing values
Scaled geo-location data
Prepared coordinates for clustering
3. K-Means Clustering

Applied K-Means clustering on customer coordinates to create geographic demand zones.

Objective:

Group nearby customers together to simulate delivery regions.

4. Cluster Evaluation

Used Silhouette Score to evaluate clustering performance.

Result:
Silhouette Score ≈ 0.45

This indicates reasonably good cluster separation.

5. Warehouse Assignment

Each cluster centroid was mapped to the nearest warehouse using distance calculations.

Goal:

Minimize delivery distance between customers and assigned warehouses.

6. Load Distribution Analysis

Analyzed:

Number of orders handled per warehouse
Demand concentration
Potential warehouse overloads
Machine Learning Concept Used 🧠
K-Means Clustering

K-Means partitions customer locations into clusters by minimizing the distance between data points and cluster centroids.

Results 📊
Successfully segmented customer demand regions
Optimized warehouse assignment based on nearest demand cluster
Reduced simulated delivery distance
Identified high-demand warehouse regions
Built a scalable logistics optimization workflow
Folder Structure 📁
project/
│
├── data/
│   ├── orders.csv
│   └── warehouses.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── clustering.py
│   ├── warehouse_assignment.py
│   └── visualization.py
│
├── requirements.txt
├── README.md
└── main.py
Installation ⚙️

Clone the repository:

git clone https://github.com/ShivamxCj/your-repo-name.git

Move into the project directory:

cd your-repo-name

Install dependencies:

pip install -r requirements.txt

Run the project:

python main.py
Future Improvements 🚀
Real-time traffic-aware warehouse assignment
Delivery route optimization
Dynamic clustering based on order frequency
Integration with mapping APIs
Demand forecasting using time-series models
Reinforcement Learning for logistics optimization
Learning Outcomes 📚

Through this project, I learned:

Practical implementation of K-Means clustering
Geo-spatial data analysis
Logistics optimization concepts
Distance-based assignment systems
Real-world ML applications in supply chain management
Author 👨‍💻
Shivam Chatterjee
GitHub: ShivamxCj GitHub
LinkedIn: Shivam Chatterjee LinkedIn