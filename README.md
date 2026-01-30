# Pizza Orders SQL Analysis 

## Overview 
This project contains a set of SQL queries designed to analyze pizza sales and orders from a hypothetical pizza store. The queries are structured in three levels of complexity: **Basic**, **Intermediate**, and **Advanced**. The goal is to extract insights such as total revenue, most popular pizza types, order trends, and category-wise contributions to revenue.

---

## Project Structure 
- `pizza_sales_analysis.sql` - Main SQL file containing all queries.
- `README.md` - Project documentation (this file).

--- 

## SQL Query Levels 

### **Basic** 
These queries provide foundational insights: 
1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.

### **Intermediate** 
These queries involve joining tables and performing aggregation for deeper insights: 
1. Join the necessary tables to find the total quantity of each pizza category ordered.
2. Determine the distribution of orders by hour of the day.
3. Join relevant tables to find the category-wise distribution of pizzas
4. Group the orders by date and calculate the average number of pizzas ordered per day.
5. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

### **Advanced** 
These queries involve advanced analytics and cumulative calculations: 
1. Calculate the percentage contribution of each pizza type to total revenue.
2. Analyze the cumulative revenue generated over time.
3. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

--- 

## Database Schema 
The queries assume the following tables: 

- **orders**
   - `order_id`
   - `date`
   - `time`

- **order_details**
   - `order_id`
   - `pizza_id`
   - `quantity`

- **pizzas**
   - `pizza_id`
   - `pizza_type`
   - `size`
   - `price`

- **pizza_types**
   - `pizza_type`
   - `name`
   - `category`
   - `ingredients`
 
## Insights 
- Total sales and revenue trends.
- Most popular pizza types and sizes.
- Revenue contribution by pizza category.
- Customer ordering behaviour by time and day.
- Top-selling pizzas by quantity and revenue.
  
