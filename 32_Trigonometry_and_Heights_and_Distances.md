# Trigonometry and Heights and Distances

> Read this like a class: draw the right triangle first, mark the angle you can actually see, and label the sides relative to that angle.

## 0. Start here: turn looking up into a triangle

When you look up at a tower, the ground, the tower, and your line of sight form a right triangle. The angle of elevation is the angle at your eyes; the height and horizontal distance are the two sides that let you calculate with trigonometry. Looking down from a height gives an angle of depression, which matches the corresponding angle of elevation on the ground.

Questions ask for a height, a distance, or an angle, often after someone moves to a second observation point. Draw one triangle for each position and label what stays the same. A useful sense check: from the same ground level, moving closer to a tower makes the angle of elevation larger.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Height of tower from angle of elevation and distance | 1 |
| Distance from tower given angle of depression | 2 |
| Two elevation angles from same horizontal line (find height) | 3 |
| Angles from foot and top of a building to an object | 4 |
| Shadow problems (sun angle and pole height) | 5 |
| Elevation angle changes as observer moves toward tower | 6 |
| Width of river using two observation points | 7 |
| Cliff height with lighthouse on top | 8 |
| Ladder or inclined plane (height and base) | 9 |
| Trigonometric identities involving sin, cos, tan | 10 |
| Complementary angles ($\sin/\cos$ pair) | 11 |
| Tower seen from north and south (two directions) | 12 |
| Moving object changing elevation angle | 13 |
| Angle between two buildings or objects | 14 |
| Sum or product identity simplification | 15 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "angle of elevation $= \theta$" | Observer looks up; $\tan\theta = \dfrac{\text{height}}{\text{distance}}$ |
| "angle of depression $= \theta$" | Observer looks down; equal to elevation from ground (alternate angles) |
| "from a point $d$ m away" | Horizontal distance from the base of the object |
| "moves $x$ m closer" | Distance reduces; set up two equations |
| "shadow of length $s$" | $\tan(\text{sun angle}) = \dfrac{\text{height}}{s}$ |
| "ladder of length $L$, angle $\theta$" | $\text{height} = L\sin\theta$, $\text{base} = L\cos\theta$ |
| "from due south / due north" | Two equations for the same tower from two directions |
| "$\sin\theta = \dfrac{p}{h}$" | Use $\cos^2\theta + \sin^2\theta = 1$ to find other ratios |
| "top angle $\alpha$, bottom angle $\beta$" | Two $\tan$ equations; subtract to isolate height of segment |

## 3. The core idea

- **Standard values** (memorise):

| $\theta$ | $0°$ | $30°$ | $45°$ | $60°$ | $90°$ |
|---|---|---|---|---|---|
| $\sin\theta$ | $0$ | $\dfrac{1}{2}$ | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{\sqrt{3}}{2}$ | $1$ |
| $\cos\theta$ | $1$ | $\dfrac{\sqrt{3}}{2}$ | $\dfrac{1}{\sqrt{2}}$ | $\dfrac{1}{2}$ | $0$ |
| $\tan\theta$ | $0$ | $\dfrac{1}{\sqrt{3}}$ | $1$ | $\sqrt{3}$ | undefined |

- **Pythagorean identities:** $\sin^2\theta + \cos^2\theta = 1$; $1 + \tan^2\theta = \sec^2\theta$; $1 + \cot^2\theta = \text{cosec}^2\theta$.
- **Key relations:** $\tan\theta = \dfrac{\sin\theta}{\cos\theta}$; $\cot\theta = \dfrac{1}{\tan\theta}$; $\sec\theta = \dfrac{1}{\cos\theta}$; $\text{cosec}\,\theta = \dfrac{1}{\sin\theta}$.
- **Complementary:** $\sin(90°-\theta) = \cos\theta$, $\tan(90°-\theta) = \cot\theta$.

## 4. Question-type walkthroughs

### Question type 1. Height of tower from angle of elevation

**Idea:** draw the right triangle; the tower is the opposite side, the horizontal distance is the adjacent side. $\tan\theta = \dfrac{h}{d}$.

