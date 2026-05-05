
# Stage 0 — Number Sense & Arithmetic 🔢
### The atoms of math

> *Before algebra, before calculus, before anything — there are numbers. This stage is not "easy math". It is the foundation every skyscraper of mathematics stands on. Go deep here.*

---

## Table of Contents

- [Counting & Place Value](#1-counting--place-value)
- [Addition & Subtraction](#2-addition--subtraction)
- [Multiplication & Division](#3-multiplication--division)
- [Fractions & Decimals](#4-fractions--decimals)
- [Percentages & Ratios](#5-percentages--ratios)
- [Negative Numbers](#6-negative-numbers)
- [Order of Operations](#7-order-of-operations)
- [Estimation & Rounding](#8-estimation--rounding)
- [What to Understand Deeply](#what-to-understand-deeply)
- [Practice Problems](#practice-problems)

---

## 1. Counting & Place Value

Numbers are symbols we use to represent quantities. The **decimal system** (base-10) means every position in a number is worth 10× the position to its right.

```
  5  4  3  2  1
  |  |  |  |  |
  |  |  |  |  └── ones        (1)
  |  |  |  └───── tens        (10)
  |  |  └──────── hundreds    (100)
  |  └─────────── thousands   (1,000)
  └────────────── ten-thousands (10,000)
```

**Example:** The number `3,472` means:
```
3 × 1000  +  4 × 100  +  7 × 10  +  2 × 1
= 3000    +   400     +    70    +    2
= 3,472
```

> **Deep insight:** Place value is why `10` and `01` are different numbers. Position carries meaning. This idea — that *where* something sits determines its value — echoes all the way into matrix algebra and beyond.

---

## 2. Addition & Subtraction

Addition combines quantities. Subtraction finds the difference.

### Key properties of addition

| Property      | What it means              | Example                   |
| :------------ | :------------------------- | :------------------------ |
| Commutative   | Order doesn't matter       | `3 + 5 = 5 + 3`           |
| Associative   | Grouping doesn't matter    | `(2+3)+4 = 2+(3+4)`       |
| Identity      | Adding zero changes nothing| `7 + 0 = 7`               |

### Worked example

```
  Carry:   1
  ────────────
    3 8 7
  + 2 4 6
  ───────
    6 3 3
```
`7 + 6 = 13` → write 3, carry 1  
`8 + 4 + 1 = 13` → write 3, carry 1  
`3 + 2 + 1 = 6` → write 6

---

## 3. Multiplication & Division

Multiplication is **repeated addition**. Division is **repeated subtraction** (or splitting into equal groups).

```
  4 × 3  =  4 + 4 + 4  =  12
  12 ÷ 3 =  how many 3s fit in 12?  =  4
```

### Key properties

| Property      | Example                          |
| :------------ | :------------------------------- |
| Commutative   | `4 × 3 = 3 × 4`                  |
| Associative   | `(2 × 3) × 4 = 2 × (3 × 4)`     |
| Distributive  | `3 × (4 + 5) = 3×4 + 3×5`       |
| Identity      | `n × 1 = n`                      |
| Zero property | `n × 0 = 0`                      |

> **The distributive property** is one of the most important things in all of mathematics. It's why `3(x + 5) = 3x + 15` works in algebra. Understand it here, at the simplest level.

### Division with remainders

```
  17 ÷ 5  =  3  remainder  2

  Because:  5 × 3 = 15,  and  17 − 15 = 2
```

---

## 4. Fractions & Decimals

A fraction represents a **part of a whole**.

```
    3        ← numerator   (parts you have)
   ───
    4        ← denominator (total equal parts)
```

### Operations with fractions

**Adding/subtracting** — need a common denominator:
```
  1   +   1   =   3   +   2   =   5
  ─       ─       ─       ─       ─
  2       3       6       6       6
```

**Multiplying** — straight across:
```
  2   ×   3   =    6    =   1
  ─       ─        ─        ─
  3       4       12        2
```

**Dividing** — flip the second fraction and multiply:
```
  2   ÷   4   =   2   ×   5   =   10   =   5
  ─       ─       ─       ─        ─        ─
  3       5       3       4       12        6
```

### Fractions ↔ Decimals

| Fraction | Decimal | Notes                     |
| :------- | :------ | :------------------------ |
| `1/2`    | `0.5`   | Terminates                |
| `1/3`    | `0.333…`| Repeats                   |
| `1/4`    | `0.25`  | Terminates                |
| `1/8`    | `0.125` | Terminates                |
| `2/3`    | `0.666…`| Repeats                   |
| `1/7`    | `0.142857…` | Repeats (long cycle) |

> **Deep insight:** Some fractions produce repeating decimals — this is not a flaw, it's a feature. It hints at something deep: not all numbers can be written as fractions. Those are called *irrational numbers* (like π and √2), and they'll matter enormously later.

---

## 5. Percentages & Ratios

**Percent** means *per hundred*. `45%` = `45/100` = `0.45`

### Common conversions

```
  Fraction → Percent:  1/4 = 0.25 = 25%
  Percent → Decimal:   73% = 0.73
  Decimal → Percent:   0.6 = 60%
```

### Worked examples

```
  What is 30% of 250?
  → 0.30 × 250 = 75

  What percent is 18 of 72?
  → 18/72 = 0.25 = 25%

  A price rises from 200 to 250. What's the % increase?
  → (250 − 200) / 200 × 100 = 50/200 × 100 = 25%
```

### Ratios

A ratio compares two quantities. `3:5` means for every 3 of one thing, there are 5 of another.

```
  Ratio 3:5 → fractions are 3/8 and 5/8 of the total
  If total = 40:  → 15 and 25
```

---

## 6. Negative Numbers

Negative numbers live to the **left of zero** on the number line.

```
  ←─────────────────────────────────────────→
  -5   -4   -3   -2   -1    0    1    2    3
```

### Rules for operations

| Operation           | Rule                              | Example            |
| :------------------ | :-------------------------------- | :----------------- |
| `pos + neg`         | Subtract, keep sign of larger     | `7 + (−3) = 4`     |
| `neg + neg`         | Add, result is negative           | `−3 + (−4) = −7`   |
| `pos × neg`         | Result is negative                | `5 × (−3) = −15`   |
| `neg × neg`         | Result is **positive**            | `(−4) × (−3) = 12` |
| `neg ÷ pos`         | Result is negative                | `−12 ÷ 4 = −3`     |

> **Deep insight:** Negative × negative = positive is not a arbitrary rule. It's forced by the distributive property needing to stay consistent. This is your first glimpse of math being *internally consistent* — rules aren't invented, they're *required*.

---

## 7. Order of Operations

When an expression has multiple operations, the order you evaluate them matters.

### PEMDAS / BODMAS

```
  P  — Parentheses  (Brackets)
  E  — Exponents    (Orders)
  M  — Multiplication   ┐
  D  — Division         ┘  left to right
  A  — Addition     ┐
  S  — Subtraction  ┘  left to right
```

### Worked examples

```
  3 + 4 × 2
  = 3 + 8        ← multiply first
  = 11

  (3 + 4) × 2
  = 7 × 2        ← brackets first
  = 14

  2 + 3² × (4 − 1)
  = 2 + 9 × 3    ← brackets, then exponent
  = 2 + 27       ← multiply
  = 29
```

> **Common mistake:** `6 ÷ 2(1+2)` — always resolve brackets first → `6 ÷ 2 × 3` — then left to right → `9`. The ambiguity is in bad notation, not in the rules.

---

## 8. Estimation & Rounding

### Rounding rules

- Look at the digit **after** the place you're rounding to
- `0–4` → round down (keep the digit)
- `5–9` → round up (increase the digit by 1)

```
  Round 3.746 to 2 decimal places:
  → look at 3rd decimal: 6 ≥ 5 → round up
  → 3.75

  Round 4,382 to the nearest hundred:
  → look at tens digit: 8 ≥ 5 → round up
  → 4,400
```

### Mental estimation

```
  Exact:    197 × 4 = 788
  Estimate: 200 × 4 = 800   ← close enough to check sanity

  Exact:    √50 ≈ 7.07
  Estimate: √49 = 7          ← anchored to a known square root
```

---

## What to Understand Deeply

These are the ideas that matter beyond the mechanics:

**1. Numbers are abstractions.** "3" doesn't exist in nature. Three apples do. The number is a mental model — and an extraordinarily powerful one.

**2. Operations are transformations.** Addition moves you along a number line. Multiplication scales. Division splits. Once you see operations as *actions on numbers*, algebra becomes natural.

**3. The distributive property is everywhere.** `a(b + c) = ab + ac`. It shows up in algebra, calculus, linear algebra, and abstract algebra. Understand it deeply now.

**4. Fractions are division.** `3/4` literally means `3 ÷ 4`. This is why dividing by a fraction flips it — you're undoing a division.

**5. Zero is not nothing.** Zero is a number with its own rules. Division by zero is undefined (not infinity, not zero — *undefined*). This matters in calculus and analysis.

---

## Practice Problems

### Level 1 — Mechanics
```
1.  347 + 896 = ?
2.  1002 − 487 = ?
3.  24 × 35 = ?
4.  756 ÷ 12 = ?
5.  3/4 + 5/6 = ?
6.  2/3 × 9/4 = ?
7.  What is 15% of 340?
8.  −8 × (−7) = ?
```

### Level 2 — Thinking
```
9.  Simplify: 4 + 3² × (2 + 1) − 6 ÷ 2
10. A jacket costs ₹2,400. After a 35% discount, what is the price?
11. Two numbers are in ratio 5:3. Their sum is 96. Find both numbers.
12. If a temperature drops from 4°C to −11°C, what is the total drop?
```

### Level 3 — Deep
```
13. Without a calculator: estimate √200 to one decimal place. Explain your method.
14. Why is any number × 0 = 0? Prove it using the distributive property.
15. Is 0.999… equal to 1? Make a case using fractions.
```

---

### Answers (Level 1)
```
1.  1,243
2.  515
3.  840
4.  63
5.  19/12  (= 1 7/12)
6.  3/2    (= 1.5)
7.  51
8.  56
```

---

## Next Stage

Once you can do Level 2 problems without hesitation and think clearly about Level 3 questions — you're ready.

➡️ **[Stage 1 — Pre-Algebra & Basic Geometry](./one.md)**

---

*Part of the [Math Learning Roadmap](./MATH_ROADMAP.md) — Zero to the Universe.*