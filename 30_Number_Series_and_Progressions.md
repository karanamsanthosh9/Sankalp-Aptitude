# Number Series and Progressions: Model-wise Notes

## Part 1. What comes from this topic

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Model |
|---|---|
| Find the next term: constant difference | 1 |
| Find the next term: constant ratio | 2 |
| Find the next term: squares or square-based | 3 |
| Find the next term: cubes or cube-based | 4 |
| Find the next term: prime numbers | 5 |
| Alternating or interleaved series | 6 |
| Two-step or increasing-difference series | 7 |
| Missing number in the middle of a series | 8 |
| Wrong number in a series | 9 |
| AP: nth term and sum of terms | 10 |
| GP: nth term and sum of terms | 11 |
| Arithmetic and geometric means | 12 |
| Number of terms in AP or GP | 13 |
| Inserting means between two numbers | 14 |
| Sum to infinity of a GP | 15 |

## Part 2. What data is usually given

| Data you will see | What it means |
|---|---|
| A list of numbers with a blank at the end | Find the next term |
| A list with one term missing in the middle | Find the missing term |
| A list where one term does not fit | Find the wrong (odd) term |
| "AP", "arithmetic progression" | Constant difference series |
| "GP", "geometric progression" | Constant ratio series |
| "First term $a$, common difference $d$" | Use $T_n = a+(n-1)d$ |
| "First term $a$, common ratio $r$" | Use $T_n = a \cdot r^{n-1}$ |
| "Sum of first $n$ terms" | Use the AP or GP sum formula |
| "Insert $k$ means between $p$ and $q$" | Find $d$ or $r$ for $k+2$ terms |
| "Sum to infinity" | GP with $|r|<1$; use $S=\dfrac{a}{1-r}$ |

## Part 3. The base idea (read once)

- **AP** (arithmetic progression): each term differs by a constant $d$. $T_n = a+(n-1)d$, $S_n = \dfrac{n}{2}[2a+(n-1)d]$.
- **GP** (geometric progression): each term is multiplied by a constant $r$. $T_n = a \cdot r^{n-1}$, $S_n = \dfrac{a(r^n-1)}{r-1}$ (for $r \neq 1$).
- **Sum to infinity of GP**: $S_\infty = \dfrac{a}{1-r}$, valid only when $|r| < 1$.
- For a **missing or wrong term**: work out the pattern (difference, ratio, squares, primes), then check which term breaks it.
- **Number of terms in AP**: $n = \dfrac{l - a}{d} + 1$, where $l$ is the last term.

## Part 4. Models

### Model 1. Constant-difference (arithmetic) series

**Idea:** subtract consecutive terms to get the common difference $d$, then add $d$ to find the next term.

**Example 1:** $3, 7, 11, 15, ?$
- Differences: $4, 4, 4$. Common difference $d = 4$.
- Next term $= 15 + 4 =$ **19**.

**Example 2:** $2, 5, 10, 17, 26, ?$
- Differences: $3, 5, 7, 9$. The differences increase by $2$ each time.
- Next difference $= 11$. Next term $= 26 + 11 =$ **37**.

### Model 2. Constant-ratio (geometric) series

**Idea:** divide consecutive terms to get the common ratio $r$, then multiply to find the next term.

**Example 1:** $3, 6, 12, 24, ?$
- Ratio $= 2$. Next term $= 24 \times 2 =$ **48**.

**Example 2:** $162, 54, 18, 6, ?$
- Ratio $= \dfrac{1}{3}$. Next term $= 6 \times \dfrac{1}{3} =$ **2**.

### Model 3. Square-based series

**Idea:** check if terms are perfect squares, or squares $\pm$ a constant, or $n^2 \pm n$.

**Example 1:** $1, 4, 9, 16, 25, ?$
- Terms are $1^2, 2^2, 3^2, 4^2, 5^2$. Next $= 6^2 =$ **36**.

**Example 2:** $2, 5, 10, 17, 26, ?$
- Terms are $1^2+1, 2^2+1, 3^2+1, 4^2+1, 5^2+1$. Next $= 6^2+1 =$ **37**.

### Model 4. Cube-based series

**Idea:** check if terms are perfect cubes or cubes $\pm$ a constant.