**Example 1:** From a point 30 m away, the angle of elevation of a tower is $30°$. Find the height.
- $h = d\tan 30° = 30 \times \dfrac{1}{\sqrt{3}} = \dfrac{30}{\sqrt{3}} = 10\sqrt{3}$ m $\approx$ **17.32 m**.

**Example 2:** The angle of elevation is $45°$ and the height is 50 m. Find the distance from the tower.
- $d = \dfrac{h}{\tan 45°} = \dfrac{50}{1} =$ **50 m**.

### Question type 2. Distance from base using angle of depression

**Idea:** the angle of depression equals the angle of elevation from the ground (alternate interior angles). Set $\tan\theta = \dfrac{h}{d}$ and solve for $d$.

**Example:** An observer at the top of a 40 m tower sees a car at an angle of depression of $30°$. Distance of the car from the base?
- $\tan 30° = \dfrac{40}{d}$, so $d = \dfrac{40}{\tan 30°} = 40\sqrt{3} \approx$ **69.28 m**.

### Question type 3. Two elevation angles from two points on the same line

**Idea:** set up two equations ($\tan\alpha = h/x$ and $\tan\beta = h/(x+d)$), then divide or subtract to eliminate the unknown distance.

**Example:** From a point A the elevation of a tower is $60°$, and from point B, 20 m further away, the elevation is $30°$. Find the height.
- $\tan 60° = h/x \Rightarrow x = h/\sqrt{3}$.
- $\tan 30° = h/(x+20) \Rightarrow x+20 = h\sqrt{3}$.
- Subtracting: $h\sqrt{3} - h/\sqrt{3} = 20 \Rightarrow \dfrac{2h}{\sqrt{3}} = 20 \Rightarrow h = 10\sqrt{3} \approx$ **17.32 m**.

### Question type 4. Angles from foot and top of a building to a pole

**Idea:** from the foot the elevation is large; from the top the elevation is smaller (since the observer is now closer in height). Write two $\tan$ equations and subtract.

**Example:** From the foot of a building the angle of elevation to the top of a pole is $60°$; from the top of the 30 m building it is $30°$. The pole and the building are the same horizontal distance apart. Find the height of the pole.
- Let pole height $= p$ and horizontal distance $= d$.
- From foot: $\tan 60° = p/d \Rightarrow d = p/\sqrt{3}$.
- From top: $\tan 30° = (p-30)/d \Rightarrow (p-30)/(p/\sqrt{3}) = 1/\sqrt{3} \Rightarrow 3(p-30) = p \Rightarrow 2p = 90$.
- $p =$ **45 m**.

### Question type 5. Shadow problems

**Idea:** the sun's angle of elevation $\theta$ satisfies $\tan\theta = \dfrac{\text{pole height}}{\text{shadow length}}$.

**Example 1:** A 6 m pole casts a shadow when the sun's elevation is $60°$. Find the shadow length.
- $\tan 60° = 6/s \Rightarrow s = 6/\sqrt{3} = 2\sqrt{3} \approx$ **3.46 m**.

**Example 2:** A 10 m pole casts a shadow of 10 m. What is the angle of elevation of the sun?
- $\tan\theta = 10/10 = 1 \Rightarrow \theta =$ **45°**.

### Question type 6. Elevation angle changes as observer moves closer

**Idea:** the observer moves from point A to point B (closer to the tower). Write two $\tan$ equations and subtract distances.

**Example:** The angle of elevation of a tower changes from $30°$ to $45°$ when the observer moves 10 m toward the tower. Find the height.
- At $45°$: $\tan 45° = h/d_2 \Rightarrow d_2 = h$.
- At $30°$: $\tan 30° = h/d_1 \Rightarrow d_1 = h\sqrt{3}$.
- $d_1 - d_2 = 10$: $h\sqrt{3} - h = 10 \Rightarrow h(\sqrt{3}-1) = 10 \Rightarrow h = \dfrac{10}{\sqrt{3}-1} = 5(\sqrt{3}+1) \approx$ **13.66 m**.

### Question type 7. Width of river using two observation points

**Idea:** the tower (or tree) stands on one bank; angles are measured from two points on the other bank separated by a known distance.

