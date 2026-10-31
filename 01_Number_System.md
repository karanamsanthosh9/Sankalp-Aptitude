# Number System

> Read this like a class, not like a formula list. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" boxes with a pen before reading the answer next to them.

## 0. Start here: what is this topic really about?

Think of the numbers you use every day — your phone number has digits, a price tag has a decimal, a recipe uses fractions, and a date uses integers. The Number System chapter is about understanding numbers deeply: what kind they are, how they are built, what divides them, and what happens to their last digits when you raise them to big powers.

Questions you will see in the exam look like these:

- "What is the unit digit of $7^{95}$?"
- "Find the largest number that divides 245, 1029 and 1365 leaving the same remainder."
- "How many trailing zeros does 30! have?"
- "Find a missing digit so that a number is divisible by 9."

**What the exam gives you:** a number, or an expression involving powers, or a condition about divisibility. **What it asks for:** a digit, a remainder, a count, or an unknown.

**How many marks to expect:** SSC CGL, CHSL, RRB NTPC, RRB Group D, IBPS and SBI exams typically carry 2 to 4 questions from Number System. APPSC and PSU papers can carry up to 5. It is one of the most formula-rich chapters, but once you know the patterns, the questions are fast.

## 1. The only ideas you must understand

### What kind of number is it?

Every number belongs to one or more families. Knowing the family tells you what rules apply.

- **Natural numbers:** 1, 2, 3, 4, … (counting numbers; zero is NOT included)
- **Whole numbers:** 0, 1, 2, 3, … (natural numbers plus zero)
- **Integers:** …, −3, −2, −1, 0, 1, 2, 3, … (includes negative numbers)
- **Rational numbers:** numbers that can be written as $\frac{p}{q}$ with $q \ne 0$ — like $\frac{3}{4}$, $0.5$, $−7$
- **Irrational numbers:** cannot be written as a fraction — like $\sqrt{2}$, $\pi$, $\sqrt{3}$
- **Prime numbers:** have exactly two factors: 1 and themselves — 2, 3, 5, 7, 11, 13, …
- **Composite numbers:** have more than two factors — 4, 6, 8, 9, 10, …
- **Note:** 1 is neither prime nor composite. 2 is the only even prime.

### Place value vs face value

In the number **5 3 7 8**, the digit 3 sits in the hundreds place.

- **Face value** of 3 is simply 3.
- **Place value** of 3 is $3 \times 100 = 300$.

Face value never changes. Place value depends on position.

### The VBODMAS order of operations

When a problem mixes brackets, powers, multiplication and addition, you must do them in this exact order:

**V**inculum (the bar above) → **B**rackets ( ) { } [ ] → **O**rders (powers, roots) → **D**ivision → **M**ultiplication → **A**ddition → **S**ubtraction

Work from the innermost bracket outward.

**Example:** $18 + [4 - \{6 - (2 + 3)\}]$

- Innermost: $2 + 3 = 5$
- Next: $6 - 5 = 1$
- Then: $4 - 1 = 3$
- Finally: $18 + 3 = \mathbf{21}$

**Sense check:** if your answer looks wildly large or negative when all numbers were positive, you probably did the order wrong.

### Divisibility rules (memorise these cold)

| Divisible by | Rule | Quick example |
|---|---|---|
| 2 | Last digit even | 1728: last digit 8, yes |
| 3 | Sum of digits divisible by 3 | 1728: $1+7+2+8=18$, yes |
| 4 | Last two digits divisible by 4 | 456: 56/4=14, yes |
| 5 | Last digit 0 or 5 | 1725: ends in 5, yes |
| 6 | Divisible by both 2 and 3 | 1728: even and digit-sum 18, yes |
| 7 | No simple rule; do the division | 1001/7=143, yes |
| 8 | Last three digits divisible by 8 | 1728: 728/8=91, yes |
| 9 | Sum of digits divisible by 9 | 1728: sum 18, yes |
| 10 | Last digit 0 | — |
| 11 | Alternate digit sum difference divisible by 11 | 1001: $(1+0)-(0+1)=0$, yes |
| 12 | Divisible by both 3 and 4 | — |
| 25 | Last two digits 00, 25, 50 or 75 | — |

