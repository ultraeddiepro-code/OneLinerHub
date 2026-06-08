# Bit Manipulation

## Check Power of Two

```cpp
n && !(n & (n - 1))
```

Returns true if power of two.

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