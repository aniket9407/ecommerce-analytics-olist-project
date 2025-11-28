Olist E-Commerce Analytics — End-to-End Data Analytics Project
SQL • Python • Power BI • Data Modeling • Business Insights

Author: Aniket Sharma

🧭 1. Project Overview

This project is a complete end-to-end analytics workflow built on the Brazilian Olist E-commerce dataset (100,000+ orders).
It showcases industry-level data analytics capabilities including:

Data extraction, cleaning & transformation (SQL, Python)

Business-focused exploratory data analysis

Cohort-based customer retention analytics

Product, sales, and logistics performance modeling

Operational insights using advanced DAX & Power BI

Interactive 4-page dashboard for stakeholders

The purpose of this project is to demonstrate real-world problem-solving skills required for a Data Analyst role across e-commerce, logistics, supply chain, and business intelligence teams.

2. Tools & Technologies
| Tool                                     | Usage                                                  |
| ---------------------------------------- | ------------------------------------------------------ |
| **MySQL**                                | Data schema creation, cleaning, transformations, joins |
| **Python (Pandas, Matplotlib, Seaborn)** | EDA, cohort analysis, correlation modeling             |
| **Power BI**                             | Data modeling, DAX measures, KPI dashboards            |
| **GitHub**                               | Version control, repository management                 |
| **Google Drive**                         | Hosting large PBIX and dataset files                   |

3. Repository Structure
ecommerce-analytics-olist-project/
│
├── data-raw/               # Placeholder (Actual files in Google Drive)
├── docs/                   # Executive summary & documentation
├── data-cleaned/           # Placeholder (Actual files in Google Drive)
├── powerbi-dashboard/      # Placeholder (PBIX stored in Google Drive)
├── python-analysis/        # Python notebook for EDA & modeling
├── screenshots/            # Dashboard images & EDA plots
├── sql-scripts/            # SQL data cleaning, transformations, joins
└── README.md               # This file
Full project files (PBIX, raw datasets, cleaned datasets, SQL scripts, Python notebook):
 Google Drive Link: https://drive.google.com/drive/folders/1xRZDSdSYuSX3CoiITQaRLeER4d1VILg7?usp=sharing

4. Data Preparation & Cleaning (SQL)
- Addressed inconsistent timestamp formats

Converted raw text timestamps into proper DATETIME format

Fixed invalid or missing dates (e.g., 30,699 missing delivery dates)

- Standardized product dimension columns

Handled missing weight, height, width, and length fields

Converted empty fields to NULL and imputed when necessary

- Removed data anomalies

Negative price or freight values

Duplicate customer IDs

Invalid product categories

- Built a master dataset using joins

Final master dataset includes:

Customer details

Order info

Order item info

Product metadata

Freight and logistics details

Delivery timestamps

Calculated delivery days

Financial metrics (price, freight, revenue)

SQL tasks included:

INNER, LEFT, RIGHT joins

Date difference calculations

CTEs

Null handling

Data validation

Performance optimization through indexing

5. Exploratory Data Analysis (Python)
- Conducted comprehensive EDA:

Revenue distribution

Sales trend visualizations

Freight analysis

Outlier detection

Category-level performance

Seller performance

Delivery time behavior

- Correlation Analysis

Significant finding:

Product weight has a strong correlation (0.61) with freight cost.
This indicates shipping charges are influenced more by physical characteristics than price.

- Cohort Analysis

Created cohort groups using first purchase date:

Month 0 → High number of unique customers

Month 1 → Sharp drop in retention

Month 2+ → Very low repeat behavior

Repeat customer rate ≈ 2–3%, indicating major opportunities for CRM improvements.

6. Power BI Dashboard — 4 Pages
### Page 1 — Sales Overview

Total Revenue, Total Orders

Monthly Revenue Trend

Top Selling Categories

Top Customer Cities

Year-over-year patterns

Seasonality spikes (e.g., peak in Nov 2017)

Page 2 — Customer Analytics

Total vs Repeat Customers

Repeat Customer Rate

Customer Funnel (New → Repeat)

Avg Orders per Customer

Top 10 Customer Cities

Cohort Summary Table

Insight:
Very low repeat rate (2%) exposes a retention/marketing gap.

Page 3 — Product & Category Analytics

Best & worst performing categories

Freight cost by category

Delivery days by category

Scatter plots:

Weight vs Freight

Price vs Freight

Category contribution to revenue

Insight:

Categories like Beleza Saude dominate revenue.

Heavy/bulky items incur significantly higher freight cost.

Page 4 — Delivery & Logistics

Average delivery days

SLA compliance rate

Very late orders > 30 days

Delivery distribution histogram

Freight outliers

Top 10 slowest sellers

Delivery performance by city

Insight:

Avg delivery = 12 days

Several categories frequently exceed delivery SLA

Seller performance varies significantly

Cities far from seller clusters show longer delivery times

7. Key Data-Driven Insights
- Sales

Total Revenue: 15.8M+

Peak month: Nov 2017

High-performing categories:

Beleza Saude

Relogios Presentes

Cama Mesa Banho

- Customer

Total customers: 95k

Repeat customer rate: ~2%

Avg orders per customer: 1.03

Low retention → urgent need for customer loyalty programs

- Logistics

Avg delivery time: 12–13 days

30 day late deliveries: 4,553 orders

Product weight strongly increases freight cost

Certain sellers consistently deliver late → SLA risk

8. Skills Demonstrated

SQL data modeling & optimization

Python analytic storytelling

Time-series, cohort, and correlation analysis

Power BI data modeling & DAX

Professional dashboard development

Business domain knowledge (E-commerce & logistics)

Insight presentation for stakeholders

9. Executive Summary (Business View)

This analysis provides an end-to-end view of how an e-commerce business performs across the funnel:

Acquisition: Many new customers, but very low retention

Product performance: A few categories dominate the business

Operations: Logistics delays and freight outliers impact customer satisfaction

Revenue: Consistent growth with seasonal peaks

Recommendations:

Implement targeted retention campaigns

Improve seller SLA monitoring

Use weight-based shipping optimization

Focus on improving delivery predictability

Prioritize high-potential categories

10. Access Full Project (Datasets + PBIX + Code)

Google Drive Link: https://drive.google.com/drive/folders/1xRZDSdSYuSX3CoiITQaRLeER4d1VILg7?usp=sharing
Includes:

PBIX dashboard

Cleaned & raw datasets

SQL scripts

Python notebook

Documentation

11. About Me

I am Aniket Sharma, an aspiring Data Analyst with hands-on experience in:

SQL

Power BI

Python

Business analytics

Dashboarding & storytelling

This project demonstrates my full capability to deliver real business impact using data.

