# 🧠 Clustering Projects: K-Means & Hierarchical Clustering on Real-World Datasets

This repository presents a comprehensive analysis using **K-Means** and **Hierarchical Clustering** on multiple real-world datasets. The objective is to uncover hidden patterns, group similar data points, and extract meaningful business insights across different domains such as airlines, crime, telecom, and insurance.

## 📁 Datasets & Problem Statements

1. **EastWest Airlines Dataset (`EastWestAirlines.xlsx`)**  
   - Segment frequent flyer customers.  
   - Apply K-Means and Hierarchical Clustering for customer profiling.

2. **Crime Data (`crime_data.csv`)**  
   - Cluster U.S. states based on crime statistics.  
   - Use clustering to categorize regions by crime intensity.

3. **Telecom Churn Data (`Telco_customer_churn.xlsx`)**  
   - Segment telecom users based on behavior and churn indicators.  
   - Handle mixed data types through encoding and scaling.

4. **Auto Insurance Dataset (`Autoinsurance.csv`)**  
   - Group customers for targeted marketing based on insurance usage and demographics.

## 🔍 Project Workflow

Each dataset follows this ML pipeline:

1. **Business Understanding**
2. **Data Dictionary & Feature Exploration**
3. **Data Preprocessing**
   - Handling nulls, scaling, encoding
4. **Exploratory Data Analysis (EDA)**
   - Univariate, bivariate analysis with visualizations
5. **Clustering**
   - **K-Means Clustering**
     - Optimal cluster selection via Elbow Method
     - Cluster interpretation and business insights
   - **Hierarchical Clustering**
     - Dendrogram visualization to choose optimal clusters
     - Agglomerative clustering approach
     - Comparison with K-Means results
6. **Business Insights & Impact**
   - Highlighting actionable insights based on cluster profiles
   - Strategic recommendations based on findings

## 🛠️ Tools & Technologies

- Python
- Libraries: Pandas, NumPy, Scikit-learn, SciPy, Seaborn, Matplotlib
- Jupyter Notebooks

## 📌 Key Takeaways

- Compared K-Means and Hierarchical clustering across domains
- Used scaling, encoding, and EDA to prepare mixed datasets
- Visualized cluster formations using Elbow plots and dendrograms
- Derived domain-specific insights for marketing, policy planning, and churn reduction

## 📂 Repository Structure

```bash
📦Clustering-Projects/
 ┣ 📁 EastWestAirlines/
 ┃ ┣ 📄 KMeans_EastWestAirlines.ipynb
 ┃ ┗ 📄 HClust_EastWestAirlines.ipynb
 ┣ 📁 CrimeData/
 ┃ ┣ 📄 KMeans_CrimeData.ipynb
 ┃ ┗ 📄 HClust_CrimeData.ipynb
 ┣ 📁 TelcoChurn/
 ┃ ┣ 📄 KMeans_TelcoChurn.ipynb
 ┃ ┗ 📄 HClust_TelcoChurn.ipynb
 ┣ 📁 AutoInsurance/
 ┃ ┣ 📄 KMeans_AutoInsurance.ipynb
 ┃ ┗ 📄 HClust_AutoInsurance.ipynb
 ┗ 📄 README.md
```

## 🙋‍♂️ Author Info

**Name:** _[Your Name]_  
**Batch ID:** _[Your Batch ID]_  
**Topic:** Clustering - K-Means & Hierarchical