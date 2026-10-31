# Simplification and Approximation

> Read this like a class, not like a formula list. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" boxes with a pen before reading the answer next to them.

## 0. Start here: what is this topic really about?

You see a question like this in the exam:

$$5.9^3 + 3.1^3 + 3 \times 5.9 \times 3.1 \times (5.9 + 3.1) = ?$$

That looks terrifying. But if you recognise that $a^3 + b^3 + 3ab(a+b) = (a+b)^3$, the whole thing collapses to $9^3 = 729$ in two seconds.

That is what this chapter is about: **seeing through the surface of a calculation to the pattern underneath**, and then either simplifying it exactly or approximating it fast.

There are two kinds of questions:
- **Simplification:** find the exact answer by applying VBODMAS, algebraic identities, laws of indices, or fraction rules.
- **Approximation:** round numbers to the nearest clean value, calculate that instead, and pick the closest option.

**What the exam gives you:** an expression involving brackets, fractions, decimals, powers, roots, or percentages — or a statement like "approximate to the nearest whole number." **What it asks for:** a number, or which option is closest.

**How many marks to expect:** SSC CGL and CHSL carry 3 to 5 questions from this chapter. RRB NTPC carries 2 to 3. IBPS and SBI PO and Clerk carry 3 to 5 approximation questions in a separate set. APPSC and PSU papers carry 2 to 4. These are among the quickest marks in any paper once you have practised the patterns.

## 1. The only ideas you must understand

### VBODMAS: the order of operations

You must do operations in this exact sequence — no exceptions:

**V**inculum (bar above an expression) → **B**rackets in order ( ) then { } then [ ] → **O**rders (powers and roots) → **D**ivision → **M**ultiplication → **A**ddition → **S**ubtraction

Work from the **innermost bracket outward**, and within the same level, left to right.

**Example:** $225 - [48 - \{36 - (18 - 6)\}]$
- Innermost ( ): $18 - 6 = 12$
- Next { }: $36 - 12 = 24$
- Next [ ]: $48 - 24 = 24$
- Final: $225 - 24 = \mathbf{201}$

**Sense check:** after you open a bracket, the sign in front of it flips the signs of everything inside if the sign is a minus. $-\{x - y\} = -x + y$.

### Laws of indices (powers and roots)

These six laws cover every indices question:

| Law | Meaning | Example |
|---|---|---|
| $a^m \times a^n = a^{m+n}$ | Same base, multiply → add powers | $2^3 \times 2^4 = 2^7$ |
| $a^m \div a^n = a^{m-n}$ | Same base, divide → subtract powers | $5^7 \div 5^3 = 5^4$ |
| $(a^m)^n = a^{mn}$ | Power of a power → multiply | $(2^3)^4 = 2^{12}$ |
| $(ab)^n = a^n b^n$ | Power over a product | $(2 \times 3)^4 = 2^4 \times 3^4$ |
| $a^0 = 1$ | Any non-zero base to zero power | $7^0 = 1$ |
| $a^{-n} = \frac{1}{a^n}$ | Negative power = reciprocal | $2^{-3} = \frac{1}{8}$ |

Also: $a^{1/n} = \sqrt[n]{a}$ and $a^{m/n} = \sqrt[n]{a^m}$.

**Example:** simplify $\dfrac{4^5 \times 8^3}{16^4}$.

Convert everything to powers of 2: $\dfrac{2^{10} \times 2^9}{2^{16}} = 2^{10+9-16} = 2^3 = \mathbf{8}$.

**Sense check:** if your final result has a huge number like $2^{100}$, you probably missed a cancellation.

### Algebraic identities

Memorise these — they are the heart of simplification questions:

| Identity | Used when you see |
|---|---|
| $(a+b)^2 = a^2 + 2ab + b^2$ | A squared bracket sum |
| $(a-b)^2 = a^2 - 2ab + b^2$ | A squared bracket difference |
| $a^2 - b^2 = (a+b)(a-b)$ | Difference of two squares |
| $(a+b)^3 = a^3 + 3a^2b + 3ab^2 + b^3$ | A cubed sum |
| $(a-b)^3 = a^3 - 3a^2b + 3ab^2 - b^3$ | A cubed difference |
| $a^3 + b^3 = (a+b)(a^2 - ab + b^2)$ | Sum of two cubes |
| $a^3 - b^3 = (a-b)(a^2 + ab + b^2)$ | Difference of two cubes |
| $a^3 + b^3 + 3ab(a+b) = (a+b)^3$ | Rearrangement of the cube identity |
| $a^3 - b^3 - 3ab(a-b) = (a-b)^3$ | Another rearrangement |

