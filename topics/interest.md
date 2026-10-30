# Simple & Compound Interest

## 1. Core Concept & Fundamental Equations

- Simple interest: $SI=PRT/100$; amount $A=P+SI$.
- Compound amount, compounded annually: $A=P(1+R/100)^T$; $CI=A-P$.
- For half-yearly compounding, use rate $R/2$ and periods $2T$; for quarterly, use $R/4$ and $4T$.
- Difference between CI and SI for two years: $P(R/100)^2$.
- For changing annual rates, multiply each year's growth factor: $A=P(1+r_1/100)(1+r_2/100)\cdots$.
- Depreciation uses $A=P(1-R/100)^T$.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| SI per year | Principal and rate stay constant. | Interest is compounded or principal changes. |
| Growth multiplier | CI, population growth, or depreciation. | The problem explicitly uses simple interest. |
| Two-year CI-SI difference | Exactly two years with annual compounding. | Other periods/frequencies apply. |
| Year-by-year factors | Rates vary by year. | Rate is constant; use a single power. |
| Assume a convenient principal | Only ratios or percentage comparisons matter. | Actual principal is supplied and needed. |

## 3. Model-Wise Question Classification

### Model 1: Simple interest
**Problem:** Find SI on $5000$ at $8\%$ for 3 years.
- **Method A:** $SI=5000\times8\times3/100=1200$.
- **Method B:** Annual interest is $8\%$ of $5000=400$; three years gives $1200$. **Answer: $1200$.**

### Model 2: Compound interest annually
**Problem:** Find CI on $10,000$ at $10\%$ for 2 years.
- **Method A:** Amount $=10000(1.1)^2=12100$; CI $=2100$.
- **Method B:** First-year interest $1000$; second-year interest on $11,000$ is $1100$. Total $=2100$. **Answer: $2100$.**

### Model 3: CI-SI difference
**Problem:** Find the difference between CI and SI on $8000$ at $5\%$ for 2 years.
- **Method A:** SI $=800$; CI $=8000(1.05)^2-8000=820$; difference $=20$.
- **Method B:** $P(R/100)^2=8000(0.05)^2=20$. **Answer: $20$.**

### Model 4: Half-yearly compounding
**Problem:** Find amount on $4000$ at $10\%$ per annum for one year, compounded half-yearly.
- **Method A:** Rate per half-year $=5\%$; two periods: $4000(1.05)^2=4410$.
- **Method B:** Interest factors are $1.05\times1.05=1.1025$; amount $=4410$. **Answer: $4410$.**

### Model 5: Depreciation
**Problem:** A machine worth $50,000$ depreciates by $10\%$ annually. Find value after 2 years.
- **Method A:** $50,000\to45,000\to40,500$.
- **Method B:** $50000(0.9)^2=40,500$. **Answer: $40,500$.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** SI-CI comparisons, rate/time/principal changes, and annual versus half-yearly compounding.
- **RRB lens:** Direct interest, amount, and depreciation questions with clean values.
- **AP State / PSU lens:** Variable rates, installments, compounding frequency, and population or asset-growth applications.

## 5. Common Traps & Speed Killers

1. **Using CI on the original principal each year:** later interest earns interest too.
2. **Forgetting to adjust periods:** half-yearly means rate halves and number of periods doubles.
3. **Using a CI-SI shortcut outside its conditions:** the two-year difference formula assumes annual compounding over exactly two years.

## 6. Quick Check

1. Find SI on $3000$ at $6\%$ per year for 2 years.

<details>
<summary>Reveal answer</summary>

$360$.
</details>

2. Find CI on $1000$ at $10\%$ per year for 2 years.

<details>
<summary>Reveal answer</summary>

$210$: amount $=1000(1.1)^2=1210$.
</details>