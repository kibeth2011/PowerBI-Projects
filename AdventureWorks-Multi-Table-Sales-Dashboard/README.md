# AdventureWorks Executive Sales Analysis Using Power BI (2018–2021)

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

## Data Preparation
Data preparation activities included:
- Imported and reviewed the dataset in Power BI and modeled using a star schema approach.
- Validated relationships between fact and dimension tables.
- Created DAX measures for Total Sales, Total Orders, Total Customers, and Total Resellers.
- Built a dedicated measure table to organize calculations.
- Applied filters and Top N analysis for product and reseller performance reporting.
- Formatted visuals and KPI cards to improve dashboard usability and readability.

### Data Quality Note
Some sales records were associated with an unknown reseller (ResellerKey = -1). These records were excluded from reseller-level analysis to ensure accurate reporting of reseller performance while retaining them in overall sales calculations.

## Dashsboard Features
- KPI Cards for Total Sales, Total Orders, Total Customers, and Total Resellers.
- Sales Trend Analysis across fiscal years.
- Total Sales by Country visualization.
- Top 5 Products by Sales analysis.
- Top 5 Resellers by Sales analysis.
- Sales Performance by Category and Business Type matrix.
- Interactive Country and Date slicers.

## Key Findings
1. AdventureWorks generated a revenue of approximately $109.81 million
2. Sales increased steadily between FY2018 and FY2020, indicating strong business growth.
3. The United States generated the highest sales revenue among all countries.
4. The Bikes category generated the highest sales revenue among product categories.
5. The Mountain-200 Black, 38 product line dominated the top-selling products ranking.
6. World of Bikes was the top-performing reseller by sales revenue.
7. The business processed approximately 31,000 orders.
8. The customer base consisted of approximately 18,000 customers.
9. The company worked with 701 resellers.

## Matrix Analysis
The matrix visual reveals that the Bikes category generated the highest sales revenue, contributing over $66 million in sales. Within this category, Value Added Resellers and Warehouses accounted for the largest share of revenue, highlighting the importance of reseller partnerships in driving bicycle sales.

The Components category ranked second, generating approximately $11.8 million in revenue, while Accessories and Clothing contributed comparatively smaller amounts. Across most product categories, Warehouse and Value Added Reseller business types consistently generated the highest sales, indicating that these channels played a critical role in product distribution and revenue generation.

## Dashboard Preview
<img width="977" height="551" alt="Dashboard" src="https://github.com/user-attachments/assets/b9d52c2c-4a4c-461a-af88-825d7207b867" />

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modeling

## Conclusion
This project demonstrates the use of Power BI for multi-table data modeling, relationship management, DAX calculations, and interactive dashboard development. By integrating sales, product, reseller, customer, territory, and date data, the dashboard provides meaningful insights into business performance, product demand, reseller effectiveness, and geographic sales distribution. The project highlights practical business intelligence skills applicable to real-world reporting and decision-making environments.

## Author

Kibet Hillary

BSc Applied Statistics, with IT (Second Class Honours, Upper Division)

Aspiring Data Analyst/Scientist

Email: kibeth2011@gmail.com

- <a href="https://github.com/kibeth2011">GitHub</a>

- <a href="https://www.linkedin.com/in/kibet-hillary-4654507b/">LinkedIn</a>



