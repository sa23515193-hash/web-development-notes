# SQL Basics

SQL databases organize data into tables.

Example:

```sql
CREATE TABLE products (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    price DECIMAL(10, 2)
);
```

Query data:

```sql
SELECT name, price
FROM products
WHERE price > 1000;
```
