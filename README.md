# Superstore_Dashboard-Streamlit-

### This project shows my kaggleX Mentorship Project (part 1)
The part 1 shows the data exploration and visualization od superstores dataset. The data exploration and visualixzation include the following:
* **Product Analysis**
    * Segment, Category and Sub-category of Products and sales
    * Total Sales and Profit by Year, Month and Quarter
    * Total Quantity Sold by Year, Month and Quarter
* **Customers Analysis**
    * Total Number of Customers
    * Total Number of Orders
    * How many customers are buying from the superstores each year, month and quater
    * What region, states are these customers coming from.
    * Total Sales, Profits, Quantity and Discount.
    * Charts to showing yearly total sales and profit by state
    * Also showing charts showing total sales by Region and Category
 
  **About the Dataset**
Superstore Sales generally refer to the sales data and performance of a superstore or a large retail store that offers a wide range of products and merchandise. These superstores are typically known for their extensive inventory, competitive pricing, and one-stop shopping experience.
Analyzing superstore sales data is essential for store owners, managers, and analysts to understand the store's performance, identify trends, and make informed business decisions.

The dataset contains 21 columns and 9994 rows. Here are the columns:
* **Row ID** -  Row ID
* **Order ID** - Order ID
* **Order Date** - Order Date
* **Ship Date** - Mode of Shipping
* **Ship Mode** - Mode of Shipping
* **Customer ID** - Customer ID
* **Customer Name** - Name of the Customers
* **Segment** - Segment of Customers
* **Country** - Country for order and shipping
* **City** - City for order and shipping
* **State** - State for order and shipping
* **Postal Code** - Postal code
* **Region** - Regions for order and shipping
* **Product ID** - Products ID
* **Category** - Products category
* **Sub-Category** - Products sub-category
* **Product Name** - Product Name
* **Sales** - Sales for products
* **Quantity** - Quantity sold
* **Discount** - products discounts
* **Profit** - profits

### How to use the Year, Month and Quater Filter
* To filter by Year and Month - first select month then Year.
* To filter by Quater and Year - dirst select quater then Year.

Link to streamlit dashboard can be found [Here](https://m35jf2fj6buemnvpxvmwfk.streamlit.app/)

### More Features to add
I will like to add the difference in **total sales**, **profit**, **discount**, **orders**, **customers**, and **quanity** using the delta parameter in `st.metrics()`.


**Part 2** (Coming soon) will be on Time Series Forecast of Superstores Sales.
      
