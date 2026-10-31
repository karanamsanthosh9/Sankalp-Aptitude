# Mensuration 2D

> Read this like a class: sketch the shape, mark its dimensions, and decide whether the question is about its boundary or the space it covers.

## 0. Start here: border or surface?

Imagine fencing a garden and then laying grass inside it. The fence follows the boundary, so it depends on perimeter; the grass covers the inside, so it depends on area. This distinction unlocks questions about triangles, quadrilaterals, circles, paths, wheels, and reshaped wire.

Start with a sketch and label the units. For a rectangle, increasing both sides increases the area faster than the perimeter: if each side doubles, the perimeter doubles but the area becomes four times as large. That is a useful sense check when a problem changes dimensions by a percentage.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Scalene, right, and isosceles triangles | 1 |
| Equilateral triangles, inradius, and circumradius | 2 |
| Rectangles and squares (perimeter, area, diagonal) | 3 |
| Parallelograms and rhombuses | 4 |
| Trapeziums and parallel side relationships | 5 |
| Regular polygons (hexagon, octagon, interior/exterior angles) | 6 |
| Circles, semicircles, sectors, and segments | 7 |
| Pathways, borders, and cross roads in fields | 8 |
| Inscribed and circumscribed figures | 9 |
| Wheel rotations and distance covered | 10 |
| Wire bending and reshaping figures | 11 |
| Shaded regions and leaf/corner shapes | 12 |
| Percentage and ratio changes in dimensions | 13 |
| Costing of fencing, paving, turfing, and tiling | 14 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Sides $a, b, c$" | Use Heron's formula $s = \dfrac{a+b+c}{2}$ and $\text{Area} = \sqrt{s(s-a)(s-b)(s-c)}$ |
| "Equilateral triangle side $a$" | $\text{Area} = \dfrac{\sqrt{3}}{4}a^2$, Height $h = \dfrac{\sqrt{3}}{2}a$, $r = \dfrac{a}{2\sqrt{3}}$, $R = \dfrac{a}{\sqrt{3}}$ |
| "Diagonal of square $d$" | $\text{Side} = \dfrac{d}{\sqrt{2}}$, $\text{Area} = \dfrac{d^2}{2}$ |
| "Diagonals of rhombus $d_1, d_2$" | $\text{Area} = \dfrac{1}{2}d_1 d_2$, $\text{Side} = \sqrt{\left(\dfrac{d_1}{2}\right)^2 + \left(\dfrac{d_2}{2}\right)^2}$ |
| "Path of width $w$ outside/inside" | New dimensions are $L \pm 2w$ and $B \pm 2w$ |
| "Cross roads running through centre" | $\text{Area} = w(L + B - w)$ |
| "A wheel of radius $r$ rotates $N$ times" | $\text{Distance} = N \times 2\pi r$ |
| "Wire reshaped into another figure" | Perimeter remains constant across both shapes |
| "Radius/side increased by $x\%$" | Net area change $= 2x + \dfrac{x^2}{100}\%$ |

## 3. The core idea

- **Triangle area:** $\text{Area} = \dfrac{1}{2} \times \text{base} \times \text{height} = \sqrt{s(s-a)(s-b)(s-c)} = \dfrac{1}{2}ab\sin\theta$.
- **Circle standard relations:** Circumference $= 2\pi r$, Area $= \pi r^2$, Sector area $= \dfrac{\theta}{360^\circ} \times \pi r^2 = \dfrac{1}{2}lr$ where $l = \dfrac{\theta}{360^\circ} \times 2\pi r$.
- **Perimeter vs Area:** Perimeter scales linearly with dimension factor $k$; Area scales with $k^2$. Cost of fencing uses perimeter; cost of turfing/paving uses area.
- Standard exam convention takes $\pi = \dfrac{22}{7}$ unless specified otherwise.

## 4. Question-type walkthroughs

### Question type 1. Scalene, right, and isosceles triangles

