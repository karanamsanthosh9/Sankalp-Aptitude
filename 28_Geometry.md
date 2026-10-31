# Geometry

> Read this like a class: draw the figure, label what is given, and mark the angle or length you are trying to find.

## 0. Start here: geometry is a story about relationships

A diagram is more than a picture: parallel lines create equal angles, a triangle’s angles add to 180°, and a circle’s chords and tangents obey predictable relationships. Questions ask you to use one or more of these facts to find a missing angle, side, area, or coordinate.

Begin by copying the given information onto a sketch. Then identify the relationship that connects it to the unknown. For example, if one angle on a straight line is 65°, the adjacent angle must be $180°-65°=115°$. Check that your final angles and lengths fit the figure—angles in a triangle must total 180°, and lengths must be positive.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Parallel lines, transversals, and intersecting angle pairs | 1 |
| Triangle angle sum, exterior angles, and angle bisectors | 2 |
| Triangle congruence, similarity, and Thales theorem | 3 |
| Triangle centres (Centroid, Incentre, Circumcentre, Orthocentre) | 4 |
| Apollonius theorem and median calculations | 5 |
| Right-angled and equilateral triangle geometric properties | 6 |
| Quadrilaterals and cyclic quadrilaterals | 7 |
| Circle chords, perpendicular from centre, and chord intersections | 8 |
| Angles subtended by arcs, chords, and semicircle angle | 9 |
| Circle tangents, secants, and alternate segment theorem | 10 |
| Direct and transverse common tangents to two circles | 11 |
| Polygons (interior/exterior angles, number of diagonals) | 12 |
| Coordinate geometry: distance, section, and midpoint formulas | 13 |
| Coordinate geometry: area of triangle and line slopes | 14 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Parallel lines cut by a transversal" | Corresponding and alternate interior angles are equal; co-interior sum to $180^\circ$ |
| "Angle bisector of $\angle A$ meets $BC$ at $D$" | $\dfrac{AB}{AC} = \dfrac{BD}{DC}$ |
| "$\triangle ABC \sim \triangle DEF$" | $\dfrac{\text{Area}(ABC)}{\text{Area}(DEF)} = \left(\dfrac{AB}{DE}\right)^2 = \left(\dfrac{\text{Altitude}_1}{\text{Altitude}_2}\right)^2$ |
| "$I$ is incentre, $O$ is circumcentre, $H$ is orthocentre" | $\angle BIC = 90^\circ + \dfrac{A}{2}$, $\angle BOC = 2A$, $\angle BHC = 180^\circ - A$ |
| "$G$ is centroid with median $AD$" | $AG : GD = 2 : 1$ |
| "Cyclic quadrilateral $ABCD$" | $\angle A + \angle C = 180^\circ$, $\angle B + \angle D = 180^\circ$ |
| "Chords $AB$ and $CD$ intersect at $P$" | $PA \cdot PB = PC \cdot PD$ |
| "Tangent $PT$ and secant $PAB$" | $PT^2 = PA \cdot PB$ |
| "Direct Common Tangent ($DCT$)" | $DCT = \sqrt{d^2 - (r_1 - r_2)^2}$ |
| "Transverse Common Tangent ($TCT$)" | $TCT = \sqrt{d^2 - (r_1 + r_2)^2}$ |

## 3. The core idea

- **Triangle angle sum:** Sum of angles $= 180^\circ$. Exterior angle equals the sum of two interior opposite angles.
- **Centres of triangle:** Centroid ($G$, medians, $2:1$), Incentre ($I$, angle bisectors, equidistant from sides), Circumcentre ($O$, perpendicular bisectors, equidistant from vertices), Orthocentre ($H$, altitudes).
- **Circle geometry:** Angle subtended at the centre is twice the angle subtended at any point on the remaining circumference. Angle in a semicircle is $90^\circ$.
- **Polygons:** Sum of interior angles $= (n-2) \times 180^\circ$, Number of diagonals $= \dfrac{n(n-3)}{2}$, Sum of exterior angles $= 360^\circ$.

## 4. Question-type walkthroughs

### Question type 1. Parallel lines and transversals

