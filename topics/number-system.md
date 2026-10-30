# Number System

**The idea:** A number question usually asks you to spot a property: divisibility, factors, a remainder, or a repeating pattern.

## The essentials

- **Prime:** exactly two positive factors. $2$ is the only even prime.
- **Division rule:** dividend $=$ divisor $\times$ quotient $+$ remainder. The remainder is always smaller than the divisor.
- **Fast divisibility:** digit sum tests $3$ and $9$; last 2 digits test $4$; last 3 digits test $8$; alternating digit sum tests $11$.
- **Factor count:** if $N=p^a q^b$, number of positive factors $=(a+1)(b+1)$.
- **Trailing zeros in $n!$:** add $\lfloor n/5\rfloor+\lfloor n/25\rfloor+\lfloor n/125\rfloor+\cdots$. Each division counts another layer of fives.
- **For two numbers:** product $=$ HCF $\times$ LCM.

## Choose your move

| The question asks for... | Start with... |
|---|---|
| A missing digit | Apply each divisibility test separately. |
| A huge power's remainder | Find the repeating remainder cycle. |
| The last digit | Track only unit digits; most cycles have length 4. |
| Number of factors | Prime-factorize, then add 1 to each exponent and multiply. |
| Zeros at the end of a factorial | Count factors of 5, including extra 5s from 25, 125, etc. |

## Five common question types

### 1. Find a missing digit
**Question:** Find $x$ if $47x2$ is divisible by both 4 and 9.
- **Step by step:** For 9, digit sum $13+x$ must be a multiple of 9, so $x=5$. Check the last two digits: 52 is divisible by 4.
- **Fast check:** Test the digit-sum condition first; it gives the only candidate. **Answer: $5$.**

### 2. Find a large-power remainder
**Question:** Find the remainder when $7^{103}$ is divided by 5.
- **Step by step:** Remainders of powers of 7 are $2,4,3,1$, then repeat. Since $103=4(25)+3$, use the third remainder: 3.
- **Fast way:** $7^4$ leaves remainder 1, so reduce the exponent to $7^3$. **Answer: $3$.**

### 3. Find a unit digit
**Question:** Find the last digit of $3^{2025}\times7^{2024}$.
- **Step by step:** Powers of 3 cycle $3,9,7,1$; exponent 2025 gives 3. Powers of 7 end in 1 when the exponent is a multiple of 4.
- **Fast way:** $2025\bmod4=1$ and $2024\bmod4=0$. Multiply the cycle digits: $3\times1$. **Answer: $3$.**

### 4. Count factors
**Question:** How many positive factors does 360 have?
- **Step by step:** $360=2^3\cdot3^2\cdot5$. A factor may choose exponents $0$–$3$, $0$–$2$, and $0$–$1$.
- **Fast way:** $(3+1)(2+1)(1+1)=24$. **Answer: $24$.**

### 5. Count factorial zeros
**Question:** How many zeros are at the end of $100!$?
- **Step by step:** Each zero needs a 2 and a 5; 2s are plentiful, so count 5s. Multiples of 5 give 20 fives; multiples of 25 give 4 extra.
- **Fast way:** $\lfloor100/5\rfloor+\lfloor100/25\rfloor=24$. **Answer: $24$.**

## What exams tend to test

- **SSC:** missing digits, combined divisibility, remainders, and algebraic conditions on integers.
- **RRB:** direct divisibility, factor counts, unit digits, and HCF/LCM.
- **APPSC / PSU:** prime factors, factorial zeros, and number-property puzzles.

## Watch for these

1. Digit sum tests 3 or 9; it does not test divisibility by 7 or 13.
2. In a power cycle, exponent remainder 0 means the final cycle entry.
3. For factorial zeros, count multiples of 25, 125, and higher powers too.

## Quick check

1. How many factors does $72=2^3\cdot3^2$ have?

<details>
<summary>Show answer</summary>

$(3+1)(2+1)=12$.
</details>

2. Find the remainder when $2^6$ is divided by 5.

<details>
<summary>Show answer</summary>

$4$: $2^4$ leaves remainder 1, so $2^6$ leaves the same remainder as $2^2$.
</details>