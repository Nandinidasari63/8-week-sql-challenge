🍕 Case Study #2 - Pizza Runner
🍝 Solution - A. Pizza Metrics
*Query #1**

    --How many pizzas were ordered?
    select count(*) as pizza_order_count 
    from customer_orders;

| pizza_order_count |
| ----------------- |
| 14                |

---
2.How many unique customer orders were made?
select * from customer_orders;
select count(distinct(order_id)) from customer_orders; 
