# Surds, Indices and Roots

> Read this like a class, not like a list of rules. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" problems with a pen before looking at the answer.

## 0. Start here: what is this topic really about?

Think of the two operations your calculator has that look exotic: the power button $x^y$ and the root button $\sqrt{\phantom{x}}$. Every question in this chapter is built on those two buttons.

**Indices** (singular: index) means the little raised number in $2^5$. It tells you how many times to multiply 2 by itself. **Surds** are roots that do not simplify to whole numbers - $\sqrt{2}$, $\sqrt{3}$, $\sqrt{5}$ are surds because you cannot write them as exact fractions. $\sqrt{4} = 2$ is not a surd because it simplifies.

- **What the exam gives you:** a complicated-looking expression with powers, roots, or both.
- **What it asks for:** a single number or a simplified form.
- **What patterns repeat:** compare two surds, rationalise a denominator, simplify a power expression, solve an equation like $2^x = 32$.

**How many marks to expect:** SSC CGL and CHSL carry 2 to 4 questions. RRB NTPC and Group D carry 1 to 3 questions. IBPS and SBI papers carry 1 to 2 questions. APPSC and PSU papers carry 2 to 4 questions. They look harder than they are because of the notation. Once you know the seven laws, the questions are mechanical.

## 1. The only ideas you must understand

### What is an index?

$a^n$ means $a$ multiplied by itself $n$ times. We call $a$ the **base** and $n$ the **index** (or exponent).

$$2^5 = 2\times2\times2\times2\times2 = 32$$

A **surd** is an irrational root. $\sqrt{5}$ is a surd. $\sqrt{9} = 3$ is not.

### The seven laws (these are all you need)

Let $a$ and $b$ be positive numbers, $m$ and $n$ be any rational numbers.

| Law | What it says | Example |
|---|---|---|
| 1 | $a^m \times a^n = a^{m+n}$ | $2^3 \times 2^5 = 2^8 = 256$ |
| 2 | $a^m \div a^n = a^{m-n}$ | $3^5 \div 3^2 = 3^3 = 27$ |
| 3 | $(a^m)^n = a^{m \times n}$ | $(2^3)^4 = 2^{12}$ |
| 4 | $(ab)^n = a^n \times b^n$ | $(2\times3)^2 = 4\times9 = 36$ |
| 5 | $a^0 = 1$ | $7^0 = 1$ |
| 6 | $a^{-n} = \dfrac{1}{a^n}$ | $5^{-2} = \dfrac{1}{25}$ |
| 7 | $a^{m/n} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m$ | $8^{2/3} = (\sqrt[3]{8})^2 = 4$ |

### About surds

$\sqrt{a} \times \sqrt{b} = \sqrt{ab}$ and $\dfrac{\sqrt{a}}{\sqrt{b}} = \sqrt{\dfrac{a}{b}}$.

To **simplify a surd**, look for the largest perfect-square factor:

$$\sqrt{75} = \sqrt{25 \times 3} = 5\sqrt{3}$$

**Sense check:** $\sqrt{75}$ is between $\sqrt{64}=8$ and $\sqrt{81}=9$, so $5\sqrt{3}\approx 5\times 1.73 = 8.66$ is reasonable.

### Rationalising the denominator

Surds in a denominator are "untidy". We remove them by multiplying top and bottom by the **conjugate** or by the surd itself.

$$\dfrac{1}{\sqrt{5}+\sqrt{3}} = \dfrac{1}{\sqrt{5}+\sqrt{3}} \times \dfrac{\sqrt{5}-\sqrt{3}}{\sqrt{5}-\sqrt{3}} = \dfrac{\sqrt{5}-\sqrt{3}}{5-3} = \dfrac{\sqrt{5}-\sqrt{3}}{2}$$

The key identity used here: $(a+b)(a-b) = a^2-b^2$.

## 2. The shortcuts / tricks

### Speed trick 1: compare surds by raising to a common power

To compare $2^{1/2}$ and $3^{1/3}$, raise both to the power 6 (LCM of 2 and 3):

