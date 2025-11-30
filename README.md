# Telecom Customer Churn Analysis Dashboard (Power BI)

This project presents a complete Telecom Customer Churn Analysis built using Power BI.  
It helps identify why customers Churn Rate , which groups are at high risk, and what business actions can reduce churn.

## Project Files Included
Telecom churn Analysis.pbix — Power BI dashboard  
Dataset.xls — Raw telecom customer dataset  

## Project Objective
The main goal of this project is to help telecom companies:

- Understand customer churn behaviour  
- Identify high-risk customer segments  
- Analyze billing patterns, tenure, contract type, and service usage  
- Build an interactive dashboard for decision-making  
- Provide actionable insights to reduce churn  

## Key Insights
Some major findings from the dashboard include:

- **Month-to-month contract customers churn the most**  
- Customers with **higher monthly charges** show higher churn rates  
- **Short tenure** customers are at the highest risk  
- **Electronic check** payment method has the highest churn  
- **Fiber optic** internet users churn more compared to DSL users  
- Senior citizens show a comparatively higher churn tendency  

## Data Preparation
Performed using Power Query in Power BI:

- Removed duplicates  
- Standardized column names  
- Converted incorrect data types  
- Cleaned categorical values  
- Created calculated columns (Tenure Groups, Churn Flag, etc.)  
- Prepared a clean dataset for dashboard visuals  

## Dashboard Highlights
The Power BI dashboard includes:

- Overall Churn Rate KPI
- Churn by Contract Type
- Monthly Charges vs Churn Visualization
- Tenure Group Analysis
- Internet Service & Payment Method Insights
- Customer Segmentation Charts
- Interactive slicers for gender, senior citizen, tenure, services, etc.  

## How to Use This Project
1. Download the ".pbix" file  
2. Open in Power BI Desktop  
3. Use slicers to explore customer segments  
4. Study churn behaviours using visual reports  
5. Review insights to understand root causes of churn  

## Dataset Information
- Dataset.xls → Raw dataset used in the dashboard  
- Columns include: customerID, gender, senior citizen, tenure, contract type, payment method, monthly charges, total charges, churn, services, etc.

