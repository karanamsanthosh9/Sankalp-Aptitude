# HCF & LCM

**The idea:** HCF is the biggest number that divides each value. LCM is the first positive number they all divide into.

## The essentials

- Prime-factorize first. For HCF take the **smallest** power of each shared prime; for LCM take the **largest**.
- For two numbers only: $a\times b=\operatorname{HCF}(a,b)\times\operatorname{LCM}(a,b)$.
- To find HCF of large numbers, divide repeatedly: the last non-zero remainder is the HCF.
- Same remainder on division? The divisor must divide the **differences** between the numbers.
- Use HCF for the largest equal piece size; use LCM for events that happen together again.

## Choose your move

| Question clue | Use |
|---|---|
| Largest number dividing several values | HCF; use repeated remainders if values are large. |
| First time schedules match | LCM. |
| Same remainder for each number | HCF of their differences. |
| Two numbers, their HCF and LCM, one number missing | Product identity. |

## Five common question types

### 1. Find an HCF
**Question:** Find the HCF of 252 and 198.
- **Step by step:** $252=198+54$; $198=3(54)+36$; $54=36+18$; $36=2(18)$. The last non-zero remainder is 18.
- **Fast way:** Keep replacing the pair by (smaller number, remainder). **Answer: $18$.**

### 2. Find an LCM
**Question:** Find the LCM of 24 and 90.
- **Step by step:** $24=2^3\cdot3$; $90=2\cdot3^2\cdot5$. Keep the largest power of each prime: $2^3\cdot3^2\cdot5=360$.
- **Fast way:** HCF is 6, so LCM $=24\cdot90/6=360$. **Answer: $360$.**

### 3. Find a missing number
**Question:** HCF is 12, LCM is 720, and one number is 144. Find the other.
- **Step by step:** Product of the numbers $=12\cdot720=8640$. Then $8640/144=60$.
- **Fast way:** Apply $ab=\text{HCF}\times\text{LCM}$. **Answer: $60$.**

### 4. Same remainder
**Question:** Find the greatest number that divides 43, 91, and 183 leaving the same remainder.
- **Step by step:** Take differences: $48,92,140$. Their HCF is 4.
- **Fast way:** Equal remainders disappear on subtraction; find $\gcd(48,92,140)$. **Answer: $4$.**

### 5. Events happen together
**Question:** Alarms ring every 18 and 24 minutes. When will they next ring together?
- **Step by step:** The first common multiple of 18 and 24 is 72.
- **Fast way:** $18=2\cdot3^2$, $24=2^3\cdot3$; LCM $=2^3\cdot3^2=72$. **Answer: $72$ minutes.**

## What exams tend to test

- **SSC:** same-remainder puzzles and HCF/LCM word problems.
- **RRB:** bells, signals, and direct factorization.
- **APPSC / PSU:** Euclidean algorithm and conditions involving multiples.

## Watch for these

1. HCF uses smaller prime powers; LCM uses larger ones.
2. The product identity here is for two numbers, not three.
3. For equal remainders, find the HCF of differences, not original values.

## Quick check

1. Find the HCF of 48 and 72.

<details>
<summary>Show answer</summary>

$24$.
</details>

2. Find the LCM of 12 and 15.

<details>
<summary>Show answer</summary>

$60$.
</details>