- $(2^{1/2})^6 = 2^3 = 8$
- $(3^{1/3})^6 = 3^2 = 9$

Since $9 > 8$, we have $3^{1/3} > 2^{1/2}$.

**Why it works:** raising both to the same power preserves the order (both are positive numbers less than their 6th powers), so the comparison does not flip.

### Speed trick 2: infinite nested surd

When you see $x = \sqrt{k + \sqrt{k + \sqrt{k + \cdots}}}$, the trick is that the expression inside the first root is the same as $x$ itself. So:

$$x = \sqrt{k+x} \implies x^2 = k+x \implies x^2 - x - k = 0$$

Solve for the positive root.

**Example:** $x = \sqrt{12 + \sqrt{12 + \sqrt{12+\cdots}}}$

$x^2 - x - 12 = 0 \implies (x-4)(x+3)=0 \implies x = 4$.

### Speed trick 3: telescoping product with indices

When you see $\left(\dfrac{x^a}{x^b}\right)^{a+b} \times \left(\dfrac{x^b}{x^c}\right)^{b+c} \times \left(\dfrac{x^c}{x^a}\right)^{c+a}$, the exponents cancel:

$(a-b)(a+b) + (b-c)(b+c) + (c-a)(c+a) = a^2-b^2+b^2-c^2+c^2-a^2 = 0$

So the whole expression equals $x^0 = 1$.

### Speed trick 4: converting base

Whenever you see a power equation like $9^x = 27$, convert everything to a prime base:

$9 = 3^2$ and $27 = 3^3$, so $3^{2x} = 3^3 \implies x = 3/2$.

## 3. Types of questions and how to crack each one

### Type 1. Laws of indices (simplify an expression)

**How you spot it:** an expression with the same or related bases - "simplify $2^5 \times 4^3 \div 8^2$."

**Think:** convert everything to the smallest prime base, then apply Law 1 and Law 2.

**Example.** Simplify $2^5 \times 4^3 \div 8^2$.

- $4^3 = (2^2)^3 = 2^6$. $8^2 = (2^3)^2 = 2^6$.
- $2^5 \times 2^6 \div 2^6 = 2^{5+6-6} = 2^5 = \mathbf{32}$.

**Your turn:** Simplify $3^4 \times 9^2 \div 27^2$. (Answer: $3^4 \times 3^4 \div 3^6 = 3^2 = 9$)

### Type 2. Simplify a surd

**How you spot it:** $\sqrt{72}$, $3\sqrt{12} + 2\sqrt{48}$, etc.

**Think:** factor out perfect squares. Then add like surds (same radicand) the way you add like terms.

**Example.** Simplify $4\sqrt{3} - \sqrt{75} + \sqrt{108}$.

- $\sqrt{75} = \sqrt{25\times3} = 5\sqrt{3}$.
- $\sqrt{108} = \sqrt{36\times3} = 6\sqrt{3}$.
- $4\sqrt{3} - 5\sqrt{3} + 6\sqrt{3} = (4-5+6)\sqrt{3} = \mathbf{5\sqrt{3}}$.

**Your turn:** Simplify $3\sqrt{2} + 5\sqrt{8}$. (Answer: $3\sqrt{2}+5\times2\sqrt{2}=13\sqrt{2}$)

### Type 3. Rationalise the denominator

**How you spot it:** a surd or surd-sum appears in the denominator - "find the value of $\dfrac{1}{3+\sqrt{5}}$."

**Think:** multiply top and bottom by the **conjugate** of the denominator. The conjugate of $(a+\sqrt{b})$ is $(a-\sqrt{b})$.

**Example.** Rationalise $\dfrac{1}{3-\sqrt{5}}$.

- Multiply by $\dfrac{3+\sqrt{5}}{3+\sqrt{5}}$.
- Denominator: $(3)^2-(\sqrt{5})^2 = 9-5=4$.
- Result: $\dfrac{3+\sqrt{5}}{4}$.

**Exam twist:** sometimes the question says "find the value given $\sqrt{5} = 2.236$". Just substitute after rationalising.

