# Pizza Sales Analysis using SQL

Analysis of pizza-restaurant sales data in **MySQL** to answer 13 business questions, from simple counts to window functions.

## Objective
Understand total sales, best-selling pizzas, customer preferences and peak ordering hours.

##  Dataset
| Table | Description |
|---|---|
| `orders` | order_id, order_date, order_time |
| `orders_details` | order_details_id, order_id, pizza_id, quantity |
| `pizzas` | pizza_id, pizza_type_id, size, price |
| `pizza_types` | pizza_type_id, name, category, ingredients |

##  Tools & Skills
MySQL Workbench · JOINs · GROUP BY · Subqueries · Window functions (`SUM() OVER`, `RANK() OVER`)

##  Questions Solved
**Basic**
1. Total number of orders placed
2. Total revenue from pizza sales
3. Highest-priced pizza
4. Most common pizza size ordered
5. Top 5 most ordered pizza types

**Intermediate**
6. Total quantity ordered per pizza category
7. Orders by hour of the day
8. Category-wise distribution of pizzas
9. Average pizzas ordered per day
10. Top 3 pizza types by revenue

**Advanced**
11. Percentage contribution of each category to revenue
12. Cumulative revenue over time
13. Top 3 pizza types by revenue within each category

##  Key Results
| Metric | Result |
|---|---|
| Total orders | 21,350 |
| Total revenue | $817,860.05 |
| Highest-priced pizza | The Greek Pizza ($35.95) |
| Most common size | L (18,526 order lines) |
| Best-selling pizza | The Classic Deluxe Pizza (2,453) |
| Top category by quantity | Classic (14,888) |
| Peak hours | 12:00-13:00 and 17:00-18:00 |
| Avg pizzas per day | 138 |
| Top revenue pizza | The Thai Chicken Pizza ($43,434.25) |

##  Project Structure
```
pizza-sales-sql-analysis/
├── pizzahut.sql          # all queries
├── images/               # query output screenshots
├── presentation/         # PDF presentation
└── README.md
```

## How to Run
1. Create the database and the `orders` / `orders_details` tables using the top of `pizzahut.sql`.
2. Import the `pizzas` and `pizza_types` CSV files (MySQL Workbench → Table Data Import Wizard).
3. Run the queries in `pizzahut.sql`.


## 👤 Author
**ATUL CHAUHAN** 
