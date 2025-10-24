# SaaS Customer Churn Analysis

## Project Overview
This project analyzes customer churn data from a SaaS (Software as a Service) company to understand user retention patterns and business performance.  
The dataset includes account information, subscription details, and churn events, allowing for the exploration of customer behavior, churn reasons, and renewal rates.

## Dataset
The dataset consists of three main tables:
- **Accounts** – company-level details such as industry, country, and plan tier.  
- **Subscriptions** – information on subscription status, revenue, and auto-renew settings.  
- **Churn Events** – records of customer churn, including churn dates and reasons.

All tables were merged into a unified analytical dataset for further exploration.

## Analysis Goals
- **Explore data quality and structure**: clean and merge the datasets for analysis.  
- **Measure churn rate**: calculate the percentage of customers who ended their subscriptions.  
- **Analyze churn patterns**: study how churn varies by plan type, industry, and region.  
- **Understand churn reasons**: identify the most common causes behind customer attrition.  
- **Evaluate revenue impact**: assess how churn affects recurring revenue and renewal rates.  
- **Visualize trends**: build clear dashboards in Power BI to highlight key business insights.

## Technologies Used
- **Python (Pandas, NumPy)** – data cleaning and analysis  
- **Matplotlib & Seaborn** – visualization in Jupyter Notebook  
- **Power BI** – interactive dashboards and churn trend reporting  
- **Jupyter Notebook** – workflow documentation (`saas_analysis.ipynb`)

## Key Findings
- The **overall churn rate** is approximately **80%**, with little variation across plan tiers.  
- Industries such as **DevTools and EdTech** show slightly higher churn compared to FinTech and HealthTech.  
- The **most common churn reasons** are related to **features**, **budget**, and **support quality**.  
- Around **80% of subscriptions have auto-renew enabled**, suggesting strong retention potential for ongoing plans.  
- Monthly revenue trends remain stable, indicating that most churn occurs among smaller or trial accounts.

---