**Your turn:** Is 1234 divisible by 11? (Answer: $1-2+3-4=-2$; $-2$ is not divisible by 11, so **no**.)

## 2. The shortcuts / tricks

### Unit digit trick

Only the last digit of the base matters; the rest of the number is irrelevant. Make the cycle of the last digit (for example, 7 → 7, 9, 3, 1), divide the power by the cycle length, and use the remainder to pick the position; if remainder is 0, use the last element of the cycle. Example: $7^{83}$ → cycle 7,9,3,1; $83 \div 4 = 20$ remainder 3 → unit digit is **3**.

| Unit digit | Cycle (powers 1,2,3,4,…) | Cycle length |
|---|---|---|
| 0 | 0, 0, 0, 0 | 1 |
| 1 | 1, 1, 1, 1 | 1 |
| 2 | 2, 4, 8, 6 | 4 |
| 3 | 3, 9, 7, 1 | 4 |
| 4 | 4, 6, 4, 6 | 2 |
| 5 | 5, 5, 5, 5 | 1 |
| 6 | 6, 6, 6, 6 | 1 |
| 7 | 7, 9, 3, 1 | 4 |
| 8 | 8, 4, 2, 6 | 4 |
| 9 | 9, 1, 9, 1 | 2 |

**How to use it:** divide the power by the cycle length. The remainder tells you which position in the cycle gives the answer. If the remainder is 0, use the last position (position 4).

**Example:** unit digit of $7^{83}$?
- Cycle of 7 is 7, 9, 3, 1 (length 4).
- $83 \div 4 = 20$ remainder $3$.
- Third in the cycle is **3**. Unit digit = **3**.

**Example:** unit digit of $2^{100}$?
- Cycle of 2 is 2, 4, 8, 6 (length 4).
- $100 \div 4 = 25$ remainder $0$ → use position 4.
- Fourth in cycle is **6**. Unit digit = **6**.

**Your turn:** unit digit of $3^{65}$? (Cycle of 3: 3,9,7,1; $65 \div 4 = 16$ r 1; position 1 = **3**.)

### Trailing zeros in $n!$

The number of zeros at the end of $n!$ equals the number of times 5 divides $n!$, because there are always enough 2s to pair with each 5.

$$\text{Trailing zeros} = \left\lfloor \frac{n}{5} \right\rfloor + \left\lfloor \frac{n}{25} \right\rfloor + \left\lfloor \frac{n}{125} \right\rfloor + \cdots$$

**Example:** trailing zeros in $30!$?
- $\lfloor 30/5 \rfloor = 6$
- $\lfloor 30/25 \rfloor = 1$
- Total = **7**.

**Your turn:** trailing zeros in $50!$? ($\lfloor 50/5 \rfloor + \lfloor 50/25 \rfloor = 10 + 2$ = **12**.)

### Number of factors

If $n = 2^a \times 3^b \times 5^c \times \cdots$, then the number of factors of $n$ is $(a+1)(b+1)(c+1)\cdots$

**Example:** factors of $72$?
- $72 = 2^3 \times 3^2$
- Factors $= (3+1)(2+1) = 4 \times 3$ = **12**.

### Remainder shortcut

To find the remainder of a big power, look for a pattern.

**Example:** remainder when $17^{100}$ is divided by 16.
- $17 = 16 + 1$, so $17 \equiv 1 \pmod{16}$.
- $17^{100} \equiv 1^{100}$ = **1**.

## 3. Types of questions and how to crack each one

### Type 1. Unit digit of a power

**How you spot it:** "Find the unit digit of $7^{95}$" or "what is the last digit of $(4137)^{754}$?"