**Your turn:** Rationalise $\dfrac{1}{\sqrt{7}+\sqrt{5}}$. (Answer: $\dfrac{\sqrt{7}-\sqrt{5}}{2}$, since denominator becomes $7-5=2$)

### Type 4. Product and quotient of surds

**How you spot it:** $\sqrt{a}\times\sqrt{b}$ or $\dfrac{\sqrt{a}}{\sqrt{b}}$.

**Think:** merge under one root. $\sqrt{a}\times\sqrt{b} = \sqrt{ab}$.

**Example.** Find $\sqrt{2}\times\sqrt{50}$.

$\sqrt{2\times50} = \sqrt{100} = \mathbf{10}$.

**Your turn:** Find $\sqrt{3}\times\sqrt{75}$. (Answer: $\sqrt{225}=15$)

### Type 5. Fractional and negative exponents

**How you spot it:** $8^{2/3}$, $32^{4/5}$, $(0.027)^{1/3}$, $4^{-3/2}$.

**Think:** $a^{m/n}$ = take the $n$-th root first, then raise to power $m$. Negative exponent means take the reciprocal.

**Example 1.** Find $32^{3/5}$.

$32 = 2^5$, so $32^{3/5} = (2^5)^{3/5} = 2^3 = \mathbf{8}$.

**Example 2.** Find $4^{-3/2}$.

$4^{-3/2} = \dfrac{1}{4^{3/2}} = \dfrac{1}{(\sqrt{4})^3} = \dfrac{1}{2^3} = \mathbf{\dfrac{1}{8}}$.

**Example 3.** Find $(0.027)^{1/3}$.

$0.027 = \dfrac{27}{1000}$, so $(0.027)^{1/3} = \dfrac{3}{10} = \mathbf{0.3}$.

**Your turn:** Find $16^{3/4}$. (Answer: $(2^4)^{3/4}=2^3=8$)

### Type 6. Comparing two surds

**How you spot it:** "which is greater: $3^{1/2}$ or $2^{1/3}$?"

**Think:** raise both to the LCM of the two denominators. Whichever becomes bigger is the larger surd.

**Example.** Compare $7^{1/2}$ and $5^{1/3}$.

LCM of 2 and 3 is 6. $(7^{1/2})^6 = 7^3 = 343$. $(5^{1/3})^6 = 5^2 = 25$. Since $343 > 25$, we have $7^{1/2} > 5^{1/3}$.

**Your turn:** Which is larger, $5^{1/2}$ or $4^{1/3}$? (Answer: $(5^{1/2})^6=125$, $(4^{1/3})^6=16$, so $5^{1/2}$ is larger)

### Type 7. Negative and zero exponents

**How you spot it:** $(2/3)^{-2}$, $x^0$, something like $\left(\dfrac{a}{b}\right)^{-n}$.

**Think:** flip the fraction when the exponent is negative. $\left(\dfrac{a}{b}\right)^{-n} = \left(\dfrac{b}{a}\right)^{n}$.

**Example.** Find $\left(\dfrac{3}{4}\right)^{-2}$.

$= \left(\dfrac{4}{3}\right)^{2} = \dfrac{16}{9}$.

**Your turn:** Find $(0.1)^{-3}$. (Answer: $(1/0.1)^3 = 10^3 = 1000$)

### Type 8. Adding and subtracting surds

**How you spot it:** $5\sqrt{3} + 2\sqrt{3}$ or a more disguised form where you first simplify each term.

**Think:** you can only add surds with the same number under the root - just like adding like algebraic terms.

**Example.** Simplify $5\sqrt{45} - 3\sqrt{20}$.

- $\sqrt{45} = 3\sqrt{5}$, so $5\sqrt{45} = 15\sqrt{5}$.
- $\sqrt{20} = 2\sqrt{5}$, so $3\sqrt{20} = 6\sqrt{5}$.
- $15\sqrt{5} - 6\sqrt{5} = \mathbf{9\sqrt{5}}$.

