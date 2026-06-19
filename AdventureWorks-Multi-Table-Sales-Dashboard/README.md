# AdventureWorks Executive Sales Dashboard Using Power BI (2018–2021)

## Project Overview
This Power BI dashboard analyzes AdventureWorks sales data using a multi-table data model. The project demonstrates data modeling, relationship management, DAX measures, and interactive dashboard design to provide insights into sales performance, product performance, reseller contributions, and geographic distribution of sales.

## Business Questions
1. What is the total sales revenue generated?
2. How did sales performance change over time?
3. Which countries generated the highest sales revenue?
4. Which product categories contributed the most sales?
5. Which products generated the highest sales revenue?
6. Which resellers generated the most sales?
7. How do product categories and reseller business types contribute to overall sales performance?

## Dataset
- <a href="https://github.com/microsoft/powerbi-desktop-samples/raw/main/AdventureWorks%20Sales%20Sample/AdventureWorks%20Sales.xlsx">AdventureWorks Sales</a>

## Data Model
The dashboard was built using multiple related tables:
- Sales
- Product
- Customer
- Reseller
- Date
- Sales Territory
- Sales Order
Relationships were created between dimension tables and the Sales fact table to support cross-table analysis and filtering.

## Data Preparation
The following steps were performed before creating the dashboard:
- Imported and reviewed the dataset in Power BI.
- Verified data types for financial and date fields.
- Created DAX measures for Total Revenue, Total Profit, Total Cost, and Profit Margin.
- Applied data modeling and formatting techniques to improve report usability.
- Designed interactive filters for Country, Segment, Product, and Date.

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modeling

## Dashsboard Features
KPI Cards for Total Sales, Total Orders, Total Customers, and Total Resellers.
Sales Trend Analysis across fiscal years.
Total Sales by Country visualization.
Top 5 Products by Sales analysis.
Top 5 Resellers by Sales analysis.
Sales Performance by Category and Business Type matrix.
Interactive Country and Date slicers.
Multi-table data model with relationship-based filtering.
DAX measures for business performance analysis.
Matrix Analysis

## Key Findings
AdventureWorks generated $109.81 million in total sales.
The business processed approximately 31,000 orders.
The customer base consisted of approximately 18,000 customers.
The company worked with 701 resellers.
Sales increased steadily between FY2018 and FY2020, indicating strong business growth.
The United States generated the highest sales revenue among all countries.
World of Bikes was the top-performing reseller by sales revenue.
The Mountain-200 product line dominated the top-selling products ranking.
The Bikes category generated the highest sales revenue among product categories.

## Matrix Analysis

The matrix visual reveals that the Bikes category generated the highest sales revenue, contributing over $66 million in sales. Within this category, Value Added Resellers and Warehouses accounted for the largest share of revenue, highlighting the importance of reseller partnerships in driving bicycle sales.

The Components category ranked second, generating approximately $11.8 million in revenue, while Accessories and Clothing contributed comparatively smaller amounts. Across most product categories, Warehouse and Value Added Reseller business types consistently generated the highest sales, indicating that these channels played a critical role in product distribution and revenue generation.

This analysis demonstrates how product categories and reseller business types jointly influence overall sales performance and provides insight into the organization's most effective sales channels.

## Data Preparation

The AdventureWorks dataset was imported into Power BI and modeled using a star schema approach. Relationships were established between the Sales fact table and the Product, Customer, Reseller, Sales Territory, Date, and Sales Order dimension tables to enable cross-table analysis.

Data preparation activities included:

Validating relationships between fact and dimension tables.
Creating DAX measures for Total Sales, Total Orders, Total Customers, and Total Resellers.
Building a dedicated measure table to organize calculations.
Applying filters and Top N analysis for product and reseller performance reporting.
Formatting visuals and KPI cards to improve dashboard usability and readability.

## Data Quality Note:

Some sales records were associated with an unknown reseller (ResellerKey = -1). These records were excluded from reseller-level analysis to ensure accurate reporting of reseller performance while retaining them in overall sales calculations.

Based on your matrix, I would add the following insight:

## Conclusion

## Author

Kibet Hillary

BSc Applied Statistics, with IT (Second Class Honours, Upper Division)

Aspiring Data Analyst/Scientist

Email: kibeth2011@gmail.com

- <a href="https://github.com/kibeth2011">GitHub</a>

- <a href="https://www.linkedin.com/in/kibet-hillary-4654507b/">LinkedIn</a>