**Think:** strip all digits except the last; find the cycle length; use remainder of (power / cycle length).

**Solved example:** unit digit of $7^{95}$.
- Base unit digit: 7. Cycle: 7, 9, 3, 1 (length 4).
- $95 \div 4 = 23$ r $3$.
- Position 3 in cycle: **3**.

**Solved example:** unit digit of $(4137)^{754}$.
- Unit digit of 4137 is 7. Same as above.
- $754 \div 4 = 188$ r $2$. Position 2: **9**.

**Exam twist:** a product like $17^{23} \times 13^{22}$. Find each unit digit separately, then multiply those and take the unit digit.
- $17^{23}$: unit 7, $23 \div 4 = 5$ r 3, position 3 → 3.
- $13^{22}$: unit 3, $22 \div 4 = 5$ r 2, position 2 → 9.
- Product unit digit: $3 \times 9 = 27$, unit digit = **7**.

**Your turn:** unit digit of $9^{100}$? (Cycle of 9: 9,1; $100 \div 2 = 50$ r 0, use position 2 = **1**.)

### Type 2. Missing digit in a divisibility problem

**How you spot it:** "Find the digit $k$ in $473k$ so that it is divisible by 9."

**Think:** for div by 9, sum of digits must be divisible by 9. For div by 3, same rule. For div by 11, alternate-difference rule.

**Solved example:** $473k$ divisible by 9.
- Sum so far: $4 + 7 + 3 + k = 14 + k$.
- We need $14 + k$ divisible by 9.
- $k = 4$ gives $18$, which is $9 \times 2$. So $k$ = **4**.
- Check: $4734 \div 9 = 526$. Correct.

**Solved example:** $4a752b$ divisible by both 4 and 3.
- Divisible by 4: the last two digits must be divisible by 4. All three possibilities work: $b=0$ gives 20, $b=4$ gives 24, and $b=8$ gives 28.
- Divisible by 3: the digit sum is $18+a+b$. For $b=0$, $a \in \{0,3,6,9\}$; for $b=4$, $a \in \{2,5,8\}$; for $b=8$, $a \in \{1,4,7\}$.
- **Answer:** the valid $(a,b)$ pairs are $(0,0),(3,0),(6,0),(9,0),(2,4),(5,4),(8,4),(1,8),(4,8),(7,8)$.

**Your turn:** find $k$ if $47k5$ is divisible by 9. (Sum: $4+7+k+5 = 16+k$; need $16+k$ divisible by 9; $k = 2$, giving $18$. **Answer: $k=2$**.)

### Type 3. Divisibility rule application

**How you spot it:** "Which of the following is divisible by 8?" or "Is 5176 divisible by 8?"

**Think:** apply the rule from the table above. For 8, check the last three digits.

**Solved example:** Is 5176 divisible by 8?
- Last three digits: 176.
- $176 \div 8 = 22$. Yes, exactly. So **5176 is divisible by 8**.

**Exam twist:** "Which number from the list is NOT divisible by 11?"
- Test each: alternating sum rule. For 1234: $1-2+3-4 = -2$. Not divisible by 11. **Answer: 1234.**

**Your turn:** Is 1001 divisible by 7, 11, and 13? (1001 = 7 × 11 × 13. So yes to all three. **Divisible by all three**.)

### Type 4. Trailing zeros in a factorial

**How you spot it:** "How many zeros are at the end of 25!" or "What is the highest power of 5 in 100!?"

**Think:** use $\lfloor n/5 \rfloor + \lfloor n/25 \rfloor + \lfloor n/125 \rfloor + \cdots$

**Solved example:** trailing zeros in $25!$.
- $\lfloor 25/5 \rfloor = 5$
- $\lfloor 25/25 \rfloor = 1$
- Total = **6**.

**Solved example:** trailing zeros in $100!$.
- $\lfloor 100/5 \rfloor = 20$
- $\lfloor 100/25 \rfloor = 4$
- Total = **24**.

