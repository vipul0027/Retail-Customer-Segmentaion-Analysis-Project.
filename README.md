# 🛒 Retail & Marketing Analytics: Customer Segmentation & Retention
*Prepared by: Vipul Kamble* | [LinkedIn](www.linkedin.com/in/vipul-kamble-281533300) | [Portfolio](https://github.com/vipul0027)

---

## 📌 Project Overview
Ye project ek retail dataset par based hai jahan humne *Customer Behavior, **Sales Trends, aur **Segmentation* ka analysis kiya hai. Iska main goal marketing strategies ko optimize karna aur customer retention badhana hai.

### 🛠 Tech Stack
- *Language:* Python
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- *Concepts:* K-Means Clustering, RFM Analysis, Cohort Analysis

---

## 🧼 1. Data Cleaning & Quality Assurance
Analysis se pehle data ko "Clean" karna sabse zaroori step tha:
* *Missing Values:* Humne identify kiya ki Customer_Name aur Profit mein missing values thi jise handle kiya gaya.
![Data Quality](retail_viz/missing_values_analysis.png)
* *Statistical Summary:* Data ki average, mean, aur distribution ko check kiya gaya.
![Stats Summary](retail_viz/statistical_distribution.png)
* *Outlier Treatment:* Sales aur Profit ke extreme values (Outliers) ko Boxplot ke through identify aur treat kiya gaya.
![Outliers](retail_viz/outlier_detection.png)

---

## 📈 2. Exploratory Data Analysis (EDA)
Humne kuch key patterns find kiye:
* *Correlation Analysis:* Sales aur Profit ke beech ka relation check kiya gaya.
![Correlation](retail_viz/correlation_heatmap.png)
* *Demographic Distribution:* Region aur Category wise sales ka distribution.
![Category Distribution](retail_viz/categorical_distribution.png)

---

## 🤖 3. Machine Learning: Customer Segmentation
K-Means Clustering ka use karke humne customers ko alag-alag segments mein baata:
* *The Elbow Method:* Optimal number of clusters find karne ke liye.
![Elbow Method](retail_viz/elbow_method_clustering.png)
* *Result:* Humne Loyal, At-Risk, aur New Customers ke distinct groups banaye.

---

## 🔄 4. Customer Retention (Cohort Analysis)
Sabse advanced part ye tha ki humne check kiya ki kitne % customers har mahine wapas aa rahe hain.
![Retention Analysis](retail_viz/cohort_retention_matrix.png)

---

## 📂 Repository Structure
* data/: Raw & Processed datasets.
* retail_viz/: Professional visualizations.
* Notebooks/: Main Python file with detailed code and comments.
