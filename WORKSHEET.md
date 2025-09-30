# SQL Basics – Practice Worksheet (Student Version)

**Database:** `sql_intro_class_100_orders.sqlite`  

**Tables:**  

- `customers(customer_id, customer_name, country)`  
- `products(product_id, product_name, category, unit_price)`  
- `orders(order_id, customer_id, order_date)`  
- `order_items(order_item_id, order_id, product_id, quantity, unit_price)`  

---

## 1. SELECT + FROM

👉 List all customers’ names and countries.

## 2. WHERE

👉 Find all orders placed after July 1, 2024.

## 3. Basic Calculations in SELECT

👉 Show each order item’s total price (`quantity * unit_price`).

## 4. ORDER BY

👉 List products ordered by highest unit price first.

## 5. JOIN

👉 List each customers' orders.

## 6. GROUP BY

👉 Show how many orders each customer has made.

## 7. GROUP BY + ORDER BY + LIMIT

👉 Find the top 5 countries by total revenue.

## 8. Stretch Challenge (Put it all together)

👉 For each product category, show:

- Number of items sold  
- Total revenue  
- Average order item value  
