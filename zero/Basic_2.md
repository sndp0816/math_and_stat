\# Quantitative Aptitude Notes

\### Unit Digit • Remainders • Factorials • BODMAS • Fractions • Surds \& Indices



\---



\## 1. Unit Digit (Last Digit) of a Number



The \*\*unit digit\*\* of a product or power depends only on the unit digits of the numbers involved.



\### Key Idea

Unit digit of a product = unit digit of (product of unit digits of the numbers).



\*\*Example:\*\* Unit digit of `23 × 37`

→ Unit digits are 3 and 7 → 3 × 7 = 21 → Unit digit = \*\*1\*\*



\### Unit Digit of Powers (aⁿ)

Unit digits repeat in a \*\*cycle\*\*. Cycle length depends on the base's last digit:



| Last digit of base | Cycle | Length |

|---|---|---|

| 0, 1, 5, 6 | always same digit | 1 |

| 4, 9 | 2 values | 2 |

| 2, 3, 7, 8 | 4 values | 4 |



\*\*Steps to find unit digit of aⁿ:\*\*

1\. Take the last digit of `a`.

2\. Find the cycle length (1, 2, or 4) from the table above.

3\. Compute `n mod cycle\_length`. If remainder is 0, use the cycle length itself.

4\. Look up that position in the cycle.



\*\*Example:\*\* Find unit digit of `7^123`

\- Last digit 7 → cycle of 4: 7¹=7, 7²=9, 7³=3, 7⁴=1 (repeats)

\- 123 mod 4 = 3 → 3rd value in cycle = \*\*3\*\*



\---



\## 2. Remainders



\### Basic Remainder Rule

When `a` is divided by `b`: `a = b × q + r`, where `0 ≤ r < b`.



\### Useful Techniques



\*\*a) Remainder using negative remainder trick\*\*

If a number is close to a multiple of the divisor, use negative remainders.

Example: `48 ÷ 5` → 48 = 50 − 2 → remainder = 5 − 2 = 3 (since −2 mod 5 = 3)



\*\*b) Remainder of a product\*\*

`(a × b) mod n = \[(a mod n) × (b mod n)] mod n`



\*\*c) Remainder of a sum\*\*

`(a + b) mod n = \[(a mod n) + (b mod n)] mod n`



\*\*d) Remainder of powers — using cyclicity\*\*

Same idea as unit digits, but applied to `mod n` instead of mod 10.



\*\*e) Fermat's Little Theorem\*\* (when p is prime and a is not divisible by p):

`a^(p-1) mod p = 1`

Useful for large powers with prime divisors.



\*\*Example:\*\* Find remainder of `2^100` divided by 7.

\- 7 is prime → 2⁶ mod 7 = 1 (Fermat)

\- 100 mod 6 = 4 → 2⁴ mod 7 = 16 mod 7 = \*\*2\*\*



\---



\## 3. Factorials



`n! = n × (n-1) × (n-2) × ... × 2 × 1`, and `0! = 1`



\### Key Properties

\- Factorials grow very fast: 5! = 120, 10! = 3,628,800

\- \*\*Trailing zeros in n!\*\* are created by factors of 10 = 2 × 5. Since 2s are more frequent than 5s, count the number of 5s:



