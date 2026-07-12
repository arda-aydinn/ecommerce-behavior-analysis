# Strategic E-Commerce Customer Behavior Analysis

## 📌 Project Overview

This project analyzes customer behavior using a synthetic e-commerce dataset focused on transactions across different cities in Turkey. The analysis explores purchasing patterns, demographic differences, membership tiers, discount dynamics, and customer satisfaction.

The project follows an end-to-end data analysis workflow: raw data inspection, data cleaning, exploratory data analysis, visualization, insight extraction, and final technical reporting.

## 👤 My Role

This was completed as a 4-person academic project for STAT 112 at Middle East Technical University.

I served as the **Project Lead & Primary Contributor**. My main responsibilities included:

- Building the full data cleaning pipeline from raw data to cleaned dataset
- Standardizing column names, data types, categorical values, and missing values
- Detecting and handling outliers using the IQR method
- Conducting the primary exploratory analysis for my assigned research question
- Writing and editing the majority of the final technical report
- Compiling the report into a consistent academic format

## 🔄 Project Workflow

1. **Raw Data Inspection**
   - Examined dataset structure, variable types, missing values, and formatting issues.

2. **Data Cleaning**
   - Standardized column names and categorical values.
   - Removed unnecessary formatting characters.
   - Fixed inconsistent category labels.
   - Converted variables into appropriate data types.
   - Detected and treated outliers using the IQR method.
   - Imputed missing values using mean/mode-based strategies.

3. **Exploratory Data Analysis**
   - Investigated purchasing behavior across product categories, gender, membership tiers, discount rates, and customer satisfaction.

4. **Visualization & Reporting**
   - Created visualizations using Matplotlib and Seaborn.
   - Summarized findings in an IEEE-style final report.

## 🔑 Key Findings

- **Category Performance:** Electronics showed the highest average basket value, while Home & Kitchen also performed strongly across genders.
- **Gender-Based Spending:** Basket values varied by category; for example, male customers showed higher average spending in Beauty, while female customers had higher basket values in Books & Stationery.
- **Membership Behavior:** Spending patterns were more strongly associated with membership tier than gender differences.
- **Discount Dynamics:** Guest users showed higher variability in discount rates, while loyalty program members had more consistent discount distributions.
- **Value-Satisfaction Matrix:** Groceries appeared as a risk category due to high spending but relatively low satisfaction, while Home & Kitchen emerged as a strong value-satisfaction category.

## 🛠️ Tools & Methods Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Exploratory Data Analysis
- Data Cleaning
- Statistical Data Analysis

## 🔗 Resources

- 🧹 [Data Cleaning Notebook](notebooks/data-cleaning.ipynb)
- 📊 [Exploratory Analysis Notebook](notebooks/exploratory-analysis.ipynb)
- 📄 [Final Project Report](reports/project-report.pdf)
