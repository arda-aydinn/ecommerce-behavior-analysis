# Strategic E-Commerce Customer Behavior Analysis

## 📌 Project Overview
This repository contains the data cleaning, exploratory data analysis (EDA), and visualization pipeline for a comprehensive e-commerce customer behavior study. The primary objective of this project was to understand the correlations between purchasing behaviors, demographic information (such as gender and age), and customer membership tiers across various cities in Turkey.

## 🚀 My Role & Contributions
While this was a 4-person academic project, I acted as the **Project Lead and Primary Author**. I was solely responsible for developing the end-to-end data cleaning pipeline, conducted the primary exploratory data analysis (EDA) for category-based trends, and edited/compiled the final technical report to ensure high academic and professional standards.

## 🛠️ Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

## 🧹 Data Tidying & Cleaning Pipeline
The raw dataset consisted of 1,725 rows and 16 columns. I executed a rigorous, 16-step data cleaning checklist using Pandas to ensure strict adherence to tidy data principles:
1. **Structural Verification:** Confirmed the dataset's tidy format (eliminating the need for melt/stack techniques) and verified variable data types.
2. **Column & String Standardization:** Standardized column names by fixing typos and spacing issues. Converted all string values to lowercase and programmatically removed formatting artifacts (e.g., `%`, `*`, and trailing white spaces).
3. **Data Optimization:** Dropped the irrelevant `ORDERID` column and resolved non-unique categorical observations (e.g., merging "f3male" into "female") to achieve perfect uniqueness.
4. **Outlier Handling:** Detected potential outliers using the Interquartile Range (IQR) method and replaced identified anomalies with the mean to maintain statistical uniformity.
5. **Missing Value Imputation:** Handled `NaN` values by applying a domain-specific imputation strategy: filling categorical variables with the mode and numerical variables with the mean.

## 📊 Key Business Insights Derived
Through the EDA and visualizations, several critical operational insights were identified:
* **The "Star" Category:** The *Home & Kitchen* segment demonstrated high average basket values coupled with high customer satisfaction scores, making it a robust revenue driver.
* **The "Risk Zone":** The *Groceries* category exhibited high transaction values but concerningly low satisfaction scores, highlighting a critical area for operational improvement and churn prevention.
* **Premium Memberships:** Analysis revealed that gender does not significantly impact spending within premium (Gold/Silver) loyalty tiers, suggesting that high-value incentives should be universally applied rather than gender-segmented.
