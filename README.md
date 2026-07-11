# Thiranex_project3

# 🛍️ Customer Segmentation using Machine Learning

## 📌 Project Overview

This project demonstrates a complete **Customer Segmentation** workflow using **Machine Learning** with the **Ecommerce Customer Behavior Dataset**. The primary objective is to analyze customer demographics and purchasing behavior, group similar customers using the **K-Means Clustering** algorithm, and generate actionable business insights that help improve marketing strategies, customer retention, and overall sales performance.

The project follows an end-to-end Machine Learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, visualization, and business recommendations.

---

## 🎯 Project Objectives

- Load and analyze the Ecommerce Customer Behavior Dataset.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Encode categorical variables.
- Scale numerical features.
- Determine the optimal number of customer clusters.
- Apply K-Means Clustering.
- Visualize customer segments.
- Analyze each customer cluster.
- Generate business insights and marketing recommendations.

---

## 📂 Dataset

**Dataset:** Ecommerce Customer Behavior Dataset (CSV)

The dataset contains customer demographic information, purchasing behavior, engagement metrics, and transaction-related details that can be used to identify meaningful customer segments.

### Important Features

- Customer_ID
- Age
- Gender
- Country
- Subscription Type
- Purchase Frequency
- Total Spend
- Average Order Value
- Product Category
- Payment Method
- Customer Satisfaction
- Loyalty Score
- Engagement Score
- Session Duration
- Number of Visits
- Churn Risk
- Preferred Device
- Tenure
- Discount Usage
- Last Purchase Date

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📚 Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings

from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import LabelEncoder
from sklearn.cluster import KMeans
from sklearn.metrics import silhouette_score

warnings.filterwarnings("ignore")
```

---

## 🤖 Machine Learning Algorithm

**Algorithm Used**

- K-Means Clustering

K-Means is an Unsupervised Machine Learning algorithm used to group customers with similar characteristics into meaningful clusters.

---

## 🔄 Machine Learning Workflow

```
Dataset Collection
        │
        ▼
Load Dataset
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Feature Scaling
        │
        ▼
Elbow Method
        │
        ▼
Silhouette Score
        │
        ▼
K-Means Clustering
        │
        ▼
Cluster Visualization
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
```

---

## 🔍 Exploratory Data Analysis (EDA)

The project performs:

- Display first and last five rows
- Dataset shape
- Dataset information
- Column names
- Data types
- Summary statistics
- Missing value analysis
- Duplicate record detection
- Unique value analysis
- Numerical variable analysis
- Categorical variable analysis
- Outlier detection

---

## 🧹 Data Preprocessing

The preprocessing stage includes:

- Handle missing values
- Remove duplicate records
- Convert data types
- Encode categorical variables
- Scale numerical features using StandardScaler
- Remove unnecessary columns
- Prepare data for clustering

---

## ⚙️ Feature Engineering

The project performs feature engineering by:

- Creating meaningful derived features
- Selecting relevant clustering variables
- Preparing optimized input features for K-Means
- Explaining feature importance

---

## 📊 Cluster Optimization

The optimal number of customer segments is determined using:

- Elbow Method
- Silhouette Score

The final number of clusters is selected based on both evaluation methods.

---

## 📈 Data Visualization

The notebook includes professional visualizations such as:

- Age Distribution
- Gender Distribution
- Total Spend Distribution
- Purchase Frequency Distribution
- Customer Satisfaction Distribution
- Correlation Heatmap
- Elbow Method Graph
- Silhouette Score Graph
- Customer Clusters Scatter Plot
- Spending by Cluster
- Purchase Frequency by Cluster
- Cluster Size Distribution

---

## 👥 Customer Segment Analysis

Each customer cluster is analyzed based on:

- Age Group
- Spending Behavior
- Purchase Frequency
- Customer Satisfaction
- Loyalty Level
- Engagement Score
- Business Value

---

## 💼 Business Insights

The project identifies:

- High-value customers
- Loyal customers
- Potential loyal customers
- Premium customers
- Budget-conscious customers
- Customers at risk of churn
- Customers needing promotional campaigns

---

## 📢 Business Recommendations

Based on customer segmentation, recommendations include:

- Personalized marketing campaigns
- Loyalty reward programs
- Customer retention strategies
- Discount and promotional offers
- Premium membership plans
- Product recommendations
- Customer engagement improvements

---

## 📁 Output Files

The project generates:

```
customer_segments.csv
```

This file contains the original customer data along with the assigned cluster labels.

---

## 📁 Project Structure

```
Customer-Segmentation-Using-Machine-Learning/
│
├── Dataset/
│   └── ecommerce_customer_behavior.csv
│
├── Notebook/
│   └── Customer_Segmentation.ipynb
│
├── Output/
│   └── customer_segments.csv
│
├── Images/
│   └── Charts/
│
├── README.md
│
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone this repository.
2. Download the Ecommerce Customer Behavior Dataset.
3. Open the notebook in Jupyter Notebook.
4. Install the required Python libraries.
5. Run all notebook cells from top to bottom.
6. Review the generated customer segments, visualizations, and business insights.

---

## 🚀 Future Improvements

- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Build an interactive dashboard using Streamlit.
- Automate customer segmentation updates.
- Deploy the model as a web application.
- Integrate real-time customer data.
- Apply advanced clustering algorithms for improved segmentation.

---

## 📌 Conclusion

This project demonstrates a complete end-to-end Customer Segmentation workflow using Machine Learning. By applying K-Means Clustering to customer behavior data, meaningful customer groups were identified, enabling valuable business insights and targeted marketing strategies. The project highlights the importance of customer analytics in improving customer satisfaction, retention, and overall business performance.

---

## 👨‍💻 Author

**Kaviya B**

**B.Sc. Computer Science**

**Machine Learning | Data Science | Customer Analytics | Python | Data Visualization**

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
