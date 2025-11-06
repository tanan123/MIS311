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

# 3. Descriptive Statistics
Insight 1 :

<img width="690" height="417" alt="image" src="https://github.com/user-attachments/assets/6d2c23b1-1776-46a2-b455-942659ff4054" />

The chart shows that **Shampoo** and **Notebook** have the highest total sales, indicating strong customer demand in both personal care and stationery categories. In contrast, **Apples** have the lowest sales, suggesting lower consumer interest or possible pricing or supply issues. The supermarket could focus on promoting fresh produce while maintaining stock and marketing for top-performing items to sustain overall revenue growth.

Insight 2 : 

<img width="592" height="359" alt="image" src="https://github.com/user-attachments/assets/17e89819-0ea5-4178-ab28-0ae7a9b5dc1f" />

The data shows that **Branch A** (Chicago and New York) significantly outperforms **Branch B** (Los Angeles) in total sales, indicating stronger overall performance and customer engagement in Branch A locations. This suggests that Branch A’s sales strategies or market conditions are more effective. The supermarket could analyze what drives Branch A’s success and why Branch B had lower sales then implement similar practices from A to Branch B to improve overall sales performance.




