# Algebra

> Read this like a class: an equation is a balance, and every operation must preserve that balance.

## 0. Start here: turn words into a relationship

Imagine balancing two sides of a scale. If you add, subtract, multiply, or divide one side, do the same to the other. That simple picture carries you from one-step equations to simultaneous equations and quadratics. Algebra questions ask you to find an unknown, describe how roots are related, test whether real roots exist, or simplify an expression without calculating every power directly.

First decide what the unknown represents and write the relationship. Solve it, then substitute your answer back into the original equation. For a quadratic word problem, also check which roots make sense in the story: a length or count cannot be negative.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Linear equations in one variable | 1 |
| Simultaneous linear equations in two variables | 2 |
| Consistency of linear systems (unique, infinite, no solution) | 3 |
| Word problems leading to linear equations | 4 |
| Solving quadratic equations by factorisation and formula | 5 |
| Relations between roots and coefficients | 6 |
| Symmetric expressions in roots ($\alpha^2+\beta^2$, $\alpha^3+\beta^3$) | 7 |
| Nature of roots and discriminant | 8 |
| Common roots between two quadratic equations | 9 |
| Maximum and minimum value of quadratic expressions | 10 |
| Standard algebraic identities ($x + \frac{1}{x}$, $x - \frac{1}{x}$) | 11 |
| Higher power identities ($x^4+\frac{1}{x^4}$, $x^5+\frac{1}{x^5}$) | 12 |
| Three-variable identity ($a^3+b^3+c^3-3abc$) | 13 |
| Quadratic word problems | 14 |
| Inequality comparison of quadratic roots (Banking type) | 15 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "System has infinitely many solutions" | Ratios are equal: $\dfrac{a_1}{a_2} = \dfrac{b_1}{b_2} = \dfrac{c_1}{c_2}$ |
| "System has no solution" | $\dfrac{a_1}{a_2} = \dfrac{b_1}{b_2} \neq \dfrac{c_1}{c_2}$ |
| "Roots are equal and real" | Discriminant $D = b^2 - 4ac = 0$ |
| "Roots are $\alpha, \beta$" | Sum $\alpha+\beta = -\dfrac{b}{a}$, Product $\alpha\beta = \dfrac{c}{a}$ |
| "If $x + \dfrac{1}{x} = k$" | $x^2 + \dfrac{1}{x^2} = k^2 - 2$, $x^3 + \dfrac{1}{x^3} = k^3 - 3k$ |
| "If $a + b + c = 0$" | $a^3 + b^3 + c^3 = 3abc$ |
| "Quantity A vs Quantity B" | Solve both quadratics and compare root sets |

## 3. The core idea

- **Linear system:** $a_1 x + b_1 y = c_1$, $a_2 x + b_2 y = c_2$.
- **Quadratic formula:** for $ax^2 + bx + c = 0$, $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.
- **Vieta's formulas:** $\alpha + \beta = -\dfrac{b}{a}$, $\alpha\beta = \dfrac{c}{a}$, and equation is $x^2 - (\alpha+\beta)x + \alpha\beta = 0$.
- **Discriminant:** $D = b^2 - 4ac$. $D > 0 \implies$ real and distinct; $D = 0 \implies$ real and equal; $D < 0 \implies$ complex/no real roots.
- **Extrema of $ax^2+bx+c$:** occurs at $x = -\dfrac{b}{2a}$; value is $\dfrac{4ac-b^2}{4a}$ (minimum if $a>0$, maximum if $a<0$).

## 4. Question-type walkthroughs

### Question type 1. Linear equations in one variable

**Idea:** expand brackets, collect like terms on one side, isolate $x$.

**Example:** Solve for $x$: $3(2x - 5) - 4(x - 2) = 11$.
- $6x - 15 - 4x + 8 = 11$.
- $2x - 7 = 11 \implies 2x = 18$.
- $x =$ **9**.

### Question type 2. Simultaneous linear equations in two variables

**Idea:** eliminate one variable by multiplying equations by suitable coefficients.

**Example:** Solve $3x + 2y = 23$ and $2x + 3y = 22$.
- Multiply equation 1 by 3 and equation 2 by 2: $9x + 6y = 69$ and $4x + 6y = 44$.
- Subtract: $5x = 25 \implies x = 5$.
- Substitute $x = 5$: $3(5) + 2y = 23 \implies 2y = 8 \implies y = 4$.
- Solution: **$x = 5, y = 4$**.

