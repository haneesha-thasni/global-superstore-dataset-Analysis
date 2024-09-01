# global-superstore-data-analysis

![image](https://github.com/user-attachments/assets/ca838545-dc19-4dfc-ae38-fb704e228fa4)

## Global Superstore Data Description

The Global Superstore dataset is a popular sample dataset often used for data analysis and visualization exercises. It generally includes the following key fields:

* Order ID: Unique identifier for each order.

* Order Date: Date when the order was placed.

* Ship Date: Date when the order was shipped.

* Ship Mode: The shipping method used (e.g., Standard Class, Second Class, etc.).

* Customer ID: Unique identifier for each customer.

* Customer Name: Name of the customer.

* Segment: Customer segment (e.g., Consumer, Corporate, Home Office).

* Country: Country where the customer is located.

* City: City where the customer is located.

* State: State where the customer is located.

* Postal Code: Postal code of the customer's address.

* Category: Product category (e.g., Furniture, Office Supplies, Technology).

* Sub-Category: More specific category within the broader category.

* Product Name: Name of the product.

* Sales: Sales amount for the order.

* Quantity: Quantity of products ordered.

* Discount: Discount applied to the order.

* Profit: Profit made on the order.

This dataset is used to analyze sales performance, customer behavior, and other

## Information of the Dataset

* 2 Dimension dataset
* Columns=
* Rows=
* Data types
    - integer = 2
    - float = 5
    - object = 15
    - datetime = 2
* Occur Null values
    - postal code = 41296
* No Duplicate values

##   Questions:

1) Create a feature that calculate the profit margin as a percentage of the total sales?
2) Create a feature that calculates the price of the product after applying the discount.
3) create a feature that represents the shipping cost per unit sold
4) create a new column for the order delivery time difference b/w ship date and order date
5) Create a feature that calculates the age of an order in days from the order date to today's date
6)  average shipping delay for orders placed in december
7)  replace 'standard class' value in 'ship mode' column with 'std'
8)  replace 'low' value in 'order priority' column with 'standard'
9)  filter the rows where profit lessthan zero
10)  filter rows where profit is negative and the quantity is greater than 10
11)  calculate the average sales of these filtered rows
12)  modify the 'order priority' column to label all orders with a 'profit below zero as "urgent"
13)  how many rows have 'Urgent' as the order priority
14)  filter data where category is furniture and profit is greater than 1000
15)  filter rows where product name contain word'phone'
16)   sort the dataset first by 'category' in ascending order and then by 'profit' in descending order
17)   how can you sort the dataset by 'quantity' in descending order and then select the top 10 records
18)   sort the dataset by "order date" in ascending order
19)   Filter the dataset to include  only rows where the order date is between '2013-01-01' and '2014-12-31