**Your turn:** Simplify $2\sqrt{12}+3\sqrt{27}$. (Answer: $4\sqrt{3}+9\sqrt{3}=13\sqrt{3}$)

### Type 9. Solving index equations

**How you spot it:** "find $x$ if $4^{x+1} = 64$" or "$9^x = 27$."

**Think:** write both sides as powers of the same prime base. If $a^m = a^n$, then $m=n$.

**Example 1.** Find $x$ if $4^x = 64$.

$4^x = 2^{2x}$, $64 = 2^6$. So $2x = 6 \implies x = \mathbf{3}$.

**Example 2.** Find $x$ if $9^x = 27$.

$3^{2x} = 3^3 \implies 2x=3 \implies x = \mathbf{\dfrac{3}{2}}$.

**Example 3.** Find $x$ if $5^{x-2}\times3^{2x-3} = 135$.

$135 = 5\times27 = 5^1\times3^3$. Matching bases: $x-2=1$ and $2x-3=3$. Both give $x=\mathbf{3}$.

**Your turn:** Find $x$ if $3^{2x+1} = 81$. (Answer: $3^3 = 27 \neq 81$, so $3^4=81$, meaning $2x+1=4$, $x=1.5$)

### Type 10. Rationalise and find a value

**How you spot it:** "find $\dfrac{\sqrt{7}+\sqrt{2}}{\sqrt{7}-\sqrt{2}}$."

**Think:** multiply by conjugate. Use $(a+b)^2 = a^2+2ab+b^2$ for the numerator.

**Example.** Find $\dfrac{\sqrt{7}+\sqrt{2}}{\sqrt{7}-\sqrt{2}}$.

$$\dfrac{(\sqrt{7}+\sqrt{2})^2}{(\sqrt{7})^2-(\sqrt{2})^2} = \dfrac{7+2\sqrt{14}+2}{5} = \dfrac{9+2\sqrt{14}}{5}$$

**Your turn:** Find $\dfrac{\sqrt{5}+\sqrt{3}}{\sqrt{5}-\sqrt{3}}$. (Answer: multiply by $\dfrac{\sqrt{5}+\sqrt{3}}{\sqrt{5}+\sqrt{3}}$: denominator $5-3=2$, numerator $5+3+2\sqrt{15}=8+2\sqrt{15}$, so $\dfrac{8+2\sqrt{15}}{2}=4+\sqrt{15}$)

### Type 11. Square root of a fraction or decimal

**How you spot it:** $\sqrt{\dfrac{9}{16}}$, $\sqrt{0.0049}$, $\sqrt{0.0081}^{0.25}$.

**Think:** apply root to numerator and denominator separately. Convert decimals to fractions first.

**Example.** Find $\sqrt{0.0081}^{0.25}$, i.e., $(0.0081)^{1/4}$.

$0.0081 = \dfrac{81}{10000}$. $\left(\dfrac{81}{10000}\right)^{1/4} = \dfrac{81^{1/4}}{10000^{1/4}} = \dfrac{3}{10} = \mathbf{0.3}$.

**Your turn:** Find $\sqrt{\dfrac{25}{49}}$. (Answer: $\dfrac{5}{7}$)

### Type 12. Infinite nested radical (find the value)

**How you spot it:** $x = \sqrt{k+\sqrt{k+\sqrt{k+\cdots}}}$.

**Think:** the portion inside the first radical is just $x$ again. Write $x^2 = k+x$ and solve.

**Example.** If $x = \sqrt{20+\sqrt{20+\sqrt{20+\cdots}}}$, find $x$.

$x^2 = 20+x \implies x^2-x-20=0 \implies (x-5)(x+4)=0$. Since $x>0$, $x=\mathbf{5}$.

**Your turn:** Find $x$ if $x = \sqrt{6+\sqrt{6+\sqrt{6+\cdots}}}$. (Answer: $x^2-x-6=0$, $(x-3)(x+2)=0$, $x=3$)

### Type 13. Laws applied to combined expressions

**How you spot it:** $16^{3/4}\times8^{-2/3}$, $64^{5/6}$.

