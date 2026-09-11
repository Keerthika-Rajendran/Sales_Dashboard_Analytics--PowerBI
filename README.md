Sales Dashboard Analytics

📌 Project Overview

Sales Dashboard Analytics is a Power BI project focused on analyzing sales performance and generating useful business insights from sales data.

The project transforms raw sales data into an interactive dashboard that helps users monitor sales, profit, orders, targets, regional performance, salesperson performance, and product performance.

🎯 Project Objective

The main objective of this project is to:

- Analyze overall sales and profit performance
- Track sales against targets
- Identify high and low-performing regions and salespersons
- Analyze product and category performance
- Understand sales trends over time
- Support data-driven business decisions through interactive dashboards

📂 Data Source

The data was provided in an Excel workbook containing multiple sheets with the required sales data.

The workbook included data related to:

- Sales
- Customers
- Products
- Regions
- Salespersons
- Targets

A dedicated Date table was also created for time-based analysis.

🔄 Project Workflow

1. Data Source

I sourced the data from an Excel workbook and imported it into Power BI. The workbook contained multiple sheets with the required sales data.

2. Data Transformation

I used Power Query to clean and prepare the data for analysis. This included checking data types, missing values, errors, and performing the required transformations.

3. Data Modeling

I identified the Sales table as the fact table and the Customers, Products, Regions, Salespersons, and Date tables as dimension tables.

I created relationships between the tables using common fields and structured the model using a proper star schema.

I also created a Date table using DAX for time-based analysis and reporting.

4. DAX Measures

I created DAX measures to calculate important business KPIs, including:

- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin %
- Sales Growth %
- Sales Target
- Target Achievement %

5. Dashboard Development

I created multiple report pages to analyze different aspects of the business.

The dashboard includes:

- KPI Cards
- Bar Charts
- Line Charts
- Donut Charts
- Treemaps
- Tables
- Gauges
- Interactive Slicers
- Filters

6. Business Insights

The dashboard helps identify:

- Overall sales and profit performance
- Sales trends over time
- Target achievement
- High and low-performing regions
- Salesperson performance
- Product and category performance
- Areas that may require further attention

📊 Dashboard Pages

Executive Dashboard

Provides an overview of overall business performance using key KPIs, sales trends, regional performance, and target analysis.

Regional & Salesperson Performance

Analyzes sales and profit performance across regions and salespersons and compares sales performance with targets.

Product & Customer Analysis

Provides insights into product, category, and customer performance.

Business Insights & Performance

Highlights important business metrics, growth trends, profit margins, target achievement, and performance comparisons.

🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

💡 Business Value

This dashboard helps users understand business performance quickly in one place. It can support management in monitoring KPIs, identifying performance gaps, comparing actual sales with targets, and making more informed data-driven decisions.

📁 Project File

The Power BI project file (".pbix") is included in this repository.

