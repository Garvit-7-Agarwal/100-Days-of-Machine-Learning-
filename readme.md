# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## Bold Text

**This is bold text**

---

## Italic Text

*This is italic text*

---

## Bold + Italic

***This is bold and italic***

---

## Strikethrough

~~This text is crossed out~~

---

## Bullet List

- Item 1
- Item 2
- Item 3

---

## Numbered List

1. First Item
2. Second Item
3. Third Item

---

## Nested List

- Machine Learning
  - Supervised Learning
  - Unsupervised Learning

---

## Inline Code

Use `pd.read_csv()` to read CSV files.

---

## Code Block

```python
import pandas as pd

df = pd.read_csv("data.csv")
print(df.head())
```

---

## Block Quote

> This is an important note.

---

## Horizontal Line

---

## Table

| Parameter | Purpose |
|------------|------------|
| parse_dates | Convert date columns |
| dtype | Set datatype |
| usecols | Select columns |

---

## Task List

- [x] Completed
- [ ] Not Completed

---

## Link

[Google](https://www.google.com)

---

## Image

![Image Name](image.png)

---

## HTML Color (Works in Jupyter)

<span style="color:red">Red Text</span>

<span style="color:blue">Blue Text</span>

<span style="color:green">Green Text</span>

<span style="color:orange">Orange Text</span>

---

## HTML Text Size

<h1>Large Text</h1>

<h2>Medium Text</h2>

<h3>Small Text</h3>

---

## Highlight Text

<mark>Important Note</mark>

---

## Center Text

<div align="center">

Centered Text

</div>

---

## Line Break

First Line<br>
Second Line

---

## Example Note Format

# parse_dates Parameter

## Purpose

Converts date columns from object type to datetime format.

### Benefits

- Extract year
- Extract month
- Extract day
- Perform date calculations

### Example

```python
df = pd.read_csv(
    "data.csv",
    parse_dates=["Date"]
)
```

### Quick Summary

| Syntax | Purpose |
|----------|----------|
| parse_dates=["Date"] | Convert one date column |
| parse_dates=["Date","JoiningDate"] | Convert multiple columns |
| parse_dates=[[0,1]] | Combine columns |
| parse_dates={"Date":[0,1]} | Combine and rename |