**Think:** convert each base to a prime, then add/subtract the exponents.

**Example.** Simplify $16^{3/4}\times8^{-2/3}$.

$16^{3/4} = (2^4)^{3/4} = 2^3 = 8$. $8^{-2/3} = (2^3)^{-2/3} = 2^{-2} = \dfrac{1}{4}$.

$8\times\dfrac{1}{4} = \mathbf{2}$.

**Your turn:** Find $27^{2/3}\times16^{3/4}$. (Answer: $3^2 \times 2^3 = 9\times8=72$)

### Type 14. Simplified surd form $\sqrt{a+2\sqrt{b}}$

**How you spot it:** simplify $\sqrt{11-6\sqrt{2}}$ or $\sqrt{3+2\sqrt{2}}$.

**Think:** try to write it as $(\sqrt{p}-\sqrt{q})^2$ or $(\sqrt{p}+\sqrt{q})^2$ and match terms.

**Example.** Simplify $\sqrt{3+2\sqrt{2}}$.

Try $(\sqrt{a}+\sqrt{b})^2 = a+b+2\sqrt{ab} = 3+2\sqrt{2}$. So $a+b=3$ and $ab=2$. This gives $a=2, b=1$. Answer: $\sqrt{2}+1$.

**Check:** $(\sqrt{2}+1)^2 = 2+2\sqrt{2}+1 = 3+2\sqrt{2}$. Correct.

**Your turn:** Simplify $\sqrt{11-6\sqrt{2}}$. (Answer: try $(p-q)^2$: $p+q=11$, $pq=18$, so $p=9, q=2$. Answer: $3-\sqrt{2}$)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Same base, multiply | Add the indices |
| Same base, divide | Subtract the indices |
| Power of a power | Multiply the indices |
| Zero exponent | Always 1 (if base not zero) |
| Negative exponent | Take reciprocal |
| Fraction exponent $m/n$ | Root $n$ first, then power $m$ |
| Simplify a surd | Pull out the largest perfect square |
| Add/subtract surds | Simplify each, then add like terms |
| Surd in denominator | Multiply by conjugate |
| Compare surds | Raise to LCM of their denominator |
| Infinite nested radical | Set equal to $x$, square both sides |
| Index equation (same base) | Equate the exponents |

### Powers of 2 to memorise

$2^1=2,\ 2^2=4,\ 2^3=8,\ 2^4=16,\ 2^5=32,\ 2^6=64,\ 2^7=128,\ 2^8=256,\ 2^9=512,\ 2^{10}=1024$

### Powers of 3 and 5

$3^1=3,\ 3^2=9,\ 3^3=27,\ 3^4=81,\ 3^5=243$

$5^1=5,\ 5^2=25,\ 5^3=125,\ 5^4=625$

### Surds to 4 decimal places

$\sqrt{2}\approx1.4142,\ \sqrt{3}\approx1.7321,\ \sqrt{5}\approx2.2361,\ \sqrt{6}\approx2.4495,\ \sqrt{7}\approx2.6458$

## 5. Mistakes that cost marks

1. **Adding exponents when bases are different.** $2^3\times3^2\neq6^5$. You can only add exponents when the **base is the same**.
2. **Forgetting to flip when the exponent is negative.** $2^{-3}$ is $\dfrac{1}{8}$, not $-8$.
3. **$a^0 = 0$ trap.** $a^0 = 1$ for any non-zero $a$. Only $0^0$ is undefined.
4. **Wrong order in $a^{m/n}$.** It does not matter whether you root first or power first, but on big numbers rooting first (to get a small integer) is far easier. $64^{5/6}$: root first to get 2, then $2^5=32$.
5. **Adding surds with different radicands.** $\sqrt{2}+\sqrt{3}\neq\sqrt{5}$. They cannot be combined.
6. **Conjugate sign error.** The conjugate of $\sqrt{5}+\sqrt{3}$ is $\sqrt{5}-\sqrt{3}$, not $\sqrt{5}+\sqrt{3}$ again.
7. **Forgetting a negative root.** When solving $x^2-x-k=0$, check that you pick the positive root, since a length or a value cannot be negative.

