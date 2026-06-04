# File Operations

## Find Large Files

```bash
find . -type f -size +100M
```

Find files larger than 100 MB.

---

## Count Files

```bash
find . -type f | wc -l
```

Count files recursively.

---

## Delete Empty Files

```bash
find . -type f -empty -delete
```

Remove empty files.

---

## Create Nested Directories

```bash
mkdir -p project/src/components
```

Create directories recursively.