**Idea:** Use base-height formula when height is known; use Heron's formula for three sides; use Pythagoras theorem for right and isosceles triangles.

**Example 1 (Heron's formula):** Find the area of a triangle with sides $13\text{ cm}$, $14\text{ cm}$, and $15\text{ cm}$.
- Semi-perimeter $s = \dfrac{13 + 14 + 15}{2} = 21\text{ cm}$.
- $\text{Area} = \sqrt{21(21-13)(21-14)(21-15)} = \sqrt{21 \times 8 \times 7 \times 6} = \sqrt{7056} =$ **84 $\text{cm}^2$**.

**Example 2 (Right triangle):** The hypotenuse of a right-angled triangle is $25\text{ cm}$ and one side is $24\text{ cm}$. Find its area.
- Other side $= \sqrt{25^2 - 24^2} = \sqrt{625 - 576} = \sqrt{49} = 7\text{ cm}$.
- $\text{Area} = \dfrac{1}{2} \times 24 \times 7 =$ **84 $\text{cm}^2$**.

**Example 3 (Isosceles triangle):** An isosceles triangle has base $12\text{ cm}$ and equal sides of length $10\text{ cm}$. Find its area.
- Altitude bisects the base: $h = \sqrt{10^2 - 6^2} = \sqrt{100 - 36} = 8\text{ cm}$.
- $\text{Area} = \dfrac{1}{2} \times 12 \times 8 =$ **48 $\text{cm}^2$**.

### Question type 2. Equilateral triangles

**Idea:** All sides equal $a$. Area $= \dfrac{\sqrt{3}}{4}a^2$, height $h = \dfrac{\sqrt{3}}{2}a$, inradius $r = \dfrac{a}{2\sqrt{3}}$, circumradius $R = \dfrac{a}{\sqrt{3}}$. Note $R = 2r$.

**Example 1:** Find the area and height of an equilateral triangle of side $12\text{ cm}$.
- $\text{Height} = \dfrac{\sqrt{3}}{2} \times 12 =$ **$6\sqrt{3}\text{ cm}$**.
- $\text{Area} = \dfrac{\sqrt{3}}{4} \times 12^2 =$ **$36\sqrt{3}\text{ cm}^2$**.

**Example 2:** The height of an equilateral triangle is $9\text{ cm}$. Find its area.
- $h = \dfrac{\sqrt{3}}{2}a = 9 \implies a = \dfrac{18}{\sqrt{3}} = 6\sqrt{3}\text{ cm}$.
- $\text{Area} = \dfrac{\sqrt{3}}{4} \times (6\sqrt{3})^2 = \dfrac{\sqrt{3}}{4} \times 108 =$ **$27\sqrt{3}\text{ cm}^2$**.

**Example 3:** Find the ratio of the area of the circumcircle to that of the incircle of any equilateral triangle.
- $R : r = 2 : 1$, so ratio of areas $= R^2 : r^2 = 2^2 : 1^2 =$ **4 : 1**.

### Question type 3. Rectangles and squares

**Idea:** Rectangle: Area $= L \times B$, Diagonal $d = \sqrt{L^2 + B^2}$. Square: Area $= a^2 = \dfrac{d^2}{2}$, Diagonal $d = a\sqrt{2}$.

**Example 1:** The ratio of length to breadth of a rectangle is $5:3$ and its perimeter is $64\text{ cm}$. Find its area and diagonal.
- $2(5x + 3x) = 64 \implies 16x = 64 \implies x = 4$.
- $L = 20\text{ cm}, B = 12\text{ cm}$. $\text{Area} = 20 \times 12 =$ **240 $\text{cm}^2$**.
- $\text{Diagonal} = \sqrt{20^2 + 12^2} = \sqrt{544} =$ **$4\sqrt{34}\text{ cm}$**.

**Example 2:** The diagonal of a square is $10\text{ cm}$. Find its area and perimeter.
- $\text{Area} = \dfrac{d^2}{2} = \dfrac{100}{2} =$ **50 $\text{cm}^2$**.
- $\text{Side} = \dfrac{10}{\sqrt{2}} = 5\sqrt{2}\text{ cm}$. $\text{Perimeter} = 4 \times 5\sqrt{2} =$ **$20\sqrt{2}\text{ cm}$**.

### Question type 4. Parallelograms and rhombuses

**Idea:** Parallelogram: Area $= \text{base} \times \text{height}$. Rhombus: Area $= \dfrac{1}{2}d_1 d_2$, $4a^2 = d_1^2 + d_2^2$, diagonals bisect perpendicularly.

**Example 1:** A parallelogram has base $18\text{ cm}$ and corresponding altitude $11\text{ cm}$. Find its area.
- $\text{Area} = 18 \times 11 =$ **198 $\text{cm}^2$**.

**Example 2:** The diagonals of a rhombus are $16\text{ cm}$ and $12\text{ cm}$. Find its area and perimeter.
- $\text{Area} = \dfrac{1}{2} \times 16 \times 12 =$ **96 $\text{cm}^2$**.
- $\text{Side} = \sqrt{8^2 + 6^2} = 10\text{ cm}$. $\text{Perimeter} = 4 \times 10 =$ **40 cm**.

### Question type 5. Trapeziums

**Idea:** Area $= \dfrac{1}{2}(a+b)h$, where $a, b$ are parallel sides and $h$ is perpendicular distance between them.

**Example 1:** Parallel sides of a trapezium are $14\text{ cm}$ and $20\text{ cm}$, and the distance between them is $8\text{ cm}$. Find its area.
- $\text{Area} = \dfrac{1}{2}(14 + 20) \times 8 = \dfrac{34 \times 8}{2} =$ **136 $\text{cm}^2$**.

**Example 2:** The area of a trapezium is $180\text{ cm}^2$ and its height is $9\text{ cm}$. If one parallel side is $6\text{ cm}$ longer than the other, find both parallel sides.
- $\dfrac{1}{2}(x + x + 6) \times 9 = 180 \implies 2x + 6 = 40 \implies 2x = 34 \implies x = 17\text{ cm}$.
- The parallel sides are **17 cm and 23 cm**.

### Question type 6. Regular polygons

**Idea:** For an $n$-sided regular polygon: each interior angle $= \dfrac{(n-2)\times 180^\circ}{n}$, each exterior angle $= \dfrac{360^\circ}{n}$. Regular hexagon area $= 6 \times \dfrac{\sqrt{3}}{4}a^2$.

**Example 1:** Find the area of a regular hexagon with side $6\text{ cm}$.
- $\text{Area} = 6 \times \dfrac{\sqrt{3}}{4} \times 6^2 = 6 \times 9\sqrt{3} =$ **$54\sqrt{3}\text{ cm}^2$**.

**Example 2:** If each interior angle of a regular polygon is $140^\circ$, find the number of sides.
- Exterior angle $= 180^\circ - 140^\circ = 40^\circ$.
- Number of sides $n = \dfrac{360^\circ}{40^\circ} =$ **9 sides**.

### Question type 7. Circles, semicircles, sectors, and segments

**Idea:** Circle: $C = 2\pi r$, $A = \pi r^2$. Semicircle: Perimeter $= \pi r + 2r = \dfrac{36}{7}r$ (when $\pi=\dfrac{22}{7}$), $A = \dfrac{1}{2}\pi r^2$. Sector: $l = \dfrac{\theta}{360^\circ} \times 2\pi r$, $A = \dfrac{\theta}{360^\circ}\pi r^2$.

**Example 1:** Find the area and circumference of a circle of diameter $28\text{ cm}$.
- Radius $r = 14\text{ cm}$.
- $\text{Circumference} = 2 \times \dfrac{22}{7} \times 14 =$ **88 cm**.
- $\text{Area} = \dfrac{22}{7} \times 14^2 =$ **616 $\text{cm}^2$**.

**Example 2:** Find the perimeter and area of a semicircle of radius $14\text{ cm}$.
- $\text{Perimeter} = \pi r + 2r = \left(\dfrac{22}{7} \times 14\right) + 28 = 44 + 28 =$ **72 cm**.
- $\text{Area} = \dfrac{1}{2} \times \dfrac{22}{7} \times 14^2 =$ **308 $\text{cm}^2$**.

**Example 3:** A sector has radius $21\text{ cm}$ and central angle $60^\circ$. Find its arc length and area.
- $\text{Arc length} = \dfrac{60}{360} \times 2 \times \dfrac{22}{7} \times 21 = \dfrac{1}{6} \times 132 =$ **22 cm**.
- $\text{Area} = \dfrac{60}{360} \times \dfrac{22}{7} \times 21^2 = \dfrac{1}{6} \times 1386 =$ **231 $\text{cm}^2$**.

### Question type 8. Pathways and borders

**Idea:** Outside path: $(L + 2w)(B + 2w) - LB$. Inside path: $LB - (L - 2w)(B - 2w)$. Cross paths through centre: $w(L + B - w)$. Circular ring: $\pi(R^2 - r^2) = \pi(R - r)(R + r)$.

**Example 1 (Outside path):** A rectangular lawn $40\text{ m} \times 30\text{ m}$ is surrounded by a path of uniform width $2.5\text{ m}$. Find the area of the path.
- Outer length $= 40 + 2(2.5) = 45\text{ m}$, Outer breadth $= 30 + 2(2.5) = 35\text{ m}$.
- $\text{Path area} = (45 \times 35) - (40 \times 30) = 1575 - 1200 =$ **375 $\text{m}^2$**.

**Example 2 (Cross paths):** A park $60\text{ m} \times 40\text{ m}$ has two cross roads of width $2\text{ m}$ running through the centre parallel to the sides. Find the area of the roads.
- $\text{Area} = w(L + B - w) = 2(60 + 40 - 2) = 2 \times 98 =$ **196 $\text{m}^2$**.

### Question type 9. Inscribed and circumscribed figures

**Idea:** Incircle radius of right triangle: $r = \dfrac{a + b - c}{2}$. Circumradius of right triangle: $R = \dfrac{c}{2}$. Square in circle of radius $R$: side $= R\sqrt{2}$. Circle in square of side $a$: radius $= \dfrac{a}{2}$.

**Example 1:** A right-angled triangle has legs $6\text{ cm}$ and $8\text{ cm}$. Find its inradius and circumradius.
- Hypotenuse $c = \sqrt{6^2 + 8^2} = 10\text{ cm}$.
- $\text{Inradius } r = \dfrac{6 + 8 - 10}{2} =$ **2 cm**.
- $\text{Circumradius } R = \dfrac{10}{2} =$ **5 cm**.

**Example 2:** A circle is inscribed in a square of side $14\text{ cm}$. Find the area enclosed between the square and the circle.
- $\text{Radius of circle} = \dfrac{14}{2} = 7\text{ cm}$.
- $\text{Area of square} = 14^2 = 196\text{ cm}^2$. $\text{Area of circle} = \dfrac{22}{7} \times 7^2 = 154\text{ cm}^2$.
- $\text{Remaining area} = 196 - 154 =$ **42 $\text{cm}^2$**.

### Question type 10. Revolutions of wheels

**Idea:** Distance covered in $N$ revolutions $= N \times (2\pi r)$. Number of revolutions $N = \dfrac{\text{Total distance}}{\text{Circumference}}$.

**Example 1:** A wheel of radius $35\text{ cm}$ makes $500$ revolutions. Find the distance traveled in metres.
- $\text{Circumference} = 2 \times \dfrac{22}{7} \times 35 = 220\text{ cm} = 2.2\text{ m}$.
- $\text{Distance} = 500 \times 2.2 =$ **1100 m** (or **1.1 km**).

**Example 2:** A bicycle wheel makes $5000$ revolutions to cover $33\text{ km}$. Find its diameter.
- $\text{Distance per revolution} = \dfrac{33000\text{ m}}{5000} = 6.6\text{ m} = 660\text{ cm}$.
- $\pi d = 660 \implies \dfrac{22}{7}d = 660 \implies d = \dfrac{660 \times 7}{22} =$ **210 cm**.

### Question type 11. Wire bending and reshaping

**Idea:** When a wire is bent from one shape to another, the perimeter remains constant.

**Example 1:** A wire is bent into a circle enclosing an area of $616\text{ cm}^2$. If the same wire is bent into a square, find the area of the square.
- $\pi r^2 = 616 \implies \dfrac{22}{7}r^2 = 616 \implies r^2 = 196 \implies r = 14\text{ cm}$.
- $\text{Length of wire} = 2\pi r = 2 \times \dfrac{22}{7} \times 14 = 88\text{ cm}$.
- $\text{Side of square} = \dfrac{88}{4} = 22\text{ cm}$. $\text{Area of square} = 22^2 =$ **484 $\text{cm}^2$**.

**Example 2:** An equilateral triangle made of wire has side $22\text{ cm}$. If it is rebent into a circle, find the circle's radius and area.
- $\text{Length of wire} = 3 \times 22 = 66\text{ cm}$.
- $2 \times \dfrac{22}{7} \times r = 66 \implies r = \dfrac{66 \times 7}{44} =$ **10.5 cm**.
- $\text{Area} = \dfrac{22}{7} \times 10.5^2 =$ **346.5 $\text{cm}^2$**.

### Question type 12. Shaded regions and leaf shapes

**Idea:** Space between 4 touching circles of radius $r$: $\text{Area} = (2r)^2 - \pi r^2 = \left(4 - \dfrac{22}{7}\right)r^2 = \dfrac{6}{7}r^2$. Leaf shape between two quadrants in square of side $a$: $\text{Area} = \dfrac{4}{7}a^2$.

**Example 1:** Four equal coins of radius $7\text{ cm}$ are placed touching each other. Find the area enclosed between them.
- $\text{Area} = \dfrac{6}{7}r^2 = \dfrac{6}{7} \times 7^2 =$ **42 $\text{cm}^2$**.

**Example 2:** Find the area of the leaf-shaped region enclosed by arcs of two opposite quadrants in a square of side $14\text{ cm}$.
- $\text{Area} = \dfrac{4}{7}a^2 = \dfrac{4}{7} \times 14^2 = \dfrac{4}{7} \times 196 =$ **112 $\text{cm}^2$**.

### Question type 13. Percentage and ratio changes in dimensions

**Idea:** Net percentage change in area when dimensions change by $x\%$ and $y\%$: $\Delta A = \left(x + y + \dfrac{xy}{100}\right)\%$. For circles and squares with change $x\%$: $\Delta A = \left(2x + \dfrac{x^2}{100}\right)\%$.

**Example 1:** If the length of a rectangle increases by $20\%$ and breadth increases by $10\%$, find the percentage increase in area.
- $\Delta A = 20 + 10 + \dfrac{20 \times 10}{100} = 30 + 2 =$ **32% increase**.

**Example 2:** If the radius of a circle increases by $50\%$, find the percentage increase in its area.
- $\Delta A = 2(50) + \dfrac{50^2}{100} = 100 + 25 =$ **125% increase**.

**Example 3:** If the length of a rectangle increases by $25\%$, by what percentage must breadth decrease so area remains constant?
- $\text{Decrease} = \dfrac{25}{100 + 25} \times 100 = \dfrac{25}{125} \times 100 =$ **20%**.

### Question type 14. Cost of fencing, flooring, turfing, and tiling

**Idea:** Fencing cost $= \text{Perimeter} \times \text{Rate per metre}$. Turfing/paving/tiling cost $= \text{Area} \times \text{Rate per unit area}$.

**Example 1:** A rectangular plot is $50\text{ m}$ long and $30\text{ m}$ wide. Find the cost of fencing it at Rs $15$ per metre.
- $\text{Perimeter} = 2(50 + 30) = 160\text{ m}$.
- $\text{Cost} = 160 \times 15 =$ **Rs 2400**.

**Example 2:** A circular ground has radius $28\text{ m}$. Find the cost of turfing it at Rs $5$ per square metre.
- $\text{Area} = \dfrac{22}{7} \times 28^2 = \dfrac{22}{7} \times 784 = 2464\text{ m}^2$.
- $\text{Cost} = 2464 \times 5 =$ **Rs 12320**.

## 5. Before you practise

**Your turn:** A square has side 5 cm. If its side doubles, what happens to its perimeter and area?

**Think it through:** Originally the perimeter is $4\times5=20$ cm and area is $5^2=25$ cm$^2$. With side 10 cm they become 40 cm and 100 cm$^2$: perimeter doubles, while area becomes four times as large.

### Quick revision

- Perimeter measures the boundary; area measures the flat region inside.
- Use perpendicular height—not a sloping side—in base-height area formulas.
- For a path or border, subtract the inner area from the outer area.
- Keep linear units (cm) separate from square units (cm$^2$).

### Common mistakes

1. Confusing radius and diameter.
2. Using the triangle’s sloping side as its height.
3. Including an internal boundary in a fencing or shaded-area question when it is not part of the requested region.
4. Adding overlapping road areas twice.
5. Applying a length percentage directly to area; area changes with the square of the scale factor.

## 6. Practice

1. Find the area of a right-angled triangle whose sides containing the right angle are $9\text{ cm}$ and $12\text{ cm}$.
2. A triangle has sides $11\text{ cm}$, $13\text{ cm}$, and $20\text{ cm}$. Find its area.
3. An isosceles triangle has perimeter $32\text{ cm}$ and base $12\text{ cm}$. Find its area.
4. Find the area of an equilateral triangle whose side is $8\text{ cm}$.
5. The area of an equilateral triangle is $36\sqrt{3}\text{ cm}^2$. Find its perimeter.
6. The inradius of an equilateral triangle is $2\sqrt{3}\text{ cm}$. Find the side of the triangle.
7. The area of a square is $289\text{ cm}^2$. Find the length of its diagonal.
8. The perimeter of a rectangle is $50\text{ cm}$ and its length and breadth are in the ratio $3:2$. Find its area.
9. A rectangular hall is $15\text{ m}$ long and $12\text{ m}$ wide. What is the length of the longest rod that can be placed flat on the floor?
10. The diagonals of a rhombus are $24\text{ cm}$ and $10\text{ cm}$. Find its perimeter.
11. The perimeter of a rhombus is $40\text{ cm}$ and one of its diagonals is $12\text{ cm}$. Find its area.
12. The adjacent sides of a parallelogram are $15\text{ cm}$ and $10\text{ cm}$. If the distance between the $15\text{ cm}$ sides is $6\text{ cm}$, find the distance between the $10\text{ cm}$ sides.
13. Parallel sides of a trapezium are $18\text{ cm}$ and $12\text{ cm}$, and its height is $7\text{ cm}$. Find its area.
14. The area of a trapezium is $250\text{ cm}^2$ and its height is $10\text{ cm}$. If the parallel sides are in the ratio $3:2$, find the shorter parallel side.
15. Find the area of a regular hexagon whose perimeter is $36\text{ cm}$.
16. If each interior angle of a regular polygon is $150^\circ$, find its number of sides.
17. The circumference of a circular plot is $132\text{ cm}$. Find its area. (Take $\pi = \dfrac{22}{7}$)
18. The perimeter of a semicircular plate is $36\text{ cm}$. Find its diameter. (Take $\pi = \dfrac{22}{7}$)
19. A sector of a circle of radius $14\text{ cm}$ has a central angle of $45^\circ$. Find its area. (Take $\pi = \dfrac{22}{7}$)
20. A square garden of side $20\text{ m}$ has a $2\text{ m}$ wide gravel walk running all around inside it. Find the area of the gravel walk.
21. A rectangular park $50\text{ m} \times 30\text{ m}$ has two perpendicular roads $3\text{ m}$ wide passing through its centre parallel to the sides. Find the area of the roads.
22. Find the inradius of a right triangle with sides $8\text{ cm}$, $15\text{ cm}$, and $17\text{ cm}$.
23. Find the area of the circle circumscribing a square of side $14\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
24. A wheel has diameter $70\text{ cm}$. How many metres does it travel in $250$ complete revolutions? (Take $\pi = \dfrac{22}{7}$)
25. A wheel covers a distance of $88\text{ km}$ in $1000$ revolutions. Find the radius of the wheel. (Take $\pi = \dfrac{22}{7}$)
26. A wire when bent in the form of a square encloses an area of $121\text{ cm}^2$. If the same wire is bent into a circle, find the area enclosed. (Take $\pi = \dfrac{22}{7}$)
27. A circular wire of radius $28\text{ cm}$ is cut and bent into a rectangle whose length and breadth are in the ratio $6:5$. Find the area of the rectangle. (Take $\pi = \dfrac{22}{7}$)
28. Find the area of the leaf-shaped region between two quarter circles in a square of side $7\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
29. Four identical circles each of radius $14\text{ cm}$ touch each other externally. Find the area of the space enclosed between them. (Take $\pi = \dfrac{22}{7}$)
30. The length of a rectangle is increased by $30\%$ and its breadth is decreased by $20\%$. Find the net percentage change in its area.
31. If the radius of a circle is decreased by $10\%$, find the percentage decrease in its area.
32. Find the cost of paving a $7\text{ m}$ wide circular path around a circular lawn of radius $14\text{ m}$ at Rs $10$ per square metre. (Take $\pi = \dfrac{22}{7}$)

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 54 $\text{cm}^2$ | Right-angled: $\frac{1}{2} \times 9 \times 12 = 54$ |
| 2 | 66 $\text{cm}^2$ | $s = 22$, $\sqrt{22 \times 11 \times 9 \times 2} = \sqrt{4356} = 66$ |
| 3 | 48 $\text{cm}^2$ | Equal sides $= 10$, $h = \sqrt{100-36} = 8$, $\frac{1}{2} \times 12 \times 8 = 48$ |
| 4 | $16\sqrt{3}\text{ cm}^2$ | $\frac{\sqrt{3}}{4} \times 8^2 = 16\sqrt{3}$ |
| 5 | 36 cm | $a^2 = 144 \implies a = 12$, perimeter $= 3 \times 12 = 36$ |
| 6 | 12 cm | $r = \frac{a}{2\sqrt{3}} \implies a = 2\sqrt{3} \times 2\sqrt{3} = 12$ |
| 7 | $17\sqrt{2}\text{ cm}$ | $\text{Side} = \sqrt{289} = 17$, $\text{diagonal} = 17\sqrt{2}$ |
| 8 | 150 $\text{cm}^2$ | $2(3x+2x) = 50 \implies x = 5$, $L=15, B=10$, $\text{area} = 15 \times 10 = 150$ |
| 9 | $3\sqrt{41}\text{ m}$ | $\text{Diagonal} = \sqrt{15^2 + 12^2} = \sqrt{369} = 3\sqrt{41}$ |
| 10 | 52 cm | $\text{Side} = \sqrt{12^2 + 5^2} = 13$, $\text{perimeter} = 4 \times 13 = 52$ |
| 11 | 96 $\text{cm}^2$ | $\text{Side} = 10$, $\text{half } d_2 = \sqrt{100-36} = 8 \implies d_2 = 16$, $\text{area} = \frac{1}{2} \times 12 \times 16 = 96$ |
| 12 | 9 cm | $\text{Area} = 15 \times 6 = 90$, height on $10\text{ cm}$ side $= \frac{90}{10} = 9$ |
| 13 | 105 $\text{cm}^2$ | $\frac{1}{2} \times (18 + 12) \times 7 = 105$ |
| 14 | 20 cm | Sum of parallel sides $= \frac{250 \times 2}{10} = 50$, ratio $3:2 \implies 30$ and $20$ |
| 15 | $54\sqrt{3}\text{ cm}^2$ | $\text{Side} = \frac{36}{6} = 6$, $\text{area} = 6 \times \frac{\sqrt{3}}{4} \times 36 = 54\sqrt{3}$ |
| 16 | 12 | $\text{Exterior angle} = 180^\circ - 150^\circ = 30^\circ$, sides $= \frac{360^\circ}{30^\circ} = 12$ |
| 17 | 1386 $\text{cm}^2$ | $2 \times \frac{22}{7} \times r = 132 \implies r = 21$, $\text{area} = \frac{22}{7} \times 21^2 = 1386$ |
| 18 | 14 cm | $r\left(\frac{22}{7} + 2\right) = 36 \implies r\left(\frac{36}{7}\right) = 36 \implies r = 7$, diameter $= 14$ |
| 19 | 77 $\text{cm}^2$ | $\frac{45}{360} \times \frac{22}{7} \times 14^2 = \frac{1}{8} \times 616 = 77$ |
| 20 | 144 $\text{m}^2$ | $\text{Outer} = 20^2 = 400$, $\text{inner side} = 16 \implies \text{inner} = 256$, path $= 400 - 256 = 144$ |
| 21 | 231 $\text{m}^2$ | $w(L + B - w) = 3(50 + 30 - 3) = 3 \times 77 = 231$ |
| 22 | 3 cm | $r = \frac{a + b - c}{2} = \frac{8 + 15 - 17}{2} = 3$ |
| 23 | 308 $\text{cm}^2$ | $R = \frac{14}{\sqrt{2}}$, $R^2 = 98$, $\text{area} = \frac{22}{7} \times 98 = 308$ |
| 24 | 550 m | $\text{Circumference} = \frac{22}{7} \times 0.7 = 2.2\text{ m}$, distance $= 250 \times 2.2 = 550$ |
| 25 | 14 m | $\text{Circumference} = \frac{88000}{1000} = 88\text{ m}$, $2 \times \frac{22}{7} \times r = 88 \implies r = 14$ |
| 26 | 154 $\text{cm}^2$ | $\text{Side} = 11 \implies \text{perimeter} = 44$, $2\pi r = 44 \implies r = 7$, $\text{area} = \frac{22}{7} \times 49 = 154$ |
| 27 | 1920 $\text{cm}^2$ | $\text{Perimeter} = 2 \times \frac{22}{7} \times 28 = 176$, $2(6x+5x) = 176 \implies x = 8$, area $= 48 \times 40 = 1920$ |
| 28 | 28 $\text{cm}^2$ | $\text{Leaf area} = \frac{4}{7} \times a^2 = \frac{4}{7} \times 49 = 28$ |
| 29 | 168 $\text{cm}^2$ | $\text{Enclosed area} = \frac{6}{7} \times r^2 = \frac{6}{7} \times 196 = 168$ |
| 30 | 4% increase | $30 - 20 - \frac{30 \times 20}{100} = 10 - 6 = +4\%$ |
| 31 | 19% decrease | $-10 - 10 + \frac{(-10)(-10)}{100} = -20 + 1 = -19\%$ |
| 32 | Rs 7700 | $\text{Outer } R = 21$, path area $= \frac{22}{7}(21^2 - 14^2) = 770\text{ m}^2$, cost $= 770 \times 10 = 7700$ |