**Your turn:** trailing zeros in $20!$? ($\lfloor 20/5 \rfloor = 4$, $\lfloor 20/25 \rfloor = 0$. **Answer: 4**.)

### Type 5. Number of factors / prime factorisation

**How you spot it:** "How many factors does 120 have?" or "Find the number of prime factors of $24^3 \times 36$."

**Think:** prime factorise, then apply the formula.

**Solved example:** factors of 120.
- $120 = 2^3 \times 3 \times 5$.
- Factors $= (3+1)(1+1)(1+1) = 4 \times 2 \times 2$ = **16**.

**Solved example:** factors of $24^3 \times 36$.
- $24 = 2^3 \times 3$, so $24^3 = 2^9 \times 3^3$.
- $36 = 2^2 \times 3^2$.
- Product $= 2^{11} \times 3^5$.
- Factors $= (11+1)(5+1) = 12 \times 6$ = **72**.

**Your turn:** how many factors does 100 have? ($100 = 2^2 \times 5^2$; factors $= 3 \times 3$ = **9**.)

### Type 6. Remainder when a power is divided

**How you spot it:** "Find the remainder when $3^{100}$ is divided by 4" or "what is $2^{50} \div 3$ remainder?"

**Think:** find the pattern. If $a \equiv r \pmod{m}$, then $a^n \equiv r^n \pmod{m}$.

**Solved example:** remainder of $3^{100} \div 4$.
- $3 \equiv -1 \pmod{4}$.
- $3^{100} \equiv (-1)^{100} = 1 \pmod{4}$.
- **Remainder = 1**.

**Solved example:** remainder of $2^{50} \div 3$.
- $2 \equiv 2 \pmod 3$. Cycle: $2^1 \equiv 2$, $2^2 \equiv 1$, $2^3 \equiv 2$, cycle of 2.
- $50$ is even, so $2^{50} \equiv 1 \pmod 3$. **Remainder = 1**.

**Your turn:** remainder when $17^3$ is divided by 16? ($17 \equiv 1 \pmod{16}$; $17^3 \equiv 1$. **Answer: 1**.)

### Type 7. Sum of natural numbers / series

**How you spot it:** "Find the sum $1 + 2 + \cdots + 50$" or "find $1^3 + 2^3 + \cdots + 10^3$."

**Think:** use the standard formulas:

$$\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$$

$$\sum_{k=1}^{n} k^2 = \frac{n(n+1)(2n+1)}{6}$$

$$\sum_{k=1}^{n} k^3 = \left[\frac{n(n+1)}{2}\right]^2$$

**Solved example:** $1 + 2 + \cdots + 100$.
- $\frac{100 \times 101}{2}$ = **5050**.

**Solved example:** $1^3 + 2^3 + \cdots + 10^3$.
- $\left[\frac{10 \times 11}{2}\right]^2 = 55^2$ = **3025**.

**Your turn:** $1^2 + 2^2 + \cdots + 10^2$? ($\frac{10 \times 11 \times 21}{6}$ = **385**.)

### Type 8. Finding a number from a clue about quotient and remainder

**How you spot it:** "A number when divided by 12 gives a quotient of 5 and remainder of 7. Find the number."

**Think:** $\text{Number} = \text{Divisor} \times \text{Quotient} + \text{Remainder}$.

**Solved example:** divisor 12, quotient 5, remainder 7.
- $N = 12 \times 5 + 7 = 60 + 7$ = **67**.
- Check: $67 \div 12 = 5$ remainder 7. Correct.

**Exam twist:** "A number exceeds its $\frac{3}{7}$ by 48." Let the number be $N$: $N - \frac{3N}{7} = 48 \Rightarrow \frac{4N}{7} = 48 \Rightarrow N = 84$.

**Your turn:** a number divided by 7 gives quotient 5 and remainder 3. Find the number. ($7 \times 5 + 3 = 38$. **Answer: 38**.)

