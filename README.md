# 1. Data overview
The data set is about Supermarket sales of 2 branch A and B with A from Chicago and New York while B from Los Angeles. The data collected from the individual assignment of course MIS311. 
There are 253 rows and 8 columns which are: 
•	Sale_id (object): Unique identifier 
•	Branch (object): brand of the supermarket 
•	City (object): city of the supermarket 
•	Customer_type (object): Type of customers 
•	Product_name (object): Name of product 
•	Product_category (object): Category of product 
•	Quantity (int): amount sold 
•	Total_price (float64): amount of sales in USD 
# 2. Data cleaning
There are 3 duplicated values found in unique identifier : Sales_id so those row has been removed from the data set so the data only have 250 rows remaining.
In 250 rows remaings, there are 12 missing values with 3 values from Quantity columns, 3 values from Customer type and 6 values from Product category.
To deal with missing data, I replace them with N/A  because if I delete the missing value the sales data from Total_price columns can be under estimated or If i replace with specific values from Customer type , Product category and quantity the sales can be overestimated in those category.
