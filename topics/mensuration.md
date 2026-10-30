# Mensuration

## 1. Core Concept & Fundamental Equations

- Rectangle: area $lb$, perimeter $2(l+b)$. Square: area $s^2$, perimeter $4s$.
- Circle: circumference $2\pi r$, area $\pi r^2$; semicircle perimeter includes the diameter, unless only curved length is requested.
- Cuboid: volume $lbh$, total surface area $2(lb+bh+hl)$. Cube: volume $s^3$, total surface area $6s^2$.
- Cylinder: volume $\pi r^2h$, curved surface area $2\pi rh$, total surface area $2\pi r(r+h)$.
- Cone: volume $\frac13\pi r^2h$, curved surface area $\pi rl$, with slant height $l=\sqrt{r^2+h^2}$.
- Sphere: volume $\frac43\pi r^3$, surface area $4\pi r^2$.
- Similar solids with linear scale ratio $k$ have surface-area ratio $k^2$ and volume ratio $k^3$.

## 2. Universal Shortcut Engine

| Technique | Use it when | Avoid it when |
|---|---|---|
| Factor out $\pi$ | Comparing circle-based areas or volumes. | A numerical answer requires a specified approximation for $\pi$. |
| Scale ratios | Solids are similar and dimensions scale uniformly. | Only one dimension changes. |
| Displacement | A solid is immersed in liquid. | The container overflows or the object floats; account for those conditions. |
| Composite-shape split | A figure is built from standard shapes. | Areas overlap; subtract overlaps to avoid double counting. |
| Unit conversion first | Length, area, and volume units differ. | All measurements already use consistent units. |

## 3. Model-Wise Question Classification

### Model 1: Rectangle dimensions
**Problem:** Find the area of a rectangle $18$ cm by $12$ cm.
- **Method A:** Area $=18\times12=216$ cm$^2$.
- **Method B:** $18\times(10+2)=180+36=216$ cm$^2$. **Answer: $216$ cm$^2$.**

### Model 2: Circle circumference
**Problem:** Find circumference for radius 7 cm, using $\pi=22/7$.
- **Method A:** $2\pi r=2(22/7)(7)=44$ cm.
- **Method B:** Diameter is 14 cm; circumference $=\pi d=(22/7)(14)=44$ cm. **Answer: $44$ cm.**

### Model 3: Cylinder volume
**Problem:** Find volume of a cylinder with radius 3 cm and height 10 cm.
- **Method A:** $\pi r^2h=\pi(9)(10)=90\pi$ cm$^3$.
- **Method B:** Base area is $9\pi$; multiply by height 10. **Answer: $90\pi$ cm$^3$.**

### Model 4: Solid scale change
**Problem:** The side of a cube is doubled. By what factor does its volume change?
- **Method A:** Original volume $s^3$, new volume $(2s)^3=8s^3$.
- **Method B:** Volume scales as the cube of the linear factor: $2^3=8$. **Answer: 8 times.**

### Model 5: Melting and recasting
**Problem:** A metal sphere is melted into smaller spheres of radius half the original radius. How many are formed?
- **Method A:** Equate total volumes: $R^3=n(R/2)^3$, so $n=8$.
- **Method B:** Volume scale is $2^3$; one original equals 8 smaller spheres. **Answer: $8$.**

## 4. Exam-Specific Alignment & Variations

- **SSC lens:** Composite figures, cylinder/cone/sphere formulas, and dimension changes.
- **RRB lens:** Direct area, perimeter, surface-area, and volume calculations.
- **AP State / PSU lens:** Recasting, capacity, unit conversion, and composite solids.

## 5. Common Traps & Speed Killers

1. **Confusing curved surface area and total surface area:** identify whether bases are included.
2. **Forgetting squared or cubed units:** area uses square units; volume uses cubic units.
3. **Using linear scaling for volume:** similar-solid volume scales with the cube of the side ratio.

## 6. Quick Check

1. Find the circumference of a circle with radius 7 cm, using $\pi=22/7$.

<details>
<summary>Reveal answer</summary>

$44$ cm.
</details>

2. Find the volume of a cube with side 4 cm.

<details>
<summary>Reveal answer</summary>

$64$ cm$^3$.
</details>