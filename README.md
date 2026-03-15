🛒 SmartCart Clustering System












📌 Project Overview

The SmartCart Clustering System is an Unsupervised Machine Learning project that analyzes customer data and groups customers into different segments based on purchasing behavior and demographic characteristics.

Customer segmentation helps businesses:

Understand different customer types

Improve marketing strategies

Target the right audience

Increase customer satisfaction and sales

This project applies K-Means Clustering to automatically identify meaningful customer groups.

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

VS Code

📂 Project Structure
SmartCart-Clustering-System
│
├── data
│   └── customer_dataset.csv
│
├── notebooks
│   └── smartcart_clustering.ipynb
│
├── src
│   └── clustering_model.py
│
├── requirements.txt
│
└── README.md
🔄 Project Workflow
Customer Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Feature Scaling
      ↓
K-Means Clustering
      ↓
Customer Segmentation
      ↓
Cluster Visualization
🤖 Clustering Algorithm

The system uses K-Means Clustering, an unsupervised learning algorithm that groups customers based on similarity.

Steps followed by the algorithm:

Select number of clusters (K)

Assign customers to the nearest cluster center

Update cluster centroids

Repeat until clusters stabilize

This helps discover hidden patterns in customer behavior.

📊 Features Used

The model uses the following attributes:

Age

Income

Education

Marital Status

Total Spending

Customer Tenure

Number of Children

These features allow the algorithm to group customers with similar demographic and spending patterns.

▶️ How to Run the Project (Using VS Code)
1️⃣ Clone the Repository
git clone https://github.com/saifullah857/Smartcart-Clustering-System.git
2️⃣ Open Project in VS Code
cd smartcart-clustering-system
code .
3️⃣ Install Required Libraries
pip install -r requirements.txt
4️⃣ Run the Notebook

Open the Jupyter Notebook file in VS Code and run all cells.

📈 Visualization

The project visualizes clusters using:

Scatter plots

Customer distribution graphs

Spending pattern analysis

These visualizations help interpret customer segmentation results.

🚀 Future Improvements

Future enhancements include:

Implement Hierarchical Clustering

Add DBSCAN Clustering

Build an interactive Streamlit Dashboard

Create a Customer Recommendation System

Deploy the project online

👨‍💻 Author

Saifullah Khalid