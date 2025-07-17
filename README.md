**Customer Churn Analysis – Telco Dataset**

This project aims to analyze and visualize customer churn data from a telecom company. The goal is to identify key factors driving customer attrition and help business stakeholders reduce churn through actionable insights.


## Problem Statement

Customer churn is a major problem in the telecom industry, especially among month-to-month customers. Understanding **why** customers leave and **who** is at high risk allows companies to design effective retention strategies.


## Dataset

- **Source**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records**: 7043 customers
- **Features**: Customer demographics, services opted, contract details, charges, tenure, and churn status.


## Tools Used

- **Python** – Data cleaning, feature engineering, EDA
- **Pandas, Matplotlib, Seaborn** – Visualization & Data Manipulation
- **SQL** – Data filtering & insights (simulated queries)
- **Power BI** – Executive dashboard for retention strategy


##  Key Steps

### 1. Data Cleaning & Preparation
- Converted `TotalCharges` to numeric
- Handled missing values
- Created churn flag & tenure groups

### 2. Exploratory Data Analysis
- Churn distribution by contract, charges, and tenure
- Correlation matrix for numerical features
- Identified patterns using bar charts, heatmaps, and boxplots

### 3. Feature Engineering
- `TenureGroup`: Binned tenure into 5 categories
- `ChurnFlag`: Binary target for churn prediction

### 4. Power BI Dashboard
- KPI cards: Total Customers, Churn %, Avg Monthly Charge
- Bar & Donut Charts: Churn by contract, gender, tenure
- Slicers: Gender, Contract Type, Tenure Group
- Identified high-risk customer segments visually


##  Insights & Recommendations

- **Month-to-month** customers churn the most (42%)  
- **Fiber optic users** have higher churn than DSL  
- Customers with **high monthly charges** and **tenure < 12 months** are more likely to leave  
- Recommend offering **long-term contracts** or **loyalty rewards** to reduce early churn


##  Files in Repositor

`Customer_Churn_Analysis.ipynb` | Python code for data cleaning and EDA 
`cleaned_telco_data.csv` | Clean dataset used for Power BI 
`churn_dashboard.pbix` | Power BI file with interactive visuals 
`README.md` | Project overview and documentation 
