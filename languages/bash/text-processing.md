# Text Processing

## Count Lines

```bash
wc -l file.txt
```

Count lines in a file.

---

## Search Text

```bash
grep "error" logfile.txt
```

Find matching lines.

---

## Remove Duplicate Lines

```bash
sort file.txt | uniq
```

Remove duplicates.

---

## Top 10 Frequent Words

```bash
tr ' ' '\n' < file.txt | sort | uniq -c | sort -nr | head
```

Find most common words.