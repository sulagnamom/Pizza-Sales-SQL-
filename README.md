# Frictional PizzaHut-Sales-SQL-

1. **Project Background**
I worked on a fun and practical data analysis project using **SQL** where I explored transactional data from a fictional **PizzaHut** database. The goal was to understand sales patterns, customer preferences, and revenue trends by writing different types of SQL queries.
2. **Executive Summary**
    
    The analysis covers **revenue tracking**, **product preference**, **category trends**, and **temporal patterns**. Insights were derived from multiple joined tables using aggregations, subqueries.
    
3. **Total Orders Analysis**
    
    A simple aggregate query was used to calculate the **total number of orders placed**, forming the baseline for volume-based metrics.
    
4. **Revenue Generation**
    
    Calculated the **total revenue** from all pizza sales by joining the order details and pizza pricing tables, rounding the result to two decimal places for reporting.
    
5. **Top-Priced Pizza Identification**
    
    Used a descending price sort to identify the **most expensive pizza type** sold, helping understand premium pricing strategy.
    
6. **Popular Pizza Size**
    
    Grouped orders by pizza size and ranked them by frequency to identify the **most commonly ordered pizza size**, useful for inventory optimization.
    
7. **Top 5 Pizza Types by Quantity**
    
    Aggregated the **top 5 most ordered pizza types** by total quantity across all transactions, which helps product strategy and promotion planning.
    
8. **Category-wise Quantity Distribution**
    
    Summed up total pizza sales by category (e.g., Classic, Veggie, Chicken) to analyze **category-level performance** and demand segmentation.
    
9. **Time-based Order Distribution**
    
    Analyzed **hourly order patterns** using the **HOUR()** function to help schedule staffing and promotional timing based on peak order hours.
    
10. **Revenue-Based Ranking & Daily Patterns**
- Identified the **top 3 pizza types based on total revenue**, combining price and quantity metrics.
- Analyzed **daily average pizza orders** using nested aggregation to detect order volume trends per date.
