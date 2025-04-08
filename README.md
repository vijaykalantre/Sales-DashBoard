## Sales-Dashboard

## Problem Statement
This Sales Dashboard is designed to help the company analyze its overall sales performance and identify growth opportunities. By monitoring sales metrics such as total revenue, profit margin, top-performing products, and regional performance, the dashboard provides valuable insights for decision-making. It allows the company to track KPIs in real-time, understand customer purchasing behavior, and optimize strategies to boost sales and profitability.

## Steps Followed
Step 1: Load sales data into Power BI Desktop (e.g., from a CSV/Excel file or SQL database).

Step 2: Open Power Query Editor and enable Column Distribution, Column Profile, and Column Quality.

Step 3: Enable “Column profiling based on entire dataset” for accurate data quality analysis.

Step 4: Handle missing or null values – removed or imputed where necessary (e.g., missing discounts or profit values).

Step 5: Used "Transform" tab to format columns like dates, text, currency, etc.

Step 6: Selected a theme in Report View > View Tab to improve visual aesthetics.

Step 7: Added slicers for Region, Category, Customer Segment, and Year to enable user-driven insights.

Step 8: Added Card Visuals to represent KPIs like Total Sales, Total Profit, and Total Orders.

Step 9: Used Bar and Column Charts to show Sales by Category, Sub-Category, and Region.

Step 10: Added Pie Chart for Market Share by Region.

Step 11: Used Line Chart for tracking Monthly Sales Trends.

Step 12: Created DAX Measures for KPIs and performance metrics.

Step 13: Added company name, logo, and tagline using Text Box and Image from the Insert tab.

Step 14: Published the report to Power BI Service for sharing and collaboration.

📂 ## Dataset Information
Dataset Name: Orders_Sales_Dashboard.csv

Source: Internal sales records

Total Records: ~10,000

Time Period: 2014 – 2017


 Header & Filters
Title: SALES DASHBOARD

Year Filter: 2014 is selected (2015–2017 available)
➤ This allows users to filter data by year for trend analysis over time.

🔷 Key Metrics (Top Row Cards)
Metric	Value	Meaning
Revenue	2.30M	Total sales amount for 2014
Profit	286.40K	Net profit earned
Orders	9994	Number of orders placed
Customers	9994	Unique customers (1 order per customer)
Quantity	38K	Total items sold
Insight: High quantity and order count, but profit margin (~12.45%) is relatively low, suggesting optimization opportunities in pricing or cost control.

🔷 Sales Performance (Line Chart)
X-axis: Months (Jan–Dec)

Y-axis: Revenue

Insight:

Growth trend from August to November

Highest revenue in October and November — likely due to seasonal promotions or holiday sales.

Low sales in January and February

This trend helps plan marketing campaigns and inventory better.

🔷 Sub-Category Ranking Table
Sub-Category	Segment	Orders	Revenue
Accessories	Technology	6939	8.36M
Appliances	Office Supplies	22906	7.19M
Bookcases	Furniture	8028	7.42M
Insight:

Accessories generate the highest revenue in Technology

Appliances have most orders, but slightly lower revenue

Furniture shows moderate performance with Bookcases leading

🔷 Region Performance (Bar Chart)
Categories: Furniture, Office Supplies, Technology (color-coded)

Regions: West, East, Central, South

Region	Performance Summary
West	Highest total revenue, especially in Technology
East	Second-highest performance
Central	Moderate sales
South	Lowest performance
Insight: Focus more marketing and resources in South to boost sales. West is a strong-performing region, especially for technology products.

🔷 Performance Ratio (Bar Visual)
Blue Bar (88.91%): Revenue

Purple Bar (11.09%): Profit

Insight:

While sales are high, profit margin is relatively low

Indicates potential high costs, discounting, or low-margin products

✅ Overall Insights Summary
Area	Key Takeaways
Sales Trend	Strong Q4 performance, especially in Nov
Best-Selling Region	West (esp. in Technology)
Most Ordered Subcategory	Appliances
Highest Revenue Subcategory	Accessories
Customer Engagement	Strong (9994 customers)
Quantity vs Profit	High sales volume, but lower profitability
Optimization Area	Improve profit margins, especially in low-performing regions and subcategories






🚀 Tools Used
Microsoft Power BI (Desktop)

Power Query (ETL)

DAX (Data Analysis Expressions)

GitHub (Project Hosting)



🤝 Let’s Connect
If you're looking for a Power BI developer to create advanced dashboards, feel free to reach out!
