# Mensuration 3D

> Read this like a class: picture the solid you are measuring, and ask whether you need what it holds or what must be covered.

## 0. Start here: inside or outside?

A box has a volume—the space inside it—and a surface area—the material needed to cover it. A water tank question may ask how much it holds; a painting question asks for surface area. This chapter uses the same distinction for cubes, cylinders, cones, spheres, and combinations of solids.

Sketch the solid and mark its dimensions before choosing a formula. Volume uses cubic units; area uses square units. As a sense check, doubling every length makes a solid’s volume eight times as large, because $2^3=8$, while each surface area becomes four times as large.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Cube (volume, surface areas, space diagonal) | 1 |
| Cuboid and longest rod in a room | 2 |
| Right circular cylinder (solid and hollow) | 3 |
| Right circular cone (slant height, volume, areas) | 4 |
| Sphere and hemisphere (solid and hollow) | 5 |
| Frustum of a right circular cone | 6 |
| Right prism and right pyramid | 7 |
| Regular tetrahedron | 8 |
| Melting, recasting, and reshaping of solids | 9 |
| Combination and composite solids (tents, toys, capsules) | 10 |
| Cutting, slicing, and ratio of divided solids | 11 |
| Water flow through pipes and cylindrical/rectangular tanks | 12 |
| Immersion of solid objects in liquids and level rise | 13 |
| Percentage and ratio changes in 3D dimensions | 14 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Diagonal of a cube is $d$" | Side $a = \dfrac{d}{\sqrt{3}}$ |
| "Longest rod that fits in a room $l \times b \times h$" | Space diagonal $d = \sqrt{l^2 + b^2 + h^2}$ |
| "Area of 4 walls of a room" | Lateral surface area $= 2(l + b)h$ |
| "Slant height of cone $l$" | $l = \sqrt{r^2 + h^2}$, $\text{CSA} = \pi r l$ |
| "Hollow cylinder inner radius $r$, outer $R$" | Volume $= \pi(R^2 - r^2)h$, $\text{TSA} = 2\pi(R+r)h + 2\pi(R^2-r^2)$ |
| "Frustum of height $h$, radii $R$ and $r$" | Slant height $l = \sqrt{h^2 + (R-r)^2}$, $V = \dfrac{1}{3}\pi h (R^2 + r^2 + Rr)$ |
| "Solid melted and recast into another" | Total volume remains unchanged ($V_1 = V_2$) |
| "Water flows at speed $v$ through pipe radius $r$" | Volume per second $= \pi r^2 v$ |
| "Solid immersed into liquid in container" | $\text{Base area of container} \times \text{Rise in level} = \text{Volume of solid}$ |

## 3. The core idea

- **Volume:** Space occupied. Cube $= a^3$, Cuboid $= lbh$, Cylinder $= \pi r^2 h$, Cone $= \dfrac{1}{3}\pi r^2 h$, Sphere $= \dfrac{4}{3}\pi r^3$, Hemisphere $= \dfrac{2}{3}\pi r^3$.
- **Surface areas:** Curved/Lateral Surface Area (CSA/LSA) covers the sides only. Total Surface Area (TSA) includes top and bottom bases: $\text{TSA} = \text{CSA} + \text{Base areas}$.
- **Prism and Pyramid rule:** Prism volume $= \text{Base area} \times h$. Pyramid volume $= \dfrac{1}{3} \times \text{Base area} \times h$.
- When melting or recasting, mass and volume are conserved: $N \times V_{\text{small}} = V_{\text{large}}$. Standard convention takes $\pi = \dfrac{22}{7}$.

## 4. Question-type walkthroughs

### Question type 1. Cube

**Idea:** Side $a$. Volume $V = a^3$, $\text{LSA} = 4a^2$, $\text{TSA} = 6a^2$, Space diagonal $d = a\sqrt{3}$.

**Example 1:** Find the volume, TSA, and space diagonal of a cube of edge $6\text{ cm}$.
- $\text{Volume} = 6^3$ = **216 $\text{cm}^3$**.
- $\text{TSA} = 6 \times 6^2 = 6 \times 36$ = **216 $\text{cm}^2$**.
- $\text{Diagonal} = 6\sqrt{3}$ = **$6\sqrt{3}\text{ cm}$**.

