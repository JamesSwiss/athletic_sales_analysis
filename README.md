# athletic_sales_analysis

# Athletic Sales Analysis

## Introduction
In this project, we'll analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. We'll also determine which retailers had the greatest total sales for athletic wear and which retailers sold the most women's athletic footwear. Finally, we'll identify the day and week with the highest sales for women's athletic footwear.

## Software Used
- Python
- Pandas

## Methodology
### Combine and Clean the Data
- Import the CSV files and read them into DataFrames.
- Check for null values and data types.
- Combine the DataFrames by rows using an inner join.
- Convert the "invoice_date" column to a datetime data type.

### Determine which Region Sold the Most Products
- Create a multi-index DataFrame using groupby or pivot_table with "region", "state", and "city" columns.
- Rename the aggregated column.
- Sort the results to show the top five regions with the most products sold.

### Determine which Region had the Most Sales
- Follow similar steps as above to determine the region with the highest sales.

### Determine which Retailer had the Most Sales
- Create a multi-index DataFrame with "retailer", "region", "state", and "city" columns.
- Rename the aggregated column.
- Sort the results to show the top five retailers with the most sales.

### Determine which Retailer Sold the Most Women's Athletic Footwear
- Filter the DataFrame to include only women's athletic footwear sales data.
- Create a multi-index DataFrame and rename the aggregated column.
- Sort the results to show the top five retailers with the most women's athletic footwear sales.

### Determine the Day with the Most Women's Athletic Footwear Sales
- Create a pivot table with "invoice_date" as the index and "total_sales" as the values.
- Rename the aggregated column and apply the resample function.
- Sort the results to show the days with the most women's athletic footwear sales.

### Determine the Week with the Most Women's Athletic Footwear Sales
- Apply resample to the pivot table from the previous step to get weekly sales.
- Sort the results to show the weeks with the most women's athletic footwear sales.

## Task List
1. Combine and clean the data (15 points)
2. Determine which region sold the most products (15 points)
3. Determine which region had the most sales (15 points)
4. Determine which retailer had the most sales (15 points)
5. Determine which retailer sold the most women's athletic footwear (20 points)
6. Determine the day with the most women's athletic footwear sales (15 points)
7. Determine the week with the most women's athletic footwear sales (5 points)