## 6. Practice questions

Do the first ten without a time limit. Do Level 2 with 90 seconds each. Do Level 3 like a real exam.

### Level 1: single idea

1. Simplify $\sqrt{180}$.
2. Simplify $\sqrt{12}+\sqrt{27}$.
3. Rationalise $\dfrac{1}{\sqrt{7}+\sqrt{5}}$.
4. Rationalise $\dfrac{\sqrt{5}+1}{\sqrt{5}-1}$.
5. Find $27^{2/3}$.
6. Find $4^{-3/2}$.
7. Which is larger: $3^{1/2}$ or $2^{1/3}$?
8. Find $x$ if $x = \sqrt{12+\sqrt{12+\sqrt{12+\cdots}}}$.
9. Find $x$ if $5^{x-2}\times3^{2x-3} = 135$.
10. Find $\sqrt{3}\times\sqrt{75}$.

### Level 2: mixed

11. Find $\sqrt{0.0049}$.
12. Find $32^{4/5}$.
13. Find $x$ if $3^{x+1}=9^{x-1}$.
14. Find $\sqrt{8}\times\sqrt{18}$.
15. Rationalise $\dfrac{1}{2+\sqrt{3}}$.
16. Find $x$ if $2^{3x}=512$.
17. Simplify $\sqrt{5+2\sqrt{6}}$.
18. Simplify $(a^2 b^{-1})^3\times(a^{-1}b^2)^2$. (Express in terms of $a$ and $b$.)
19. Simplify $5\sqrt{45}-3\sqrt{20}$.
20. Find $\dfrac{4^3\times8^{-2}}{2^5}$.
21. Find $(\sqrt{3}+1)^2$.
22. Find $x$ if $3^{2x-1}=27$.
23. Simplify $\sqrt{3+2\sqrt{2}}$.
24. Find the cube root of $0.001$.
25. Find $(1/8)^{-2/3}$.

### Level 3: exam style

