# Mensuration

> **ASK:** boundary? surface? capacity? Pick perimeter, area, or volume.

## First decide what is being measured

Before choosing a formula, picture the question: walking around a flat shape measures its boundary; covering its inside measures area; filling a solid measures volume. For a solid's outside, use surface area and check whether the question includes the ends or bases. This choice also predicts the units: length, square units, or cubic units.

### Walk through: volume of a cylinder

Think of the cylinder as a stack of identical circular layers. One layer has area $\pi r^2$; stacking it to height $h$ gives $V=\pi r^2h$. With $r=3$ cm and $h=10$ cm, $V=90\pi$ cm$^3$.

**Sanity check:** The answer must be cubic centimetres, and increasing the height would increase the volume in the same proportion. **Your turn:** find the volume when $r=2$ cm and $h=5$ cm. *(Answer: $20\pi$ cm$^3$; $\pi(2)^2(5)$.)*

## ⚡ Shape formula cards

| Shape | Area / surface | Perimeter / volume |
|---|---|---|
| Rectangle | $A=lb$ | $P=2(l+b)$ |
| Triangle | $A=\frac12 bh$ | — |
| Circle | $A=\pi r^2$ | $C=2\pi r$ |
| Cuboid | — | $V=lbh$ |
| Cylinder | Curved area $=2\pi rh$ | $V=\pi r^2h$ |
| Cone | — | $V=\frac13\pi r^2h$ |
| Sphere | Surface $=4\pi r^2$ | $V=\frac43\pi r^3$ |

> **Unit check:** Area ends in square units; volume ends in cubic units.

```text
2D shape ──> perimeter (around) / area (inside)
3D solid ──> surface area (outside) / volume (inside)
Scale side by k ──> length k | area k² | volume k³
```

## Exam shortcut playbook

| If you spot... | Shortcut |
|---|---|
| A boundary/fence | Use perimeter or circumference, not area. |
| A painted/covered solid | Identify curved vs total surface area; check whether bases are included. |
| A scale change by $k$ | Length $\times k$, area $\times k^2$, volume $\times k^3$. |
| A solid melted and recast | Equate volumes; material amount is unchanged. |
| A circle with diameter given | Use $r=d/2$ before applying circle formulas. |
| Different measurement units | Convert all lengths to one unit before squaring/cubing. |

## Ten worked examples

### 1. Find rectangle area
**Question:** Find the area of a rectangle 18 cm by 12 cm.
- **Step by step:** Area $=18\times12=216$ square centimetres.
- **Fast way:** Multiply length by width. **Answer: $216$ cm$^2$.**

### 2. Find circle circumference
**Question:** Find circumference for radius 7 cm; use $\pi=22/7$.
- **Step by step:** $2\pi r=2(22/7)(7)=44$ cm.
- **Fast way:** Diameter is 14 cm; use $\pi d$. **Answer: $44$ cm.**

### 3. Find cylinder volume
**Question:** A cylinder has radius 3 cm and height 10 cm. Find volume.
- **Step by step:** Base area $=\pi(3)^2=9\pi$. Multiply by height 10.
- **Fast way:** $\pi r^2h=90\pi$. **Answer: $90\pi$ cm$^3$.**

### 4. Scale a solid
**Question:** A cube's side doubles. By what factor does its volume change?
- **Step by step:** New volume $(2s)^3=8s^3$.
- **Fast way:** Volume scales as the cube of the side factor: $2^3=8$. **Answer: 8 times.**

### 5. Melt and recast
**Question:** A sphere is recast into spheres with half its radius. How many small spheres are made?
- **Step by step:** Same metal means same total volume: $R^3=n(R/2)^3$, so $n=8$.
- **Fast way:** Halve each length; volume of each small sphere is $1/8$ as much. **Answer: $8$.**

### 6. Find a cuboid volume
**Question:** Find the volume of a box 8 cm long, 5 cm wide, and 3 cm high.
- **Step by step:** Multiply its three dimensions.
- **Calculation:** $V=8(5)(3)=120$. **Answer: $120$ cm$^3$.**

### 7. Find a triangle's area
**Question:** Find the area of a triangle with base 14 cm and perpendicular height 9 cm.
- **Step by step:** A triangle is half of a rectangle with the same base and height.
- **Calculation:** $A=\frac{1}{2}(14)(9)=63$. **Answer: $63$ cm$^2$.**

### 8. Find circle area from its radius
**Question:** Find the area of a circle with radius 14 cm. Use $\pi=22/7$.
- **Shortcut:** Cancel $7$ before multiplying: $\frac{22}{7}(14^2)$.
- **Calculation:** $22(28)$. **Answer: $616$ cm$^2$.**

### 9. Find cylinder volume
**Question:** Find the volume of a cylinder with radius 7 cm and height 10 cm. Use $\pi=22/7$.
- **Shortcut:** Cancel one 7: $\frac{22}{7}(7^2)(10)$.
- **Answer:** **1,540 cm$^3$**.

### 10. Scale a cube
**Question:** A cube's side is tripled. By what factor do its surface area and volume change?
- **Shortcut:** Surface scales as $k^2$; volume as $k^3$.
- **Calculation:** $3^2=9$ and $3^3=27$. **Answer: area is 9 times; volume is 27 times.**

## Quick practice

1. A rectangle is 9 cm by 4 cm. Find its perimeter. *(Answer: 26 cm; $2(9+4)$.)*
2. A circle has diameter 10 cm. Write its area in terms of $\pi$. *(Answer: $25\pi$ cm$^2$; radius is 5 cm.)*
3. A cube's side is multiplied by 2. By what factor does its surface area change? *(Answer: 4; area scales by $2^2$.)*