**Example:** $(a-b)^3 = a^3 - b^3 - 3ab(a-b)$, so $a^3 - b^3 - 3ab(a-b) = (a-b)^3$.

With $a = 7$, $b = 3$: $7^3 - 3^3 - 3 \times 7 \times 3 \times 4 = 4^3 = 64$.

### Your turn

Verify: $(5-2)(25+10+4) = 5^3 - 2^3$. ($3 \times 39 = 117 = 125 - 8$. **Yes**.)

## 2. The shortcuts / tricks

### Trick 1: approximation — round, compute, pick

When the exam says "approximate," you are expected to substitute clean values and compute mentally.

**Rules for clean rounding:**
- Decimals close to a whole number → round to that whole number.
- A number like 0.496 → treat as 0.5.
- A percentage like 32.01% → treat as 32%.
- $\sqrt{80.1} \approx \sqrt{81} = 9$.

**Example:** approximate $23.98^2 + \dfrac{48.01}{8.02}$.
- $\approx 24^2 + \dfrac{48}{8} = 576 + 6 = \mathbf{582}$.
- Exact: 581.9. The approximation is close enough to select the right option.

### Trick 2: near-round-number multiplication

Use $a^2 - b^2 = (a+b)(a-b)$ to multiply numbers close to a round number.

**Example:** $3998 \times 4002 = (4000 - 2)(4000 + 2) = 4000^2 - 4 = 16000000 - 4 = \mathbf{15999996}$.

**Example:** $97 \times 103 = (100-3)(100+3) = 10000 - 9 = \mathbf{9991}$.

### Trick 3: telescoping sums

$\dfrac{1}{n(n+1)} = \dfrac{1}{n} - \dfrac{1}{n+1}$, so the terms collapse:

$$\frac{1}{1 \times 2} + \frac{1}{2 \times 3} + \cdots + \frac{1}{9 \times 10} = 1 - \frac{1}{10} = \frac{9}{10}$$

### Trick 4: fraction simplification

Convert all fractions to the same denominator, or cancel common factors before multiplying.

**Example:** $\dfrac{5}{8}$ of $\dfrac{4}{3}$ of 1440.
- $= \dfrac{5}{8} \times \dfrac{4}{3} \times 1440 = \dfrac{5 \times 4 \times 1440}{8 \times 3} = \dfrac{5 \times 480}{8} = \dfrac{2400}{8} = \mathbf{1200}$.

**Your turn:** simplify $\left(3 + \dfrac{2}{3}\right) \div \left(1 - \dfrac{2}{9}\right)$. ($= \dfrac{11}{3} \div \dfrac{7}{9} = \dfrac{11}{3} \times \dfrac{9}{7} = \dfrac{33}{7}$. **Answer: $\frac{33}{7}$**.)

## 3. Types of questions and how to crack each one

### Type 1. VBODMAS (nested brackets)

**How you spot it:** an expression with two or more levels of brackets, written with ( ), { }, [ ].

**Think:** innermost bracket first, then outward. Copy the number carefully each step — bracket mistakes come from rushing.

**Solved example:** $12 + 4 \times [8 - 2 \times (5 - 3)]$
- Inner (): $5 - 3 = 2$
- Next: $2 \times 2 = 4$
- Inside [ ]: $8 - 4 = 4$
- Multiply: $4 \times 4 = 16$
- Final: $12 + 16 = \mathbf{28}$

**Solved example:** $225 - [48 - \{36 - (18 - 6)\}]$
- $(18-6)=12$; $\{36-12\}=24$; $[48-24]=24$; $225-24=\mathbf{201}$.

**Your turn:** evaluate $36 \div 4 + 5 \times 3 - 8$. ($9 + 15 - 8$ = **16**.)

### Type 2. Simplification using indices

**How you spot it:** expressions like $2^5 \times 2^3 \div 2^6$ or $\dfrac{4^5 \times 8^3}{16^4}$ or $\dfrac{3^4}{3^2} + 2^3$.

**Think:** convert all bases to the same prime base, apply the laws, simplify.

**Solved example:** $\dfrac{3^4}{3^2} + 2^3 = 3^{4-2} + 8 = 9 + 8 = \mathbf{17}$.

