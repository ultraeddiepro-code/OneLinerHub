# Bit Manipulation

## Check Power of Two

```cpp
n && !(n & (n - 1))
```

Check if number is power of two.

---

## Count Set Bits

```cpp
__builtin_popcount(n)
```

Count bits set to 1.

---

## Lowest Set Bit

```cpp
n & (-n)
```

Extract rightmost set bit.

---

## Toggle Bit

```cpp
n ^= (1 << k)
```

Flip kth bit.

---

## Check kth Bit

```cpp
(n >> k) & 1
```

Check kth bit.

---

## Set kth Bit

```cpp
n |= (1 << k)
```

Set kth bit to 1.