**Example 1:** $1, 8, 27, 64, ?$
- Terms are $1^3, 2^3, 3^3, 4^3$. Next $= 5^3 =$ **125**.

**Example 2:** $2, 9, 28, 65, ?$
- Terms are $1^3+1, 2^3+1, 3^3+1, 4^3+1$. Next $= 5^3+1 =$ **126**.

### Model 5. Prime-number series

**Idea:** list the primes in order: $2, 3, 5, 7, 11, 13, 17, 19, 23, \ldots$ and match the pattern.

**Example 1:** $2, 3, 5, 7, 11, 13, ?$
- Consecutive primes. Next prime $=$ **17**.

**Example 2:** $4, 6, 10, 14, 22, 26, ?$
- Terms are $2 \times$ (consecutive primes): $2\times2, 2\times3, 2\times5, 2\times7, 2\times11, 2\times13$. Next $= 2\times17 =$ **34**.

### Model 6. Alternating / interleaved series

**Idea:** split the series into two separate sub-series by taking odd-position and even-position terms, then find each pattern independently.

**Example 1:** $2, 3, 4, 6, 6, 12, 8, ?$
- Odd positions: $2, 4, 6, 8$ (add 2). Even positions: $3, 6, 12, ?$ (multiply by 2). Next even-position term $= 12\times2 =$ **24**.

**Example 2:** $1, 2, 4, 3, 9, 4, ?$
- Odd positions: $1, 4, 9, ?$ (perfect squares $\to$ next $= 16$). Even positions: $2, 3, 4$ (add 1). Blank is in odd position $\to$ **16**.

### Model 7. Two-step / triangular-number series

**Idea:** the differences themselves form an AP. Take differences of differences (second-order difference) to confirm a constant.

**Example 1:** $1, 2, 4, 7, 11, 16, ?$
- Differences: $1, 2, 3, 4, 5$. Second differences: all $1$.
- Next difference $= 6$. Next term $= 16 + 6 =$ **22**.

**Example 2:** $5, 7, 10, 14, 19, 25, ?$
- Differences: $2, 3, 4, 5, 6$. Next difference $= 7$.
- Next term $= 25 + 7 =$ **32**.

### Model 8. Missing number in the middle

**Idea:** establish the rule from the known terms, then apply it to the blank.

**Example 1:** $6, ?, 24, 48$
- Ratio $= 2$ (each term doubles). Missing term $= 6\times2 =$ **12**.

**Example 2:** $3, 7, ?, 19, 27$
- Differences: $4, ?, ?, 8$. The differences alternate $4, 8, 4, 8$. So the missing difference $= 8$. Missing term $= 7 + 8 =$ **15**.

### Model 9. Wrong number in a series

**Idea:** establish the correct rule from the majority of terms, then identify the one term that breaks the rule.

**Example 1:** $1, 2, 4, 8, 15, 32$
- Rule: powers of 2 ($1, 2, 4, 8, 16, 32$). The term $15$ should be **16**.

**Example 2:** $3, 7, 15, 27, 63, 127$
- Rule: $2^n - 1$: $3, 7, 15, 31, 63, 127$. The term $27$ should be **31**.

### Model 10. AP: nth term and sum

**Idea:** $T_n = a + (n-1)d$ and $S_n = \dfrac{n}{2}[2a + (n-1)d]$.

**Example 1:** Find the 15th term of $3, 7, 11, \ldots$
- $a=3$, $d=4$. $T_{15} = 3 + 14\times4 = 3 + 56 =$ **59**.

**Example 2:** Find the sum of the first 20 terms of $5, 8, 11, \ldots$
- $a=5$, $d=3$, $n=20$. $S_{20} = \dfrac{20}{2}[10 + 19\times3] = 10\times67 =$ **670**.

### Model 11. GP: nth term and sum

**Idea:** $T_n = a \cdot r^{n-1}$ and $S_n = \dfrac{a(r^n - 1)}{r - 1}$.

**Example 1:** Find the 8th term of $2, 6, 18, \ldots$
- $a=2$, $r=3$. $T_8 = 2\times3^7 = 2\times2187 =$ **4374**.

**Example 2:** Find the sum of the first 6 terms of $3, 6, 12, \ldots$
- $a=3$, $r=2$. $S_6 = \dfrac{3(2^6-1)}{2-1} = 3\times63 =$ **189**.

