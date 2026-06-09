# String One-Liners

## Reverse String

```cpp
reverse(s.begin(), s.end());
```

Reverse a string in-place.

---

## Convert to Uppercase

```cpp
transform(s.begin(), s.end(), s.begin(), ::toupper);
```

Convert string to uppercase.

---

## Convert to Lowercase

```cpp
transform(s.begin(), s.end(), s.begin(), ::tolower);
```

Convert string to lowercase.

---

## String Length

```cpp
s.length()
```

Get string length.

---

## Check Palindrome

```cpp
s == string(s.rbegin(), s.rend())
```

Check if string is palindrome.

---

## Count Character

```cpp
count(s.begin(), s.end(), 'a')
```

Count occurrences of a character.