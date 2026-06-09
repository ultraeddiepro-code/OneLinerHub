# Vector One-Liners

## Sort Vector

```cpp
sort(v.begin(), v.end());
```

Sort ascending.

---

## Reverse Vector

```cpp
reverse(v.begin(), v.end());
```

Reverse elements.

---

## Maximum Element

```cpp
*max_element(v.begin(), v.end())
```

Get largest value.

---

## Minimum Element

```cpp
*min_element(v.begin(), v.end())
```

Get smallest value.

---

## Sum Elements

```cpp
accumulate(v.begin(), v.end(), 0)
```

Calculate total.

---

## Remove Duplicates

```cpp
v.erase(unique(v.begin(), v.end()), v.end());
```

Remove adjacent duplicates after sorting.