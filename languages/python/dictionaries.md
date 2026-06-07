# Dictionary One-Liners

## Merge Dictionaries

```python
{**dict1, **dict2}
```

Combine dictionaries.

---

## Sort by Value

```python
dict(sorted(d.items(), key=lambda x: x[1]))
```

Sort dictionary by values.

---

## Get Key with Maximum Value

```python
max(d, key=d.get)
```

Return key having largest value.

---

## Dictionary Comprehension

```python
{k: v*2 for k, v in d.items()}
```

Create transformed dictionary.

---

## Invert Dictionary

```python
{v: k for k, v in d.items()}
```

Swap keys and values.