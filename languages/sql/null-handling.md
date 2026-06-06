# NULL Handling

## COALESCE

```sql
COALESCE(phone, 'Unknown')
```

Returns the first non-NULL value.

---

## NULLIF

```sql
NULLIF(score, 0)
```

Returns NULL if values match.

---

## IS NULL

```sql
WHERE email IS NULL
```

Find rows containing NULL values.

---

## IS NOT NULL

```sql
WHERE email IS NOT NULL
```

Find rows that contain values.