**Example:** From point A the angle of elevation of a tree on the opposite bank is $60°$, and from point B (30 m behind A) the angle is $30°$. Find the width of the river.
- Let width $= w$ and tree height $= h$.
- $\tan 60° = h/w \Rightarrow h = w\sqrt{3}$.
- $\tan 30° = h/(w+30) \Rightarrow 3w = w+30 \Rightarrow w =$ **15 m**. Height $= 15\sqrt{3}$ m.

### Question type 8. Cliff with a lighthouse on top

**Idea:** two angles are given to the top and bottom of the lighthouse from a ship. The lighthouse sits on the cliff. Write two $\tan$ equations and subtract.

**Example:** A lighthouse 100 m tall stands on a cliff. From a ship, the angle of elevation of the top of the lighthouse is $60°$ and of the bottom is $30°$. Find the height of the cliff.
- Let cliff height $= c$ and horizontal distance $= d$.
- $\tan 30° = c/d \Rightarrow d = c\sqrt{3}$.
- $\tan 60° = (c+100)/d \Rightarrow c+100 = d\sqrt{3} = 3c \Rightarrow 2c = 100$.
- Cliff height $=$ **50 m**.

### Question type 9. Ladder or inclined plane

**Idea:** a ladder of length $L$ leaning at angle $\theta$ from the ground: height $= L\sin\theta$, base distance $= L\cos\theta$.

**Example:** A ladder 20 m long makes an angle of $60°$ with the ground. Find the height it reaches and its distance from the wall.
- Height $= 20\sin 60° = 20\times\dfrac{\sqrt{3}}{2} = 10\sqrt{3} \approx$ **17.32 m**.
- Distance from wall $= 20\cos 60° = 20\times0.5 =$ **10 m**.

### Question type 10. Trigonometric identities

**Idea:** use $\sin^2\theta + \cos^2\theta = 1$ to find unknown ratios. Memorise the Pythagorean triples: $(3, 4, 5)$, $(5, 12, 13)$, $(8, 15, 17)$, $(7, 24, 25)$.

**Example 1:** $\sin\theta = \dfrac{3}{5}$. Find $\cos\theta$ and $\tan\theta$.
- $\cos\theta = \dfrac{4}{5}$ (Pythagorean triple $3, 4, 5$). $\tan\theta = \dfrac{3}{4}$.

**Example 2:** $\tan\theta = \dfrac{5}{12}$. Find $\sec\theta$.
- $\sec^2\theta = 1 + \tan^2\theta = 1 + \dfrac{25}{144} = \dfrac{169}{144}$. $\sec\theta = \dfrac{13}{12}$.

### Question type 11. Complementary angles

**Idea:** $\sin(90°-\theta)=\cos\theta$, $\cos(90°-\theta)=\sin\theta$, $\tan(90°-\theta)=\cot\theta$. Pairs that add to $90°$ simplify products to 1.

**Example 1:** Evaluate $\sin 70° \times \sec 20°$.
- $\sec 20° = 1/\cos 20° = 1/\sin 70°$.
- $\sin 70° \times (1/\sin 70°) =$ **1**.

**Example 2:** Evaluate $\cos 40° \times \text{cosec}\,50°$.
- $\text{cosec}\,50° = 1/\sin 50° = 1/\cos 40°$ (since $\sin 50° = \cos 40°$).
- $\cos 40° \times (1/\cos 40°) =$ **1**.

### Question type 12. Tower seen from two directions (north-south)

**Idea:** set up two right triangles back-to-back. The total horizontal distance is the sum of the two base distances.

**Example:** From due south of a tower the elevation is $45°$; from due north the elevation is $30°$. The two observation points are 40 m apart. Find the tower height.
- From south: $\tan 45° = h/a \Rightarrow a = h$.
- From north: $\tan 30° = h/b \Rightarrow b = h\sqrt{3}$.
- $a + b = 40$: $h + h\sqrt{3} = 40 \Rightarrow h = \dfrac{40}{1+\sqrt{3}} = 20(\sqrt{3}-1) \approx$ **14.64 m**.

### Question type 13. Moving object changing elevation angle

**Idea:** a bird or aeroplane flies horizontally at a fixed height $H$. Its horizontal distance from the observer changes, causing the angle to change.