**Solved example:** $\dfrac{4^5 \times 8^3}{16^4} = \dfrac{(2^2)^5 \times (2^3)^3}{(2^4)^4} = \dfrac{2^{10} \times 2^9}{2^{16}} = 2^{10+9-16} = 2^3 = \mathbf{8}$.

**Exam twist:** "Simplify $\dfrac{x^5 \times x^7}{x^9}$." Answer: $x^{5+7-9} = x^3$.

**Your turn:** simplify $2^5 \times 2^3 \div 2^6$. ($2^{5+3-6} = 2^2$ = **4**.)

### Type 3. Simplification using algebraic identities

**How you spot it:** expressions like $(a+b)^2 - (a-b)^2$, $a^3 + b^3 + 3ab(a+b)$, $(a-b)(a^2+ab+b^2)$.

**Think:** match the pattern to a known identity before computing.

**Solved example:** $(5+3)^2 - (5-3)^2$.
- Use $(a+b)^2 - (a-b)^2 = 4ab$.
- $= 4 \times 5 \times 3 = \mathbf{60}$.

**Solved example:** $5.9^3 + 3.1^3 + 3 \times 5.9 \times 3.1 \times (5.9 + 3.1)$.
- Matches $a^3 + b^3 + 3ab(a+b) = (a+b)^3$ with $a=5.9$, $b=3.1$.
- $(5.9 + 3.1)^3 = 9^3 = \mathbf{729}$.

**Solved example:** $(a-b)^3 = a^3 - b^3 - 3ab(a-b)$. So if $a=7$, $b=3$: $7^3 - 3^3 - 3 \times 7 \times 3 \times (7-3) = 4^3 = \mathbf{64}$.

**Your turn:** evaluate $(12 - 15)^2$ using the identity $(a-b)^2 = a^2 - 2ab + b^2$. ($144 + 225 - 360$ = **9** $= (-3)^2$.)

### Type 4. Simplification with surds and square roots

**How you spot it:** expressions like $\sqrt{3} \times \sqrt{75}$, $\sqrt{18} \times \sqrt{8}$, $\sqrt{6.25} + \sqrt{56.25}$.

**Think:** $\sqrt{a} \times \sqrt{b} = \sqrt{ab}$. Simplify surds by pulling out perfect-square factors.

**Solved example:** $\sqrt{3} \times \sqrt{75} = \sqrt{3 \times 75} = \sqrt{225} = \mathbf{15}$.

**Solved example:** $\sqrt{6.25} + \sqrt{56.25}$.
- $\sqrt{6.25} = 2.5$ and $\sqrt{56.25} = 7.5$.
- Sum $= \mathbf{10}$.

**Solved example:** $\sqrt{18} \times \sqrt{8} = \sqrt{144} = \mathbf{12}$.

**Exam twist:** $\dfrac{1}{\sqrt{2}+1} = \sqrt{2}-1$ after rationalising the denominator.

**Your turn:** evaluate $\sqrt{2.25}$. ($\sqrt{225/100} = 15/10$ = **1.5**.)

### Type 5. Decimal and fraction operations

**How you spot it:** mixed expressions with fractions and decimals, recurring decimals, "find the value of $0.25 \times 480 + 0.75 \times 320$."

**Think:** convert decimals to fractions or percentages where it is easier; use the distributive property.

**Solved example:** $0.25 \times 480 + 0.75 \times 320 = 120 + 240 = \mathbf{360}$.

**Solved example:** $\dfrac{7}{8} - \dfrac{5}{12}$.
- LCM of 8 and 12 is 24: $\dfrac{21}{24} - \dfrac{10}{24} = \dfrac{11}{24}$.

**Solved example:** recurring decimal $0.6363\ldots = \dfrac{63}{99} = \dfrac{7}{11}$.

**Your turn:** simplify $\dfrac{11}{12} - \dfrac{5}{12} \times 1$. ($\dfrac{6}{12} = \dfrac{1}{2}$ = **0.5**.)

### Type 6. Percentage expressions in simplification

**How you spot it:** "15% of 480 + 25% of 360" or "48% of 450 − 24% of 900."

**Think:** convert to fractions, or use the factor method. When both expressions share the same base number, factor it out.

**Solved example:** $15\%$ of $480 + 25\%$ of $360$.
- $= 0.15 \times 480 + 0.25 \times 360 = 72 + 90 = \mathbf{162}$.