**Idea:** When two parallel lines are cut by a transversal, alternate interior angles are equal, corresponding angles are equal, and consecutive interior (co-interior) angles are supplementary ($A + B = 180^\circ$).

**Example 1:** Two parallel lines $AB \parallel CD$ are intersected by a transversal. If one interior angle is $65^\circ$, find its alternate interior angle and its co-interior angle.
- Alternate interior angle $= 65^\circ$.
- Co-interior angle $= 180^\circ - 65^\circ$ = **115^\circ**.

**Example 2:** In two intersecting straight lines $AB$ and $CD$ meeting at $O$, $\angle AOC + \angle BOE = 70^\circ$ and $\angle BOD = 40^\circ$. Find $\angle BOE$ and reflex $\angle COE$.
- Vertically opposite angles: $\angle AOC = \angle BOD = 40^\circ$.
- $\angle BOE = 70^\circ - 40^\circ$ = **30^\circ**.
- $\angle COE = 180^\circ - 70^\circ = 110^\circ$, so reflex $\angle COE = 360^\circ - 110^\circ$ = **250^\circ**.

### Question type 2. Triangle angle properties and angle bisectors

**Idea:** Angle sum $= 180^\circ$. Exterior angle = sum of non-adjacent interior angles. Interior angle bisector theorem: $\dfrac{AB}{AC} = \dfrac{BD}{DC}$.

**Example 1:** In $\triangle ABC$, $\angle A = 70^\circ$ and $\angle B = 50^\circ$. Side $BC$ is extended to $D$. Find exterior angle $\angle ACD$.
- Exterior $\angle ACD = \angle A + \angle B = 70^\circ + 50^\circ$ = **120^\circ**.

**Example 2:** In $\triangle ABC$, $AD$ is the bisector of $\angle A$ meeting $BC$ at $D$. If $AB = 6\text{ cm}$, $AC = 8\text{ cm}$, and $BC = 7\text{ cm}$, find the length of $BD$.
- $\dfrac{BD}{DC} = \dfrac{AB}{AC} = \dfrac{6}{8} = \dfrac{3}{4}$.
- $BD = \dfrac{3}{3 + 4} \times 7 = \dfrac{3}{7} \times 7$ = **3 cm**.

### Question type 3. Congruence, similarity, and Thales theorem

**Idea:** If $\triangle ABC \sim \triangle DEF$, then $\dfrac{\text{Area}(ABC)}{\text{Area}(DEF)} = \left(\dfrac{AB}{DE}\right)^2 = \left(\dfrac{BC}{EF}\right)^2$. If $DE \parallel BC$, then $\dfrac{AD}{DB} = \dfrac{AE}{EC}$ (Thales theorem).

**Example 1:** $\triangle ABC \sim \triangle DEF$. $\text{Area}(\triangle ABC) = 64\text{ cm}^2$, $\text{Area}(\triangle DEF) = 121\text{ cm}^2$, and $BC = 8\text{ cm}$. Find $EF$.
- $\dfrac{\text{Area}(ABC)}{\text{Area}(DEF)} = \left(\dfrac{BC}{EF}\right)^2 \implies \dfrac{64}{121} = \left(\dfrac{8}{EF}\right)^2$.
- $\dfrac{8}{11} = \dfrac{8}{EF} \implies EF$ = **11 cm**.

**Example 2:** In $\triangle ABC$, $DE \parallel BC$ with $D$ on $AB$ and $E$ on $AC$. If $AD = 3\text{ cm}$, $DB = 5\text{ cm}$, and $AE = 4.5\text{ cm}$, find $EC$ and $AC$.
- $\dfrac{AD}{DB} = \dfrac{AE}{EC} \implies \dfrac{3}{5} = \dfrac{4.5}{EC} \implies EC = \dfrac{5 \times 4.5}{3} = 7.5\text{ cm}$.
- $AC = AE + EC = 4.5 + 7.5$ = **12 cm** (and $EC$ = **7.5 cm**).

### Question type 4. Triangle centres

**Idea:** Incentre $I$: $\angle BIC = 90^\circ + \dfrac{\angle A}{2}$. Circumcentre $O$: $\angle BOC = 2\angle A$. Orthocentre $H$: $\angle BHC = 180^\circ - \angle A$. Centroid $G$: Divides median $AD$ in ratio $AG : GD = 2 : 1$.

