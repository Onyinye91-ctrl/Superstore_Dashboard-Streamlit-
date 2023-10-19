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

The Dataset used can be found on Kaggle with this link [Here](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset contains `21 columns` and `9994 rows`. Here are the columns:
* **Row ID** -  Unique ID for each row
* **Order ID** - Unique Order ID for each Customer.
* **Order Date** - Order Date of the product.
* **Ship Date** - Shipping Date of the Product.
* **Ship Mode** - Shipping Mode specified by the Customer.
* **Customer ID** - Unique ID to identify each Customer.
* **Customer Name** - Name of the Customer.
* **Segment** - The segment where the Product belongs
* **Country** - Country of residence of the Customer.
* **City** - City of residence of the Customer.
* **State** - State of residence of the Customer.
* **Postal Code** - Postal Code of every Customer.
* **Region** - Region where the Customer belong.
* **Product ID** - Unique ID of the Product.
* **Category** - Category of the product ordered.
* **Sub-Category** - Sub-Category of the product ordered.
* **Product Name** - Name of the Product
* **Sales** - Sales of the Product.
* **Quantity** - Quantity of the Product.
* **Discount** - Discount provided.
* **Profit** - Profit/Loss incurred.

### How to use the Year, Month and Quater Filter
* To filter by Year and Month - first select month then Year.
* To filter by Quater and Year - dirst select quater then Year.

Link to streamlit dashboard can be found [Here](https://m35jf2fj6buemnvpxvmwfk.streamlit.app/)

### More Features to add
I will like to add the difference in **total sales**, **profit**, **discount**, **orders**, **customers**, and **quanity** using the delta parameter in `st.metrics()`.


**Part 2** (Coming soon) will be on Time Series Forecast of Superstores Sales.
      