### Type 9. Chinese Remainder / two simultaneous conditions

**How you spot it:** "Find the smallest number that leaves remainder 5 when divided by 7 and remainder 3 when divided by 4."

**Think:** write $N = 7a + 5$ and substitute into the second condition, or use trial from the first condition.

**Solved example:** $N \equiv 5 \pmod 7$ and $N \equiv 3 \pmod 4$.
- Numbers with remainder 5 from 7: 5, 12, 19, 26, 33, …
- Check each mod 4: $5 \div 4 = 1$ r 1; $12 \div 4 = 3$ r 0; $19 \div 4 = 4$ r 3. **$N = 19$**.
- Check: $19 \div 7 = 2$ r 5, $19 \div 4 = 4$ r 3. Correct.

**Your turn:** smallest $N$ such that $N$ leaves remainder 4 when divided by 5, and remainder 2 when divided by 3. (List rem-4-mod-5: 4, 9, 14, 19…; $14 \div 3 = 4$ r 2. **Answer: 14**.)

### Type 10. Numbers divisible by two conditions (LCM-type count)

**How you spot it:** "How many numbers from 1 to 200 are divisible by both 5 and 7?" or "divisible by 6 but not 9?"

**Think:** divisible by both 5 and 7 means divisible by $\text{LCM}(5,7)=35$. Use $\lfloor N/35 \rfloor$ to count.

**Solved example:** how many numbers from 1 to 200 are divisible by both 5 and 7?
- $\text{LCM}(5,7) = 35$.
- $\lfloor 200/35 \rfloor = 5$. **Answer: 5** (namely 35, 70, 105, 140, 175).

**Solved example:** numbers from 1 to 100 divisible by 6 but not 9.
- Divisible by 6: $\lfloor 100/6 \rfloor = 16$.
- Divisible by both 6 and 9 means divisible by $\text{LCM}(6,9) = 18$: $\lfloor 100/18 \rfloor = 5$.
- Answer: $16 - 5$ = **11**.

**Your turn:** how many numbers from 1 to 100 are divisible by 4 but not by 8? ($\lfloor 100/4 \rfloor = 25$; $\lfloor 100/8 \rfloor = 12$; $25-12$ = **13**.)

### Type 11. Face value and place value

**How you spot it:** "In 78564, find the difference between the place value of 8 and the face value of 8."

**Think:** face value = the digit itself; place value = digit × positional value.

**Solved example:** number 78564.
- 8 is in the thousands place.
- Place value $= 8 \times 1000 = 8000$.
- Face value $= 8$.
- Difference $= 8000 - 8$ = **7992**.

**Your turn:** in 5325, find the product of the place values of both 5s. (5 at thousands: $5000$; 5 at units: $5$; product = **25000**.)

### Type 12. Perfect squares and cubes range

**How you spot it:** "How many perfect squares lie between 100 and 500?"

**Think:** the perfect squares are $11^2, 12^2, \ldots$ Find how many.

**Solved example:** perfect squares from 1 to 500.
- $\sqrt{500} \approx 22.36$, so $22^2 = 484$ is the largest. There are **22** perfect squares.

**Solved example:** perfect squares strictly between 100 and 500.
- From $11^2 = 121$ to $22^2 = 484$: that is $22 - 11 + 1$ = **12** values.

**Your turn:** find the largest 3-digit perfect square. ($31^2 = 961$, $32^2 = 1024 > 999$. **Answer: 961**.)

### Type 13. Number equals a multiple of its digit-sum

**How you spot it:** "A 3-digit number is 17 times the sum of its digits. Find the number."

**Think:** let the number be $N = 100a + 10b + c$. Set up the equation $N = k \times (a+b+c)$.

**Solved example:** $N = 17(a+b+c)$.
- Try $a=1$: $100 + 10b + c = 17(1+b+c)$, so $83 - 7b - 16c = 0$. With $b=5, c=3$: $83 - 35 - 48 = 0$. Yes!
- $N = 153$. Check: $1+5+3=9$, $9 \times 17 = 153$. **Answer: 153**.