**Example 1:** In $\triangle ABC$, $\angle A = 80^\circ$. Find $\angle BIC$ where $I$ is incentre, $\angle BOC$ where $O$ is circumcentre, and $\angle BHC$ where $H$ is orthocentre.
- $\angle BIC = 90^\circ + \dfrac{80^\circ}{2} = 90^\circ + 40^\circ$ = **130^\circ**.
- $\angle BOC = 2 \times 80^\circ$ = **160^\circ**.
- $\angle BHC = 180^\circ - 80^\circ$ = **100^\circ**.

**Example 2:** $G$ is the centroid of $\triangle ABC$ and $AD$ is a median of length $12\text{ cm}$. Find the lengths of $AG$ and $GD$.
- $AG = \dfrac{2}{3} \times 12$ = **8 cm**, $GD = \dfrac{1}{3} \times 12$ = **4 cm**.

### Question type 5. Apollonius theorem and medians

**Idea:** If $AD$ is a median to side $BC$, then $AB^2 + AC^2 = 2(AD^2 + BD^2) = 2\left(AD^2 + \left(\dfrac{BC}{2}\right)^2\right)$.

**Example 1:** In $\triangle ABC$, $AB = 7\text{ cm}$, $AC = 9\text{ cm}$, and $BC = 8\text{ cm}$. Find the length of median $AD$.
- $BD = \dfrac{8}{2} = 4\text{ cm}$.
- $7^2 + 9^2 = 2(AD^2 + 4^2) \implies 49 + 81 = 2(AD^2 + 16)$.
- $130 = 2(AD^2 + 16) \implies AD^2 + 16 = 65 \implies AD^2 = 49 \implies AD$ = **7 cm**.

### Question type 6. Right-angled and equilateral triangles

**Idea:** Right $\triangle ABC$ with altitude $BD$ on hypotenuse $AC$: $BD = \dfrac{AB \times BC}{AC}$, $BD^2 = AD \times CD$, $AB^2 = AD \times AC$.

**Example 1:** In right-angled $\triangle ABC$ ($\angle B = 90^\circ$), $AB = 15\text{ cm}$ and $BC = 20\text{ cm}$. Find the length of perpendicular $BD$ dropped on hypotenuse $AC$.
- Hypotenuse $AC = \sqrt{15^2 + 20^2} = 25\text{ cm}$.
- $BD = \dfrac{AB \times BC}{AC} = \dfrac{15 \times 20}{25}$ = **12 cm**.

**Example 2:** Find the altitude of an equilateral triangle whose side is $8\text{ cm}$.
- $\text{Altitude} = \dfrac{\sqrt{3}}{2} \times 8$ = **$4\sqrt{3}\text{ cm}$**.

### Question type 7. Quadrilaterals and cyclic quadrilaterals

**Idea:** In a cyclic quadrilateral: $\angle A + \angle C = 180^\circ$, $\angle B + \angle D = 180^\circ$. Exterior angle equals the opposite interior angle.

**Example 1:** In a cyclic quadrilateral $ABCD$, $\angle A = (2x + 10)^\circ$ and $\angle C = (3x + 20)^\circ$. Find the value of $x$ and $\angle A$.
- $(2x + 10) + (3x + 20) = 180 \implies 5x + 30 = 180 \implies 5x = 150 \implies x = 30$.
- $\angle A = 2(30) + 10$ = **70^\circ**.

**Example 2:** Side $AB$ of cyclic quadrilateral $ABCD$ is produced to $E$. If exterior angle $\angle CBE = 85^\circ$, find $\angle ADC$.
- Exterior angle equals opposite interior angle: $\angle ADC = \angle CBE$ = **85^\circ**.

### Question type 8. Circle chords and distances from centre

**Idea:** Perpendicular from centre bisects chord: $r^2 = d^2 + \left(\dfrac{L}{2}\right)^2$. Intersecting chords theorem: $PA \cdot PB = PC \cdot PD$.

**Example 1:** A chord of length $16\text{ cm}$ is at a distance of $6\text{ cm}$ from the centre of a circle. Find the radius of the circle.
- Half chord $= \dfrac{16}{2} = 8\text{ cm}$.
- Radius $r = \sqrt{8^2 + 6^2} = \sqrt{64 + 36} = \sqrt{100}$ = **10 cm**.

