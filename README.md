# 🧠 K-Means Clustering Projects on Real-World Datasets

This repository contains end-to-end K-Means clustering analysis on multiple real-world datasets to identify meaningful customer segments and patterns that drive business decisions across various domains.

## 📁 Datasets & Problem Statements

1. **EastWest Airlines Dataset (`EastWestAirlines.xlsx`)**  
   Goal: Segment airline customers using K-Means clustering to understand frequent flyer behaviors and loyalty metrics.

2. **Crime Data (`crime_data.csv`)**  
   Goal: Group states in the U.S. based on crime statistics to identify high-risk areas and create actionable insights for public safety initiatives.

3. **Telecom Churn Data (`Telco_customer_churn.xlsx`)**  
   Goal: Analyze customer churn patterns by clustering telecom users. The data includes both categorical and numerical features. The objective is to extract churn-prone segments.

4. **Auto Insurance Dataset (`Autoinsurance.csv`)**  
   Goal: Cluster customers based on demographic and policy features to help insurance companies tailor products and marketing strategies.

## 🔍 Project Workflow

Each dataset follows a consistent ML pipeline:

1. **Business Understanding**
   - Clear articulation of the business problem and objectives.
   - Identifying domain-specific constraints.

2. **Data Dictionary Creation**
   - Feature-wise explanation and data type mapping for each dataset.

3. **Data Preprocessing**
   - Missing value treatment
   - Feature engineering
   - Encoding categorical variables
   - Normalization/scaling

4. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Univariate and bivariate visualizations
   - Insights on data distribution and correlation

5. **Modeling**
   - K-Means clustering with multiple `k` values
   - Scree plots (Elbow Method) to determine optimal clusters
   - Cluster labeling and interpretation
   - Comparison of results using different preprocessing approaches

6. **Business Impact**
   - Translating model outputs into strategic actions
   - Identifying customer segments for targeted marketing, churn reduction, policy design, etc.

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks

## 📌 Key Takeaways

- Performed unsupervised learning to uncover hidden patterns in the data.
- Applied feature engineering and scaling techniques tailored to each dataset.
- Used visual methods like Elbow plots to optimize cluster selection.
- Derived actionable insights across industries (airline, telecom, insurance, public safety).

## 📂 Structure

```bash
📦KMeans-Clustering-Projects/
 ┣ 📁 EastWestAirlines/
 ┃ ┗ 📄 KMeans_EastWestAirlines.ipynb
 ┣ 📁 CrimeData/
 ┃ ┗ 📄 KMeans_CrimeData.ipynb
 ┣ 📁 TelcoChurn/
 ┃ ┗ 📄 KMeans_TelcoChurn.ipynb
 ┣ 📁 AutoInsurance/
 ┃ ┗ 📄 KMeans_AutoInsurance.ipynb
 ┗ 📄 README.md
```

## 🙋‍♂️ Author Info

**Name:** AMARENDER REDDY SUDIREDDY

**Topic:** K-Means Clustering