**Your turn:** $\frac{3}{7}$ of a number is 48. Find the number. ($N \times \frac{3}{7} = 48 \Rightarrow N = \frac{48 \times 7}{3}$ = **112**.)

### Type 14. Sum of all 2-digit (or n-digit) multiples of k

**How you spot it:** "Find the sum of all 2-digit multiples of 7."

**Think:** list first and last terms; count terms; use sum $= \frac{\text{count}}{2} \times (\text{first} + \text{last})$.

**Solved example:** sum of 2-digit multiples of 7.
- First: 14, Last: 98.
- Count: $(98-14)/7 + 1 = 84/7 + 1 = 12 + 1 = 13$.
- Sum $= \frac{13}{2} \times (14 + 98) = \frac{13 \times 112}{2} = 13 \times 56$ = **728**.

**Your turn:** sum of all 2-digit multiples of 9. (First: 18, last: 99; count: $(99-18)/9+1=10$; sum $= 10/2 \times 117$ = **585**.)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Unit digit of a power | Find the last digit of the base, note its cycle length, use (power mod cycle) to pick position |
| Divisibility check | Use the rule table: 2 last digit, 3 sum of digits, 4 last two digits, 8 last three digits, 9 sum, 11 alternating sum |
| Missing digit for divisibility | Form the sum or alternating sum, set equal to the nearest multiple of the divisor, solve for the digit |
| Trailing zeros in $n!$ | $\lfloor n/5 \rfloor + \lfloor n/25 \rfloor + \lfloor n/125 \rfloor + \cdots$ |
| Number of factors | Prime factorise as $p^a q^b \cdots$, then $(a+1)(b+1)\cdots$ |
| Remainder of a power | Reduce the base mod the divisor, find the cycle, use power mod cycle length |
| Sum of series | Use formula: $n(n+1)/2$ or $n(n+1)(2n+1)/6$ or $[n(n+1)/2]^2$ |
| Quotient-remainder clue | $N = D \times q + r$ |
| Two remainder conditions | Write $N = D_1 a + r_1$, trial-and-error or algebra to satisfy second condition |
| Count multiples in range | $\lfloor \text{max}/k \rfloor - \lfloor (\text{min}-1)/k \rfloor$ |
| Face/place value difference | Place value $= \text{digit} \times$ positional power; face value = digit itself |

### Squares to memorise

$1^2=1,\ 2^2=4,\ 3^2=9,\ 4^2=16,\ 5^2=25,\ 6^2=36,\ 7^2=49,\ 8^2=64,\ 9^2=81,\ 10^2=100$

$11^2=121,\ 12^2=144,\ 13^2=169,\ 14^2=196,\ 15^2=225,\ 16^2=256,\ 17^2=289,\ 18^2=324,\ 19^2=361,\ 20^2=400$

$21^2=441,\ 22^2=484,\ 23^2=529,\ 24^2=576,\ 25^2=625,\ 30^2=900$

### Cubes to memorise

$1^3=1,\ 2^3=8,\ 3^3=27,\ 4^3=64,\ 5^3=125,\ 6^3=216,\ 7^3=343,\ 8^3=512,\ 9^3=729,\ 10^3=1000$

$11^3=1331,\ 12^3=1728,\ 13^3=2197,\ 14^3=2744,\ 15^3=3375$

## 5. Mistakes that cost marks

1. **Confusing face value and place value.** Face value of 5 is always 5. Place value depends on position.
2. **Forgetting 1 is neither prime nor composite.** Many MCQs test this directly.
3. **Treating 0 as a natural number.** Natural numbers start at 1. Whole numbers include 0.
4. **Wrong cycle position when remainder is 0.** When power $\div$ cycle length gives remainder 0, use the last position in the cycle (position = cycle length), not position 0.
5. **Summing times in trailing zero formula.** Add $\lfloor n/5 \rfloor + \lfloor n/25 \rfloor + \cdots$ — do not multiply or stop at the first term.
6. **Applying divisibility rule 3 to check div by 9.** For 9, the digit sum must itself be divisible by 9, not just 3.
7. **Forgetting 2 is the only even prime.** Questions like "which prime is even?" directly target this.

