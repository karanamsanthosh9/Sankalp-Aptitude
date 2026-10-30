# Average

## 1. Core Concept & Fundamental Equations

- Average $=\frac{\text{sum of observations}}{\text{number of observations}}$; therefore sum $=n\times$ average.
- Adding a value $x$ changes the total by $x$; replacing $a$ with $b$ changes it by $b-a$.
- Combined average $=\frac{n_1a_1+n_2a_2}{n_1+n_2}$.
- For equally spaced values, average is the midpoint of the first and last values.
- If each of $n$ values changes by $k$, the average changes by $k$.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Total = count × average | A group gains, loses, or replaces members. | Group sizes or averages are unknown; set up equations. |
| Deviation from assumed average | Values cluster around a convenient number. | Deviations are as hard as the original calculation. |
| Weighted average | Groups have different sizes. | Group sizes are equal; simple mean is faster. |
| Midpoint property | Values are in arithmetic progression. | Values are irregular or weighted. |
| Difference method | One observation is replaced. | Several values change; update the total explicitly. |

## 3. Model-Wise Question Classification

### Model 1: Find the total from an average
**Problem:** The average of 8 numbers is 15. Find their sum.
- **Method A:** Average $=S/8=15$, so $S=120$.
- **Method B:** $8\times15=120$. **Answer: $120$.**

### Model 2: Replace one observation
**Problem:** The average of 10 values is 24. Replacing 18 by 38 changes the average to what?
- **Method A:** Old sum $=240$; new sum $=240-18+38=260$; new average $=26$.
- **Method B:** Replacement adds $20$ to total, so average rises by $20/10=2$. **Answer: $26$.**

### Model 3: Combined average
**Problem:** 20 students average 70 marks and 30 students average 80. Find the combined average.
- **Method A:** Total $=20(70)+30(80)=3800$; divide by $50$ to get $76$.
- **Method B:** Weighted mean: $70+\frac{30}{50}(80-70)=76$. **Answer: $76$.**

### Model 4: Consecutive integers
**Problem:** Find the average of integers from 21 through 39.
- **Method A:** There are 19 integers; their sum is $19(21+39)/2=570$, average $=30$.
- **Method B:** Equally spaced sequence midpoint: $(21+39)/2=30$. **Answer: $30$.**

### Model 5: Joining or leaving a group
**Problem:** The average age of 5 people is 24. A sixth person joins, and the average becomes 25. Find the new person's age.
- **Method A:** Old total $=120$; new total $=150$; age $=30$.
- **Method B:** New total is $6\times25=150$; subtract the old total $5\times24=120$. **Answer: $30$.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Missing observations, replacement, age groups, and weighted averages.
- **RRB lens:** Consecutive numbers, marks, and quick group-joining/leaving questions.
- **AP State / PSU lens:** Combined averages in production, salary, and multi-group data.

## 5. Common Traps & Speed Killers

1. **Averaging group averages directly:** weight each average by group size.
2. **Forgetting count changes:** adding a member changes both total and denominator.
3. **Using a simple mean for equally spaced values:** midpoint gives the answer immediately.

## 6. Quick Check

1. Six numbers have an average of $14$. What is their sum?

<details>
<summary>Reveal answer</summary>

$84$.
</details>

2. One group of 10 has average $60$; another group of 20 has average $75$. Find the combined average.

<details>
<summary>Reveal answer</summary>

$70$: total $=(10\cdot60+20\cdot75)/30$.
</details>