**Example 2:** The diagonal of a cube is $8\sqrt{3}\text{ cm}$. Find its volume and total surface area.
- $a\sqrt{3} = 8\sqrt{3} \implies a = 8\text{ cm}$.
- $\text{Volume} = 8^3$ = **512 $\text{cm}^3$**.
- $\text{TSA} = 6 \times 8^2 = 6 \times 64$ = **384 $\text{cm}^2$**.

### Question type 2. Cuboid

**Idea:** Dimensions $l, b, h$. Volume $V = lbh$, $\text{TSA} = 2(lb + bh + hl)$, Area of 4 walls $= 2(l + b)h$, Space diagonal $d = \sqrt{l^2 + b^2 + h^2}$.

**Example 1:** A cuboid has length $10\text{ cm}$, breadth $8\text{ cm}$, and height $6\text{ cm}$. Find its volume, TSA, and space diagonal.
- $\text{Volume} = 10 \times 8 \times 6$ = **480 $\text{cm}^3$**.
- $\text{TSA} = 2(10 \times 8 + 8 \times 6 + 10 \times 6) = 2(80 + 48 + 60) = 2(188)$ = **376 $\text{cm}^2$**.
- $\text{Diagonal} = \sqrt{10^2 + 8^2 + 6^2} = \sqrt{100 + 64 + 36} = \sqrt{200}$ = **$10\sqrt{2}\text{ cm}$**.

**Example 2:** Find the length of the longest rod that can be placed in a room $12\text{ m}$ long, $9\text{ m}$ broad, and $8\text{ m}$ high.
- $\text{Longest rod} = \sqrt{12^2 + 9^2 + 8^2} = \sqrt{144 + 81 + 64} = \sqrt{289}$ = **17 m**.

### Question type 3. Right circular cylinder

**Idea:** Solid cylinder: $V = \pi r^2 h$, $\text{CSA} = 2\pi rh$, $\text{TSA} = 2\pi r(r + h)$. Hollow cylinder: $V = \pi(R^2 - r^2)h$.

**Example 1:** A cylinder has base radius $7\text{ cm}$ and height $10\text{ cm}$. Find its volume, CSA, and TSA.
- $\text{Volume} = \dfrac{22}{7} \times 7^2 \times 10 = 154 \times 10$ = **1540 $\text{cm}^3$**.
- $\text{CSA} = 2 \times \dfrac{22}{7} \times 7 \times 10$ = **440 $\text{cm}^2$**.
- $\text{TSA} = 2 \times \dfrac{22}{7} \times 7 \times (7 + 10) = 44 \times 17$ = **748 $\text{cm}^2$**.

**Example 2:** A hollow iron pipe is $14\text{ cm}$ long. Its outer and inner diameters are $20\text{ cm}$ and $16\text{ cm}$ respectively. Find the volume of iron in the pipe.
- Outer radius $R = 10\text{ cm}$, Inner radius $r = 8\text{ cm}$.
- $\text{Volume} = \dfrac{22}{7}(10^2 - 8^2) \times 14 = \dfrac{22}{7} \times 36 \times 14 = 22 \times 36 \times 2$ = **1584 $\text{cm}^3$**.

### Question type 4. Right circular cone

**Idea:** Slant height $l = \sqrt{r^2 + h^2}$. Volume $V = \dfrac{1}{3}\pi r^2 h$, $\text{CSA} = \pi r l$, $\text{TSA} = \pi r(r + l)$.

**Example 1:** A cone has base radius $7\text{ cm}$ and height $24\text{ cm}$. Find its slant height, volume, CSA, and TSA.
- Slant height $l = \sqrt{7^2 + 24^2} = \sqrt{49 + 576} = 25\text{ cm}$.
- $\text{Volume} = \dfrac{1}{3} \times \dfrac{22}{7} \times 7^2 \times 24 = \dfrac{1}{3} \times 154 \times 24$ = **1232 $\text{cm}^3$**.
- $\text{CSA} = \dfrac{22}{7} \times 7 \times 25$ = **550 $\text{cm}^2$**.
- $\text{TSA} = \dfrac{22}{7} \times 7 \times (7 + 25) = 22 \times 32$ = **704 $\text{cm}^2$**.

