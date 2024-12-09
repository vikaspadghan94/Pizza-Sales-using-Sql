
Problem Statement:
You want to determine the top 3 most ordered pizza types based on revenue for each pizza category (e.g., Veggie, Meat). The goal is to identify the best-performing pizzas within each category to help prioritize marketing efforts and inventory planning.

Query Description:
This SQL query is structured to solve the problem by:

Calculating Revenue: Computes the total revenue for each pizza type based on its quantity sold and price.
Ranking within Categories: Uses the RANK() function to assign ranks to pizzas within each category, sorted by revenue in descending order.
Selecting Top 3: Filters the results to include only the top 3 pizzas in terms of revenue for each category.

Total revenue and sales volume by pizza type and size.
Average order value (AOV) and customer lifetime value (CLV).
Daily and monthly sales trends using time-based aggregation.
Order distribution across pizza categories.
Identifying top 5 best-selling pizzas.
