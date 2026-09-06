# Telecom-customer-churn-analysis-dashboard
A full data analytics case study that identifies why telecom customers churn, predicts future churn with machine learning, and visualizes actionable business insights in Power BI dashboards.
# About the project

Customer retention is an important challenge for telecommunications companies because losing customers directly affects recurring revenue and long-term business growth.

This project explores customer demographics, service usage, contract information, payment methods, tenure, and revenue-related metrics to understand which customer groups are more likely to leave.

The analysis transforms raw customer data into meaningful business insights through a combination of:

Data cleaning and preparation
Exploratory data analysis
SQL-based business analysis
Customer segmentation
Churn analysis
Revenue and customer value analysis
Interactive Power BI dashboards

The final outcome is a dashboard designed to help business users quickly identify churn patterns and potential retention opportunities.
<img width="1043" height="590" alt="Screenshot 2026-09-06 173515" src="https://github.com/user-attachments/assets/70ff5729-9a47-4282-9736-812c81180d0a" />
# Project Goals

The main objectives of this project are to:

Analyze the overall customer churn rate.
Identify customer characteristics associated with higher churn.
Compare churn across different contract and payment types.
Examine the relationship between customer tenure and churn.
Identify valuable customer segments that require retention attention.
Analyze the potential financial effect of customer churn.
Build an interactive dashboard for exploring churn-related KPIs.
Convert analytical findings into practical business recommendations.
🛠️ Tools & Technologies
Technology	Role in the Project
Python	Data preparation, analysis, feature creation, and modeling
Pandas & NumPy	Data manipulation and numerical analysis
Scikit-learn	Customer churn modeling
SQL	Data querying, aggregation, segmentation, and KPI calculations
Power BI	Interactive dashboard development and visualization
Excel	Initial data inspection and validation
GitHub	Source control and project documentation
# 🔄 Project Workflow
Raw Customer Data
       ↓
Data Cleaning & Preparation
       ↓
SQL-Based Analysis
       ↓
Python Analytics & Modeling
       ↓
Customer Segmentation
       ↓
Power BI Dashboard
       ↓
Business Insights & Recommendations
1. Data Preparation

The initial dataset was reviewed and prepared for analysis.

Key preparation activities included:

Handling missing values.
Checking for duplicate records.
Standardizing categorical variables.
Converting fields into appropriate data types.
Creating additional analytical variables.
Preparing the dataset for SQL, Python, and Power BI analysis.
2. SQL Analysis

SQL was used to investigate customer behavior and create business-level metrics.

The analysis includes:

Churn comparison across contract types.
Churn analysis by payment method.
Tenure-based customer segmentation.
Revenue-based customer grouping.
Customer and churn KPIs.
Analysis of potential revenue exposure from customer losses.
3. Python Analysis

Python was used to perform additional analytical work and develop churn-related insights.

The workflow includes:

Exploratory data analysis.
Feature engineering.
Customer segmentation.
Churn probability analysis.
Logistic regression modeling.
Model evaluation using standard classification metrics.

The resulting analysis can then be incorporated into the Power BI reporting layer.

# 📊 Dashboard Overview

The Power BI dashboard is organized around several analytical areas.

🏠 1. Business Overview

Provides a quick snapshot of the customer base and overall business performance.

Key indicators include:

Total Customers
Active Customers
Churned Customers
Overall Churn Rate
Average Customer Tenure
Monthly Revenue
Total Revenue

This page is intended to give decision-makers an immediate understanding of the current customer base.

🔎 2. Customer Churn Analysis

This section focuses on identifying patterns behind customer churn.

Users can analyze churn according to factors such as:

Contract type
Payment method
Gender
Customer tenure
Services subscribed to
Customer segments

Interactive filters allow users to investigate specific groups and compare their churn behavior.

📈 3. Revenue Impact

This page examines the financial implications associated with customer churn.

The analysis can be used to explore:

Revenue associated with churned customers.
Revenue differences between customer segments.
Historical revenue trends.
Potential revenue exposure from continued churn.
Possible improvements resulting from stronger customer retention.
💰 4. Customer Value Analysis

This section evaluates customers based on their contribution to the business.

Customers can be grouped into different value categories, allowing the business to identify:

High-value customers.
Medium-value customers.
Lower-value customers.
High-value customers with elevated churn risk.

This helps prioritize retention efforts where they may have the greatest financial impact.

🧮 5. Retention Scenario Analysis

A scenario-based analysis can be used to understand how changes in customer retention could influence revenue.

Possible scenarios include:

Improving customer retention.
Encouraging customers to move to longer contracts.
Introducing customer loyalty initiatives.
Targeting high-risk customer segments.

The purpose is to connect customer churn metrics with potential business outcomes.

# 🔍 Key Findings

The analysis highlights several important patterns within the customer base:

Customers on month-to-month contracts show substantially higher churn compared with customers on longer-term contracts.
Customers with shorter tenure form an important portion of the churned customer population.
Electronic check customers demonstrate relatively high churn compared with several other payment groups.
High-value customers require particular attention because losing them can have a greater impact on revenue.
Improving retention among vulnerable customer segments can potentially contribute to stronger recurring revenue.

Note: Specific percentages and financial estimates should be updated according to the results generated from your own dataset and analysis.

# 📋 Key Metrics
KPI	Purpose
Customer Churn Rate	Measures the percentage of customers who have left
Total Customers	Indicates the size of the customer base
Monthly Revenue	Measures recurring monthly customer revenue
Average Tenure	Shows the typical length of the customer relationship
Churned Customers	Tracks the number of customers lost
Customer Value	Helps identify financially important customers
Churn Probability	Indicates customers or segments with higher risk
📁 Project Structure
Telecom-Customer-Churn-Dashboard/
│
├── data/
│   ├── raw/
│   │   └── telecom_customer_churn.csv
│   │
│   └── processed/
│       └── cleaned_customer_data.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── exploratory_analysis.ipynb
│   └── churn_analysis.ipynb
│
├── sql/
│   └── churn_analysis.sql
│
├── scripts/
│   ├── data_preparation.py
│   └── churn_analysis.py
│
├── powerbi/
│   └── Telecom_Customer_Churn_Dashboard.pbix
│
├── reports/
│   └── project_report.pdf
│
├── README.md
└── requirements.txt


⭐ Project Highlights
📊 Interactive Power BI customer churn dashboard
🧹 Structured data cleaning and preparation workflow
🔎 SQL-driven customer and revenue analysis
🐍 Python-based exploratory and predictive analysis
👥 Customer segmentation based on churn and value
💰 Revenue-focused churn analysis
🎯 Retention insights designed for business decision-making
💡 Business Value

The dashboard is designed to move beyond simply reporting how many customers have churned.

By combining customer characteristics, tenure, contracts, payment methods, revenue, and churn behavior, the analysis helps answer questions such as:

Who is leaving?

Which customer groups are most vulnerable?

What characteristics are associated with churn?

Which customers should receive retention attention?

What could happen to revenue if retention improves?

These insights can support more targeted customer retention and engagement strategies.

📚 References
Telco Customer Churn dataset
Microsoft Power BI documentation
Python Pandas documentation
Scikit-learn documentation
SQL documentation
👤 Author

Nupur Gupta

Data Analyst | Business Intelligence Enthusiast

📧 Email: nupur.gupta1710@gmail.com

🔗 LinkedIn: https://github.com/nupur1704

📄 License

This project is available under the MIT License. See the LICENSE file for additional information.
