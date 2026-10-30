# HCF & LCM

## 1. Core Concept & Fundamental Equations

- **HCF/GCD:** greatest positive integer dividing every given number. **LCM:** least positive common multiple.
- For two positive integers, $ab=\operatorname{HCF}(a,b)\operatorname{LCM}(a,b)$.
- In prime factorization, HCF takes the **minimum** exponent of each shared prime; LCM takes the **maximum** exponent.
- Euclidean algorithm: $\gcd(a,b)=\gcd(b,a\bmod b)$, repeated until remainder $0$.
- For fractions in lowest terms: HCF $=\frac{\text{HCF of numerators}}{\text{LCM of denominators}}$; LCM $=\frac{\text{LCM of numerators}}{\text{HCF of denominators}}$.
- For a fixed distance, the largest equal piece length is the HCF of the measurements. For repeating events, first common time is their LCM.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Prime-exponent comparison | Numbers factor cleanly. | Factorization is cumbersome; use Euclid for HCF. |
| Euclidean algorithm | Large integers need an HCF. | You need an LCM only and factorization is already known. |
| Product identity | Two numbers, HCF, LCM, and one number are related. | More than two values are involved; the identity does not generalize directly. |
| Remainder conditions | Find a number leaving the same remainder on division. | Remainders differ; translate each condition separately. |
| HCF of lengths | Largest equal segment or tile size. | Minimum tile count or constrained shapes introduce geometry restrictions. |

## 3. Model-Wise Question Classification

### Model 1: HCF by Euclidean algorithm
**Problem:** Find the HCF of $252$ and $198$.
- **Method A:** $252=198+54$, $198=3(54)+36$, $54=36+18$, $36=2(18)$. HCF is $18$.
- **Method B:** Apply repeated remainders: $252\bmod198=54$, $198\bmod54=36$, $54\bmod36=18$, $36\bmod18=0$. **Answer: $18$.**

### Model 2: LCM using prime factors
**Problem:** Find the LCM of $24$ and $90$.
- **Method A:** $24=2^3\cdot3$, $90=2\cdot3^2\cdot5$; take maximum powers: $2^3\cdot3^2\cdot5=360$.
- **Method B:** HCF is $6$, so LCM $=24\cdot90/6=360$. **Answer: $360$.**

### Model 3: Recover a number from HCF and LCM
**Problem:** HCF is $12$, LCM is $720$, and one number is $144$. Find the other.
- **Method A:** Product is $12\cdot720=8640$; divide by $144$ to get $60$.
- **Method B:** Use $ab=\text{HCF}\times\text{LCM}$: $b=12\cdot720/144=60$. **Answer: $60$.**

### Model 4: Same remainder on division
**Problem:** Find the greatest number that divides $43, 91,$ and $183$, leaving the same remainder each time.
- **Method A:** Subtract pairwise: $91-43=48$, $183-91=92$, $183-43=140$. Find $\gcd(48,92,140)=4$.
- **Method B:** A common divisor with equal remainders divides every difference. $\gcd(48,92,140)=4$. **Answer: $4$.**

### Model 5: Repeating events
**Problem:** Two alarms ring every $18$ and $24$ minutes. If they ring together now, when will they next ring together?
- **Method A:** List common multiples; the first common positive multiple is $72$ minutes.
- **Method B:** $\operatorname{LCM}(18,24)=2^3\cdot3^2=72$. **Answer: $72$ minutes.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** HCF/LCM word problems, same-remainder conditions, and fraction-based HCF/LCM.
- **RRB lens:** Bells, traffic signals, periodic schedules, and direct factorization questions.
- **AP State / PSU lens:** Euclidean algorithm, least common schedules, and constraints involving multiples or remainders.

## 5. Common Traps & Speed Killers

1. **Using the product identity for three or more numbers:** it is stated here for two integers only.
2. **Taking the wrong prime exponent:** HCF uses minimum powers; LCM uses maximum powers.
3. **For same remainder, taking the HCF of original numbers:** use differences between the numbers.

## 6. Quick Check

1. Find the HCF of $48$ and $72$.

<details>
<summary>Reveal answer</summary>

$24$.
</details>

2. Find the LCM of $12$ and $15$.

<details>
<summary>Reveal answer</summary>

$60$.
</details>