### Question type 3. Consistency of linear systems

**Idea:** compare $\dfrac{a_1}{a_2}, \dfrac{b_1}{b_2}, \dfrac{c_1}{c_2}$. Unique: $\neq$; Infinite: all equal; No solution: first two equal, third unequal.

**Example 1:** For what value of $k$ does $2x + ky = 7$ and $4x + 6y = 14$ have infinitely many solutions?
- $\dfrac{2}{4} = \dfrac{k}{6} = \dfrac{7}{14} \implies \dfrac{1}{2} = \dfrac{k}{6} \implies k =$ **3**.

**Example 2:** For what value of $p$ does $px + 3y = 5$ and $2x + 6y = 8$ have no solution?
- $\dfrac{p}{2} = \dfrac{3}{6} \neq \dfrac{5}{8} \implies \dfrac{p}{2} = \dfrac{1}{2} \implies p =$ **1**.

### Question type 4. Word problems leading to linear equations

**Idea:** express given statements as a system of linear equations.

**Example:** 5 pens and 3 notebooks cost Rs 125, while 3 pens and 5 notebooks cost Rs 155. Find the cost of 1 pen and 1 notebook.
- Let pen $= p$, notebook $= n$: $5p + 3n = 125$ and $3p + 5n = 155$.
- Add: $8p + 8n = 280 \implies p + n = 35$.
- Subtract: $2n - 2p = 30 \implies n - p = 15$.
- Add equations: $2n = 50 \implies n = 25$, so $p = 10$.
- Cost: **Pen = Rs 10, Notebook = Rs 25** (combined **Rs 35**).

### Question type 5. Solving quadratic equations by factorisation and formula

**Idea:** split the middle term into two numbers whose product is $ac$ and sum is $b$.

**Example:** Solve $2x^2 - 7x + 3 = 0$.
- Product $= 2 \times 3 = 6$, sum $= -7 \implies$ factors $-6, -1$.
- $2x^2 - 6x - x + 3 = 2x(x - 3) - 1(x - 3) = (2x - 1)(x - 3) = 0$.
- Roots: **$x = \dfrac{1}{2}, 3$**.

### Question type 6. Relations between roots and coefficients

**Idea:** $\alpha + \beta = -\dfrac{b}{a}$, $\alpha\beta = \dfrac{c}{a}$. New equation with roots $r_1, r_2$ is $x^2 - (r_1+r_2)x + r_1r_2 = 0$.

**Example:** If roots of $x^2 - 5x + 6 = 0$ are $\alpha$ and $\beta$, find the equation whose roots are $2\alpha$ and $2\beta$.
- $\alpha + \beta = 5$, $\alpha\beta = 6$.
- New sum $= 2(\alpha+\beta) = 10$. New product $= 4\alpha\beta = 24$.
- Equation: **$x^2 - 10x + 24 = 0$**.

### Question type 7. Symmetric expressions in roots

**Idea:** express required terms in $\alpha+\beta$ and $\alpha\beta$: $\alpha^2+\beta^2 = (\alpha+\beta)^2 - 2\alpha\beta$; $\alpha^3+\beta^3 = (\alpha+\beta)^3 - 3\alpha\beta(\alpha+\beta)$.

**Example:** If $\alpha, \beta$ are roots of $x^2 - 6x + 4 = 0$, find $\alpha^2 + \beta^2$ and $\alpha^3 + \beta^3$.
- $\alpha + \beta = 6$, $\alpha\beta = 4$.
- $\alpha^2 + \beta^2 = 6^2 - 2(4) = 36 - 8 =$ **28**.
- $\alpha^3 + \beta^3 = 6^3 - 3(4)(6) = 216 - 72 =$ **144**.

### Question type 8. Nature of roots and discriminant

**Idea:** $D = b^2 - 4ac$. Equal roots $\implies D = 0$. Real roots $\implies D \ge 0$.

**Example:** If $3x^2 - kx + 12 = 0$ has equal roots, find $k$.
- $D = (-k)^2 - 4(3)(12) = k^2 - 144 = 0$.
- $k^2 = 144 \implies k =$ **$\pm 12$**.

### Question type 9. Common roots between two quadratic equations

**Idea:** find roots of the simpler equation and substitute into the second, or factorise both.

