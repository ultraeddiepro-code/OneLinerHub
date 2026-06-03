# Filtering and Queries

## CASE WHEN

```sql
CASE
WHEN col > 100 THEN 'High'
ELSE 'Low'
END
```

Creates conditional categories.

---

## WHERE IN

```sql
WHERE col IN (
    SELECT col FROM table
)
```

Filters using a subquery.

---

## CTE

```sql
WITH cte AS (
    SELECT ...
)
```

Creates reusable query blocks.