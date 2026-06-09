# Useful Tricks

## Fast I/O

```cpp
ios::sync_with_stdio(false); cin.tie(nullptr);
```

Speed up input/output.

---

## Swap Values

```cpp
swap(a, b);
```

Swap variables.

---

## Lambda Function

```cpp
[](int a, int b){ return a < b; }
```

Anonymous function.

---

## Range-Based Loop

```cpp
for(auto &x : v)
```

Iterate container.

---

## Vector Size

```cpp
v.size()
```

Number of elements.

---

## Pair Creation

```cpp
make_pair(a, b)
```

Create pair.

---

## Structured Binding (C++17)

```cpp
auto [x, y] = p;
```

Unpack pair.

---

## Ternary Operator

```cpp
a > b ? a : b
```

Inline condition.