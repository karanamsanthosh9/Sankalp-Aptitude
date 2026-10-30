# Pipes & Cisterns

## 1. Core Concept & Fundamental Equations

- A filling pipe completing a tank in $x$ hours has rate $+1/x$ tank/hour; an emptying pipe has rate $-1/y$.
- Net rate is the signed sum of all open pipes. Time $=1/|\text{net rate}|$ for one tank, if the net rate fills it.
- For a tank of capacity $V$, rate is measured in volume per unit time; keep units consistent.
- If pipes operate in intervals, calculate the net work in one complete cycle and any remaining portion.
- Leakage questions treat leakage as an outlet, not as a reduction in inlet efficiency unless stated.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Signed rates | Inlets and outlets work simultaneously. | Pipes switch on/off; account for each interval. |
| LCM tank units | Times are integer-friendly. | Capacity or rates are already given in units/hour. |
| Cycle method | Pipes open according to a repeated schedule. | The tank fills before a cycle completes; stop at the fill time. |
| Compare actual and expected time | A leak delays filling. | More than one changing rate is involved. |
| Outlet subtraction | A pipe empties while another fills. | The problem says an outlet is closed during filling. |

## 3. Model-Wise Question Classification

### Model 1: Two inlets together
**Problem:** Pipes fill a tank in 12 and 18 hours. Find their combined time.
- **Method A:** Rate $=1/12+1/18=5/36$; time $=36/5=7.2$ hours.
- **Method B:** Use 36 tank units; rates are 3 and 2 units/hour, so $36/5=7.2$ hours. **Answer: $7.2$ hours.**

### Model 2: Inlet with outlet
**Problem:** An inlet fills a tank in 8 hours and an outlet empties it in 12 hours. Both open together; find fill time.
- **Method A:** Net rate $=1/8-1/12=1/24$ tank/hour; time $=24$ hours.
- **Method B:** Take 24 units capacity: inlet adds 3 units/hour, outlet removes 2; 1 net unit/hour. **Answer: $24$ hours.**

### Model 3: Find outlet time from net time
**Problem:** An inlet fills a tank in 6 hours. With an outlet open, it fills in 10 hours. How long would the outlet alone take to empty it?
- **Method A:** Outlet rate $=1/6-1/10=1/15$ tank/hour; emptying time $=15$ hours.
- **Method B:** Net rate is $3/5$ of inlet rate; outlet accounts for $1/6-1/10=1/15$. **Answer: $15$ hours.**

### Model 4: Pipes open on alternate hours
**Problem:** Inlets fill a tank in 4 and 6 hours. They are opened alternately for one hour each, first the 4-hour pipe. Find fill time.
- **Method A:** In 2 hours they fill $1/4+1/6=5/12$. After 4 hours, $10/12$ is filled; the 4-hour pipe adds the remaining $1/6$ in $2/3$ hour. Total $4\frac23$ hours.
- **Method B:** Each two-hour cycle adds $5/12$. After two cycles, $1/6$ remains, which the first pipe fills in $2/3$ hour. **Answer: $4\frac23$ hours.**

### Model 5: Leakage delay
**Problem:** A pipe fills a tank in 5 hours, but a leak makes it take 6 hours. Find the leak's emptying time.
- **Method A:** Leak rate $=1/5-1/6=1/30$ tank/hour; time $=30$ hours.
- **Method B:** In one hour the missing fill rate is $1/30$ of the tank. **Answer: $30$ hours.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Inlet-outlet combinations, leak delays, and alternating operation schedules.
- **RRB lens:** Direct rate addition/subtraction with simple filling times.
- **AP State / PSU lens:** Multiple pipes, non-hour intervals, and variable schedules.

## 5. Common Traps & Speed Killers

1. **Adding emptying rates:** outlets subtract from filling rates.
2. **Using net rate as time:** time is reciprocal of the net rate for one tank.
3. **Ignoring the fill point within a cycle:** never continue a schedule after the tank is full.

## 6. Quick Check

1. One pipe fills a tank in 10 hours and a leak empties it in 15 hours. How long to fill with both open?

<details>
<summary>Reveal answer</summary>

$30$ hours: net rate $=1/10-1/15=1/30$ tank/hour.
</details>

2. An inlet fills a tank in 6 hours. What fraction does it fill in 2 hours?

<details>
<summary>Reveal answer</summary>

$1/3$ of the tank.
</details>