**Example:** An aeroplane flies at a height of 100 m. When flying toward an observer the angle of elevation changes from $30°$ to $60°$. How far did the plane travel?
- At $30°$: $d_1 = 100/\tan 30° = 100\sqrt{3}$.
- At $60°$: $d_2 = 100/\tan 60° = 100/\sqrt{3}$.
- Distance flown $= d_1 - d_2 = 100\sqrt{3} - 100/\sqrt{3} = \dfrac{200}{\sqrt{3}} = \dfrac{200\sqrt{3}}{3} \approx$ **115.47 m**.

### Question type 14. Angle between two buildings or objects

**Idea:** draw the horizontal and the difference in heights. $\tan\theta = \dfrac{\text{height difference}}{\text{horizontal distance}}$.

**Example:** Two buildings, 40 m and 30 m tall, stand 20 m apart. Find the angle of depression from the top of the taller building to the top of the shorter one.
- Height difference $= 10$ m, horizontal distance $= 20$ m.
- $\tan\theta = \dfrac{10}{20} = \dfrac{1}{2}$. $\theta = \arctan(0.5) \approx$ **26.57°**.

### Question type 15. Sum and product identity simplification

**Idea:** expand using algebraic identities, then apply Pythagorean identities to simplify.

**Example:** Show that $(\sin A + \text{cosec}\,A)^2 + (\cos A + \sec A)^2 = 7 + \tan^2 A + \cot^2 A$.
- $(\sin A + \text{cosec}\,A)^2 = \sin^2 A + 2 + \text{cosec}^2 A$.
- $(\cos A + \sec A)^2 = \cos^2 A + 2 + \sec^2 A$.
- Sum $= (\sin^2 A + \cos^2 A) + 4 + \text{cosec}^2 A + \sec^2 A = 1 + 4 + (1+\cot^2 A) + (1+\tan^2 A) =$ **$7 + \tan^2 A + \cot^2 A$**. Verified.

## 5. Before you practise

**Your turn:** You stand 20 m from a tree. The angle of elevation to its top is 45°. How tall is the tree, ignoring your eye height?

**Think it through:** $\tan45°=\text{height}/20=1$, so the height is $\mathbf{20\text{ m}}$. At a 45° angle the opposite and adjacent sides are equal.

### Quick revision

- Draw the right triangle and identify opposite, adjacent, and hypotenuse relative to the marked angle.
- Use $\tan\theta=\text{opposite}/\text{adjacent}$ for height and horizontal distance.
- Use sine and cosine when the hypotenuse (such as a ladder) is involved.
- Convert all lengths to the same unit before solving.

### Common mistakes

1. Measuring the angle from the vertical when the question gives it from the horizontal.
2. Mixing up the horizontal distance and the slant line of sight.
3. Using the full tower height when an observer is already above ground level.
4. Forgetting that the angle of depression equals the matching angle of elevation.
5. Choosing a trigonometric ratio before identifying which sides are known and unknown.

## 6. Practice