**Example 2:** Two chords $AB$ and $CD$ intersect inside a circle at point $P$. If $AP = 4\text{ cm}$, $PB = 6\text{ cm}$, and $CP = 3\text{ cm}$, find $PD$ and $CD$.
- $AP \cdot PB = CP \cdot PD \implies 4 \times 6 = 3 \times PD \implies PD = 8\text{ cm}$.
- $CD = CP + PD = 3 + 8$ = **11 cm** (and $PD$ = **8 cm**).

### Question type 9. Angles subtended by arcs and chords

**Idea:** Angle at centre is double the angle at circumference: $\angle AOB = 2\angle ACB$. Angles in the same segment are equal. Angle in a semicircle is $90^\circ$.

**Example 1:** Chord $AB$ subtends an angle of $110^\circ$ at the centre $O$. Find the angle subtended by $AB$ at any point $C$ on the major arc.
- $\angle ACB = \dfrac{110^\circ}{2}$ = **55^\circ**.

**Example 2:** $AB$ is a diameter of a circle and $C$ is a point on the circumference. If $\angle CAB = 35^\circ$, find $\angle ABC$.
- $\angle ACB = 90^\circ$ (angle in semicircle).
- $\angle ABC = 180^\circ - 90^\circ - 35^\circ$ = **55^\circ**.

### Question type 10. Tangents, secants, and alternate segment theorem

**Idea:** Radius is perpendicular to tangent at point of contact. Tangent lengths from an external point are equal ($PA = PB$). Tangent-Secant theorem: $PT^2 = PA \cdot PB$.

**Example 1:** From an external point $P$, a tangent $PT$ is drawn to a circle of radius $5\text{ cm}$ centered at $O$. If $OP = 13\text{ cm}$, find the length of tangent $PT$.
- In right $\triangle OTP$: $PT = \sqrt{OP^2 - OT^2} = \sqrt{13^2 - 5^2} = \sqrt{144}$ = **12 cm**.

**Example 2:** A tangent $PT$ and a secant $PAB$ are drawn from point $P$ to a circle. If $PA = 4\text{ cm}$ and $AB = 5\text{ cm}$, find the length of tangent $PT$.
- $PB = PA + AB = 4 + 5 = 9\text{ cm}$.
- $PT^2 = PA \times PB = 4 \times 9 = 36 \implies PT$ = **6 cm**.

### Question type 11. Common tangents to two circles

**Idea:** Distance between centres $d$, radii $r_1$ and $r_2$. Direct Common Tangent: $DCT = \sqrt{d^2 - (r_1 - r_2)^2}$. Transverse Common Tangent: $TCT = \sqrt{d^2 - (r_1 + r_2)^2}$.

**Example 1:** Two circles of radii $8\text{ cm}$ and $3\text{ cm}$ have centres $13\text{ cm}$ apart. Find the lengths of their direct and transverse common tangents.
- $DCT = \sqrt{13^2 - (8 - 3)^2} = \sqrt{169 - 25} = \sqrt{144}$ = **12 cm**.
- $TCT = \sqrt{13^2 - (8 + 3)^2} = \sqrt{169 - 121} = \sqrt{48}$ = **$4\sqrt{3}\text{ cm}$**.

### Question type 12. Polygons and diagonals

**Idea:** $n$-sided polygon: Sum of interior angles $= (n-2) \times 180^\circ$, Number of diagonals $= \dfrac{n(n-3)}{2}$, Sum of exterior angles $= 360^\circ$.

**Example 1:** Find the number of diagonals in an octagon ($n = 8$).
- $\text{Diagonals} = \dfrac{8(8 - 3)}{2} = \dfrac{8 \times 5}{2}$ = **20**.

**Example 2:** The sum of the interior angles of a polygon is $1260^\circ$. Find the number of sides.
- $(n - 2) \times 180^\circ = 1260^\circ \implies n - 2 = \dfrac{1260}{180} = 7 \implies n$ = **9 sides**.

### Question type 13. Coordinate geometry: distance, section, and midpoint