**Solved example:** $48\%$ of $450 - 24\%$ of $900$.
- $= 0.48 \times 450 - 0.24 \times 900 = 216 - 216 = \mathbf{0}$.

**Trick:** notice $0.48 \times 450 = 0.24 \times 900$ because $0.48/0.24 = 2$ and $900/450 = 2$ (the factors invert).

**Your turn:** evaluate $32\%$ of $475 + 48\%$ of $475$. ($(32+48)\%$ of $475 = 80\%$ of $475 = 0.8 \times 475$ = **380**.)

### Type 7. Approximation: rounding to clean numbers

**How you spot it:** the question uses values like 3.98, 17.96, 0.0403, 624.5 — all close to clean numbers. The options are spread at least 5 apart.

**Think:** round each value to the nearest clean number (whole, half, power of 10), compute, and pick.

**Solved example:** approximate $3.98^2 + \sqrt{80.1}$.
- $\approx 4^2 + \sqrt{81} = 16 + 9 = \mathbf{25}$.
- Exact: $15.84 + 8.95 = 24.79$. Closest to 25. Correct.

**Solved example:** approximate $999.7 \times 0.0099$.
- $\approx 1000 \times 0.01 = \mathbf{10}$.
- Exact: 9.897. Closest to 10. Correct.

**Exam twist:** "approximate $17.96^2 - 3.02^2$."
- $\approx 18^2 - 3^2 = 324 - 9 = 315$. Or use the identity: $(18-3)(18+3) = 15 \times 21 = \mathbf{315}$.

**Your turn:** approximate $4.999 \times \sqrt{36.01} + (2.99)^3$. ($\approx 5 \times 6 + 27 = 30 + 27$ = **57**.)

### Type 8. Approximation with division

**How you spot it:** messy division like $\dfrac{624.5 \times 0.04003}{24.99 \times 0.0801}$.

**Think:** round both numerator and denominator to clean values, cancel, compute.

**Solved example:** $\dfrac{624.5 \times 0.04003}{24.99 \times 0.0801}$.
- $\approx \dfrac{625 \times 0.04}{25 \times 0.08} = \dfrac{25}{2} = \mathbf{12.5}$.
- Exact: 12.49. Correct.

**Solved example:** $\dfrac{1299.98}{13.01} - \dfrac{99.85}{20.01}$.
- $\approx \dfrac{1300}{13} - \dfrac{100}{20} = 100 - 5 = \mathbf{95}$.

**Your turn:** approximate $\dfrac{0.0403 \times 2.47}{0.00124}$. ($\approx \dfrac{0.04 \times 2.5}{0.00125} = \dfrac{0.1}{0.00125}$ = **80**.)

### Type 9. Approximation with powers and roots of large numbers

**How you spot it:** expressions like $\sqrt{1024.36}$ or $512.1^{1/3}$ or $729.1^{1/3} + 512.1^{1/3}$.

**Think:** find the nearest perfect square or cube, take its root, pick the answer.

**Solved example:** approximate $512^{1/3} + 729^{1/3}$.
- $8^3 = 512$, $9^3 = 729$.
- $= 8 + 9 = \mathbf{17}$.

**Solved example:** $\sqrt{1024.36} \approx \sqrt{1024} = 32$.

**Your turn:** approximate $(4137)^{0} + \sqrt{900.1}$. ($= 1 + 30$ = **31**. Any non-zero base to power 0 is 1; $\sqrt{900}=30$.)

### Type 10. Simplification using $(a+b)^2 - (a-b)^2 = 4ab$

**How you spot it:** "Find $(x+y)^2 - (x-y)^2$ if $x=12$, $y=8$."

**Think:** do not expand — use the identity directly.

**Solved example:** $(x+y)^2 - (x-y)^2 = 4xy = 4 \times 12 \times 8 = \mathbf{384}$.

**Solved example:** $(1.2)^2 - (0.8)^2 = (1.2+0.8)(1.2-0.8) = 2 \times 0.4 = \mathbf{0.8}$.

**Your turn:** $(9+6)^2 - (9-6)^2$. (Use $4ab = 4 \times 9 \times 6 = 216$. Check: $(15)^2-(3)^2 = 225-9 = 216$. **Answer: 216**.)

### Type 11. Simplification of products of decimals and powers of 10

**How you spot it:** expressions like $0.0625 \times 64$, $0.25 \times 480$, $1.2^2 - 0.8^2$.