1. From a point 50 m away, the angle of elevation of a tower is $30°$. Find the height of the tower.
2. The angle of elevation of a tower is $45°$ and the observer is 40 m from the base. Find the height.
3. The angle of elevation of a tower is $60°$ and its height is 30 m. Find the distance from the base.
4. From the top of a 50 m tower, the angle of depression of a car is $45°$. Find the distance of the car from the base.
5. A pole 12 m high casts a shadow when the sun's angle of elevation is $60°$. Find the shadow length.
6. The angle of elevation of a tower changes from $45°$ to $30°$ as an observer moves 10 m away. Find the height.
7. From two points A and B on the same side of a river, the angle of elevation of a tree on the opposite bank is $60°$ from A and $30°$ from B. A and B are 30 m apart. Find the width of the river.
8. A lighthouse 100 m tall stands on a cliff. From a ship, the top of the lighthouse is at elevation $60°$ and the bottom at elevation $30°$. Find the height of the cliff.
9. A ladder 10 m long leans against a wall at an angle of $60°$ to the ground. Find the height reached by the ladder.
10. $\sin\theta = \dfrac{5}{13}$. Find $\cos\theta$ and $\tan\theta$.
11. Evaluate $\sin 25° \times \sec 65°$.
12. Find the value of $\tan^2 30° + \sin^2 45°$.
13. $\cos^2\theta = \dfrac{3}{4}$. Find $\sin\theta$.
14. $\sec\theta = \dfrac{5}{3}$. Find $\tan\theta$.
15. The angle of elevation of a tower is $60°$ from point A and $30°$ from point B, which is 20 m further away from the tower. Find the height of the tower.
16. An aeroplane at 100 m height flies toward an observer. The angle of elevation changes from $30°$ to $60°$. Find the horizontal distance flown.
17. From the top of a 60 m building, the angle of depression of a car is $30°$. Find the distance of the car from the base.
18. Two poles of heights 20 m and 30 m are 15 m apart. Find the angle of depression from the top of the taller to the top of the shorter.
19. From a point on the ground, the angle of elevation of the top of a pole 20 m high is $60°$. Find the distance from the pole.
20. A man 1.8 m tall stands 10 m from a 6 m lamp-post. Find the length of his shadow.
21. $\sin(A+B) = 1$ and $\sin(A-B) = \dfrac{1}{2}$. Find $A$ and $B$.
22. From point A, the angle of elevation of a cliff is $30°$; from point B, 20 m closer, the angle is $60°$. Find the height of the cliff.
23. $\cos\theta = \dfrac{12}{13}$. Find $\sin\theta$ and $\tan\theta$.
24. Evaluate $\sin^2 30° + \cos^2 60° + \tan^2 45°$.
25. A tower is 100 m tall. From a boat the angle of elevation is $45°$. Find the distance of the boat from the base.
26. The angle of elevation of a tower is $60°$ and its height is 75 m. Find the distance from the tower.
27. $\cot\theta = \dfrac{7}{24}$. Find $\text{cosec}\,\theta$.
28. From due south the elevation of a tower is $45°$ and from due north the elevation is $60°$. The two points are 100 m apart. Find the height. (Express as $h = \dfrac{100\sqrt{3}}{\sqrt{3}+1}$.)
29. $\tan A = 1$. Find $\sin^2 A - \cos^2 A$.
30. A pole stands on top of a 20 m building. From a point 20 m away, the angle of elevation of the top of the pole is $60°$ and the base of the building is at $45°$ from the same point. Find the height of the pole.
31. Two buildings face each other, 20 m apart. They are 40 m and 30 m tall. Find the angle of depression from the top of the taller to the top of the shorter.
32. A tower stands on a hill. From a point on the ground the angle of elevation of the top of the tower is $60°$ and of the top of the hill is $30°$. The hill is 50 m tall. Find the height of the tower.
33. Prove that $(\sin\theta + \cos\theta)^2 = 1 + 2\sin\theta\cos\theta$ and evaluate it for $\theta = 45°$.
34. From a point 30 m from the base of a flagpole, the angle of elevation of the top is $60°$. Find the height of the flagpole.
35. Show that $\dfrac{\sin A}{1+\cos A} + \dfrac{1+\cos A}{\sin A} = 2\,\text{cosec}\,A$ and verify for $A = 30°$.
36. A kite is flying at a height of 60 m. The string makes an angle of $30°$ with the horizontal. Find the length of the string.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | $\dfrac{50\sqrt{3}}{3}$ m $\approx 28.87$ m | $h=50\tan 30°=50/\sqrt{3}$ |
| 2 | 40 m | $h=40\tan 45°=40$ |
| 3 | $10\sqrt{3}$ m $\approx 17.32$ m | $d=30/\tan 60°=30/\sqrt{3}$ |
| 4 | 50 m | $d=50/\tan 45°=50$ |
| 5 | $4\sqrt{3}$ m $\approx 6.93$ m | $s=12/\tan 60°=12/\sqrt{3}$ |
| 6 | $5(\sqrt{3}+1)$ m $\approx 13.66$ m | $h(\sqrt{3}-1)=10$; rationalize |
| 7 | 15 m | $3w=w+30$; $w=15$ |
| 8 | 50 m | $c+100=3c$; $c=50$ |
| 9 | $5\sqrt{3}$ m $\approx 8.66$ m | $h=10\sin 60°=10\times\frac{\sqrt{3}}{2}$ |
| 10 | $\cos\theta=\frac{12}{13}$, $\tan\theta=\frac{5}{12}$ | Pythagorean triple $5,12,13$ |
| 11 | 1 | $\sec 65°=1/\cos 65°=1/\sin 25°$ |
| 12 | $\dfrac{5}{6}$ | $\frac{1}{3}+\frac{1}{2}$ |
| 13 | $\dfrac{1}{2}$ | $\sin^2\theta=1-\frac{3}{4}=\frac{1}{4}$ |
| 14 | $\dfrac{4}{3}$ | $\tan^2\theta=\sec^2\theta-1=\frac{25}{9}-1=\frac{16}{9}$ |
| 15 | $10\sqrt{3}$ m $\approx 17.32$ m | $\frac{2h}{\sqrt{3}}=20$; $h=10\sqrt{3}$ |
| 16 | $\dfrac{200\sqrt{3}}{3}$ m $\approx 115.47$ m | $d_1-d_2=100\sqrt{3}-100/\sqrt{3}=200/\sqrt{3}$ |
| 17 | $60\sqrt{3}$ m $\approx 103.92$ m | $d=60/\tan 30°=60\sqrt{3}$ |
| 18 | $\arctan\!\left(\dfrac{2}{3}\right) \approx 33.69°$ | height diff $=10$, horiz $=15$; $\tan\theta=2/3$ |
| 19 | $\dfrac{20\sqrt{3}}{3}$ m $\approx 11.55$ m | $d=20/\tan 60°=20/\sqrt{3}$ |
| 20 | $\dfrac{30}{7}$ m $\approx 4.29$ m | $6/(10+s)=1.8/s$; $4.2s=18$ |
| 21 | $A=60°$, $B=30°$ | $A+B=90°$, $A-B=30°$ |
| 22 | $10\sqrt{3}$ m $\approx 17.32$ m | $3d_B-d_B=20$; $d_B=10$; $h=10\sqrt{3}$ |
| 23 | $\sin\theta=\dfrac{5}{13}$, $\tan\theta=\dfrac{5}{12}$ | Pythagorean triple $5,12,13$ |
| 24 | $\dfrac{3}{2}$ | $\frac{1}{4}+\frac{1}{4}+1$ |
| 25 | 100 m | $d=100/\tan 45°=100$ |
| 26 | $25\sqrt{3}$ m $\approx 43.30$ m | $d=75/\tan 60°=75/\sqrt{3}=25\sqrt{3}$ |
| 27 | $\dfrac{25}{24}$ | $\text{cosec}^2\theta=1+\cot^2\theta=1+\frac{49}{576}=\frac{625}{576}$ |
| 28 | $\dfrac{100\sqrt{3}}{\sqrt{3}+1} = 50(3-\sqrt{3}) \approx 63.40$ m | $h+h/\sqrt{3}=100$; rationalize |
| 29 | 0 | $\tan A=1\Rightarrow A=45°$; $\sin^2 45°=\cos^2 45°$ |
| 30 | $20(\sqrt{3}-1)$ m $\approx 14.64$ m | $\tan 45°=20/d\Rightarrow d=20$; $\tan 60°=(20+p)/20$; $p=20(\sqrt{3}-1)$ |
| 31 | $\arctan\!\left(\dfrac{1}{2}\right) \approx 26.57°$ | height diff $=10$, horiz $=20$; $\tan\theta=1/2$ |
| 32 | 100 m | $\tan 30°=50/d\Rightarrow d=50\sqrt{3}$; $\tan 60°=(50+h)/(50\sqrt{3})=\sqrt{3}$; $h=100$ |
| 33 | 2 for $\theta=45°$ | Identity: $1+2\sin\theta\cos\theta=1+\sin 2\theta$; at $45°$: $1+1=2$ |
| 34 | $30\sqrt{3}$ m $\approx 51.96$ m | $h=30\tan 60°=30\sqrt{3}$ |
| 35 | 4 for $A=30°$ | $2\,\text{cosec}\,30°=2\times2=4$ |
| 36 | 120 m | $\sin 30°=60/L$; $L=60/0.5=120$ |
