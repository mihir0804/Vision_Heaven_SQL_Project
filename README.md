# Vision Heaven SQL Project

## Overview
The **Vision Heaven SQL Project** is a database design and implementation project for an eyewear e-commerce system.  
It demonstrates the creation of a relational database, insertion of sample records, and execution of SQL queries to simulate real-world business operations such as customer management, orders, payments, carts, and reviews.

---

## Database Schema
The project implements the following core tables:
- **Customer** – Stores customer details such as name, email, phone, age, gender, address, and password.  
- **Products** – Contains product information (brand, type, frame, lens, material, and description).  
- **Orders** – Tracks customer orders with status, shipping details, total amount, and payment method.  
- **OrderItem** – Records product-level details for each order.  
- **Carts** – Represents a shopping cart linked to a customer.  
- **CartItem** – Holds items added to carts with prices and quantities.  
- **Payment** – Manages payment details such as method, amount, status, and linked order/customer.  
- **Reviews** – Stores customer ratings and comments for products.  

Additionally:
- Views (`customer_view`, `customer_view2`, `customer_view3`) are created for easier reporting.  
- Stored procedures (`order_detail`) demonstrate advanced SQL functionality.  

---

## Features
- **Database creation** with constraints (Primary Key, Foreign Key, Unique, Check).  
- **Data insertion** with realistic sample data for customers, products, orders, and reviews.  
- **Queries** to demonstrate:
  - Filtering (`WHERE`, `LIKE`, `BETWEEN`, `IN`, `NOT`)  
  - Sorting (`ORDER BY`)  
  - Aggregations (`SUM`, `AVG`, `MIN`, `MAX`, `COUNT`)  
  - String functions (`CONCAT`, `LOWER`, `LENGTH`, `SUBSTRING`)  
  - Joins (`INNER JOIN`, `LEFT/RIGHT JOIN`, `CROSS JOIN`)  
  - Subqueries and correlated queries  
- **Views** for summarized reporting.  
- **Stored procedures** for reusable queries.  
- **Constraints management** (`ALTER TABLE`, `DROP CONSTRAINT`).  

---

## Sample Queries
Examples include:
- Customers above a certain age.  
- Orders with total amount above/below a threshold.  
- Reviews with specific ratings.  
- Aggregate revenue from all orders.  
- Customer and order details using joins.  

---

## How to Use
1. Clone this repository.  
2. Open the `.sql` file in your MySQL environment.  
3. Run the script step by step (or all at once) to create the database and populate it.  
4. Execute provided queries to explore and analyze the data.  

---

## Technologies
- **Database**: MySQL  
- **Language**: SQL  

---

## Learning Outcomes
This project helps in understanding:
- Relational database design.  
- Implementation of constraints and relationships.  
- Querying techniques for analytics and reporting.  
- Advanced SQL concepts (views, joins, stored procedures).  

---

## License
This project is licensed under the **Apache 2.0 License**.  
