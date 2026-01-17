# Retail & Marketing Analytics: Customer Segmentation & Retention
*Author:* Vipul Kamble | [LinkedIn](www.linkedin.com/in/vipul-kamble-281533300) | [GitHub Profile](https://github.com/vipul0027)

---

## 📌 Project Overview
This project focuses on analyzing retail data to uncover actionable insights regarding customer behavior, sales trends, and marketing optimization. By leveraging data science techniques, the study aims to enhance customer retention and streamline marketing strategies through data-driven decisions.

### 🛠 Tech Stack
- *Language:* Python
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- *Methodologies:* K-Means Clustering, RFM Analysis, Cohort Retention Analysis

---

## 🧼 1. Data Preprocessing & Quality Control
Before conducting the analysis, a rigorous data cleaning process was implemented to ensure data integrity:
* *Handling Missing Values:* Identified and treated null values in critical columns like Customer_Name and Profit.
![Data Quality](retail_viz/missing_values_analysis.png)
* *Statistical Profiling:* Performed a detailed statistical summary to understand the mean, median, and variance of numerical features.
![Statistical Summary](retail_viz/statistical_distribution.png)
* *Outlier Management:* Utilized Boxplots to detect and treat anomalies in Sales and Profit distributions.
![Outlier Treatment](retail_viz/outlier_detection.png)

---

## 📈 2. Exploratory Data Analysis (EDA)
Key findings from the descriptive analysis include:
* *Correlation Analysis:* Analyzed the relationship between variables like Sales, Quantity, and Discount using heatmaps.
![Correlation Heatmap](retail_viz/correlation_heatmap.png)
* *Market Segmentation:* Visualized sales distribution across different Regions and Product Categories.
![Category Distribution](retail_viz/categorical_distribution.png)

---

## 🤖 3. Machine Learning: Customer Segmentation
Applied K-Means Clustering to group customers based on their purchasing patterns:
* *Optimal Cluster Identification:* Used the *Elbow Method* and Silhouette Scores to determine the ideal number of segments.
![Elbow Method](retail_viz/elbow_method_clustering.png)
* *Segmentation Results:* Successfully categorized customers into distinct groups such as 'Loyalists', 'At-Risk', and 'New Prospects'.

---

## 🔄 4. Advanced Analytics: Cohort Retention
Conducted a Cohort Analysis to track customer loyalty over time. This heatmap represents the percentage of customers returning in subsequent months.
![Cohort Retention Matrix](retail_viz/cohort_retention_matrix.png)

---

## 📂 Repository Structure
- data/: Contains raw and processed datasets (CSV).
- retail_viz/: High-resolution analytical plots and visualizations.
- Capstone2_Retail_and_Marketing_Analytics_Project.ipynb: Full Python implementation with detailed documentation.
