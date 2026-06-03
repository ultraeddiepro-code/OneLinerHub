# Window Functions

## RANK

```sql
RANK() OVER (ORDER BY col DESC)
```

Ranks rows with ties.

---

## LAG

```sql
LAG(col) OVER (ORDER BY date)
```

Gets previous row value.

---

## LEAD

```sql
LEAD(col) OVER (ORDER BY date)
```

Gets next row value.

---

## Running Total

```sql
SUM(col) OVER (ORDER BY date)
```

Calculates cumulative totals.

---

## Moving Average

```sql
AVG(col) OVER (PARTITION BY region)
```

Calculates average within a group.