## 6. Practice questions

Do these on paper. Do the first 10 untimed. Do the next 15 with 90 seconds each. Do the last 15 like an exam.

### Level 1: single idea

1. What is the unit digit of $7^{95}$?
2. What is the unit digit of $3^{84}$?
3. What is the unit digit of $17^{23} \times 13^{22}$?
4. Is 5176 divisible by 8?
5. Which of the following is NOT divisible by 11: 121, 1331, 14641, 1234?
6. How many trailing zeros does 30! have?
7. Find the largest 4-digit number exactly divisible by 88.
8. Find the sum of the digits of $99^2$.
9. How many factors does $24^3 \times 36$ have?
10. Find the remainder when $2^{50}$ is divided by 3.

### Level 2: mixed

11. Find the unit digit of $(4137)^{754}$.
12. Find $k$ if $473k$ is divisible by 9.
13. Find the smallest number between 200 and 300 that leaves remainder 6 when divided by 8 and remainder 4 when divided by 6.
14. Find the sum of all 2-digit multiples of 7.
15. Find the remainder when $3^{100}$ is divided by 4.
16. A number when divided by 7 gives quotient 5 and remainder 3. Find the number.
17. How many numbers from 1 to 200 are divisible by both 5 and 7?
18. In 5325, find the product of the place values of both 5s.
19. Find the smallest 3-digit number that leaves remainder 1 when divided by each of 3, 4, and 5.
20. Find the unit digit of $(4137)^{754}$ when multiplied by the unit digit of $9^{100}$.

### Level 3: exam style

