# Simple & Compound Interest

> **SI:** same principal each year. **CI:** new balance each year.

## Two ways interest can grow

With simple interest, every period's interest is calculated from the original principal, so the add-on stays level. With compound interest, each new period works from the updated balance; the balance is multiplied again. That is why the compound amount uses one growth factor per period. For a decrease in value, use a factor below 1 instead.

### Walk through: $10{,}000$ at 10% compound interest for 2 years

After year 1, the balance is $10{,}000(1.10)=11{,}000$. The next 10% applies to $11{,}000$, making $12{,}100$. The interest earned is the final amount minus the original principal: $12{,}100-10{,}000=2{,}100$.

**Sanity check:** Compound interest here should exceed simple interest ($2{,}000$), because year 2 earns interest on the first year's interest. **Your turn:** find the amount on $1{,}000$ at 10% for 2 years, compounded annually. *(Answer: $1{,}210$; $1000(1.1)^2$.)*

## ⚡ Formula cards

| Situation | Formula |
|---|---|
| Simple interest | **$SI=\frac{PRT}{100}$** |
| Simple-interest amount | **$A=P+SI$** |
| Compound amount | **$A=P(1+\frac{R}{100})^T$** |
| Compound interest | **$CI=A-P$** |
| Depreciation | **$A=P(1-\frac{R}{100})^T$** |

> **See the difference:** Simple interest repeats the same add-on; compound interest grows by a multiplier each period.

```text
SI:  P ── +same interest ── +same interest ──> A
CI:  P ── ×(1+r) ────────── ×(1+r) ─────────> A
             year 1              year 2
```

## Exam shortcut playbook

| If you spot... | Shortcut |
|---|---|
| SI and three of $P,R,T$ are known | Rearrange $SI=PRT/100$; isolate only the missing quantity. |
| Annual CI | Use growth factor $1+R/100$ once per year. |
| Half-yearly CI | Use rate $R/2$ and periods $2T$. |
| Two-year CI minus SI | Use $P(R/100)^2$ directly. |
| Rate changes by year | Multiply each year's growth factor; do not average the rates. |
| Depreciation | Use a decreasing factor $1-R/100$ per period. |

## Ten worked examples

### 1. Find simple interest
**Question:** Find SI on $5000$ at 8% for 3 years.
- **Step by step:** One year's interest is $5000(0.08)=400$. Three years: $3(400)=1200$.
- **Fast way:** $5000\times8\times3/100=1200$. **Answer: $1200$.**

### 2. Find compound interest
**Question:** Find CI on $10,000$ at 10% for 2 years.
- **Step by step:** After year 1: $11,000$. Year 2 interest: $1100$. Total interest: $2100$.
- **Fast way:** Amount $=10000(1.1)^2=12100$; subtract principal. **Answer: $2100$.**

### 3. Compare CI with SI
**Question:** Find CI minus SI on $8000$ at 5% for 2 years.
- **Step by step:** SI $=800$. CI amount $=8000(1.05)^2=8820$, so CI $=820$. Difference $=20$.
- **Fast way:** $8000(0.05)^2=20$. **Answer: $20$.**

### 4. Compound half-yearly
**Question:** Find the amount on $4000$ at 10% for one year, compounded half-yearly.
- **Step by step:** Each half-year rate is 5%; apply it twice: $4000(1.05)^2=4410$.
- **Fast way:** Two periods, each with multiplier 1.05. **Answer: $4410$.**

### 5. Calculate depreciation
**Question:** A $50,000$ machine loses 10% of its value each year. Find its value after two years.
- **Step by step:** Year 1: $45,000$. Year 2: $40,500$.
- **Fast way:** $50000(0.9)^2=40500$. **Answer: $40,500$.**

### 6. Find the simple-interest rate
**Question:** A principal of $4,000 earns $600 simple interest in 3 years. Find the annual rate.
- **Step by step:** Rearrange $SI=PRT/100$ to make the rate the subject.
- **Calculation:** $R=\frac{600(100)}{4000(3)}=5\%$. **Answer: $5\%$ per year.**

### 7. Compound for three years
**Question:** Find the amount on $2,000 at 5% per year, compounded annually for 3 years.
- **Step by step:** Apply the 5% growth multiplier once each year.
- **Calculation:** $A=2000(1.05)^3=2315.25$. **Answer: $2,315.25$.**

### 8. Find simple interest quickly
**Question:** Find SI on $6,000 at 7.5% for 2 years.
- **Shortcut:** One year's interest is 7.5% of $6,000, or $450.
- **Calculation:** $450(2)$. **Answer: $900$.**

### 9. Compound half-yearly
**Question:** Find the amount on $10,000 at 8% for one year, compounded half-yearly.
- **Shortcut:** Each half-year earns 4%; apply the factor twice.
- **Calculation:** $10000(1.04)^2$. **Answer: $10,816$.**

### 10. Find the three-year CI-SI difference
**Question:** Find CI minus SI on $10,000 at 10% for 3 years, compounded annually.
- **Shortcut:** Compare amounts: CI amount $=10000(1.1)^3=13310$; SI $=3000$.
- **Calculation:** CI is $3,310$, so difference $=3310-3000$. **Answer: $310$.**

## Quick practice

1. Find SI on $2{,}000$ at 5% for 3 years. *(Answer: $300$; $2000(5)(3)/100$.)*
2. Find the amount on $5{,}000$ at 10% for one year, compounded annually. *(Answer: $5{,}500$; multiply by 1.10.)*
3. A $800$ item depreciates by 25% once. What is its new value? *(Answer: $600$; retain 75% of the value.)*