**Think:** convert decimal to a fraction ($0.0625 = 1/16$), multiply, simplify.

**Solved example:** $0.0625 \times 64 = \dfrac{1}{16} \times 64 = \mathbf{4}$.

**Solved example:** $0.9 \times 0.9 + 0.9 \times 0.1 = 0.9 \times (0.9 + 0.1) = 0.9 \times 1 = \mathbf{0.9}$.

**Your turn:** $0.0625 \times 64 + 2^3 - 3$. ($4 + 8 - 3$ = **9**.)

### Type 12. Telescoping and partial fractions

**How you spot it:** sums like $\dfrac{1}{1 \times 2} + \dfrac{1}{2 \times 3} + \cdots + \dfrac{1}{9 \times 10}$.

**Think:** write each term as $\dfrac{1}{n} - \dfrac{1}{n+1}$ — most terms cancel.

**Solved example:** $\dfrac{1}{1 \times 2} + \dfrac{1}{2 \times 3} + \cdots + \dfrac{1}{9 \times 10}$.

$$= \left(1 - \frac{1}{2}\right) + \left(\frac{1}{2}-\frac{1}{3}\right) + \cdots + \left(\frac{1}{9}-\frac{1}{10}\right) = 1 - \frac{1}{10} = \frac{9}{10}$$

**Your turn:** $\dfrac{1}{3 \times 4} + \dfrac{1}{4 \times 5} + \dfrac{1}{5 \times 6}$. ($= \frac{1}{3} - \frac{1}{6} = \frac{2-1}{6}$ = **$\frac{1}{6}$**.)

### Type 13. Approximation involving percentages

**How you spot it:** "Approximate $45.02\%$ of $999.7 + 55.04\%$ of $1199.9$."

**Think:** round percentages and numbers.

**Solved example:** $45.02\%$ of $999.7 + 55.04\%$ of $1199.9$.
- $\approx 45\%$ of $1000 + 55\%$ of $1200 = 450 + 660 = \mathbf{1110}$.

**Your turn:** approximate $24\%$ of $999 + 76\%$ of $999$. ($(24+76)\%$ of $1000 = 100\%$ of $1000$ = **1000**.)

### Type 14. Simplification with cube identity

**How you spot it:** expressions involving $(a^3 - b^3)$ factored using $(a-b)(a^2+ab+b^2)$.

**Think:** use $a^3 - b^3 = (a-b)(a^2+ab+b^2)$ to expand or collapse.

**Solved example:** $(5-2)(25 + 10 + 4) = 5^3 - 2^3 = 125 - 8 = \mathbf{117}$.

**Solved example:** evaluate $(0.8)^3 + (0.2)^3$ using $a^3 + b^3 = (a+b)(a^2-ab+b^2)$.
- $(0.8+0.2)(0.64 - 0.16 + 0.04) = 1 \times 0.52 = \mathbf{0.52}$.

**Your turn:** evaluate $(8^{2/3}) \times 2$. ($8^{2/3} = (8^{1/3})^2 = 2^2 = 4$. $4 \times 2$ = **8**.)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Nested brackets | Work innermost outward; watch for sign flip with minus outside a bracket |
| Indices with same base | Add/subtract exponents for × and ÷; multiply for power of power |
| Different bases, convert | Express as powers of a prime base (usually 2 or 3) |
| Difference of squares | $(a+b)(a-b) = a^2-b^2$ |
| Sum or difference of cubes | Factor using standard identity |
| $(a+b)^2 - (a-b)^2$ | Always equals $4ab$ |
| $a^3+b^3+3ab(a+b)$ | Always equals $(a+b)^3$ |
| $a^3-b^3-3ab(a-b)$ | Always equals $(a-b)^3$ |
| Approximate messy number | Round to nearest whole/half/power-of-10; compute |
| Telescope sum $\sum \frac{1}{n(n+1)}$ | $= 1 - \frac{1}{\text{last }+1}$ |
| Fraction ÷ fraction | Multiply by reciprocal of denominator |
| Surd product | $\sqrt{a} \times \sqrt{b} = \sqrt{ab}$; rationalise denominator by multiplying conjugate |

### Key values to memorise

**Fraction to decimal:** $\frac{1}{2}=0.5$, $\frac{1}{3}=0.33$, $\frac{1}{4}=0.25$, $\frac{1}{5}=0.2$, $\frac{1}{6}=0.167$, $\frac{1}{7}=0.143$, $\frac{1}{8}=0.125$, $\frac{1}{9}=0.111$, $\frac{1}{11}=0.0909$

