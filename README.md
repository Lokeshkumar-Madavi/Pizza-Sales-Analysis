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


![1 P](https://github.com/user-attachments/assets/b35f10cc-3272-478d-87d5-10ebe70d04bb)
![2 P](https://github.com/user-attachments/assets/5ee7c423-1b93-4175-b18f-d7e72ab401fa)
![3 P](https://github.com/user-attachments/assets/42031024-58f0-4809-aa36-0a59d95a8023)
![4 P](https://github.com/user-attachments/assets/5ce0d86c-cb54-4087-b3f0-b5bfb3e1d8fa)
![5 P](https://github.com/user-attachments/assets/8e7f7184-58ff-4752-ba48-6a8b967410de)
![6 P](https://github.com/user-attachments/assets/a7607213-2f66-4587-a68f-e91da1a99c9c)
![7 P](https://github.com/user-attachments/assets/92fe1cc2-edf6-4a3c-a5e1-592fa980c875)
![8 P](https://github.com/user-attachments/assets/a57cd01a-d41c-4177-aa41-b67e4e02bc52)
![9 P](https://github.com/user-attachments/assets/f72dfa3d-3a7c-4874-bf06-e7854bfb03e0)
![10 P](https://github.com/user-attachments/assets/2020ed03-0d8e-486f-a0dc-a1a5baebc71c)
![11 P](https://github.com/user-attachments/assets/263f4cbd-996c-4ea3-9416-7f4f9b73b198)
![12 P](https://github.com/user-attachments/assets/ad172468-70ce-44db-a93d-63dfd5b833a9)
![13 P](https://github.com/user-attachments/assets/ae498b75-f349-4342-bd26-51f991506f48)






 

