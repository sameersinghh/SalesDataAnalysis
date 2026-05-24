# Sales Data Analysis
Sales Data Analytics dashboard project built using Power BI, SQL to analyse revenue trends, customer behaviour, KPI performance, and regional sales insights through interactive visualisations.

# Problem Statement / Requirements

1) Top/Bottom 5 products by Sales/Profit/Quantity Sold.
2) How do sales trends vary over time (daily, monthly, quarterly, annually)?
3) Show the relationship between sales & profit.
4) Compare sales/profit/quantity sold between any two periods selected by the user.
5) Average discount offered in each discount category.
6) Total number of orders.
7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product/Date/Customer ID/Promotion Categories)
8) Show sales by different cities.

# Steps Followed

- Step 1: Load data into Power BI Desktop, the dataset is an Excel file.

- Step 2: Open Power Query editor & in view tab under the Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3: Since by default, the profile will be opened only for 1000 rows, you need to select "column profiling based on entire dataset".

- Step 4: There were many columns with null values, such as Price per unit, Total Sales, Discount Percentage, Discount Value, Net Sales etc.

- Step 5: Merged dimension tables (Product, Promotion, Customer) with the fact table via Left outer join to access data from merged columns in place of null values.

- Step 6: Created custom and conditional columns (Price per unit, Total Sales, Discount Percentage, Discount Value, Net Sales etc.) with accurate values. 

- Step 7: Changed the datatype from number to text in the Customer ID column in the Customer Dimensions table.

- Step 8: Defined relationships between dimensions and the fact table.

- Step 9: Created various types of visualisations (map, bar chart, scatter plot, line chart, column chart) using different filters (both measures and edit interactions).