**Example:** Find the common root of $x^2 - 5x + 6 = 0$ and $x^2 - 7x + 12 = 0$.
- Roots of first: $x = 2, 3$.
- Roots of second: $x = 3, 4$.
- Common root: **3**.

### Question type 10. Maximum and minimum value of quadratic expressions

**Idea:** for $ax^2 + bx + c$, vertex at $x = -\dfrac{b}{2a}$, value $= \dfrac{4ac-b^2}{4a}$.

**Example:** Find the minimum value of $2x^2 - 8x + 11$.
- Here $a = 2 > 0$ (has minimum). Vertex at $x = -\dfrac{-8}{2(2)} = 2$.
- Minimum value $= 2(2)^2 - 8(2) + 11 = 8 - 16 + 11 =$ **3**.

### Question type 11. Standard algebraic identities ($x + \frac{1}{x}$)

**Idea:** $(x + \frac{1}{x})^2 = x^2 + \frac{1}{x^2} + 2 \implies x^2 + \frac{1}{x^2} = k^2 - 2$; $x^3 + \frac{1}{x^3} = k^3 - 3k$.

**Example:** If $x + \dfrac{1}{x} = 3$, find $x^2 + \dfrac{1}{x^2}$ and $x^3 + \dfrac{1}{x^3}$.
- $x^2 + \dfrac{1}{x^2} = 3^2 - 2 =$ **7**.
- $x^3 + \dfrac{1}{x^3} = 3^3 - 3(3) = 27 - 9 =$ **18**.

### Question type 12. Higher power identities

**Idea:** $x^4 + \dfrac{1}{x^4} = (x^2 + \dfrac{1}{x^2})^2 - 2$; $x^5 + \dfrac{1}{x^5} = (x^2 + \dfrac{1}{x^2})(x^3 + \dfrac{1}{x^3}) - (x + \dfrac{1}{x})$.

**Example:** If $x + \dfrac{1}{x} = 3$, find $x^5 + \dfrac{1}{x^5}$.
- $x^2 + \dfrac{1}{x^2} = 7$, $x^3 + \dfrac{1}{x^3} = 18$.
- $x^5 + \dfrac{1}{x^5} = (7 \times 18) - 3 = 126 - 3 =$ **123**.

### Question type 13. Three-variable identity ($a^3+b^3+c^3-3abc$)

**Idea:** if $a + b + c = 0$, then $a^3 + b^3 + c^3 = 3abc$.

**Example:** Evaluate $15^3 + (-10)^3 + (-5)^3$.
- $15 + (-10) + (-5) = 0 \implies a^3 + b^3 + c^3 = 3(15)(-10)(-5) = 3 \times 750 =$ **2250**.

### Question type 14. Quadratic word problems

**Idea:** set up an equation from word description, form standard quadratic $ax^2+bx+c=0$.

**Example:** The product of two consecutive positive even numbers is 168. Find the numbers.
- Let numbers be $x$ and $x+2$: $x(x+2) = 168 \implies x^2 + 2x - 168 = 0$.
- $(x + 14)(x - 12) = 0 \implies x = 12$ (as $x > 0$).
- Numbers: **12 and 14**.

### Question type 15. Inequality comparison of quadratic roots (Banking type)

**Idea:** solve both equations for $x$ and $y$, compare all pairs $(x_i, y_j)$.

**Example:** Compare $x$ and $y$: (I) $x^2 - 7x + 12 = 0$, (II) $y^2 - 9y + 20 = 0$.
- Equation I: $(x - 3)(x - 4) = 0 \implies x = 3, 4$.
- Equation II: $(y - 4)(y - 5) = 0 \implies y = 4, 5$.
- Comparing: $3 < 4, 3 < 5, 4 \le 4, 4 < 5 \implies \mathbf{x \le y}$.

## 5. Before you practise

**Your turn:** Solve $3(x-2)=12$, then check your answer in the original equation.

**Think it through:** Divide both sides by 3: $x-2=4$. Add 2: $x=\mathbf{6}$. Check: $3(6-2)=3\times4=12$.

### Quick revision

- Keep an equation balanced by applying the same operation to both sides.
- For a quadratic, identify $a,b,c$ before using the discriminant or quadratic formula.
- Use the sum and product of roots when an expression is symmetric in the roots.
- The sign of $a$ tells whether a quadratic has a minimum ($a>0$) or maximum ($a<0$).