### Question type 5. Sphere and hemisphere

**Idea:** Sphere: Volume $V = \dfrac{4}{3}\pi r^3$, $\text{Surface Area} = 4\pi r^2$. Solid hemisphere: Volume $V = \dfrac{2}{3}\pi r^3$, $\text{CSA} = 2\pi r^2$, $\text{TSA} = 3\pi r^2$.

**Example 1:** Find the volume and surface area of a sphere of radius $21\text{ cm}$.
- $\text{Volume} = \dfrac{4}{3} \times \dfrac{22}{7} \times 21^3 = 4 \times 22 \times 441$ = **38808 $\text{cm}^3$**.
- $\text{Surface Area} = 4 \times \dfrac{22}{7} \times 21^2 = 4 \times 1386$ = **5544 $\text{cm}^2$**.

**Example 2:** Find the CSA and TSA of a solid hemisphere of radius $7\text{ cm}$.
- $\text{CSA} = 2 \times \dfrac{22}{7} \times 7^2$ = **308 $\text{cm}^2$**.
- $\text{TSA} = 3 \times \dfrac{22}{7} \times 7^2 = 3 \times 154$ = **462 $\text{cm}^2$**.

### Question type 6. Frustum of a cone

**Idea:** Radii $R$ and $r$, vertical height $h$. Slant height $l = \sqrt{h^2 + (R-r)^2}$, Volume $V = \dfrac{1}{3}\pi h (R^2 + r^2 + Rr)$, $\text{CSA} = \pi(R + r)l$.

**Example 1:** A bucket in the shape of a frustum of a cone has circular top radius $10\text{ cm}$, bottom radius $4\text{ cm}$, and vertical height $8\text{ cm}$. Find its slant height and CSA.
- Slant height $l = \sqrt{8^2 + (10 - 4)^2} = \sqrt{64 + 36}$ = **10 cm**.
- $\text{CSA} = \dfrac{22}{7} \times (10 + 4) \times 10 = \dfrac{22}{7} \times 14 \times 10$ = **440 $\text{cm}^2$**.

### Question type 7. Right prism and right pyramid

**Idea:** Prism: Volume $= \text{Base Area} \times h$, $\text{LSA} = \text{Base Perimeter} \times h$, $\text{TSA} = \text{LSA} + 2(\text{Base Area})$. Pyramid: Volume $= \dfrac{1}{3} \times \text{Base Area} \times h$, $\text{LSA} = \dfrac{1}{2} \times \text{Base Perimeter} \times \text{Slant Height}$.

**Example 1 (Prism):** The base of a right prism is an equilateral triangle of side $6\text{ cm}$ and its height is $10\text{ cm}$. Find its volume and LSA.
- $\text{Base Area} = \dfrac{\sqrt{3}}{4} \times 6^2 = 9\sqrt{3}\text{ cm}^2$.
- $\text{Volume} = 9\sqrt{3} \times 10$ = **$90\sqrt{3}\text{ cm}^3$**.
- $\text{LSA} = (3 \times 6) \times 10$ = **180 $\text{cm}^2$**.

**Example 2 (Pyramid):** A right pyramid has a square base of side $10\text{ cm}$ and vertical height $12\text{ cm}$. Find its slant height, volume, and TSA.
- Slant height $l = \sqrt{12^2 + 5^2} = \sqrt{144 + 25} = 13\text{ cm}$.
- $\text{Volume} = \dfrac{1}{3} \times 10^2 \times 12$ = **400 $\text{cm}^3$**.
- $\text{LSA} = \dfrac{1}{2} \times (4 \times 10) \times 13 = 260\text{ cm}^2$. $\text{TSA} = 260 + 100$ = **360 $\text{cm}^2$**.

### Question type 8. Regular tetrahedron

**Idea:** A pyramid with 4 congruent equilateral triangular faces of side $a$. Volume $V = \dfrac{\sqrt{2}}{12}a^3$, $\text{TSA} = \sqrt{3}a^2$, Height $h = \sqrt{\dfrac{2}{3}}a$.

