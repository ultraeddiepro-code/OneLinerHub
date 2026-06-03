# Aggregation Functions

## COUNT DISTINCT

```sql
SELECT COUNT(DISTINCT customer_id)
FROM orders;
```

Counts unique values.

---

## GROUP BY HAVING

```sql
SELECT department_id
FROM employees
GROUP BY department_id
HAVING COUNT(*) > 1;
```

Filters grouped results.

---

## UNION ALL

```sql
SELECT city FROM customers
UNION ALL
SELECT city FROM suppliers;
```

Combines results and keeps duplicates.