21. Find the largest 3-digit perfect square.
22. How many perfect squares lie strictly between 100 and 500?
23. A 3-digit number equals 17 times the sum of its digits. Find the number.
24. Find the value of $\frac{3}{7}$ of a number if the number is 112.
25. Find the remainder when $17^3$ is divided by 16.
26. A number when divided by 12 gives quotient 5, remainder 7. Another number when divided by 8 gives quotient 9, remainder 3. Find their sum.
27. What is the unit digit of $9^{100}$?
28. Find the smallest number which when divided by 3, 7, and 9 leaves remainder 1 each time.
29. How many numbers from 1 to 100 are divisible by 6 but not by 9?
30. In 78564, find the difference between the place value and face value of 8.
31. Find the sum $1^2 + 2^2 + \cdots + 10^2$.
32. Find the sum $1^3 + 2^3 + \cdots + 10^3$.
33. $\sqrt{2}$, $\sqrt{3}$, $\sqrt{5}$ are irrational. Which of the following is rational: $\sqrt{4}$, $\sqrt{5}$, $\sqrt{6}$, $\sqrt{7}$?
34. Find three consecutive even numbers whose sum is 162.
35. Find $k$ if $47k5$ is divisible by 9.
36. How many trailing zeros does 50! have?
37. Find the remainder when $7^{100}$ is divided by 100. (Hint: $7^4 \equiv 1 \pmod{100}$.)
38. The sum of all 2-digit multiples of 9.
39. Find the number of natural numbers from 1 to 100 that are divisible by 4 but not 8.
40. Find the largest 4-digit number exactly divisible by 7.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | 3 | Cycle of 7: 7,9,3,1; $95 \div 4 = 23$ r 3; position 3 |
| 2 | 1 | Cycle of 3: 3,9,7,1; $84 \div 4 = 21$ r 0; position 4 |
| 3 | 7 | $17^{23}$: unit 7, r 3 → 3; $13^{22}$: unit 3, r 2 → 9; $3 \times 9 = 27$, unit 7 |
| 4 | Yes | $176 \div 8 = 22$, no remainder |
| 5 | 1234 | $1 - 2 + 3 - 4 = -2$; not divisible by 11 |
| 6 | 7 | $\lfloor 30/5 \rfloor + \lfloor 30/25 \rfloor = 6+1$ |
| 7 | 9944 | $\lfloor 9999/88 \rfloor = 113$; $113 \times 88$ |
| 8 | 18 | $99^2 = 9801$; $9+8+0+1$ |
| 9 | 72 | $24^3 \times 36 = 2^{11} \times 3^5$; $(11+1)(5+1)$ |
| 10 | 1 | $2^{50}$: 50 even, $2^{even} \equiv 1 \pmod 3$ |
| 11 | 9 | Unit 7, $754 \div 4 = 188$ r 2, position 2 in cycle of 7 |
| 12 | 4 | $4+7+3+k = 14+k$; need $18$; $k = 4$ |
| 13 | 214 | $214 \div 8 = 26$ r 6; $214 \div 6 = 35$ r 4 |
| 14 | 728 | First 14, last 98, 13 terms; $13 \times 56$ |
| 15 | 1 | $3 \equiv -1 \pmod 4$; $(-1)^{100} = 1$ |
| 16 | 38 | $7 \times 5 + 3$ |
| 17 | 5 | $\text{LCM}(5,7)=35$; $\lfloor 200/35 \rfloor = 5$ |
| 18 | 25000 | $5000 \times 5$ (thousands place × units place) |
| 19 | 121 | $\text{LCM}(3,4,5)=60$; $60k+1$; first 3-digit: $60 \times 2+1$ |
| 20 | 9 | Unit digit of $(4137)^{754}$ is 9; unit digit of $9^{100}$ is 1; $9 \times 1 = 9$ |
| 21 | 961 | $31^2 = 961 \le 999 < 1024 = 32^2$ |
| 22 | 12 | $11^2=121$ to $22^2=484$; count = $22-11+1$ |
| 23 | 153 | $153 = 17 \times 9$; digit sum = $1+5+3=9$ |
| 24 | 48 | $\frac{3}{7} \times 112 = 48$ |
| 25 | 1 | $17 \equiv 1 \pmod{16}$; $1^3 = 1$ |
| 26 | 142 | $12 \times 5+7 = 67$; $8 \times 9+3 = 75$; $67+75=142$ |
| 27 | 1 | Cycle of 9 is 9,1 (length 2); $100 \div 2 = 50$ r 0; position 2 = 1 |
| 28 | 64 | $\text{LCM}(3,7,9)=63$; $63+1$ |
| 29 | 11 | Div by 6: 16; div by $\text{LCM}(6,9)=18$: 5; $16-5$ |
| 30 | 7992 | Place value $= 8000$; face value $= 8$; $8000-8$ |
| 31 | 385 | $\frac{10 \times 11 \times 21}{6}$ |
| 32 | 3025 | $\left[\frac{10 \times 11}{2}\right]^2 = 55^2$ |
| 33 | $\sqrt{4}$ | $\sqrt{4}=2$, a whole number and rational |
| 34 | 52, 54, 56 | $3N+6=162 \Rightarrow N=52$ |
| 35 | 2 | $4+7+k+5=16+k$; need $18$; $k=2$ |
| 36 | 12 | $\lfloor 50/5 \rfloor + \lfloor 50/25 \rfloor = 10+2$ |
| 37 | 1 | $7^4 \equiv 1 \pmod{100}$; $100 \div 4 = 25$ r 0; $1^{25}=1$ |
| 38 | 585 | First 18, last 99; 10 terms; $10/2 \times 117$ |
| 39 | 13 | $\lfloor 100/4 \rfloor - \lfloor 100/8 \rfloor = 25-12$ |
| 40 | 9996 | $\lfloor 9999/7 \rfloor = 1428$; $1428 \times 7$ |