**Example 1:** Find the volume and TSA of a regular tetrahedron of edge $6\text{ cm}$.
- $\text{Volume} = \dfrac{\sqrt{2}}{12} \times 6^3 = \dfrac{\sqrt{2} \times 216}{12}$ = **$18\sqrt{2}\text{ cm}^3$**.
- $\text{TSA} = \sqrt{3} \times 6^2$ = **$36\sqrt{3}\text{ cm}^2$**.

### Question type 9. Melting, recasting, and reshaping

**Idea:** When solids are melted and recast, total volume remains constant: $\sum V_{\text{initial}} = \sum V_{\text{final}}$.

**Example 1:** Three metallic solid spheres of radii $3\text{ cm}$, $4\text{ cm}$, and $5\text{ cm}$ are melted into a single solid sphere. Find the radius of the resulting sphere.
- $R^3 = 3^3 + 4^3 + 5^3 = 27 + 64 + 125 = 216 \implies R$ = **6 cm**.

**Example 2:** A solid metallic cone of radius $6\text{ cm}$ and height $24\text{ cm}$ is melted and recast into small solid spheres of radius $3\text{ cm}$. Find the number of spheres formed.
- $\text{Number } N = \dfrac{\frac{1}{3}\pi \times 6^2 \times 24}{\frac{4}{3}\pi \times 3^3} = \dfrac{36 \times 24}{4 \times 27} = \dfrac{864}{108}$ = **8 spheres**.

### Question type 10. Composite solids

**Idea:** Add volumes of individual components; for surface area, sum only the exposed/outer surfaces.

**Example 1:** A circus tent consists of a cylindrical base of radius $14\text{ m}$ and height $3\text{ m}$, surmounted by a conical roof with slant height $10\text{ m}$. Find the total canvas required.
- $\text{Canvas} = \text{CSA(Cylinder)} + \text{CSA(Cone)} = 2\pi rh + \pi r l = \pi r (2h + l)$.
- $\text{Area} = \dfrac{22}{7} \times 14 \times (2 \times 3 + 10) = 44 \times 16$ = **704 $\text{m}^2$**.

### Question type 11. Cutting and slicing solids

**Idea:** Cutting adds new exposed faces to the surface area. For similar sections (like cones cut parallel to base), volume scales as the cube of linear scale factor: $\dfrac{V_1}{V_2} = \left(\dfrac{h_1}{h_2}\right)^3$.

**Example 1:** A solid sphere of radius $7\text{ cm}$ is cut into two equal hemispheres. Find the increase in total surface area.
- Two new circular base faces are created, each of area $\pi r^2$.
- $\text{Increase in TSA} = 2\pi r^2 = 2 \times \dfrac{22}{7} \times 7^2$ = **308 $\text{cm}^2$**.

**Example 2:** A cone of height $H$ is cut into two parts by a plane parallel to its base at midpoint $\dfrac{H}{2}$. Find the ratio of the volume of the smaller top cone to that of the lower frustum.
- $\dfrac{V_{\text{top}}}{V_{\text{full}}} = \left(\dfrac{1}{2}\right)^3 = \dfrac{1}{8}$.
- $V_{\text{frustum}} = 8 - 1 = 7$. Ratio $V_{\text{top}} : V_{\text{frustum}}$ = **1 : 7**.

### Question type 12. Water flow through pipes

**Idea:** Volume of water discharged in time $t = \text{Cross-sectional Area} \times \text{Speed} \times t$. Equate this to $\text{Tank Base Area} \times \text{Rise in Height}$.

**Example 1:** Water flows through a cylindrical pipe of internal diameter $2\text{ cm}$ at $70\text{ cm/s}$ into a cylindrical tank of base radius $40\text{ cm}$. Find the rise in water level in $30\text{ minutes}$.
- Pipe radius $r = 1\text{ cm}$, Time $= 30 \times 60 = 1800\text{ s}$.
- Volume delivered $= \pi \times 1^2 \times (70 \times 1800) = 126000\pi\text{ cm}^3$.
- Tank volume $= \pi \times 40^2 \times H = 1600\pi H$.
- $1600\pi H = 126000\pi \implies H = \dfrac{126000}{1600}$ = **78.75 cm**.