**Perfect squares and cubes:** already in Chapter 1. Review them.

**Recurring decimals:** $\frac{1}{7}=0.\overline{142857}$, $\frac{7}{11}=0.\overline{63}$, $\frac{1}{3}=0.\overline{3}$, $\frac{2}{3}=0.\overline{6}$

**Powers of 2:** $2^1=2$, $2^2=4$, $2^3=8$, $2^4=16$, $2^5=32$, $2^6=64$, $2^7=128$, $2^8=256$, $2^9=512$, $2^{10}=1024$

## 5. Mistakes that cost marks

1. **Doing division and multiplication in the wrong order.** In VBODMAS, division and multiplication have equal priority — work left to right, not "division first."
2. **Missing the sign flip when a minus sign sits outside a bracket.** $-(a-b) = -a+b$, not $-a-b$.
3. **Applying the index law incorrectly to different bases.** $2^3 \times 3^3 \ne 6^6$. The base-addition law only works when the bases are the same.
4. **Rounding too aggressively in approximation.** $3.5 \times 1.4 / 0.7$ is exact: $3.5/0.7 = 5$, then $5 \times 1.4 = 7$. Do not round $3.5$ to $4$ first.
5. **Forgetting $a^0 = 1$ (for $a \ne 0$).** Many students write 0 or skip this term.
6. **Using $(a+b)^2 = a^2 + b^2$ without the $2ab$ term.** The middle term is always there.
7. **Approximating percentages of two different bases separately when they could be combined.** $32\%$ of $475 + 48\%$ of $475 = 80\%$ of $475$. Adding first is faster.

## 6. Practice questions

Do these on paper. Do the first 10 untimed. Do the next 15 with 90 seconds each. Do the last 15 like an exam.

### Level 1: single idea

1. Evaluate $36 \div 4 + 5 \times 3 - 8$.
2. Evaluate $(23+17) \times (23-17)$.
3. Find $\sqrt{2.25}$.
4. Simplify $2^5 \times 2^3 \div 2^6$.
5. Evaluate $3^4 \div 3^2 + 2^3$.
6. Simplify $\dfrac{7}{8} - \dfrac{5}{12}$.
7. Evaluate $0.0625 \times 64$.
8. Evaluate $12 + 4 \times [8 - 2 \times (5 - 3)]$.
9. Evaluate $\sqrt{3} \times \sqrt{75}$.
10. Find $25\%$ of $360 + 35\%$ of $440$.

### Level 2: mixed

11. Approximate $3.98^2 + \sqrt{80.1}$.
12. Approximate $999.7 \times 0.0099$.
13. Evaluate $(0.8)^3 + (0.2)^3$.
14. Evaluate $48\%$ of $450 - 24\%$ of $900$.
15. Evaluate $\sqrt{6.25} + \sqrt{56.25}$.
16. Evaluate $(1.2)^2 - (0.8)^2$.
17. Evaluate $\dfrac{5}{8}$ of $\dfrac{4}{3}$ of $1440$.
18. Evaluate $12^2 + 15^2 - 2 \times 12 \times 15$.
19. Approximate $17.96^2 - 3.02^2$.
20. Evaluate $3.5 \times 1.4 \div 0.7 + \sqrt{49}$.
21. Approximate $\dfrac{624.5 \times 0.04003}{24.99 \times 0.0801}$.
22. Express $0.6363\ldots$ as a fraction in lowest terms.
23. Evaluate $(0.1 + 0.01)^2$.
24. Simplify $\dfrac{4^5 \times 8^3}{16^4}$.
25. Evaluate $0.9 \times 0.9 + 0.9 \times 0.1$.

### Level 3: exam style

