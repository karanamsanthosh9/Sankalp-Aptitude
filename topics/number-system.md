# Number System

High-yield study notes for SSC CGL/CHSL, RRB NTPC/Group D/JE, APPSC, and PSU exams.

## 1. Core Concept & Fundamental Equations

- **Natural numbers:** $1,2,3,\ldots$; **whole numbers:** $0,1,2,\ldots$; **integers:** positive numbers, negative numbers, and zero.
- **Prime number:** has exactly two positive factors. The only even prime is $2$.
- **Euclidean division:** $N=dq+r$, where $0\le r<d$. The remainder is central to divisibility and modular arithmetic.
- **Digit tests:** digit sum determines divisibility by $3$ or $9$. The alternating digit sum determines divisibility by $11$.
- **Divisibility rules:** $2$ (last digit even); $3$ or $9$ (digit sum divisible by $3$ or $9); $4$ (last two digits); $8$ (last three digits); $5$ (last digit $0$ or $5); $10$ (last digit $0$); $11$ (alternating digit-sum difference is $0$ or a multiple of $11$).
- **Prime factorization:** if $N=p^a q^b r^c$, its number of positive divisors is $(a+1)(b+1)(c+1)$.
- **HCF-LCM identity:** for positive integers $a,b$, $ab=\operatorname{HCF}(a,b)\operatorname{LCM}(a,b)$.
- **Trailing zeros in $n!$:** $\lfloor n/5\rfloor+\lfloor n/25\rfloor+\lfloor n/125\rfloor+\cdots$.
- **Remainders:** reduce values modulo the divisor before calculating. For powers, identify the repeating remainder cycle.
- **Useful fraction conversions:** $1/2=50\%$, $1/3=33\frac13\%$, $1/4=25\%$, $1/8=12.5\%$, and $1/16=6.25\%$.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Divisibility rules | A missing digit or quick divisibility check is involved. | The divisor has no simple rule; use modular arithmetic or factorization. |
| Digital sum / casting out 9s | Checking arithmetic or divisibility by $9$. | Finding an exact remainder for another divisor; digit sum alone is insufficient. |
| Modular reduction | Large numbers or powers are reduced by a small divisor. | The remainder cycle has not been established. |
| Prime factorization | Counting factors, finding HCF/LCM, or checking divisibility. | A quick multiple check is enough. |
| Unit-digit cycles | Finding the last digit of large powers. | More than the last digit is required. |
| Option elimination | Options differ by parity, digit sum, or remainder. | Options share those properties; finish the calculation. |

**Rule:** distinguish carefully between a remainder, a unit digit, a factor count, and a greatest or least integer.

## 3. Model-Wise Question Classification

### Model 1: Missing digit and divisibility

**Problem:** Find digit $x$ if $47x2$ is divisible by both $4$ and $9$.

- **Method A (standard):** Divisibility by $4$ requires $x2$ to be divisible by $4$, so $x$ is odd. Divisibility by $9$ requires $4+7+x+2=13+x$ to be a multiple of $9$. Therefore $x=5$.
- **Method B (shortcut):** The digit sum forces $x=5$. Check the last two digits, $52$, are divisible by $4$. **Answer: $5$.**

### Model 2: Remainder of a large power

**Problem:** Find the remainder when $7^{103}$ is divided by $5$.

- **Method A (standard):** $7\equiv2\pmod5$. Powers of $2$ cycle modulo $5$ as $2,4,3,1$. Since $103=4(25)+3$, use the third cycle value: $3$.
- **Method B (shortcut):** $7^4\equiv1\pmod5$, so $7^{103}=7^{4(25)+3}\equiv7^3\equiv2^3\equiv3\pmod5$. **Answer: $3$.**

### Model 3: Unit digit of a product of powers

**Problem:** Find the unit digit of $3^{2025}\times7^{2024}$.

- **Method A (standard):** Powers of $3$ have unit-digit cycle $3,9,7,1$; exponent $2025$ gives $3$. Powers of $7$ cycle $7,9,3,1$; exponent $2024$ gives $1$. Product unit digit: $3$.
- **Method B (shortcut):** Both cycles have length $4$. Since $2025\equiv1\pmod4$ and $2024\equiv0\pmod4$, the unit digits are $3$ and $1$. **Answer: $3$.**

### Model 4: Number of positive factors

**Problem:** How many positive factors does $360$ have?

- **Method A (standard):** $360=2^3\cdot3^2\cdot5^1$. Choose each prime's exponent independently: $4\cdot3\cdot2=24$ factors.
- **Method B (shortcut):** Apply the divisor-count formula: $(3+1)(2+1)(1+1)=24$. **Answer: $24$.**

### Model 5: HCF and LCM

**Problem:** Two positive integers have HCF $12$ and LCM $720$. If one number is $144$, find the other.

- **Method A (standard):** Their product is $12\cdot720=8640$. The other number is $8640/144=60$.
- **Method B (shortcut):** Use $ab=\operatorname{HCF}\cdot\operatorname{LCM}$ and divide by the known number: $12\cdot720/144=60$. Check: $\gcd(144,60)=12$. **Answer: $60$.**

### Model 6: Trailing zeros in a factorial

**Problem:** Find the number of trailing zeros in $100!$.

- **Method A (standard):** Each zero needs a factor pair $(2,5)$. There are excess factors of $2$, so count factors of $5$: $20+4=24$.
- **Method B (shortcut):** $\lfloor100/5\rfloor+\lfloor100/25\rfloor=20+4=24$. **Answer: $24$.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Missing digits, divisibility by combined factors, cyclic remainders, and algebraic conditions on integers. For divisibility by $12$, check both $3$ and $4$.
- **RRB lens:** Quick divisibility checks, HCF/LCM, unit digits, and direct remainder calculations. Large exponents become manageable once the cycle length is known.
- **AP State / PSU lens:** Prime factorization, divisor counts, HCF/LCM applications, factorial zeros, and integer-property questions; some blend these with simple algebra.

## 5. Common Traps & Speed Killers

1. **Using digit sum for the wrong divisor:** It tests divisibility by $3$ or $9$, not by $7$ or $13$. Use modular reduction for other divisors.
2. **Off-by-one in a power cycle:** An exponent remainder of $0$ means the last cycle position, not the first. Label cycle positions from exponent $1$.
3. **Missing repeated prime factors:** Multiples of $25$ contribute an extra factor of $5$ in factorial-zero questions. Keep dividing by $5$ and add every quotient.

## 6. Quick Check

1. What digit makes $6x3$ divisible by $9$?

<details>
<summary>Reveal answer</summary>

$x=0$: the digit sum is $9$.
</details>

2. How many positive factors does $72=2^3\cdot3^2$ have?

<details>
<summary>Reveal answer</summary>

$(3+1)(2+1)=12$ factors.
</details>