# Date Functions

## CAST

```sql
CAST(order_date AS DATE)
```

Converts data type.

---

## DATE_TRUNC

```sql
DATE_TRUNC('month', order_date)
```

Rounds date to specified precision.

---

## EXTRACT

```sql
EXTRACT(YEAR FROM order_date)
```

Extracts date components.

---

## DATEDIFF

```sql
DATEDIFF(day, start_date, end_date)
```

Calculates difference between dates.

---

## CURRENT_DATE

```sql
CURRENT_DATE
```

Returns current date.