# 📊 Marketing Campaign Analysis

## 📌 Project Overview
This project focuses on analyzing customer behavior and marketing performance using the Four Ps of Marketing: Product, Price, Place, and Promotion. The objective is to apply exploratory data analysis (EDA), feature engineering, statistical hypothesis testing, and visualization to uncover insights that can help businesses improve customer acquisition, campaign effectiveness, and channel strategy.

The project demonstrates a complete end-to-end data science workflow, from raw data preprocessing to actionable business insights.

---

## 🎯 Problem Objective
To understand the key factors influencing customer purchasing behavior and marketing campaign response by:
- Analyzing customer demographics and spending patterns  
- Evaluating purchase behavior across multiple sales channels  
- Measuring marketing campaign effectiveness  
- Validating business hypotheses using statistical methods  

---

## 📂 Dataset Description
The dataset is structured around the **Four Ps of Marketing**:

- **Product** – Customer spending across multiple product categories  
- **Price** – Income levels and deal-based purchasing behavior  
- **Place** – Purchases via web, catalog, and physical store channels  
- **Promotion** – Campaign acceptance, complaints, and recency  
- **Demographics** – Age, education, marital status, country, and family structure  

---

## 🔧 Key Tasks Performed

### 🧹 Data Cleaning & Preprocessing
- Parsed and corrected date and numeric data types  
- Cleaned and standardized categorical variables (Education, Marital Status)  
- Converted income from string to numeric format  
- Imputed missing income values using **group-wise median** based on education and marital status  

### 🧠 Feature Engineering
- Created new analytical features:
  - Customer age  
  - Total number of children at home  
  - Total spending across product categories  
  - Total purchases across all sales channels  
- Applied percentile-based outlier treatment to cap extreme values  

### 📊 Exploratory Data Analysis (EDA)
- Visualized distributions using histograms and boxplots  
- Generated correlation heatmaps for numerical variables  
- Analyzed revenue contribution by product category  

### 📈 Statistical Hypothesis Testing
Evaluated real-world business hypotheses using appropriate statistical techniques:
- Relationship between age and in-store shopping preference  
- Impact of children on online purchasing behavior  
- Interaction between store sales and alternative channels  
- Comparison of total purchase volumes between the USA and the rest of the world  

## 📊 Statistical methods used:
- T-tests  
- Mann–Whitney U tests  
- Pearson and Spearman correlation analysis

--- 

## 📉 Business Insights & Visual Analysis
- Identified top-performing and low-performing product categories  
- Analyzed campaign response patterns across age groups and countries  
- Studied spending behavior based on number of children at home  
- Examined educational background of customers who filed complaints  

---

## 📂 Files Uploaded
- **Marketing Campaign Problem Statement.docx** : Complete problem statement
- **Marketing Campaign.ipynb** : Python code
- **markeitng_data.csv** : Dataset of the project

---  

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (Statistical Analysis)
- Datetime
- Jupyter Notebook
- os
- warnings

---

## 📌 Key Takeaways
- Demonstrates a complete **applied data science workflow**  
- Combines **statistical rigor with business-focused analysis**  
- Translates marketing data into **actionable insights**  
- Suitable for **Data Analyst, Business Analyst, and Data Scientist portfolios**

---

## ▶️ How to Run
pip install pandas numpy matplotlib seaborn scipy

---

## 👤 Author
- Prakhar Srivastava
- Aspiring Data Scientist & Business Analyst | Machine Learning, Deep Learning & Generative AI Enthusiast
