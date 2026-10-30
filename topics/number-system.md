# Number System

> **LOOK FOR:** divisibility → factors → cycles → remainders.

## ⚡ Formula cards

| Find... | Formula / rule |
|---|---|
| Dividend | **$\text{divisor}\times\text{quotient}+\text{remainder}$** |
| Factors of $N=p^a q^b$ | **$(a+1)(b+1)$** |
| Trailing zeros in $n!$ | **$\lfloor n/5\rfloor+\lfloor n/25\rfloor+\lfloor n/125\rfloor+\cdots$** |
| HCF and LCM | **$\text{HCF}(a,b)\text{LCM}(a,b)=ab$** |

> **Remainder check:** The remainder must always be smaller than the divisor.

```text
Huge power? ──> find cycle ──> exponent ÷ cycle length
                                  │
                                  └─ remainder picks the answer
```

## Exam shortcut playbook

| If you spot... | Shortcut |
|---|---|
| Divisibility by 3 or 9 | Add digits; test the digit sum. |
| Divisibility by 4 or 8 | Check only the last 2 or 3 digits. |
| Divisibility by 11 | Take the alternating digit-sum difference. |
| A large exponent | Find the repeating remainder/unit-digit cycle; reduce the exponent modulo the cycle length. |
| Number of factors | Prime-factorize, add 1 to each exponent, then multiply. |
| Zeros at the end of $n!$ | Count 5s, including extra 5s from 25, 125, and higher powers. |

## Ten worked examples

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

### 6. Test divisibility by 11
**Question:** Is 5,060 divisible by 11?
- **Step by step:** Find the difference between alternating digit sums: $(5+6)-(0+0)=11$.
- **Rule:** A multiple of 11 has an alternating-sum difference divisible by 11. **Answer: Yes; $5060\div11=460$.**

### 7. Find the last digit of a power
**Question:** Find the last digit of $8^{23}$.
- **Step by step:** Powers of 8 cycle through last digits 8, 4, 2, 6. Since $23$ leaves remainder 3 when divided by 4, use the third digit.
- **Answer:** The last digit is $2$.

### 8. Test divisibility by 9
**Question:** Is 73,845 divisible by 9?
- **Shortcut:** Add the digits: $7+3+8+4+5=27$.
- **Rule:** 27 is divisible by 9, so **73,845 is divisible by 9**.

### 9. Find the last digit of a product
**Question:** Find the last digit of $7^{202}+3^{101}$.
- **Shortcut:** Both unit-digit cycles have length 4. $202\bmod4=2$ gives 9; $101\bmod4=1$ gives 3.
- **Calculation:** Last digit of $9+3$ is **2**.

### 10. Count zeros in a factorial
**Question:** How many trailing zeros does $125!$ have?
- **Shortcut:** Count all factors of 5: $\lfloor125/5\rfloor+\lfloor125/25\rfloor+\lfloor125/125\rfloor$.
- **Calculation:** $25+5+1$. **Answer: $31$.**
