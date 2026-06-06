# Filtering and Queries

## CASE WHEN

```sql
CASE
    WHEN salary > 100000 THEN 'High'
    ELSE 'Low'
END
```

Conditional logic in SQL.

---

## IN

```sql
WHERE department_id IN (1, 2, 3)
```

Checks multiple values.

---

## EXISTS

```sql
WHERE EXISTS (
    SELECT 1
    FROM orders
    WHERE orders.customer_id = customers.customer_id
)
```

Checks whether rows exist.

---

## CTE

```sql
WITH sales AS (
    SELECT *
    FROM orders
)
SELECT *
FROM sales;
```

Creates reusable query blocks.

---

## LIMIT

```sql
SELECT *
FROM employees
LIMIT 10;
```

Returns limited rows.