### Question type 13. Immersion of objects in liquids

**Idea:** Volume of submerged object = Volume of displaced liquid $= \text{Base Area of container} \times \text{Rise in level}$.

**Example 1:** A solid sphere of radius $6\text{ cm}$ is dropped into a cylindrical vessel of radius $12\text{ cm}$ containing water. Find the rise in water level.
- $\text{Volume of sphere} = \dfrac{4}{3}\pi \times 6^3 = \dfrac{4}{3}\pi \times 216 = 288\pi\text{ cm}^3$.
- $\text{Base area of vessel} = \pi \times 12^2 = 144\pi\text{ cm}^2$.
- $\text{Rise in level } h = \dfrac{288\pi}{144\pi}$ = **2 cm**.

### Question type 14. Percentage and ratio changes in 3D dimensions

**Idea:** If radius of a sphere increases by $x\%$, new volume factor is $\left(1 + \dfrac{x}{100}\right)^3$. For cylinder/cone: $V \propto r^2 h$.

**Example 1:** If the radius of a sphere is increased by $10\%$, find the percentage increase in its volume.
- Ratio of new radius to old $= 1.1 : 1$.
- Ratio of new volume to old $= (1.1)^3 = 1.331$.
- $\text{Percentage increase} = (1.331 - 1) \times 100$ = **33.1% increase**.

## 5. Before you practise

**Your turn:** A cube’s edge changes from 2 cm to 4 cm. By what factor do its volume and total surface area change?

**Think it through:** The edge doubles. Volume scales by $2^3=8$, and surface area scales by $2^2=4$. So the volume is multiplied by 8 and the surface area by 4.

### Quick revision

- Volume measures capacity; surface area measures covering.
- Curved/lateral area covers the sides; total surface area also includes the exposed bases.
- In melting and recasting, conserve total volume.
- For a water-level rise, displaced volume equals container base area times rise in level.

### Common mistakes

1. Using diameter where the formula expects radius.
2. Confusing vertical height with slant height in cones and pyramids.
3. Including hidden faces in the surface area of a joined solid.
4. Adding lengths, areas, or volumes with incompatible units.
5. Forgetting that dimensions scale to the second power for area and third power for volume.

## 6. Practice

