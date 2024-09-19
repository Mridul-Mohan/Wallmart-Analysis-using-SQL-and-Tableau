# Wallmart-Analysis-using-SQL-and-Tableau
This project aims to analyze Walmart sales data to uncover insights into top-performing branches, product trends, and customer behavior. The goal is to identify factors affecting sales and optimize sales strategies for improved performance. The dataset for this analysis was sourced from the Kaggle Walmart Sales Forecasting Competition.

# Project Objectives
* Branch Performance: Analyze sales across Walmart branches to determine top performers and areas for improvement.
* Product Analysis: Identify high-performing product lines and those needing optimization, while exploring factors influencing product success.
* Customer Behavior: Segment customers based on their purchase habits, demographics, and profitability to enhance targeting strategies.
* Sales Trends: Study sales trends across different timeframes (day, week, month) and determine the impact of various sales strategies.
# Dataset Overview
* Source: Kaggle Walmart Sales Forecasting Competition
* Content: Sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw
* Size: 17 columns, 1000 rows
* Key Data Columns:
* invoice_id: Unique ID for each sales transaction
* branch: The branch where the transaction occurred
* customer_type: Type of customer (e.g., Member, Normal)
* product_line: The category of product purchased
* unit_price: Price of a single unit of product
* quantity: Quantity of products sold
* total: Total cost of the purchase
* gross_income: Income from the sale after deducting COGS
* rating: Customer satisfaction rating for the purchase
# Analysis Focus
* Product Analysis:
** Assess product line performance to identify top sellers and areas for improvement.
** Analyze sales patterns across different product categories to inform sales strategy adjustments.

*Sales Analysis:
** Evaluate sales trends over time, including daily, weekly, and monthly breakdowns.
** Assess the effectiveness of sales strategies and identify peak sales periods.

*Customer Analysis:
** Segment customers by type, gender, and purchase behavior.
** Identify high-value customers and explore gender-based preferences across product lines.

* Revenue & Profit Calculations:
** Compute COGS, VAT, gross profit, and gross margin to analyze branch and product profitability.
** Example Calculation:
*** Unit Price: 45.79
*** Quantity: 7
*** COGS = 45.79 * 7 = 320.53
*** VAT = 5% * COGS = 16.0265
*** Total Sales = VAT + COGS = 336.5565
*** Gross Margin = Gross Income / Total Revenue = 4.76%
  
#Key Insights
* Branch Performance: Naypyitaw recorded the highest revenue among the branches.
* Product Insights: Fashion accessories were the top-selling product line, especially among female customers, while health and beauty products were most popular among males.
* Customer Insights: Member customers contributed significantly more revenue compared to regular customers.
* Sales Trends: Sales peaked in the afternoon, with Monday receiving the highest average customer ratings.
  
#Conclusion
This analysis provided valuable insights into Walmart's sales performance, customer behavior, and product trends. By leveraging data analytics tools such as SQL, Power BI, and Tableau, the project highlights opportunities for optimizing sales strategies and improving overall business performance.
