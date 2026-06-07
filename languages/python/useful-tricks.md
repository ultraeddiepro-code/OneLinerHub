# Useful Python Tricks

## Swap Variables

```python
a, b = b, a
```

Swap values without temp variable.

---

## Enumerate List

```python
list(enumerate(lst))
```

Get index and value.

---

## Zip Lists

```python
list(zip(list1, list2))
```

Combine lists element-wise.

---

## Random Choice

```python
random.choice(lst)
```

Select random element.

---

## Get Current Timestamp

```python
datetime.now().timestamp()
```

Current Unix timestamp.

---

## Execute Function N Times

```python
[func() for _ in range(n)]
```

Run function repeatedly.