### Common mistakes

1. Changing a sign when moving a term without applying the operation to both sides.
2. Forgetting the denominator $2a$ in the quadratic formula.
3. Using root sum $b/a$ instead of $-b/a$.
4. Treating a negative discriminant as real roots.
5. Keeping an algebraic root that cannot fit the word problem.

## 6. Practice

1. Solve for $x$: $5(2x - 3) - 3(3x - 1) = 4$.
2. Solve for $x$: $\dfrac{2x + 5}{3} - \dfrac{x - 2}{4} = 3$.
3. Solve the system: $3x + 2y = 19$ and $2x + 5y = 20$. Find the value of $x + y$.
4. For what value of $k$ will the system $2x + ky = 7$ and $4x + 6y = 14$ have infinitely many solutions?
5. For what value of $p$ will the system $px + 3y = 5$ and $2x + 6y = 8$ have no solution?
6. 4 tables and 3 chairs cost Rs 2250, while 3 tables and 4 chairs cost Rs 1950. Find the combined cost of 1 table and 1 chair.
7. Solve the quadratic equation $x^2 - 7x + 12 = 0$.
8. Solve the quadratic equation $2x^2 + 5x - 12 = 0$.
9. If $\alpha$ and $\beta$ are the roots of $x^2 - 8x + 15 = 0$, find the value of $\alpha^2 + \beta^2$.
10. If $\alpha$ and $\beta$ are the roots of $x^2 - 5x + 3 = 0$, find the value of $\alpha^3 + \beta^3$.
11. If $\alpha$ and $\beta$ are the roots of $2x^2 - 6x + 1 = 0$, find the value of $\dfrac{1}{\alpha} + \dfrac{1}{\beta}$.
12. Find the quadratic equation whose roots are $5$ and $-2$.
13. If the roots of $3x^2 - 12x + k = 0$ are equal, find the value of $k$.
14. For what value of $m$ does the equation $x^2 - 2(m + 1)x + m^2 = 0$ have real and equal roots?
15. Determine the nature of the roots of $2x^2 - 4x + 3 = 0$.
16. Find the common root between $x^2 - 5x + 6 = 0$ and $x^2 - 7x + 12 = 0$.
17. Find the minimum value of the quadratic expression $2x^2 - 8x + 15$.
18. Find the maximum value of the expression $12 - 6x - x^2$.
19. If $x + \dfrac{1}{x} = 4$, find $x^2 + \dfrac{1}{x^2}$.
20. If $x + \dfrac{1}{x} = 3$, find $x^3 + \dfrac{1}{x^3}$.
21. If $x - \dfrac{1}{x} = 5$, find $x^2 + \dfrac{1}{x^2}$.
22. If $x - \dfrac{1}{x} = 4$, find $x^3 - \dfrac{1}{x^3}$.
23. If $x + \dfrac{1}{x} = 3$, find $x^4 + \dfrac{1}{x^4}$.
24. If $x + \dfrac{1}{x} = 3$, find $x^5 + \dfrac{1}{x^5}$.
25. If $x + \dfrac{1}{x} = 2$, find the value of $x^{100} + \dfrac{1}{x^{100}}$.
26. If $x + \dfrac{1}{x} = -2$, find the value of $x^{99} + \dfrac{1}{x^{99}}$.
27. If $a + b + c = 0$, find the value of $\dfrac{a^3 + b^3 + c^3}{abc}$.
28. Evaluate $(28)^3 + (-15)^3 + (-13)^3$.
29. The sum of a number and its reciprocal is $\dfrac{10}{3}$. Find the number.
30. The product of two consecutive positive even integers is 224. Find the integers.
31. The length of a rectangle is 3 m more than its breadth, and its area is 70 $\text{m}^2$. Find its perimeter.
32. Compare $x$ and $y$: (I) $x^2 - 9x + 20 = 0$, (II) $y^2 - 11y + 30 = 0$.
33. Compare $x$ and $y$: (I) $x^2 - 13x + 40 = 0$, (II) $y^2 - 7y + 12 = 0$.
34. Compare $x$ and $y$: (I) $x^2 - 7x + 10 = 0$, (II) $y^2 - 8y + 15 = 0$.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 16 | $10x - 15 - 9x + 3 = 4 \implies x - 12 = 4 \implies x = 16$ |
| 2 | 2 | $4(2x+5) - 3(x-2) = 36 \implies 5x + 26 = 36 \implies x = 2$ |
| 3 | 7 | Multiplying gives $x = 5, y = 2 \implies x + y = 7$ |
| 4 | 3 | $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2} \implies \frac{2}{4} = \frac{k}{6} \implies k = 3$ |
| 5 | 1 | $\frac{p}{2} = \frac{3}{6} \neq \frac{5}{8} \implies p = 1$ |
| 6 | Rs 600 | Add both equations: $7(t + c) = 4200 \implies t + c = 600$ |
| 7 | 3, 4 | $(x - 3)(x - 4) = 0 \implies x = 3\text{ or }4$ |
| 8 | $\frac{3}{2}, -4$ | $(2x - 3)(x + 4) = 0 \implies x = \frac{3}{2}\text{ or }-4$ |
| 9 | 34 | $(\alpha+\beta)^2 - 2\alpha\beta = 8^2 - 2(15) = 64 - 30 = 34$ |
| 10 | 80 | $(\alpha+\beta)^3 - 3\alpha\beta(\alpha+\beta) = 5^3 - 3(3)(5) = 125 - 45 = 80$ |
| 11 | 6 | $\frac{\alpha+\beta}{\alpha\beta} = \frac{3}{1/2} = 6$ |
| 12 | $x^2 - 3x - 10 = 0$ | $x^2 - (5 + (-2))x + (5)(-2) = x^2 - 3x - 10 = 0$ |
| 13 | 12 | $b^2 - 4ac = 0 \implies 144 - 12k = 0 \implies k = 12$ |
| 14 | $-\frac{1}{2}$ | $D = 4(m+1)^2 - 4m^2 = 4(2m+1) = 0 \implies m = -\frac{1}{2}$ |
| 15 | No real roots (imaginary) | $D = (-4)^2 - 4(2)(3) = 16 - 24 = -8 < 0$ |
| 16 | 3 | Roots are $\{2, 3\}$ and $\{3, 4\}$; common root is 3 |
| 17 | 7 | Min at $x = -\frac{-8}{2(2)} = 2$; value $= 2(4) - 16 + 15 = 7$ |
| 18 | 21 | Max at $x = -\frac{-6}{2(-1)} = -3$; value $= 12 - 6(-3) - 9 = 21$ |
| 19 | 14 | $k^2 - 2 = 4^2 - 2 = 14$ |
| 20 | 18 | $k^3 - 3k = 3^3 - 3(3) = 27 - 9 = 18$ |
| 21 | 27 | $k^2 + 2 = 5^2 + 2 = 27$ |
| 22 | 76 | $k^3 + 3k = 4^3 + 3(4) = 64 + 12 = 76$ |
| 23 | 47 | $x^2 + \frac{1}{x^2} = 7 \implies 7^2 - 2 = 47$ |
| 24 | 123 | $(7 \times 18) - 3 = 126 - 3 = 123$ |
| 25 | 2 | $x + \frac{1}{x} = 2 \implies x = 1 \implies 1^{100} + 1 = 2$ |
| 26 | $-2$ | $x + \frac{1}{x} = -2 \implies x = -1 \implies (-1)^{99} + (-1) = -2$ |
| 27 | 3 | $a+b+c = 0 \implies a^3 + b^3 + c^3 = 3abc \implies \frac{3abc}{abc} = 3$ |
| 28 | 16380 | $28 - 15 - 13 = 0 \implies 3(28)(-15)(-13) = 16380$ |
| 29 | 3 or $\frac{1}{3}$ | $3x^2 - 10x + 3 = 0 \implies (3x-1)(x-3) = 0 \implies x = 3\text{ or }\frac{1}{3}$ |
| 30 | 14 and 16 | $x(x+2) = 224 \implies (x-14)(x+16) = 0 \implies x = 14, 16$ |
| 31 | 34 m | $b(b+3) = 70 \implies b = 7, l = 10 \implies 2(10 + 7) = 34$ |
| 32 | $x \le y$ | $x = \{4, 5\}, y = \{5, 6\} \implies x \le y$ |
| 33 | $x > y$ | $x = \{5, 8\}, y = \{3, 4\} \implies x > y$ |
| 34 | Cannot be determined | $x = \{2, 5\}, y = \{3, 5\} \implies$ overlapping ranges |
