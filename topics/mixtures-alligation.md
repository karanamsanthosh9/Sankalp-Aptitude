# Mixtures & Alligation

**The idea:** A mixture's average price or strength depends on how much of each ingredient you use. More of the expensive/strong ingredient pulls the average upward.

## The essentials

- Mixture average $=\frac{\text{total value or solute}}{\text{total quantity}}$.
- For low value $L$, target $M$, high value $H$: low:high quantity ratio $=(H-M):(M-L)$.
- Add water? The amount of milk/solute stays the same; only total volume changes.
- Repeatedly remove and refill the same amount: original liquid remaining $=V(1-x/V)^n$.

## Choose your move

| Question clue | Use |
|---|---|
| Two prices/strengths make a target | Alligation cross-differences. |
| Ingredient amounts are already known | Weighted average. |
| Water is added to a solution | Keep solute fixed and solve for new total volume. |
| Repeated draw-and-refill | Remaining fraction per round, raised to number of rounds. |

## Five common question types

### 1. Find the mixing ratio
**Question:** Rice at $40$/kg and $60$/kg is mixed to make $48$/kg. Find the ratio.
- **Step by step:** Let quantities be $x,y$. $40x+60y=48(x+y)$, so $12y=8x$.
- **Fast way:** Low:high $=(60-48):(48-40)=12:8$. **Answer: $3:2$.**

### 2. Find the mixture's average price
**Question:** Mix 3 kg at $40$/kg with 2 kg at $55$/kg. Find price per kg.
- **Step by step:** Total cost $=120+110=230$; divide by 5 kg.
- **Fast way:** Weighted average $=40+(2/5)(55-40)$. **Answer: $46$/kg.**

### 3. Add water to milk
**Question:** A 30 L mixture is 80% milk. How much water makes it 60% milk?
- **Step by step:** Milk is $30(0.8)=24$ L. At 60%, total volume must be $24/0.6=40$ L.
- **Fast way:** Milk stays fixed; final total is 40 L, so add 10 L. **Answer: $10$ L.**

### 4. Replace part of a mixture twice
**Question:** A 20 L vessel is full of milk. Remove 5 L and refill with water twice. How much original milk remains?
- **Step by step:** Each round keeps $15/20=3/4$ of the milk. After two rounds: $20(3/4)^2=11.25$ L.
- **Fast way:** Remaining milk $=V(1-x/V)^n$. **Answer: $11.25$ L.**

### 5. Blend two solution strengths
**Question:** Make 30 L of 40% solution using 20% and 50% solutions.
- **Step by step:** Let $x$ be litres of 50% solution: $0.5x+0.2(30-x)=12$, so $x=20$.
- **Fast way:** Low:high $=(50-40):(40-20)=1:2$. **Answer: 10 L at 20%, 20 L at 50%.**

## What exams tend to test

- **SSC:** alligation, price blends, and milk-water replacement.
- **RRB:** weighted averages and repeated replacement.
- **APPSC / PSU:** concentration, purity, and multi-ingredient cost problems.

## Watch for these

1. In alligation, the low-ingredient quantity uses the high-minus-target difference.
2. Adding water does not add milk or solute.
3. Apply the replacement factor once per round.

## Quick check

1. Mix 30% and 50% solutions to get 40%. What is the ratio?

<details>
<summary>Show answer</summary>

$1:1$.
</details>

2. A 40 L mixture is 75% milk. How much water makes it 60% milk?

<details>
<summary>Show answer</summary>

10 L. Milk is 30 L; final volume must be 50 L.
</details>