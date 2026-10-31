# Time & Work

> **NEVER ADD DAYS.** Convert each worker to rate, then add rates.

## Imagine the job as a pile of work

Days describe how long a worker needs; rates describe how much of the job is completed each day. A worker who finishes in 12 days does $1/12$ of the job per day. With people working together, add the fractions completed per day, then divide the remaining work by the new rate. This same idea handles a team change: find completed work first, then switch rates.

### Walk through: one worker joins later

A finishes in 10 days, so in 2 days alone A completes $2/10=1/5$ of the job. The remaining $4/5$ is done by the pair at rate $1/10+1/15=1/6$ per day. It takes $(4/5)/(1/6)=24/5=4.8$ more days, or 6.8 days total.

**Sanity check:** The pair is faster than A alone, but the first two days were solo work. **Your turn:** if A does $1/4$ of a job in 3 days, how long for the whole job? *(Answer: 12 days; multiply the time by 4.)*

## ⚡ Formula cards

| Situation | Formula |
|---|---|
| A finishes in $x$ days | **Rate $=\frac1x$ job/day** |
| Work together | **Add their rates** |
| Time for one job | **$\frac1{\text{combined rate}}$** |
| Same job, equal efficiency | **Workers $\times$ days $=$ constant** |

> **Think in rates, not days:** More workers add work per day; completion time goes down.

```text
A takes 12 days  →  1/12 job/day
B takes 18 days  →  1/18 job/day
Together         →  add rates → flip to get days
```

## Exam shortcut playbook

| If you spot... | Shortcut |
|---|---|
| Workers finish in different times | Use the LCM of their times as total work units; each rate becomes an integer. |
| Efficiency ratio | Time ratio is the reverse: efficiency $3:2$ means time $2:3$. |
| Team changes mid-job | Find completed work first; apply the new rate only to the remainder. |
| Same job, workers change | Keep workers $\times$ days constant, assuming equal efficiency. |
| Alternating workers | Calculate one complete cycle, then finish the leftover work on the correct turn. |

## Ten worked examples

### 1. Work together
**Question:** A finishes in 12 days; B in 18. How long together?
- **Step by step:** Daily rate $=1/12+1/18=5/36$. Time $=36/5$ days.
- **Fast way:** Use 36 work units: rates are 3 and 2 units/day. **Answer: $7.2$ days.**

### 2. Compare efficiency
**Question:** A is 50% more efficient than B. B takes 24 days. How long does A take?
- **Step by step:** A's rate is 1.5 times B's, so A needs $24/1.5=16$ days.
- **Fast way:** Efficiency A:B $=3:2$; time A:B $=2:3$. **Answer: $16$ days.**

### 3. A worker joins later
**Question:** A takes 10 days, B takes 15. A works alone for 2 days, then B joins. Find total time.
- **Step by step:** A completes $2/10=1/5$. Remaining work $=4/5$. Together rate $=1/6$, so remaining time $=(4/5)/(1/6)=4.8$ days.
- **Fast way:** Add the 2 solo days to the 4.8 team days. **Answer: $6.8$ days.**

### 4. Change the workforce
**Question:** 12 workers finish in 15 days. How long for 20 equally efficient workers?
- **Step by step:** Job size $=12(15)=180$ worker-days. Divide by 20.
- **Fast way:** $12(15)=20d$. **Answer: $9$ days.**

### 5. Alternate workdays
**Question:** A takes 6 days, B takes 12. They alternate days, A starts. When is the job done?
- **Step by step:** Each 2-day cycle completes $1/6+1/12=1/4$. After 6 days, $1/4$ remains. A does this in 1.5 days.
- **Fast way:** Three cycles take 6 days; finish the remainder on A's next turn. **Answer: $7.5$ days.**

### 6. Find the remaining work
**Question:** A worker completes a job in 20 days. What fraction remains after working alone for 8 days?
- **Step by step:** The worker completes $8/20=2/5$ of the job.
- **Calculation:** Remaining work $=1-2/5=3/5$. **Answer: $\frac{3}{5}$ of the job.**

### 7. Find a worker's time from a combined rate
**Question:** A and B together finish a job in 6 days. A alone takes 10 days. How long would B take alone?
- **Step by step:** B's rate is the combined rate minus A's rate.
- **Calculation:** $\frac{1}{6}-\frac{1}{10}=\frac{1}{15}$ job per day. **Answer: $15$ days.**

### 8. Use worker-days
**Question:** 8 workers finish a job in 15 days. How many days will 12 equally efficient workers need?
- **Shortcut:** Keep the product fixed: $8(15)=12d$.
- **Calculation:** $d=120/12$. **Answer: $10$ days.**

### 9. Find the time when workers leave
**Question:** 20 workers can finish a job in 18 days. After 6 days, 5 workers leave. How many days are needed in total?
- **Shortcut:** Total job $=20(18)=360$ worker-days. First 6 days complete $20(6)=120$; 240 remain.
- **Calculation:** $240/15=16$ more days. **Answer: $22$ days total.**

### 10. Use LCM work units
**Question:** A finishes in 8 days and B in 12 days. How much work do they complete together in 2 days?
- **Shortcut:** Let total work be $\text{LCM}(8,12)=24$ units. Rates are 3 and 2 units/day.
- **Calculation:** Together they do $5(2)=10$ units, or **$\frac{10}{24}=\frac{5}{12}$ of the job**.

## Quick practice

1. A takes 8 days and B takes 8 days. How long together? *(Answer: 4 days; their rates add to $1/4$ job per day.)*
2. A and B together finish in 5 days; A alone takes 10. How long for B alone? *(Answer: 10 days; B's rate is $1/5-1/10=1/10$.)*
3. Nine equally efficient workers finish in 12 days. How long for 18 workers? *(Answer: 6 days; doubling workers halves the time.)*
