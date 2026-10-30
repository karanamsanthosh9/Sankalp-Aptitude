# Mixtures & Alligation

## 1. Core Concept & Fundamental Equations

- Mixture concentration or value is a weighted average: $\text{mean}=\frac{q_1v_1+q_2v_2}{q_1+q_2}$.
- For two ingredients with values $C_1<C<C_2$, alligation gives quantity ratio $(C_2-C):(C-C_1)$.
- Repeated replacement: after removing and replacing fraction $x/V$ a total of $n$ times, original liquid remaining is $V(1-x/V)^n$.
- Pure-water addition changes quantity but not the amount of solute.
- Keep units and concentration bases consistent (e.g. percentages as fractions or per 100).

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Alligation cross-difference | Two sources form a target mean or price. | More than two sources or additional constraints are present. |
| Weighted average | Quantities and concentrations are known. | The mixture is repeatedly replaced; use the replacement factor. |
| Solute conservation | Water is added/removed without changing solute. | Ingredients react or solute is also removed. |
| Replacement multiplier | Repeated equal-volume draw-and-refill. | Removed volume or total volume changes each round. |
| Assume 100 units | Percent concentration arithmetic is involved. | Actual quantities are needed and not proportional. |

## 3. Model-Wise Question Classification

### Model 1: Alligation ratio
**Problem:** Mix rice costing $40$/kg and $60$/kg to get a mixture worth $48$/kg. Find the quantity ratio.
- **Method A:** Let cheaper and dearer quantities be $x,y$: $(40x+60y)/(x+y)=48$, so $12y=8x$, hence $x:y=3:2$.
- **Method B:** Alligation: cheaper:dearer $=(60-48):(48-40)=12:8=3:2$. Careful: this gives cheaper-to-dearer as $12:8=3:2$. **Answer: $3:2$.**

### Model 2: Mean price of a mixture
**Problem:** Mix $3$ kg at $40$/kg with $2$ kg at $55$/kg. Find mean price.
- **Method A:** Total cost $=120+110=230$; divide by $5$ kg to get $46$/kg.
- **Method B:** Weighted mean $=40+(2/5)(55-40)=46$. **Answer: $46$/kg.**

### Model 3: Water added to milk
**Problem:** A $30$ L mixture is $80\%$ milk. How much water must be added to make it $60\%$ milk?
- **Method A:** Milk quantity $=24$ L. At $60\%$, total mixture must be $24/0.6=40$ L; add $10$ L.
- **Method B:** Solute (milk) stays fixed: total goes from $30$ to $40$ L, so add $10$ L. **Answer: $10$ L.**

### Model 4: Repeated replacement
**Problem:** A $20$ L vessel is full of pure milk. Remove and replace $5$ L with water twice. How much original milk remains?
- **Method A:** After first replacement, milk $=20(15/20)=15$ L; after second, $15(15/20)=11.25$ L.
- **Method B:** Remaining fraction $=(1-5/20)^2=(3/4)^2=9/16$; milk $=20(9/16)=11.25$ L. **Answer: $11.25$ L.**

### Model 5: Blend to a target concentration
**Problem:** How much $20\%$ solution and $50\%$ solution are needed to make $30$ L of $40\%$ solution?
- **Method A:** Let high-concentration volume be $x$: $0.5x+0.2(30-x)=12$, so $x=20$ L and low solution $=10$ L.
- **Method B:** Alligation ratio low:high $=(50-40):(40-20)=10:20=1:2$. For 30 L, amounts are 10 L and 20 L. **Answer: $10$ L of 20%, $20$ L of 50%.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Alligation, price mixtures, milk-water replacement, and concentration changes.
- **RRB lens:** Direct weighted averages and repeated replacement with integer volumes.
- **AP State / PSU lens:** Multi-component blends, purity, concentration, and cost optimization.

## 5. Common Traps & Speed Killers

1. **Reversing the alligation ratio:** quantity of a source is paired with the opposite cross-difference.
2. **Changing solute while adding only water:** the solute amount stays fixed; total volume changes.
3. **Applying one replacement factor only once:** repeat the factor for every draw-and-refill operation.

## 6. Quick Check

1. In what ratio should $30\%$ and $50\%$ solutions be mixed to make a $40\%$ solution?

<details>
<summary>Reveal answer</summary>

$1:1$.
</details>

2. A 40 L mixture is $75\%$ milk. How much water must be added to make it $60\%$ milk?

<details>
<summary>Reveal answer</summary>

$10$ L. Milk remains $30$ L, so the final volume must be $50$ L.
</details>