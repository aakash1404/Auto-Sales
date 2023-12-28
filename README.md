Analysing automobile sales data:
-------------------------------

[Fully Rendered Notebook](https://nbviewer.org/github/aakash1404/Auto-Sales/blob/main/Auto%20Sales%20.ipynb)

Description of the dataset:

|Column Name|Description|
|-----------|-----------|
|ORDERNUMBER |This column represents the unique identification number assigned to each order.|
|QUANTITYORDERED |It indicates the number of items ordered in each order.|
|PRICEEACH |This column specifies the price of each item in the order.|
|ORDERLINENUMBER |It represents the line number of each item within an order.|
|SALES |This column denotes the total sales amount for each order, which is calculated by multiplying the quantity ordered by the price of each item.|              
|ORDERDATE |It denotes the date on which the order was placed.|
|DAYS_SINCE_LASTORDER |This column represents the number of days that have passed since the last order for each customer. It can be used to analyze customer purchasing patterns.|                                                    
|STATUS	|It indicates the status of the order, such as "Shipped", "In Process", "Cancelled", "Disputed", "OnHold", or "Resolved".|
|PRODUCTLINE |This column specifies the product line categories to which each item belongs.|
|MSRP |It stands for Manufacturer's Suggested Retail Price and represents the suggested selling price for each item.|
|PRODUCTCODE |This column represents the unique code assigned to each product.|
|CUSTOMERNAME |It denotes the name of the customer who placed the order.|
|PHONE	|This column contains the contact phone number for the customer.|
|ADDRESSLINE1 |It represents the first line of the customer's address.|
|CITY |This column specifies the city where the customer is located.|
|POSTALCODE |It denotes the postal code or ZIP code associated with the customer's address.|
|COUNTRY |This column indicates the country where the customer is located.|
|CONTACTLASTNAME |It represents the last name of the contact person associated with the customer.|
|CONTACTFIRSTNAME |This column denotes the first name of the contact person associated with the customer.|
|DEALSIZE	|It indicates the size of the deal or order, which are the categories "Small", "Medium", or "Large".|




Objectives of Analysis:
----------
-- Is there a growing trend in the overall sales for the company or not?

-- Is there any seasonality in the overall sales?

-- What is the overall sales across all years in different countries?

-- Considering the top 3 countries with respect to sales,is there any seasonality in terms of overall sales in those countries?

-- Considering the top 3 countries with respect to sales, which cities within those countries have been performing exceptionally well?

-- Is there a trend in the selling of products across the top cities across the top three countries?

-- Is there a seasonality in the selling of products across the top cities across the top three countries?

-- What are the worst and best performing products for the top cities across the top three countries?

-- On an average,how many days are receiving no orders in-between two consecutive orders for each customer?

-- Who are the most loyal customers in terms of sales and analysing their purchasing pattern?

-- Is there any correlation between the quantity ordered and the price for each orderline?

-- Which productline has been the best selling(in terms of total quantity sold) across all the years?

-- What is the overall percentage of orders which haven't been shipped across different productlines?

-- What is the percentage of different deal sizes(in terms of order count) for different productlines received for the top 3 countries with highest sales for each year?

-- What are best and worst performing products across each productline?