### Model 12. Arithmetic and geometric means

**Idea:** AM of an AP $= \dfrac{a+l}{2}$. GM of a GP $= (T_1 \times T_2 \times \cdots \times T_n)^{1/n}$.

**Example 1:** Find the sum of the AP $4, 8, 12, \ldots, 40$.
- AM $= \dfrac{4+40}{2} = 22$. Number of terms $= \dfrac{40-4}{4}+1 = 10$. Sum $= 10\times22 =$ **220**.

**Example 2:** Find the GM of the GP $2, 4, 8, 16, 32$.
- Product $= 2\times4\times8\times16\times32 = 2^{15}$. GM $= (2^{15})^{1/5} = 2^3 =$ **8**.

### Model 13. Number of terms in an AP or GP

**Idea:** AP: $n = \dfrac{l-a}{d}+1$. GP: solve $a \cdot r^{n-1} = l$ for $n$.

**Example 1:** How many terms in the AP $8, 11, 14, \ldots, 56$?
- $n = \dfrac{56-8}{3}+1 = 16+1 =$ **17**.

**Example 2:** Find the sum of all odd numbers from 1 to 99.
- AP: $a=1$, $l=99$, $d=2$. $n=50$. Sum $= \dfrac{50}{2}(1+99) = 25\times100 =$ **2500**.

### Model 14. Inserting means between two numbers

**Idea:** inserting $k$ means creates $k+2$ terms total. For AP: $d = \dfrac{l-a}{k+1}$. For GP: $r = \left(\dfrac{l}{a}\right)^{1/(k+1)}$.

**Example 1:** Insert 4 arithmetic means between 3 and 23.
- $d = \dfrac{23-3}{5} = 4$. Means: **7, 11, 15, 19**.

**Example 2:** Insert 3 geometric means between 2 and 162.
- $r = \left(\dfrac{162}{2}\right)^{1/4} = 81^{1/4} = 3$. Means: **6, 18, 54**.

### Model 15. Sum to infinity of a GP

**Idea:** valid only when $|r| < 1$. $S_\infty = \dfrac{a}{1-r}$.

**Example 1:** Find $1 + \dfrac{1}{2} + \dfrac{1}{4} + \cdots$
- $a=1$, $r=\dfrac{1}{2}$. $S_\infty = \dfrac{1}{1-\frac{1}{2}} =$ **2**.

**Example 2:** Find $\dfrac{1}{3} + \dfrac{1}{9} + \dfrac{1}{27} + \cdots$
- $a=\dfrac{1}{3}$, $r=\dfrac{1}{3}$. $S_\infty = \dfrac{\frac{1}{3}}{\frac{2}{3}} =$ **$\dfrac{1}{2}$**.

## Part 5. Practice