1. Find the volume of a cube whose edge is $12\text{ cm}$.
2. The total surface area of a cube is $150\text{ cm}^2$. Find the length of its diagonal.
3. Find the length of the longest rod that can be placed in a room of dimensions $8\text{ m} \times 6\text{ m} \times 24\text{ m}$.
4. Find the area of the four walls of a room $10\text{ m}$ long, $6\text{ m}$ broad, and $4\text{ m}$ high.
5. A wooden cuboid of dimensions $12\text{ cm} \times 9\text{ cm} \times 6\text{ cm}$ is cut into small cubes of side $3\text{ cm}$. How many cubes are obtained?
6. Find the volume of a right circular cylinder whose base radius is $14\text{ cm}$ and height is $15\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
7. The curved surface area of a cylinder of height $20\text{ cm}$ is $880\text{ cm}^2$. Find its base radius. (Take $\pi = \dfrac{22}{7}$)
8. A cylinder has base radius $7\text{ cm}$ and height $10\text{ cm}$. Find its total surface area. (Take $\pi = \dfrac{22}{7}$)
9. Find the volume of a cone whose base radius is $21\text{ cm}$ and height is $10\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
10. A conical tent has base radius $7\text{ m}$ and height $24\text{ m}$. Find its curved surface area. (Take $\pi = \dfrac{22}{7}$)
11. Find the total surface area of a cone whose base radius is $14\text{ cm}$ and slant height is $16\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
12. Find the surface area of a solid sphere of radius $14\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
13. Find the volume of a solid sphere of radius $21\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
14. Find the total surface area of a solid hemisphere of radius $7\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
15. Find the volume of a hemisphere of radius $21\text{ cm}$. (Take $\pi = \dfrac{22}{7}$)
16. The radii of the circular ends of a frustum of a cone are $14\text{ cm}$ and $7\text{ cm}$, and its slant height is $25\text{ cm}$. Find its curved surface area. (Take $\pi = \dfrac{22}{7}$)
17. A bucket in the shape of a frustum has top radius $10\text{ cm}$, bottom radius $4\text{ cm}$, and vertical height $21\text{ cm}$. Find its capacity in $\text{cm}^3$. (Take $\pi = \dfrac{22}{7}$)
18. The base of a right prism is an equilateral triangle of side $4\text{ cm}$ and its height is $15\text{ cm}$. Find its volume.
19. A right pyramid stands on a square base of side $12\text{ cm}$. If its height is $8\text{ cm}$, find its volume.
20. A right pyramid has a square base of side $12\text{ cm}$ and height $8\text{ cm}$. Find its lateral surface area.
21. Find the volume of a regular tetrahedron of edge $12\text{ cm}$.
22. Find the total surface area of a regular tetrahedron of edge $8\text{ cm}$.
23. Three metallic spheres of radii $1\text{ cm}$, $6\text{ cm}$, and $8\text{ cm}$ are melted to form a single solid sphere. Find the radius of the new sphere.
24. A solid cylinder of radius $6\text{ cm}$ and height $12\text{ cm}$ is melted and recast into solid spheres of radius $3\text{ cm}$. How many spheres are formed?
25. A solid cube of edge $10\text{ cm}$ is cut into smaller cubes of edge $2\text{ cm}$. Find the number of smaller cubes.
26. A circus tent has a cylindrical base of radius $14\text{ m}$ and height $3\text{ m}$, surmounted by a conical roof of slant height $10\text{ m}$. Find the total canvas required. (Take $\pi = \dfrac{22}{7}$)
27. A cone is cut into two parts by a plane parallel to its base through the midpoint of its axis. Find the ratio of the volume of the full cone to the volume of the lower frustum.
28. A solid sphere is cut into two equal hemispheres. What is the percentage increase in total surface area?
29. Water flows at $10\text{ km/h}$ through a cylindrical pipe of radius $7\text{ cm}$ into a rectangular tank $28\text{ m} \times 25\text{ m}$. Find the rise in water level in the tank in $1\text{ hour}$. (Take $\pi = \dfrac{22}{7}$)
30. A solid metal sphere of radius $3\text{ cm}$ is dropped into a cylindrical vessel of radius $6\text{ cm}$ partially filled with water. Find the rise in water level.
31. If each edge of a cube is increased by $20\%$, find the percentage increase in its volume.
32. If the radius of a cylinder is increased by $10\%$ and its height is decreased by $20\%$, find the net percentage change in its volume.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 1728 $\text{cm}^3$ | $V = 12^3 = 1728$ |
| 2 | $5\sqrt{3}\text{ cm}$ | $6a^2 = 150 \implies a = 5$, diagonal $= 5\sqrt{3}$ |
| 3 | 26 m | $\text{Diagonal} = \sqrt{8^2 + 6^2 + 24^2} = \sqrt{64 + 36 + 576} = \sqrt{676} = 26$ |
| 4 | 128 $\text{m}^2$ | $\text{Area of 4 walls} = 2(L + B)H = 2(10 + 6) \times 4 = 128$ |
| 5 | 24 | $\frac{12 \times 9 \times 6}{3^3} = \frac{648}{27} = 24$ |
| 6 | 9240 $\text{cm}^3$ | $V = \frac{22}{7} \times 14^2 \times 15 = 22 \times 28 \times 15 = 9240$ |
| 7 | 7 cm | $2 \times \frac{22}{7} \times r \times 20 = 880 \implies r = 7$ |
| 8 | 748 $\text{cm}^2$ | $\text{TSA} = 2 \times \frac{22}{7} \times 7 \times (7 + 10) = 44 \times 17 = 748$ |
| 9 | 4620 $\text{cm}^3$ | $V = \frac{1}{3} \times \frac{22}{7} \times 21^2 \times 10 = 4620$ |
| 10 | 550 $\text{m}^2$ | $l = \sqrt{7^2 + 24^2} = 25$, $\text{CSA} = \frac{22}{7} \times 7 \times 25 = 550$ |
| 11 | 1320 $\text{cm}^2$ | $\text{TSA} = \frac{22}{7} \times 14 \times (14 + 16) = 44 \times 30 = 1320$ |
| 12 | 2464 $\text{cm}^2$ | $\text{SA} = 4 \times \frac{22}{7} \times 14^2 = 2464$ |
| 13 | 38808 $\text{cm}^3$ | $V = \frac{4}{3} \times \frac{22}{7} \times 21^3 = 38808$ |
| 14 | 462 $\text{cm}^2$ | $\text{TSA} = 3 \times \frac{22}{7} \times 7^2 = 462$ |
| 15 | 19404 $\text{cm}^3$ | $V = \frac{2}{3} \times \frac{22}{7} \times 21^3 = 19404$ |
| 16 | 1650 $\text{cm}^2$ | $\text{CSA} = \frac{22}{7} \times (14 + 7) \times 25 = \frac{22}{7} \times 21 \times 25 = 1650$ |
| 17 | 3432 $\text{cm}^3$ | $V = \frac{1}{3} \times \frac{22}{7} \times 21 \times (10^2 + 4^2 + 10 \times 4) = 22 \times 156 = 3432$ |
| 18 | $60\sqrt{3}\text{ cm}^3$ | $\text{Base Area} = \frac{\sqrt{3}}{4} \times 16 = 4\sqrt{3}$, $V = 4\sqrt{3} \times 15 = 60\sqrt{3}$ |
| 19 | 384 $\text{cm}^3$ | $V = \frac{1}{3} \times 12^2 \times 8 = \frac{1}{3} \times 144 \times 8 = 384$ |
| 20 | 240 $\text{cm}^2$ | Slant height $= \sqrt{8^2 + 6^2} = 10$, $\text{LSA} = \frac{1}{2} \times 48 \times 10 = 240$ |
| 21 | $144\sqrt{2}\text{ cm}^3$ | $V = \frac{\sqrt{2}}{12} \times 12^3 = \frac{\sqrt{2} \times 1728}{12} = 144\sqrt{2}$ |
| 22 | $64\sqrt{3}\text{ cm}^2$ | $\text{TSA} = \sqrt{3} \times 8^2 = 64\sqrt{3}$ |
| 23 | 9 cm | $R^3 = 1^3 + 6^3 + 8^3 = 1 + 216 + 512 = 729 \implies R = 9$ |
| 24 | 12 | $N = \frac{\pi \times 6^2 \times 12}{\frac{4}{3}\pi \times 3^3} = \frac{432}{36} = 12$ |
| 25 | 125 | $N = \left(\frac{10}{2}\right)^3 = 5^3 = 125$ |
| 26 | 704 $\text{m}^2$ | $\text{Canvas} = 2 \times \frac{22}{7} \times 14 \times 3 + \frac{22}{7} \times 14 \times 10 = 264 + 440 = 704$ |
| 27 | 8 : 7 | Full cone to top cone $= 8:1$, so frustum $= 7$. Ratio $= 8:7$ |
| 28 | 50% | Sphere TSA $= 4\pi r^2$, two hemispheres TSA $= 6\pi r^2$, increase $= \frac{2\pi r^2}{4\pi r^2} \times 100 = 50\%$ |
| 29 | 22 cm | $\text{Vol} = \frac{22}{7} \times (0.07)^2 \times 10000 = 154\text{ m}^3$, rise $= \frac{154}{28 \times 25} = 0.22\text{ m} = 22\text{ cm}$ |
| 30 | 1 cm | $\text{Rise} = \frac{\frac{4}{3}\pi \times 3^3}{\pi \times 6^2} = \frac{36\pi}{36\pi} = 1$ |
| 31 | 72.8% increase | $(1.2)^3 - 1 = 1.728 - 1 = +72.8\%$ |
| 32 | 3.2% decrease | $(1.1)^2 \times 0.8 - 1 = 1.21 \times 0.8 - 1 = 0.968 - 1 = -3.2\%$ |
