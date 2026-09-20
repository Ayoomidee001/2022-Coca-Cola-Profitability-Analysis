2022 Coca-Cola Sales & Profitability Analysis 
Project Overview
This project analyzes Coca-Cola sales data from January to December 2022 to evaluate sales performance, product performance, profitability, and geographic performance using Microsoft Power BI.
The goal was to transform 2022 sales data into an interactive business intelligence dashboard that helps decision-makers understand revenue and profit performance, identify strong and underperforming beverage brands, and investigate regional sales opportunities.

Dataset
The dataset contains 3,744 sales records covering January through December 2022 and 14 columns covering:
●	Retailer
●	Retailer ID
●	Invoice Date
●	Region
●	State
●	City
●	Beverage Brand
●	Days to Deliver
●	Delivery Company
●	Price per Unit
●	Units Sold
●	Total Sales
●	Operating Profit
●	Operating Margin
The dataset was provided as an Excel workbook and prepared for analysis in Power BI.
Analysis period: January 2022 – December 2022
Note: The dataset does not contain an Invoice ID or transaction ID. Therefore, transaction-level metrics were not calculated where a unique transaction identifier would be required.

Dashboard
The Power BI report contains two main pages.
1. Executive Sales Overview
The executive dashboard provides an overview of 2022 sales performance, including:
●	Total Sales
●	Total Units Sold
●	Total Operating Profit
●	Unique Retailers
●	Operating Margin
●	Sales by Region
●	Units Sold by Beverage Brand
●	Monthly Sales Trend
●	Operating Profit by Region
●	Sales Records by Delivery Company
Interactive slicers allow users to filter the 2022 analysis by:
●	Region
●	Beverage Brand
●	Retailer
●	Invoice Date
2. Product & Geographic Performance
The second dashboard focuses on 2022 product and geographic performance:
Product Performance
●	Units Sold by Beverage Brand
●	Total Sales by Beverage Brand
●	Operating Profit by Beverage Brand
●	Operating Margin by Beverage Brand
Geographic Performance
●	Sales by State
●	Profit by State
●	Sales by Region

Tools & Technologies
Microsoft Excel — Source data and initial data inspection
Power Query — Data cleaning and preparation
DAX — Measures and profitability calculations
Microsoft Power BI — Data modeling, visualization, and dashboard development

Data Preparation
The dataset was reviewed and prepared before building the Power BI dashboard.
Key preparation steps included:
Checked column names and data types
Reviewed the dataset for missing values
Checked for duplicate records
Verified date fields and numerical columns
Reviewed sales, units sold, and operating profit values for consistency
Created DAX measures for key business metrics
Calculated overall and product-level operating margins using total profit divided by total sales
Because the dataset does not contain a unique Invoice ID or transaction ID, transaction-level metrics requiring a unique transaction identifier were not calculated.

Key DAX Measures
Total Sales =
SUM('Coca Cola Sales'[Total Sales])
Total Units Sold =
SUM('Coca Cola Sales'[Units Sold])
Total Operating Profit =
SUM('Coca Cola Sales'[Operating Profit])
Unique Retailers =
DISTINCTCOUNT('Coca Cola Sales'[Retailer ID])
Total Records =
COUNTROWS('Coca Cola Sales')
Operating Margin =
DIVIDE([Total Operating Profit], [Total Sales])
The Operating Margin measure was used instead of summing the raw Operating Margin column so that profitability was calculated correctly at the aggregated level.

Key Findings
Overall Performance
Total Sales: $8.22M
Total Units Sold: 16M
Total Operating Profit: $3.04M
Overall Operating Margin: 37.02%
Unique Retailers: 4
Regional Performance
The West region generated the highest sales at approximately $2.37M.
The West also generated the highest operating profit at approximately $790.5K.
The Midwest region recorded the highest operating margin at approximately 38.04%.
The West generated greater sales and profit, while the Midwest demonstrated stronger margin efficiency.
Product Performance
Coca-Cola was the strongest-performing beverage brand across the major sales and profitability measures.
Sales: $1.92M
Units Sold: 3.99M
Operating Profit: $767.5K
Operating Margin: 39.91%
Fanta recorded the lowest sales and operating profit among the beverage brands analyzed.
Sales: $969.9K
Operating Profit: $355.7K
Units Sold: 2.10M
Operating Margin: 36.67%
The analysis indicates that Fanta's weaker performance was primarily related to sales volume rather than an unusually low operating margin.
Profitability
Coca-Cola recorded the highest operating margin among the beverage brands at 39.91%, while Diet Coke recorded the lowest at 34.06%.
This highlights the importance of evaluating profitability alongside sales volume rather than relying on revenue alone.

Business Recommendations
Based on the analysis, the following areas could be investigated further:
Investigate Fanta's sales volume
Review Fanta's distribution and availability across retailers and regions.
Identify locations where Fanta has comparatively low unit sales.
Explore the Midwest opportunity
The Midwest recorded a strong overall operating margin but lower sales scale than the West.
Further analysis could determine opportunities to increase sales while maintaining margin performance.
Analyze retailer-level performance
Compare beverage performance across retailers to identify differences in product demand and sales volume.
Learn from high-performing products
Coca-Cola's combination of sales volume, revenue, profit, and margin provides a useful benchmark for comparing other beverage brands.
Monitor multiple KPIs together
Sales, units sold, operating profit, and operating margin should be evaluated together to distinguish volume problems from profitability problems.
These recommendations are based on patterns observed within the 2022 dataset and would require additional operational data to determine the underlying causes of those patterns.


Skills Demonstrated
This project demonstrates practical skills in:
Data cleaning and preparation
Data analysis
Power Query
DAX
Power BI dashboard development
KPI development
Profitability analysis
Sales performance analysis
Product performance analysis
Geographic analysis
Business insight generation
Data visualization
Business-focused storytelling

Project Outcome
The project transformed raw 2022 Coca-Cola sales data into an interactive Power BI business intelligence dashboard.
The final dashboard provides users with the ability to:
Monitor overall sales and profitability
Compare beverage brands
Analyze regional performance
Examine state-level sales and profit
Track monthly sales trends
Compare retailer performance
Evaluate operating margins
Filter the analysis by beverage brand, region, retailer, and date
The project demonstrates how Power BI and DAX can be used to turn raw business data into actionable insights for decision-making.

Dashboard Preview
Executive Sales Overview

Product & Geographic Performance

Conclusion
The 2022 Coca-Cola Sales & Profitability Analysis demonstrates the use of Power BI, Power Query, and DAX to analyze sales performance and profitability across products, regions, retailers, and time.
The analysis shows that Coca-Cola was the strongest-performing beverage brand in the dataset, while Fanta recorded the lowest sales and operating profit. The West region led in sales and operating profit, while the Midwest recorded the highest operating margin.
Overall, the project focuses on moving beyond simple reporting to identify performance patterns and translate those patterns into practical business questions and recommendations.

