# Pizza Sales Analysis

## 1. Situation

 * The goal is to analyze pizza sales data to gain insights into customer ordering behavior, sales performance, and product popularity.
 * Extract meaningful trends and patterns that can support decision-making in areas such as marketing, inventory, and sales strategy.

 ## 2. Given Task

  * Retrieve the total number of orders placed.

  * Calculate the total revenue generated from pizza sales.

  * Identify the highest-priced pizza.

  * Identify the most common pizza size ordered.

  * List the top 5 most ordered pizza types along with their quantities.

  * Join necessary tables to find the total quantity of each pizza category ordered.

  * Determine the distribution of orders by hour of the day.

  * Join relevant tables to find the category-wise distribution of pizzas.

  * Group the orders by date and calculate the average number of pizzas ordered per day.

  * Determine the top 3 most ordered pizza types based on revenue.

  * Calculate the percentage contribution of each pizza type to total revenue.

  * Analyze the cumulative revenue generated over time.

  * Determine the top 3 most ordered pizza types based on revenue for each pizza category.

  ## 3. Data and Tool Used
 ### Data includes following tables:
    * order_details, 
    * orders, 
    * pizza_types, 
    * pizzas.

 ### Tool : MySQL, Excel

 ## 4. Action Performed

  * Performed in-depth data analysis using SQL by applying a combination of joins, aggregations, groupings, and subqueries to derive meaningful business insights from multiple related datasets. 

  * Merged tables using INNER JOIN, LEFT JOIN, and SELF JOIN to consolidate customer, transaction, and product data. 

  * Utilized GROUP BY with aggregate functions like COUNT(), SUM(), AVG(), and MAX() to summarize sales performance, customer behavior, and product-level metrics. 

  * Implemented subqueries to filter data dynamically, identify top-performing categories, and generate comparative statistics.

## 5. Key Metrics & Insights 

 ### 1. Total Orders & Revenue

 * Total orders placed: 22,109

 * Total revenue generated: $817,860.05

### 2.Top Pizza by Price

 * The Greek Pizza (L) is the most expensive.

 ### 3.Most Popular Pizza Size

Large (L) pizzas were the most frequently ordered size, accounting for approximately 48% of total sales.

 ### 4.Top 5 Most Ordered Pizza Types (by Quantity)

 * Classic Deluxe – 2,458 orders

 * The Greek Pizza – 2,417

 * Pepperoni – 2,291

 * BBQ Chicken – 2,159

 * Hawaiian – 2,066
   *  These top 5 types make up roughly 49% of all pizza sales.

 ### 5.Pizza Category Distribution (by Quantity)

 * Classic – 38%

 * Chicken – 26%

 * Veggie – 22%

 * Supreme – 14%

 ### 6.Revenue Contribution by Pizza Type

 * Top 3 pizza types by revenue:

    * Classic Deluxe – $42,017.65

    * BBQ Chicken – $41,565.13

    * The Greek Pizza – $40,709.67

    These three account for approximately 15% of total revenue.

### 7.Order Timing Patterns

 * Peak order time is 1 PM to 2 PM

 * More than 35% of orders happen between 12 PM to 3 PM – ideal for lunch offers.

 ### 8.Daily Order Pattern

 *  Average pizzas ordered per day: 142

 * Higher weekend sales – focus promotions on Fridays to Sundays.


 ## 6.Summary
  * This analysis shows that Classic Deluxe and BBQ Chicken pizzas are leaders in both volume and revenue. 
  * Lunch hours drive the highest sales, and Large size dominates.
  *  A strong focus on the Classic category and afternoon deals can boost performance further.


 