**Idea:** Distance $d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$. Section point $P = \left(\dfrac{mx_2 + nx_1}{m + n}, \dfrac{my_2 + ny_1}{m + n}\right)$. Midpoint $= \left(\dfrac{x_1 + x_2}{2}, \dfrac{y_1 + y_2}{2}\right)$.

**Example 1:** Find the distance between points $A(3, 4)$ and $B(7, 1)$.
- $d = \sqrt{(7 - 3)^2 + (1 - 4)^2} = \sqrt{4^2 + (-3)^2} = \sqrt{16 + 9} = \sqrt{25}$ = **5 units**.

**Example 2:** Find the coordinates of the point $P$ which divides the line joining $A(1, 2)$ and $B(6, 7)$ internally in the ratio $2 : 3$.
- $x = \dfrac{2(6) + 3(1)}{2 + 3} = \dfrac{12 + 3}{5} = 3$, $y = \dfrac{2(7) + 3(2)}{2 + 3} = \dfrac{14 + 6}{5} = 4$.
- Point $P$ = **(3, 4)**.

### Question type 14. Coordinate geometry: area and line slopes

**Idea:** Area of triangle $= \dfrac{1}{2}|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)|$. Slope $m = \dfrac{y_2 - y_1}{x_2 - x_1}$. Parallel lines: $m_1 = m_2$. Perpendicular lines: $m_1 m_2 = -1$.

**Example 1:** Find the area of the triangle formed by vertices $A(1, 2)$, $B(4, 6)$, and $C(7, 2)$.
- $\text{Area} = \dfrac{1}{2}|1(6 - 2) + 4(2 - 2) + 7(2 - 6)| = \dfrac{1}{2}|4 + 0 - 28| = \dfrac{1}{2}|-24|$ = **12 sq units**.

**Example 2:** A line passes through $(2, 3)$ and $(4, 7)$. Find its slope and the slope of any line perpendicular to it.
- Slope $m = \dfrac{7 - 3}{4 - 2} = \dfrac{4}{2}$ = **2**.
- Perpendicular slope $= -\dfrac{1}{m}$ = **$-\dfrac{1}{2}$**.

## 5. Before you practise

**Your turn:** Two angles in a triangle are 48° and 67°. Find the third angle.

**Think it through:** All three angles sum to 180°, so the missing angle is $180°-48°-67°=\mathbf{65°}$. The three values add back to 180°.

### Quick revision

- Write down the theorem before substituting values.
- Similar figures have corresponding sides in the same ratio; their areas scale by the square of that ratio.
- In a cyclic quadrilateral, opposite angles add to 180°.
- For coordinate questions, use the labelled coordinates in a consistent order.

### Common mistakes

1. Confusing equal angles with supplementary angles.
2. Comparing the wrong corresponding sides in similar triangles.
3. Treating the angle at the centre as equal to the angle at the circumference; for the same arc, the centre angle is twice the inscribed angle.
4. Using a theorem without checking its condition (for example, cyclicity or parallel lines).
5. Losing a negative sign in coordinate differences.

## 6. Practice