26. Approximate $\dfrac{54.97^2 + 45.03^2}{54.97 \times 45.03}$.
27. Evaluate $(x+y)^2 - (x-y)^2$ if $x=12$, $y=8$.
28. Approximate $\dfrac{1299.98}{13.01} - \dfrac{99.85}{20.01}$.
29. Evaluate $32\%$ of $475 + 48\%$ of $475$.
30. If $a=7$, $b=3$: evaluate $a^3 - b^3 - 3ab(a-b)$.
31. Approximate $4.999 \times \sqrt{36.01} + (2.99)^3$.
32. Evaluate $\dfrac{1}{1 \times 2} + \dfrac{1}{2 \times 3} + \dfrac{1}{3 \times 4} + \cdots + \dfrac{1}{9 \times 10}$.
33. Approximate $\dfrac{0.0403 \times 2.47}{0.00124}$.
34. Evaluate $(0.6)^0 + (0.6)^1 + (0.6)^2$.
35. Evaluate $(5-2)(25+10+4)$.
36. Approximate $512^{1/3} + 729^{1/3}$.
37. Approximate $45.02\%$ of $999.7 + 55.04\%$ of $1199.9$.
38. Simplify $\left(3 + \dfrac{2}{3}\right) \div \left(1 - \dfrac{2}{9}\right)$.
39. Evaluate $5.9^3 + 3.1^3 + 3 \times 5.9 \times 3.1 \times (5.9+3.1)$.
40. Approximate $3998 \times 4002$.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | 16 | $9+15-8$ |
| 2 | 240 | $(40)(6) = 240$; or $23^2-17^2 = 529-289$ |
| 3 | 1.5 | $\sqrt{225/100}=15/10$ |
| 4 | 4 | $2^{5+3-6}=2^2$ |
| 5 | 17 | $3^2+2^3=9+8$ |
| 6 | $\frac{11}{24}$ | $\frac{21-10}{24}$; LCM of 8,12 is 24 |
| 7 | 4 | $\frac{1}{16} \times 64$ |
| 8 | 28 | $(5-3)=2$; $2\times2=4$; $8-4=4$; $4\times4=16$; $12+16$ |
| 9 | 15 | $\sqrt{3\times75}=\sqrt{225}$ |
| 10 | 244 | $90+154$ |
| 11 | 25 | $\approx 4^2+\sqrt{81}=16+9$ |
| 12 | 10 | $\approx 1000\times0.01$ |
| 13 | 0.52 | $(0.8+0.2)(0.64-0.16+0.04)=1\times0.52$ |
| 14 | 0 | $216-216$; note $0.48\times450=0.24\times900$ |
| 15 | 10 | $2.5+7.5$ |
| 16 | 0.8 | $(1.2+0.8)(1.2-0.8)=2\times0.4$ |
| 17 | 1200 | $\frac{5\times4\times1440}{8\times3}=\frac{28800}{24}$ |
| 18 | 9 | $(12-15)^2=(-3)^2$ |
| 19 | 315 | $\approx(18-3)(18+3)=15\times21$ |
| 20 | 14 | $3.5/0.7=5$; $5\times1.4=7$; $7+7$ |
| 21 | 12.5 | $\approx\frac{625\times0.04}{25\times0.08}=\frac{25}{2}$ |
| 22 | $\frac{7}{11}$ | $\frac{63}{99}=\frac{7}{11}$ |
| 23 | 0.0121 | $(0.11)^2$ |
| 24 | 8 | $2^{10+9-16}=2^3$ |
| 25 | 0.9 | $0.9\times(0.9+0.1)=0.9\times1$ |
| 26 | 2.04 | $\approx\frac{55^2+45^2}{55\times45}=\frac{5050}{2475}$ |
| 27 | 384 | $4xy=4\times12\times8$ |
| 28 | 95 | $\approx1300/13-100/20=100-5$ |
| 29 | 380 | $(32+48)\%$ of $475=80\%\times475$ |
| 30 | 64 | $(a-b)^3=(7-3)^3=4^3$ |
| 31 | 57 | $\approx5\times6+3^3=30+27$ |
| 32 | $\frac{9}{10}$ | Telescoping: $1-\frac{1}{10}$ |
| 33 | 80 | $\approx\frac{0.04\times2.5}{0.00125}=\frac{0.1}{0.00125}$ |
| 34 | 1.96 | $1+0.6+0.36$ |
| 35 | 117 | $5^3-2^3=125-8$ |
| 36 | 17 | $8^3=512$, $9^3=729$; $8+9$ |
| 37 | 1110 | $\approx45\%\times1000+55\%\times1200=450+660$ |
| 38 | $\frac{33}{7}$ | $\frac{11}{3}\times\frac{9}{7}=\frac{99}{21}=\frac{33}{7}$ |
| 39 | 729 | $a^3+b^3+3ab(a+b)=(a+b)^3=(5.9+3.1)^3=9^3$ |
| 40 | 15999996 | $(4000-2)(4000+2)=4000^2-4$ |