26. Find $\sqrt{6}\times\sqrt{54}$.
27. Which is larger: $5^{1/3}$ or $4^{1/2}$?
28. $2^{n+1}+2^n = k\times2^n$. Find $k$.
29. Find the value of $\left(\dfrac{x^a}{x^b}\right)^{a+b}\times\left(\dfrac{x^b}{x^c}\right)^{b+c}\times\left(\dfrac{x^c}{x^a}\right)^{c+a}$.
30. Simplify $\sqrt{11-6\sqrt{2}}$.
31. Find $x$ if $4^{2x+3}=2^{3x+8}$.
32. If $4^x=8^y$, find $x:y$.
33. Find $(0.0081)^{0.25}$.
34. Find $x$ if $x = \sqrt{2+\sqrt{2+\sqrt{2+\cdots}}}$.
35. Find $(\sqrt{2}+\sqrt{3})(\sqrt{2}-\sqrt{3})$.
36. Simplify $3\sqrt{12}-2\sqrt{75}+\sqrt{48}$.
37. Find $x$ and $y$ if $2^x\times4^y=32$ and $\dfrac{2^x}{4^y}=8$.
38. Find $\sqrt{\dfrac{5}{4}}$.
39. Find $\left(2^{1/3}+3^{1/3}\right)\left(2^{2/3}-6^{1/3}+3^{2/3}\right)$.
40. Find $\dfrac{3+\sqrt{5}}{2}-\dfrac{3-\sqrt{5}}{2}$.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | $6\sqrt{5}$ | $180=36\times5$, $\sqrt{36}=6$ |
| 2 | $5\sqrt{3}$ | $\sqrt{12}=2\sqrt{3}$, $\sqrt{27}=3\sqrt{3}$, sum $=5\sqrt{3}$ |
| 3 | $\frac{\sqrt{7}-\sqrt{5}}{2}$ | Conjugate: denom $= 7-5=2$ |
| 4 | $\frac{3+\sqrt{5}}{2}$ | Multiply by $\frac{\sqrt{5}+1}{\sqrt{5}+1}$: num $=6+2\sqrt{5}$, denom $=4$ |
| 5 | $9$ | $27^{2/3}=(\sqrt[3]{27})^2=3^2$ |
| 6 | $\frac{1}{8}$ | $4^{-3/2}=1/(\sqrt{4})^3=1/8$ |
| 7 | $3^{1/2}$ is larger | $(3^{1/2})^6=27$, $(2^{1/3})^6=4$ |
| 8 | $4$ | $x^2-x-12=0$, $(x-4)(x+3)=0$ |
| 9 | $x=3$ | $135=5^1\times3^3$, match exponents |
| 10 | $15$ | $\sqrt{225}=15$ |
| 11 | $0.07$ | $0.0049=49/10000$, $\sqrt{49}/100$ |
| 12 | $16$ | $(2^5)^{4/5}=2^4$ |
| 13 | $x=3$ | $3^{x+1}=3^{2x-2}$, $x+1=2x-2$, $x=3$ |
| 14 | $12$ | $\sqrt{144}=12$ |
| 15 | $2-\sqrt{3}$ | Conjugate: denom $=(4-3)=1$ |
| 16 | $x=3$ | $512=2^9$, $3x=9$ |
| 17 | $\sqrt{2}+\sqrt{3}$ | $(\sqrt{2}+\sqrt{3})^2=5+2\sqrt{6}$ |
| 18 | $a^4 b$ | $a^{6-2}\cdot b^{-3+4}$ |
| 19 | $9\sqrt{5}$ | $15\sqrt{5}-6\sqrt{5}$ |
| 20 | $\frac{1}{32}$ | $2^{6-6-5}=2^{-5}$ |
| 21 | $4+2\sqrt{3}$ | $(a+b)^2=a^2+2ab+b^2$ |
| 22 | $x=2$ | $3^{2x-1}=3^3$, $2x-1=3$, $x=2$ |
| 23 | $\sqrt{2}+1$ | $(\sqrt{2}+1)^2=3+2\sqrt{2}$ |
| 24 | $0.1$ | $(10^{-3})^{1/3}=10^{-1}$ |
| 25 | $4$ | $(8^{1/3})^2=2^2=4$ |
| 26 | $18$ | $\sqrt{324}=18$ |
| 27 | $4^{1/2}$ is larger | $(5^{1/3})^6=25$, $(4^{1/2})^6=64$ |
| 28 | $k=3$ | $2^n(2+1)=3\cdot2^n$ |
| 29 | $1$ | Exponents sum to $a^2-b^2+b^2-c^2+c^2-a^2=0$ |
| 30 | $3-\sqrt{2}$ | $(3-\sqrt{2})^2=9-6\sqrt{2}+2=11-6\sqrt{2}$ |
| 31 | $x=2$ | $2^{4x+6}=2^{3x+8}$, $4x+6=3x+8$ |
| 32 | $3:2$ | $2^{2x}=2^{3y}$, $2x=3y$, $x/y=3/2$ |
| 33 | $0.3$ | $(81/10000)^{1/4}=3/10$ |
| 34 | $x=2$ | $x^2-x-2=0$, $(x-2)(x+1)=0$ |
| 35 | $-1$ | $(a+b)(a-b)=a^2-b^2=2-3=-1$ |
| 36 | $0$ | $6\sqrt{3}-10\sqrt{3}+4\sqrt{3}=0$ |
| 37 | $x=4$, $y=\frac{1}{2}$ | $x+2y=5$, $x-2y=3$; adding: $2x=8$ |
| 38 | $\frac{\sqrt{5}}{2}$ | $\sqrt{5}/\sqrt{4}=\sqrt{5}/2$ |
| 39 | $5$ | $a^3+b^3=(a+b)(a^2-ab+b^2)$; $a=2^{1/3}$, $b=3^{1/3}$, so $a^3+b^3=5$ |
| 40 | $\sqrt{5}$ | $(3+\sqrt{5})/2-(3-\sqrt{5})/2=2\sqrt{5}/2$ |