1. In two parallel lines cut by a transversal, one co-interior angle is $125^\circ$. Find the other co-interior angle.
2. Two angles of a linear pair are in the relationship where one exceeds the other by $40^\circ$. Find the smaller angle.
3. In $\triangle ABC$, $\angle A = 55^\circ$ and $\angle B = 65^\circ$. Find $\angle C$.
4. In $\triangle ABC$, side $BC$ is produced to $D$. If $\angle ACD = 130^\circ$ and $\angle A = 50^\circ$, find $\angle B$.
5. In $\triangle ABC$, $AD$ is the angle bisector of $\angle A$. If $AB = 6\text{ cm}$, $AC = 9\text{ cm}$, and $BC = 10\text{ cm}$, find $BD$.
6. $\triangle ABC \sim \triangle DEF$. If $\text{Area}(\triangle ABC) : \text{Area}(\triangle DEF) = 49 : 81$, find the ratio of their corresponding sides $AB : DE$.
7. In $\triangle ABC$, $DE \parallel BC$. If $AD = 4\text{ cm}$, $DB = 6\text{ cm}$, and $EC = 9\text{ cm}$, find the length of $AE$.
8. In $\triangle ABC$, $\angle A = 70^\circ$. Find the angle $\angle BIC$ formed at the incentre $I$.
9. In $\triangle ABC$, $\angle A = 65^\circ$. Find the angle $\angle BOC$ subtended at the circumcentre $O$.
10. In $\triangle ABC$, $\angle A = 75^\circ$. Find the angle $\angle BHC$ formed at the orthocentre $H$.
11. $G$ is the centroid of $\triangle ABC$ and $AD$ is a median of length $15\text{ cm}$. Find the length of $GD$.
12. In $\triangle ABC$, $AB = 5\text{ cm}$, $AC = 7\text{ cm}$, and $BC = 6\text{ cm}$. Find the length of median $AD$ to side $BC$.
13. In right-angled $\triangle ABC$ with $\angle B = 90^\circ$, $AB = 9\text{ cm}$ and $BC = 12\text{ cm}$. Find the altitude from $B$ to hypotenuse $AC$.
14. Find the altitude of an equilateral triangle of side $10\text{ cm}$.
15. In cyclic quadrilateral $ABCD$, $\angle B = 115^\circ$. Find $\angle D$.
16. Side $AB$ of cyclic quadrilateral $ABCD$ is extended to $E$. If $\angle CBE = 100^\circ$, find $\angle ADC$.
17. A chord of length $24\text{ cm}$ is drawn in a circle of radius $13\text{ cm}$. Find the distance of the chord from the centre.
18. Two chords $AB$ and $CD$ intersect inside a circle at $P$. If $AP = 2\text{ cm}$, $PB = 6\text{ cm}$, and $CP = 3\text{ cm}$, find $PD$.
19. An arc subtends an angle of $140^\circ$ at the centre of a circle. Find the angle it subtends at any point on the remaining circumference.
20. $AB$ is a diameter of a circle and $C$ is a point on the circumference. If $\angle CAB = 40^\circ$, find $\angle ABC$.
21. In a cyclic quadrilateral $ABCD$, if $\angle ABC = 130^\circ$, find the angle $\angle ADC$ in the opposite segment.
22. From an external point $P$, a tangent $PT$ of length $15\text{ cm}$ is drawn to a circle of radius $8\text{ cm}$. Find the distance of $P$ from the centre $O$.
23. Secant $PAB$ and tangent $PT$ are drawn from $P$ to a circle. If $PA = 3\text{ cm}$ and $AB = 9\text{ cm}$, find $PT$.
24. A tangent $PT$ touches a circle at $A$, and $AB$ is a chord such that $\angle BAT = 65^\circ$. Find $\angle ACB$ where $C$ is a point on the alternate segment.
25. Two circles of radii $7\text{ cm}$ and $2\text{ cm}$ have centres $13\text{ cm}$ apart. Find the length of their direct common tangent.
26. Two circles of radii $5\text{ cm}$ and $3\text{ cm}$ have centres $17\text{ cm}$ apart. Find the length of their transverse common tangent.
27. Find the number of diagonals in a decagon ($n = 10$).
28. Find the sum of all interior angles of a regular hexagon.
29. Find the distance between the points $A(-1, -7)$ and $B(5, 1)$.
30. Find the coordinates of the point dividing the segment joining $(0, 4)$ and $(8, 12)$ internally in the ratio $1 : 3$.
31. Find the area of the triangle whose vertices are $(0, 0)$, $(3, 0)$, and $(0, 4)$.
32. Find the slope of a line perpendicular to the line passing through $(2, 2)$ and $(5, 8)$.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 55^\circ | Co-interior angles sum to $180^\circ$: $180^\circ - 125^\circ = 55^\circ$ |
| 2 | 70^\circ | $x + (x + 40^\circ) = 180^\circ \implies 2x = 140^\circ \implies x = 70^\circ$ |
| 3 | 60^\circ | $180^\circ - (55^\circ + 65^\circ) = 180^\circ - 120^\circ = 60^\circ$ |
| 4 | 80^\circ | $\text{Exterior angle} = \text{sum of opposite interior}: 130^\circ - 50^\circ = 80^\circ$ |
| 5 | 4 cm | Angle bisector theorem: $\frac{BD}{DC} = \frac{6}{9} = \frac{2}{3} \implies BD = 10 \times \frac{2}{5} = 4$ |
| 6 | 7 : 9 | Ratio of sides $= \sqrt{\frac{49}{81}} = \frac{7}{9}$ |
| 7 | 6 cm | Thales theorem: $\frac{AD}{DB} = \frac{AE}{EC} \implies \frac{4}{6} = \frac{AE}{9} \implies AE = 6$ |
| 8 | 125^\circ | $\angle BIC = 90^\circ + \frac{A}{2} = 90^\circ + 35^\circ = 125^\circ$ |
| 9 | 130^\circ | Circumcentre angle $\angle BOC = 2A = 2 \times 65^\circ = 130^\circ$ |
| 10 | 105^\circ | Orthocentre angle $\angle BHC = 180^\circ - A = 180^\circ - 75^\circ = 105^\circ$ |
| 11 | 5 cm | Centroid divides median $2:1$, $GD = \frac{1}{3} \times 15 = 5$ |
| 12 | $2\sqrt{7}\text{ cm}$ | $5^2 + 7^2 = 2(AD^2 + 3^2) \implies 74 = 2(AD^2 + 9) \implies AD = \sqrt{28} = 2\sqrt{7}$ |
| 13 | 7.2 cm | Hypotenuse $= 15$, altitude $= \frac{9 \times 12}{15} = 7.2$ |
| 14 | $5\sqrt{3}\text{ cm}$ | $\text{Altitude} = \frac{\sqrt{3}}{2} \times 10 = 5\sqrt{3}$ |
| 15 | 65^\circ | Opposite angles sum to $180^\circ$: $180^\circ - 115^\circ = 65^\circ$ |
| 16 | 100^\circ | Exterior angle of cyclic quadrilateral equals opposite interior angle $= 100^\circ$ |
| 17 | 5 cm | $\text{Distance} = \sqrt{13^2 - 12^2} = \sqrt{169 - 144} = 5$ |
| 18 | 4 cm | $AP \cdot PB = CP \cdot PD \implies 2 \times 6 = 3 \times PD \implies PD = 4$ |
| 19 | 70^\circ | Angle at circumference $= \frac{140^\circ}{2} = 70^\circ$ |
| 20 | 50^\circ | In semicircle $\angle ACB = 90^\circ$, $\angle ABC = 180^\circ - 90^\circ - 40^\circ = 50^\circ$ |
| 21 | 50^\circ | Opposite angles of cyclic quadrilateral: $180^\circ - 130^\circ = 50^\circ$ |
| 22 | 17 cm | $OP = \sqrt{PT^2 + r^2} = \sqrt{15^2 + 8^2} = \sqrt{289} = 17$ |
| 23 | 6 cm | $PA = 3, PB = 12 \implies PT^2 = 3 \times 12 = 36 \implies PT = 6$ |
| 24 | 65^\circ | Alternate segment theorem: $\angle ACB = \angle BAT = 65^\circ$ |
| 25 | 12 cm | $DCT = \sqrt{13^2 - (7 - 2)^2} = \sqrt{169 - 25} = 12$ |
| 26 | 15 cm | $TCT = \sqrt{17^2 - (5 + 3)^2} = \sqrt{289 - 64} = 15$ |
| 27 | 35 | Diagonals $= \frac{10(10 - 3)}{2} = \frac{70}{2} = 35$ |
| 28 | 720^\circ | Sum of interior angles $= (6 - 2) \times 180^\circ = 720^\circ$ |
| 29 | 10 units | $d = \sqrt{(5 - (-1))^2 + (1 - (-7))^2} = \sqrt{36 + 64} = 10$ |
| 30 | (2, 6) | $x = \frac{1(8) + 3(0)}{4} = 2$, $y = \frac{1(12) + 3(4)}{4} = 6 \implies (2, 6)$ |
| 31 | 6 sq units | Right triangle at origin: $\text{Area} = \frac{1}{2} \times 3 \times 4 = 6$ |
| 32 | $-\frac{1}{2}$ | $m_1 = \frac{8 - 2}{5 - 2} = \frac{6}{3} = 2 \implies m_2 = -\frac{1}{2}$ |
