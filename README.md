# SQL-Query-Analysis-of-Amazon-Sales-Data-2025-
Analyzed Amazon Sales data using SQL queries to extract key Performance metrics and customer insights.

# Description :
•	We analyzed the Provided sales data using Ten SQL queries.

•	These Queries filtered records based on Status, data and location.

•	We aggregation data to sum sales/Quantities and Count Orders by Category/Payment method.

•	Top-Performing Order, Products and high value Customer Were identified.

•	The goal was to extract initial business insights from the row sales information.


## Data set :

[amazon_sales_data 2025.csv](https://github.com/JMK-26/SQL-Query-Analysis-of-Amazon-Sales-Data-2025-/blob/main/amazon_sales_data%202025.csv)
  
# Queries :
                                       
1, Retrieve all Completed Orders ?

2, Calculate Total Sales Per Product Category ?

3, Find the Top 5 Most Expensive Order (Based on Total_Sales) ?

4, Count Order Per Payment Method ?

5, List Order Place in Mach 2025 ?

6, Calculate Total Quantity Sold For Each Product ?

7, Find Order Pending Order in New York Or Dallas ?

8, List Category With Average Order Value > 500 ?

9, List Unique Customer Location ?

10, Find Total Spending Per Customer For Completed Order (Top 4 Spender) ?


# Project Insight :

1, Retrieve all Completed Orders ?

Goal : Show all the Information for Order that have the Status ‘Completed’.

## SQL query :
                  SELECT * FROM amazon_sales
                  WHERE status = 'Completed';
                           
## Explanation :

This uses to SELECT * to get all columns and the WHERE clause to filter rows where the status column value is exactly ‘Completed’.
 
## Out put : SQL 

## Interpretation :

 Complete order :  List all details (all columns) For every sales order marked as ‘completed’.