1. Find the next term: $2, 5, 8, 11, ?$
2. Find the next term: $3, 9, 27, 81, ?$
3. Find the next term: $1, 4, 9, 16, 25, ?$
4. Find the next term: $1, 8, 27, 64, ?$
5. Find the next term: $2, 3, 5, 7, 11, ?$ (prime series)
6. Find the next term: $1, 1, 2, 3, 3, 9, 4, ?$ (alternating: odd position $+1$, even position $\times 3$)
7. Find the next term: $2, 3, 5, 8, 12, 17, ?$
8. Find the missing term: $5, ?, 20, 40$
9. Find the wrong term: $1, 3, 7, 15, 30, 63$
10. Find the 15th term of the AP $2, 5, 8, \ldots$
11. Find the sum of the first 10 terms of the AP $1, 4, 7, \ldots$
12. Find the 6th term of the GP $2, 4, 8, \ldots$
13. Find the sum of the first 5 terms of the GP $3, 6, 12, \ldots$
14. Insert 2 arithmetic means between 5 and 20.
15. Insert 2 geometric means between 4 and 108.
16. Find the sum to infinity: $9 + 3 + 1 + \cdots$
17. How many terms are in the AP $5, 10, 15, \ldots, 100$?
18. Find the wrong term: $2, 4, 8, 16, 36, 64$
19. Find the missing term: $8, ?, 32$ (GP)
20. Find the sum $1 + 2 + 3 + \cdots + 50$.
21. Find the next term: $1, 3, 6, 10, 15, ?$ (triangular numbers)
22. Find the next term: $2, 6, 12, 20, 30, ?$
23. In an AP the 3rd term is 7 and the 7th term is 15. Find the first term.
24. How many terms are in the GP $3, 6, 12, \ldots, 384$?
25. The AP is $100, 95, 90, \ldots$ At which term does it reach 0?
26. In a GP the 1st term is 2 and the 4th term is 54. Find the common ratio.
27. Find the sum of all even numbers from 2 to 40.
28. Find the next term of the Fibonacci series: $0, 1, 1, 2, 3, 5, 8, 13, ?$
29. In an AP the 5th term is 17 and the 10th term is 32. Find the common difference.
30. In a GP the 2nd term is 6 and the 5th term is 162. Find the common ratio.
31. Find the wrong term: $7, 14, 21, 28, 36, 42$
32. The sum of the first $n$ terms of an AP is $3n^2 + 2n$. Find the 5th term.
33. Find the next term: $2, 4, 7, 11, 16, 22, ?$
34. Find the sum to infinity: $16 + 8 + 4 + 2 + \cdots$
35. The $n$-th term of an AP is $4n - 3$. Find the sum of the first 10 terms.
36. A GP has first term 1 and common ratio 2. Find the ratio of the sum of the first 4 terms to the sum of the first 2 terms.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 14 | $d=3$; $11+3$ |
| 2 | 243 | $r=3$; $81\times3$ |
| 3 | 36 | $n^2$ pattern; $6^2$ |
| 4 | 125 | $n^3$ pattern; $5^3$ |
| 5 | 13 | Next prime after 11 |
| 6 | 27 | Even positions: $1,3,9,27$ ($\times3$) |
| 7 | 23 | Differences $1,2,3,4,5$; next diff $=6$; $17+6$ |
| 8 | 10 | GP ratio $=2$; $5\times2$ |
| 9 | 30 (should be 31) | Rule: $2^n-1$; $2^5-1=31$ |
| 10 | 44 | $T_{15}=2+14\times3$ |
| 11 | 145 | $S_{10}=\frac{10}{2}(2+27)$ |
| 12 | 64 | $T_6=2\times2^5$ |
| 13 | 93 | $S_5=\frac{3(2^5-1)}{1}$ |
| 14 | 10, 15 | $d=\frac{20-5}{3}=5$ |
| 15 | 12, 36 | $r=\left(\frac{108}{4}\right)^{1/3}=3$ |
| 16 | 13.5 | $S_\infty=\frac{9}{1-\frac{1}{3}}$ |
| 17 | 20 | $n=\frac{100-5}{5}+1$ |
| 18 | 36 (should be 32) | Powers of 2; $2^5=32$ |
| 19 | 16 | $r=2$; $8\times2$ |
| 20 | 1275 | $S=\frac{50\times51}{2}$ |
| 21 | 21 | Triangular; diff increases by 1; $15+6$ |
| 22 | 42 | $n(n+1)$ pattern; $6\times7$ |
| 23 | $a=3$ | $a+2d=7$, $a+6d=15$; $d=2$, $a=3$ |
| 24 | 8 | $3\times2^{n-1}=384$; $2^{n-1}=128=2^7$; $n=8$ |
| 25 | 21st term | $n=\frac{0-100}{-5}+1=21$ |
| 26 | 3 | $ar^3=54$; $r^3=27$ |
| 27 | 420 | $S=2\times(1+2+\cdots+20)=2\times210$ |
| 28 | 21 | Fibonacci: $8+13$ |
| 29 | 3 | $5d=32-17=15$; $d=3$ |
| 30 | 3 | $r^3=\frac{162}{6}=27$ |
| 31 | 36 (should be 35) | AP $d=7$; $28+7=35$ |
| 32 | 29 | $T_n=S_n-S_{n-1}=6n-1$; $T_5=29$ |
| 33 | 29 | Differences $2,3,4,5,6$; next $=7$; $22+7$ |
| 34 | 32 | $S_\infty=\frac{16}{1-0.5}$ |
| 35 | 190 | $a=1,d=4$; $S_{10}=\frac{10}{2}(2+36)$ |
| 36 | 5 | $S_4=15$, $S_2=3$; ratio $=5$ |
