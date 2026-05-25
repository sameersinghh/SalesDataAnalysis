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

# Screenshots

- Sales Overview
  
  <img width="1418" height="793" alt="Image" src="https://github.com/user-attachments/assets/a93d2b85-80ee-408e-bba4-e14d14a545b2" />

- Top/Bottom 5 Analysis
  
  <img width="1416" height="793" alt="Image" src="https://github.com/user-attachments/assets/99535f9d-857c-43c6-ad82-83abae3e2676" />

- Custom Date Filters using measures
  
  <img width="1414" height="792" alt="Image" src="https://github.com/user-attachments/assets/b5eb0102-4995-41bf-81f0-7e3d7f4ad718" />

- Custom Date Filters using edit iteractions
  
  <img width="1418" height="793" alt="Image" src="https://github.com/user-attachments/assets/263c95a6-55a3-4c73-8ec1-f8287dd48d25" />

- Linking dimension table slicers
  
  <img width="1417" height="796" alt="Image" src="https://github.com/user-attachments/assets/a443d68e-037c-465a-80c3-160075115656" />