\*\*Formula (Legendre's Formula):\*\*

```

Number of trailing zeros in n! = ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + ...

```



\*\*Example:\*\* Trailing zeros in 100!

\- ⌊100/5⌋ = 20

\- ⌊100/25⌋ = 4

\- ⌊100/125⌋ = 0

\- Total = \*\*24\*\*



\### Unit digit of factorials

\- For n ≥ 5, n! always ends in \*\*0\*\* (since it contains both 2 and 5 as factors).

\- So only 0!, 1!, 2!, 3!, 4! have non-zero unit digits (1, 1, 2, 6, 4).



\---



\## 4. BODMAS (Order of Operations)



BODMAS tells us the correct order to solve an arithmetic expression:



| Letter | Stands for |

|---|---|

| B | Brackets ( ), { }, \[ ] |

| O | Of (i.e., percentages/fractions "of") |

| D | Division |

| M | Multiplication |

| A | Addition |

| S | Subtraction |



\*\*Rule:\*\* Solve Brackets first → then "Of" → then Division \& Multiplication (left to right) → then Addition \& Subtraction (left to right).



\*\*Example:\*\* Solve `10 + 2 × (6 − 4) ÷ 2`

1\. Brackets: (6−4) = 2 → `10 + 2 × 2 ÷ 2`

2\. Division/Multiplication (left to right): 2 × 2 = 4, then 4 ÷ 2 = 2 → `10 + 2`

3\. Addition: \*\*12\*\*



⚠️ Common mistake: Division and Multiplication have \*\*equal priority\*\* — solve left to right, not "D before M" blindly. Same for Addition and Subtraction.



\---



\## 5. Fractions



A fraction represents a part of a whole: `numerator / denominator`.



\### Types

\- \*\*Proper fraction:\*\* numerator < denominator (e.g., 3/4)

\- \*\*Improper fraction:\*\* numerator ≥ denominator (e.g., 7/4)

\- \*\*Mixed number:\*\* whole number + proper fraction (e.g., 1¾)



\### Operations



\*\*Addition/Subtraction:\*\* Make denominators equal (find LCM), then add/subtract numerators.

```

1/3 + 1/4 = 4/12 + 3/12 = 7/12

```



\*\*Multiplication:\*\* Multiply numerators together and denominators together.

```

2/3 × 3/5 = 6/15 = 2/5

```



\*\*Division:\*\* Multiply by the reciprocal of the second fraction.

```

2/3 ÷ 4/5 = 2/3 × 5/4 = 10/12 = 5/6

```



\*\*Comparing fractions:\*\* Cross-multiply.

```

3/5 vs 4/7 → 3×7=21, 4×5=20 → since 21>20, 3/5 > 4/7

```



\---



\## 6. Surds



A \*\*surd\*\* is an irrational root that cannot be simplified to remove the root, e.g., `√2, √3, √5`.



\### Rules of Surds

\- `√a × √b = √(ab)`

\- `√a / √b = √(a/b)`

\- `a√x + b√x = (a+b)√x` (like surds can be combined)

\- `(√a)² = a`



\### Rationalizing the Denominator

Remove surds from the denominator by multiplying numerator and denominator by the conjugate.



\*\*Example:\*\* Rationalize `1/(√2 + 1)`

```

1/(√2+1) × (√2−1)/(√2−1) = (√2−1)/(2−1) = √2 − 1

```



\---



\## 7. Indices (Exponents)



Indices represent repeated multiplication: `aⁿ = a × a × ... × a (n times)`



\### Laws of Indices



| Rule | Formula |

|---|---|

| Product rule | `aᵐ × aⁿ = aᵐ⁺ⁿ` |

| Quotient rule | `aᵐ ÷ aⁿ = aᵐ⁻ⁿ` |

| Power of a power | `(aᵐ)ⁿ = aᵐⁿ` |

| Power of a product | `(ab)ⁿ = aⁿbⁿ` |

| Power of a fraction | `(a/b)ⁿ = aⁿ/bⁿ` |

| Zero exponent | `a⁰ = 1 (a ≠ 0)` |

| Negative exponent | `a⁻ⁿ = 1/aⁿ` |

| Fractional exponent | `a^(1/n) = ⁿ√a` |



\*\*Example:\*\* Simplify `(2³ × 2²) / 2⁴`

```

= 2^(3+2-4) = 2¹ = 2

```



\*\*Example:\*\* Simplify `8^(2/3)`

```

= (2³)^(2/3) = 2² = 4

```



\---



\## Quick Reference Summary



| Topic | Core Trick |

|---|---|

| Unit digit | Use cyclicity (1, 2, or 4-cycle) based on last digit |

| Remainders | Use negative remainders \& Fermat's Little Theorem for large powers |

| Factorials | Trailing zeros = count of 5s using Legendre's formula |

| BODMAS | Brackets → Of → Div/Mult (L→R) → Add/Sub (L→R) |

| Fractions | Common denominator to add/subtract; reciprocal to divide |

| Surds | Combine like surds; rationalize using conjugates |

| Indices | Master the 7 core exponent laws |

