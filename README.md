Customer Shopping Behavior Analysis
Overview
This project provides a comprehensive end-to-end data analytics solution to understand and optimize customer shopping behavior. By integrating Python for data processing, SQL for deep-dive querying, and Power BI for visualization, this project uncovers actionable insights into revenue drivers, customer segmentation, and subscription patterns.

Dataset
The analysis is based on the Customer Shopping Behavior Dataset, which includes 3,900 records. Key features include:

Demographics: Age, Gender, and Location.

Transaction Details: Purchase Amount (USD), Item Purchased, Category, and Size.

Behavioral Metrics: Review Ratings, Subscription Status, and Previous Purchases.

Tools
Python (Pandas, SQLAlchemy): Data cleaning, feature engineering, and database ingestion.


SQL (MySQL): Complex data manipulation and business logic queries.


Power BI: Interactive dashboarding and KPI tracking.

Gamma: AI-powered presentation generation for executive reporting.

Steps
1. Data Cleaning & EDA (Python)
Handling Nulls: Replaced missing review_rating values using the median of their respective categories.

Standardization: Normalized column names to lowercase and replaced spaces with underscores for SQL compatibility.

Feature Engineering:

Created age_group (Young Adult, Adult, Middle-aged, Senior) using quartile binning.

Mapped purchase frequencies to numerical days for deeper analysis.

Database Ingestion: Automated the export of cleaned data into a MySQL database.

2. Deep Dive Analysis (SQL)
Executed several business queries to identify key trends:


Revenue Analysis: Compared revenue by gender and age groups.


Subscription Impact: Analyzed if subscribers spend more on average than non-subscribers.


Customer Segmentation: Categorized users as New, Returning, or Loyal based on previous purchase history.

3. Visualization & Reporting

Power BI Dashboard: Developed a multi-page interactive report to visualize KPIs such as total revenue, average ratings, and discount rates.

Gamma Presentation: Created a professional PPT summarizing key findings and recommendations for stakeholders.

Dashboard
The Power BI dashboard features:


Executive Summary: High-level KPIs including total revenue and average spend.
+1


Product Performance: Top 5 items by rating and purchase volume.


Customer Insights: Spending habits across different shipping types and age segments.

Results

Subscription Loyalty: Analyzed the correlation between repeat buyers (5+ purchases) and subscription rates.


Category Leaders: Identified top-performing products within each category (Clothing, Footwear, etc.).


Revenue Drivers: Determined that specific age groups contribute disproportionately to total revenue.
