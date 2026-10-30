# HCF & LCM

> **HCF = biggest shared divisor. LCM = first shared multiple.**

## ⚡ Formula cards

| Find... | Prime-factor rule |
|---|---|
| HCF | **Shared primes; take the smaller powers** |
| LCM | **Every prime; take the larger powers** |
| HCF and LCM of two numbers | **$\text{HCF}(a,b)\text{LCM}(a,b)=ab$** |
| Same remainder | **$\text{HCF}(\text{pairwise differences})$** |

> **Memory cue:** HCF stays *inside* what both numbers share; LCM stretches to cover them both.

```text
HCF:  24 = 2³ × 3       36 = 2² × 3²
      └─ smaller powers ─┘
      HCF = 2² × 3 = 12

LCM:  └──── larger powers ────┘
      LCM = 2³ × 3² = 72
```

## Exam shortcut playbook

| If you spot... | Shortcut |
|---|---|
| Large numbers for HCF | Use Euclid: replace $(a,b)$ with $(b,\text{remainder})$ until remainder is 0. |
| Small numbers | Prime-factorize; HCF uses minimum powers and LCM uses maximum powers. |
| Same remainder on division | Subtract the numbers first; find the HCF of their differences. |
| Two numbers and their HCF | Use $\text{LCM}=ab/\text{HCF}$ instead of listing multiples. |
| “Together again” or repeating schedules | Choose LCM; for largest equal pieces, choose HCF. |

## Ten worked examples

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

### 6. Cut equal-length pieces
**Question:** What is the greatest length of identical pieces that can be cut from ribbons 84 cm and 126 cm long?
- **Step by step:** The piece length must divide both ribbon lengths.
- **Calculation:** $\text{HCF}(84,126)=42$. **Answer: $42$ cm.**

### 7. Find a shared schedule
**Question:** Two lights flash every 14 and 20 seconds. When do they flash together again?
- **Step by step:** Find the least common multiple of their intervals.
- **Calculation:** $14=2\cdot7$, $20=2^2\cdot5$, so $\text{LCM}=2^2\cdot5\cdot7=140$. **Answer: $140$ seconds.**

### 8. Find HCF using remainders
**Question:** Find the HCF of 867 and 255.
- **Shortcut:** $867=3(255)+102$; $255=2(102)+51$; $102=2(51)$.
- **Answer:** The last non-zero remainder is **51**.

### 9. Find LCM without listing multiples
**Question:** Find the LCM of 36 and 84.
- **Shortcut:** HCF is 12, so $\text{LCM}=36(84)/12$.
- **Calculation:** $3(84)$. **Answer: $252$.**

### 10. Find the greatest divisor leaving the same remainder
**Question:** Find the greatest number that divides 122, 182, and 242 leaving the same remainder.
- **Shortcut:** Take differences: $60$ and $120$; their HCF is 60.
- **Check:** Each number leaves remainder 2 on division by 60. **Answer: $60$.**
