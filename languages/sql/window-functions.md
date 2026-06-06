# Window Functions

## RANK

```sql
RANK() OVER (ORDER BY salary DESC)
```

Assigns ranking with gaps.

---

## DENSE_RANK

```sql
DENSE_RANK() OVER (ORDER BY salary DESC)
```

Assigns ranking without gaps.

---

## ROW_NUMBER

```sql
ROW_NUMBER() OVER (ORDER BY salary DESC)
```

Assigns unique row numbers.

---

## LAG

```sql
LAG(sales) OVER (ORDER BY month)
```

Access previous row.

---

## LEAD

```sql
LEAD(sales) OVER (ORDER BY month)
```

Access next row.

---

## Running Total

```sql
SUM(amount) OVER (ORDER BY order_date)
```

Calculates cumulative sum.