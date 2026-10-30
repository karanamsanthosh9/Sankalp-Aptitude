# Time & Work

## 1. Core Concept & Fundamental Equations

- Work $=$ rate $\times$ time. If A completes a job in $x$ days, A's one-day work rate is $1/x$.
- Combined rate is the sum of individual rates. For A in $x$ days and B in $y$ days, together time is $xy/(x+y)$.
- If A is $k$ times as efficient as B, their rates are in ratio $k:1$ and their times for equal work are $1:k$.
- For a fixed job, workers $\times$ days $\times$ hours per day $\times$ efficiency is constant.
- If a worker joins/leaves, calculate the completed work first, then apply the new combined rate.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| LCM work units | Completion times are integers and rates become clean. | Times have awkward values; use fractional rates. |
| Rate addition | Workers work together at constant efficiency. | They work in alternating schedules; sum work by period. |
| Efficiency ratio | Relative efficiency is given. | Individual work rates or skill changes are specified. |
| Worker-day product | Workforce and hours change on a fixed job. | Work or worker efficiency changes. |
| Remaining-work method | A worker joins or leaves mid-task. | The job has variable output by stage. |

## 3. Model-Wise Question Classification

### Model 1: Two workers together
**Problem:** A finishes in 12 days and B in 18 days. How long together?
- **Method A:** Combined rate $=1/12+1/18=5/36$; time $=36/5=7.2$ days.
- **Method B:** Take total work as LCM $36$ units. Rates are 3 and 2 units/day; $36/5=7.2$ days. **Answer: $7.2$ days.**

### Model 2: Efficiency and time ratio
**Problem:** A is 50% more efficient than B. If B takes 24 days, how long does A take?
- **Method A:** A's rate is $1.5$ times B's; time $=24/1.5=16$ days.
- **Method B:** Efficiency ratio A:B $=3:2$, so time ratio $=2:3$. A takes $24(2/3)=16$ days. **Answer: $16$ days.**

### Model 3: One worker joins later
**Problem:** A can finish a job in 10 days, B in 15 days. A works alone for 2 days, then B joins. Find total time.
- **Method A:** A completes $2/10=1/5$; remaining work $4/5$. Combined rate $=1/10+1/15=1/6$; remaining time $=(4/5)/(1/6)=24/5$ days. Total $=6.8$ days.
- **Method B:** In 2 days A completes 20% and leaves 80%; at combined rate $1/6$, 80% takes 4.8 days. **Answer: $6.8$ days.**

### Model 4: Workforce change
**Problem:** 12 workers finish a job in 15 days. How long would 20 equally efficient workers take?
- **Method A:** Total work $=12\times15=180$ worker-days; time $=180/20=9$ days.
- **Method B:** Inverse proportion: $12(15)=20t$, hence $t=9$. **Answer: $9$ days.**

### Model 5: Alternating work
**Problem:** A completes a job in 6 days and B in 12 days. They work on alternate days, starting with A. How many days to finish?
- **Method A:** In a 2-day cycle they do $1/6+1/12=1/4$. After 3 cycles (6 days), $3/4$ is done; A completes the remaining $1/4$ in 1.5 days. Total $7.5$ days.
- **Method B:** Rate per A-B cycle is $1/4$; after 6 days, 1/4 remains. A's rate is $1/6$, so 1.5 more days. **Answer: $7.5$ days.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Efficiency ratios, partial work, alternate schedules, and workers joining/leaving.
- **RRB lens:** Direct worker-day comparisons and simple combined-rate questions.
- **AP State / PSU lens:** Multi-stage staffing, variable hours, and work shared in efficiency ratios.

## 5. Common Traps & Speed Killers

1. **Adding completion times:** add rates, not days.
2. **Confusing efficiency and time:** for the same work, they are inversely proportional.
3. **Ignoring work already completed:** subtract completed work before applying a new rate.

## 6. Quick Check

1. A can finish a job in 8 days and B in 24 days. How long together?

<details>
<summary>Reveal answer</summary>

$6$ days: combined rate $=1/8+1/24=1/6$ job/day.
</details>

2. Fifteen workers finish a job in 12 days. How long would 20 equally efficient workers take?

<details>
<summary>Reveal answer</summary>

$9$ days: $15\cdot12/20=9$.
</details>