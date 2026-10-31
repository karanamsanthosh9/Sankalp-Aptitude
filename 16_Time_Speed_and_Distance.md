# Time, Speed and Distance

> Read this like a class: sketch the journey, label what is known, and keep the units beside every number.

## 0. Start here: every journey has three parts

Picture a person travelling from home to a station. The same journey can be described by how far they go, how fast they travel, and how long it takes. This chapter asks you to connect those three quantities, compare journeys, work out meeting or catching times, or follow movement around a track.

Begin with the question’s story: is the distance fixed, is the time fixed, or are two travellers moving relative to one another? For example, covering the same distance faster must take less time. A quick sense check is to ask whether your answer respects that direction, and whether kilometres, metres, hours, and seconds have been made consistent.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Unit conversion and basic formula | 1 |
| Average speed (equal distances or unequal segments) | 2 |
| Constant distance and speed-time inverse ratio | 3 |
| Constant time and speed-distance direct ratio | 4 |
| Late and early arrival times | 5 |
| Stoppages and rest time per hour | 6 |
| Relative speed and meeting time | 7 |
| Speed ratio after meeting | 8 |
| Two-part journey with mixed transport modes | 9 |
| Circular tracks and race loops | 10 |
| Linear races, head starts, and dead heats | 11 |
| Escalators and moving walkways | 12 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Speed in km/h" to "m/s" | Multiply by $\dfrac{5}{18}$ |
| "Speed in m/s" to "km/h" | Multiply by $\dfrac{18}{5}$ |
| "Travels at $\frac{3}{4}$ of usual speed" | Speed ratio is $3:4$, so time ratio is $4:3$ |
| "10 min late at speed $S_1$, 5 min early at $S_2$" | Time difference $\Delta T = 10 - (-5) = 15\text{ min}$ |
| "Excluding stoppages $S_1$, including stoppages $S_2$" | $\text{Rest time per hour} = \dfrac{S_1 - S_2}{S_1} \times 60\text{ min}$ |
| "After crossing each other, they reach destinations in $T_1, T_2$" | $\dfrac{S_1}{S_2} = \sqrt{\dfrac{T_2}{T_1}}$ |
| "A gives B a start of $x$ meters" | In a race of $D$, A runs $D$ while B runs $D - x$ |

## 3. The core idea

- $\text{Distance} = \text{Speed} \times \text{Time}$, $\text{Speed} = \dfrac{\text{Distance}}{\text{Time}}$, $\text{Time} = \dfrac{\text{Distance}}{\text{Speed}}$.
- **Average Speed** $= \dfrac{\text{Total Distance}}{\text{Total Time}}$. For two equal distances: $S_{\text{avg}} = \dfrac{2xy}{x+y}$.
- **Proportionality:** when Distance is constant, $S \propto \dfrac{1}{T}$; when Time is constant, $D \propto S$.
- **Late/Early shortcut:** $D = \dfrac{S_1 \times S_2}{|S_1 - S_2|} \times \Delta T$.

## 4. Question-type walkthroughs

### Question type 1. Unit conversion and basic formula

**Idea:** $1\text{ km/h} = \dfrac{5}{18}\text{ m/s}$ and $1\text{ m/s} = \dfrac{18}{5}\text{ km/h}$.

**Example 1:** Convert $72\text{ km/h}$ to $\text{m/s}$.
- $72 \times \dfrac{5}{18} = 4 \times 5 =$ **20 m/s**.

**Example 2:** Convert $25\text{ m/s}$ to $\text{km/h}$.
- $25 \times \dfrac{18}{5} = 5 \times 18 =$ **90 km/h**.

### Question type 2. Average speed

**Idea:** $\text{Average Speed} = \dfrac{\text{Total Distance}}{\text{Total Time}}$. For equal segments, use harmonic mean.

**Example 1 (two equal distances):** A motorist travels to a town at $60\text{ km/h}$ and returns at $40\text{ km/h}$. Average speed?
- $S_{\text{avg}} = \dfrac{2 \times 60 \times 40}{60 + 40} = \dfrac{4800}{100} =$ **48 km/h**.

**Example 2 (three equal distances):** A car covers 3 equal consecutive distances at $10\text{ km/h}$, $20\text{ km/h}$, and $30\text{ km/h}$.
- LCM of speeds $= 60\text{ km}$. Time taken $= \dfrac{60}{10} + \dfrac{60}{20} + \dfrac{60}{30} = 6 + 3 + 2 = 11\text{ hrs}$.
- $S_{\text{avg}} = \dfrac{3 \times 60}{11} =$ **$16\frac{4}{11}$ km/h** ($\dfrac{180}{11}\text{ km/h}$).

### Question type 3. Constant distance and speed-time inverse ratio

**Idea:** when distance is fixed, $\dfrac{S_1}{S_2} = \dfrac{T_2}{T_1}$.

**Example:** Walking at $\dfrac{3}{4}$ of his usual speed, a man reaches his office 20 minutes late. Find his usual time.
- Speed ratio (New : Usual) $= 3 : 4 \implies$ Time ratio $= 4 : 3$.
- Difference in time $= 4 - 3 = 1\text{ unit} = 20\text{ minutes}$.
- Usual time $= 3 \times 20 =$ **60 min** (1 hour).

### Question type 4. Constant time and speed-distance direct ratio

**Idea:** when travel time is fixed, $\dfrac{D_1}{D_2} = \dfrac{S_1}{S_2}$.

**Example:** A person walks at $14\text{ km/h}$ instead of $10\text{ km/h}$ and covers $20\text{ km}$ more in the same time. Find the actual distance walked at $10\text{ km/h}$.
- Difference in speed $= 14 - 10 = 4\text{ km/h}$.
- Time taken $= \dfrac{20\text{ km}}{4\text{ km/h}} = 5\text{ hours}$.
- Actual distance $= 10 \times 5 =$ **50 km**.

### Question type 5. Late and early arrival times

**Idea:** $D = \dfrac{S_1 \times S_2}{|S_1 - S_2|} \times \Delta T$, where $\Delta T$ is total time difference in hours.

**Example:** If a boy walks at $4\text{ km/h}$, he reaches school 10 min late. If he walks at $5\text{ km/h}$, he arrives 5 min early. Distance to school?
- $\Delta T = 10\text{ min late} - (-5\text{ min early}) = 15\text{ min} = \dfrac{15}{60}\text{ hr} = \dfrac{1}{4}\text{ hr}$.
- $D = \dfrac{4 \times 5}{5 - 4} \times \dfrac{1}{4} = 20 \times \dfrac{1}{4} =$ **5 km**.

### Question type 6. Stoppages and rest time per hour

**Idea:** $\text{Stoppage time per hour} = \dfrac{S_{\text{without stop}} - S_{\text{with stop}}}{S_{\text{without stop}}} \times 60\text{ min}$.

**Example:** Excluding stoppages, the speed of a bus is $54\text{ km/h}$ and including stoppages it is $45\text{ km/h}$. For how many minutes does the bus stop per hour?
- $\text{Stoppage time} = \dfrac{54 - 45}{54} \times 60 = \dfrac{9}{54} \times 60 = \dfrac{1}{6} \times 60 =$ **10 min/hr**.

### Question type 7. Relative speed and meeting time

**Idea:** Opposite directions $\implies S_{\text{rel}} = S_1 + S_2$; Same direction $\implies S_{\text{rel}} = |S_1 - S_2|$.

**Example:** Two towns A and B are $300\text{ km}$ apart. Car 1 leaves A at $60\text{ km/h}$ and Car 2 leaves B at $40\text{ km/h}$ simultaneously towards each other. When and where do they meet?
- Time to meet $= \dfrac{300}{60 + 40} = \dfrac{300}{100} =$ **3 hours**.
- Distance from A $= 3 \times 60 =$ **180 km**.

### Question type 8. Speed ratio after meeting

**Idea:** $\dfrac{S_1}{S_2} = \sqrt{\dfrac{T_2}{T_1}}$.

**Example:** A and B start towards each other. After passing each other, A takes 4 hours to reach B's start and B takes 9 hours to reach A's start. If A travels at $45\text{ km/h}$, find B's speed.
- $\dfrac{S_A}{S_B} = \sqrt{\dfrac{9}{4}} = \dfrac{3}{2}$.
- $S_B = 45 \times \dfrac{2}{3} =$ **30 km/h**.

### Question type 9. Two-part journey with mixed transport modes

**Idea:** Total time equation: $\dfrac{D_1}{S_1} + \dfrac{D_{\text{total}} - D_1}{S_2} = T_{\text{total}}$.

**Example:** A man travels $61\text{ km}$ in 9 hours, partly on foot at $4\text{ km/h}$ and partly on bicycle at $9\text{ km/h}$. Distance travelled on foot?
- Let time on foot be $t$ hours: $4t + 9(9 - t) = 61 \implies 81 - 5t = 61 \implies 5t = 20 \implies t = 4\text{ hours}$.
- Distance on foot $= 4 \times 4 =$ **16 km**.

### Question type 10. Circular tracks and race loops

**Idea:** First meeting time $= \dfrac{\text{Circumference}}{S_{\text{rel}}}$. Meeting at starting point $= \text{LCM}(T_1, T_2, \dots)$.

**Example:** On a circular track of $400\text{ m}$, A runs at $5\text{ m/s}$ and B runs at $3\text{ m/s}$ in the same direction. When do they first meet?
- Relative speed $= 5 - 3 = 2\text{ m/s}$.
- First meeting time $= \dfrac{400}{2} =$ **200 seconds** (3 min 20 s).

### Question type 11. Linear races, head starts, and dead heats

**Idea:** If A beats B by $x$ meters or $t$ seconds, then B covers $x$ meters in $t$ seconds ($\text{Speed of B} = \dfrac{x}{t}$).

**Example:** In a $1000\text{ m}$ race, A beats B by $100\text{ m}$ or 10 seconds. Find A's time to run the race.
- B's speed $= \dfrac{100\text{ m}}{10\text{ s}} = 10\text{ m/s}$.
- Time taken by B for $1000\text{ m} = \dfrac{1000}{10} = 100\text{ seconds}$.
- Time taken by A $= 100 - 10 =$ **90 seconds**.

### Question type 12. Escalators and moving walkways

**Idea:** Total visible steps $N = T \times (v_{\text{person}} \pm v_{\text{escalator}})$.

**Example:** A person walking up a moving escalator takes 30 steps in 30 seconds. Another person walking up faster takes 40 steps in 20 seconds. Find the total visible steps when stationary.
- Let escalator speed be $e$ steps/s. Person 1 speed $= 1\text{ step/s}$, Person 2 speed $= 2\text{ steps/s}$.
- $N = 30(1 + e) = 20(2 + e) \implies 30 + 30e = 40 + 20e \implies 10e = 10 \implies e = 1\text{ step/s}$.
- $N = 30(1 + 1) =$ **60 steps**.

## 5. Before you practise

**Your turn:** A car travels 120 km at 60 km/h, then another 120 km at 40 km/h. What is its average speed for the whole trip?

**Think it through:** The first leg takes 2 hours and the second takes 3 hours. Total distance is 240 km and total time is 5 hours, so average speed is $240\div5=\mathbf{48\ km/h}$. It is not the simple mean of the two speeds because the slower leg takes longer.

### Quick revision

- Write $\text{distance}=\text{speed}\times\text{time}$ and check units before substituting.
- Average speed always means total distance divided by total time.
- For relative motion, add speeds when moving toward each other and subtract when moving in the same direction.
- For journeys in stages, calculate each stage’s time separately.

### Common mistakes

1. Taking the arithmetic mean of speeds for unequal travel times or equal distances.
2. Adding speeds for travellers going in the same direction.
3. Comparing speeds in km/h with distances in metres without converting.
4. Forgetting that “late” and “early” are on opposite sides of the scheduled time.
5. Using circumference only once when solving multiple-lap track questions.

## 6. Practice

1. Convert a speed of $108\text{ km/h}$ into meters per second.
2. A car covers $540\text{ km}$ in 6 hours. Find its speed in meters per second.
3. A person travels from station X to Y at $30\text{ km/h}$ and returns at $20\text{ km/h}$. Find the average speed for the whole journey.
4. A car covers four successive $3\text{ km}$ stretches at speeds of $10, 20, 30,$ and $60\text{ km/h}$ respectively. Find its average speed.
5. A man travels $\dfrac{1}{3}$ of his journey at $25\text{ km/h}$, $\dfrac{1}{4}$ of the journey at $30\text{ km/h}$, and the rest at $50\text{ km/h}$. Find the average speed for the entire journey.
6. Walking at $\dfrac{6}{7}$ of his usual speed, a man is 12 minutes late for his train. Find his usual time to reach the station.
7. Walking at $\dfrac{5}{4}$ of his usual speed, a student reaches school 15 minutes early. What is his usual time?
8. A car increases its speed by 25%. By what percentage does its travel time decrease for the same distance?
9. A man walks at $12\text{ km/h}$ instead of $8\text{ km/h}$ and walks $16\text{ km}$ more in the same time. Find the actual distance covered at $8\text{ km/h}$.
10. Two persons start walking towards each other from a distance of $72\text{ km}$ at speeds of $4\text{ km/h}$ and $5\text{ km/h}$. How far does the faster person walk before they meet?
11. If a student walks at $5\text{ km/h}$, he is 10 minutes late. If he walks at $6\text{ km/h}$, he is 15 minutes early. Find the distance to his school.
12. A train running at $40\text{ km/h}$ reaches its destination 11 minutes late. At $50\text{ km/h}$, it is only 5 minutes late. Find the distance of the journey.
13. Starting from home at $3\text{ km/h}$, a student reaches school 5 minutes late. Next day at $4\text{ km/h}$, he reaches 5 minutes early. Find the exact scheduled time to reach school.
14. Excluding stoppages, the speed of a bus is $60\text{ km/h}$ and including stoppages it is $48\text{ km/h}$. For how many minutes per hour does the bus stop?
15. Excluding stoppages, the speed of a train is $80\text{ km/h}$ and including stoppages it is $64\text{ km/h}$. Find the stoppage time per hour in minutes.
16. Two towns P and Q are $240\text{ km}$ apart. Two cars start simultaneously from P and Q towards each other at speeds of $45\text{ km/h}$ and $35\text{ km/h}$. How long will they take to meet?
17. A thief steals a car at 1:30 PM and drives at $40\text{ km/h}$. The theft is discovered at 2:00 PM and the owner chases in another car at $50\text{ km/h}$. At what time will the owner catch the thief?
18. A policeman spots a thief from a distance of $200\text{ m}$. The thief starts running at $10\text{ km/h}$ and the policeman chases at $11\text{ km/h}$. What distance does the thief cover before being caught?
19. Two persons A and B start towards each other from X and Y. After meeting, A takes 16 hours to reach Y and B takes 25 hours to reach X. Find the ratio of speeds of A to B.
20. A and B start at the same time towards each other. After crossing, A reaches destination in 4 hours and B in 9 hours. If A's speed is $36\text{ km/h}$, find B's speed.
21. A person covers $80\text{ km}$ in 8 hours, partly on foot at $8\text{ km/h}$ and partly on bicycle at $16\text{ km/h}$. Find the distance covered on foot.
22. A man travelled a distance of $60\text{ km}$ in 7 hours partly on foot at $6\text{ km/h}$ and partly on cycle at $12\text{ km/h}$. Find the distance covered on cycle.
23. A farmer travelled $90\text{ km}$ in 9 hours. He travelled partly on foot at $8\text{ km/h}$ and partly on bicycle at $17\text{ km/h}$. Find the distance travelled on foot.
24. A circular running track is $600\text{ m}$ in circumference. A and B start from the same point in opposite directions at $4\text{ m/s}$ and $6\text{ m/s}$. When will they first meet?
25. On a circular track of $1200\text{ m}$, A and B run in the same direction at $15\text{ m/s}$ and $10\text{ m/s}$. When will they meet for the first time?
26. On a circular track of $300\text{ m}$, A, B, and C start together in the same direction at $3\text{ m/s}$, $5\text{ m/s}$, and $6\text{ m/s}$. After how much time will they all meet at the starting point?
27. In a $100\text{ m}$ race, A can give B a start of $20\text{ m}$ and C a start of $28\text{ m}$. In a race of $500\text{ m}$, how much start can B give C?
28. In a $1\text{ km}$ race, A beats B by $100\text{ m}$ and B beats C by $100\text{ m}$. By how many meters does A beat C in a $1\text{ km}$ race?
29. In a $500\text{ m}$ race, A beats B by $40\text{ m}$ or 8 seconds. Find A's time to complete the race.
30. An escalator moves upwards. A person walking up takes 40 steps in 20 seconds. Another person walking up faster takes 60 steps in 15 seconds. How many steps are visible when the escalator is stationary?
31. A man travels $360\text{ km}$ in 4 hours, partly by air and partly by train. If he had travelled entirely by air, he would have saved 2 hours, and the air time would be $\dfrac{4}{5}$ of the time spent in train. Find the distance travelled by train.
32. Stations A and B are $390\text{ km}$ apart. A train leaves A at 10:00 AM towards B at $65\text{ km/h}$. Another train leaves B at 11:00 AM towards A at $35\text{ km/h}$. At what time will they meet?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 30 m/s | $108 \times \frac{5}{18} = 30$ |
| 2 | 25 m/s | $\frac{540}{6} = 90\text{ km/h}$; $90 \times \frac{5}{18} = 25$ |
| 3 | 24 km/h | $\frac{2 \times 30 \times 20}{30 + 20} = \frac{1200}{50}$ |
| 4 | 20 km/h | $\frac{4}{\frac{1}{10} + \frac{1}{20} + \frac{1}{30} + \frac{1}{60}} = \frac{4}{12/60}$ |
| 5 | $33\frac{1}{3}$ km/h | Time $= \frac{1/3}{25} + \frac{1/4}{30} + \frac{5/12}{50} = \frac{3}{100}$; $\text{Speed} = \frac{100}{3}$ |
| 6 | 72 min | Time ratio $7:6 \implies \frac{1}{6}T = 12 \implies T = 72$ |
| 7 | 75 min | Time ratio $4:5 \implies \frac{1}{5}T = 15 \implies T = 75$ |
| 8 | 20% | Speed $\frac{5}{4} \implies \text{Time } \frac{4}{5} \implies \text{decrease } \frac{1}{5} = 20\%$ |
| 9 | 32 km | $12T - 8T = 16 \implies T = 4\text{ hrs}$; $8 \times 4$ |
| 10 | 40 km | Meeting time $= \frac{72}{4+5} = 8\text{ hrs}$; $5 \times 8 = 40$ |
| 11 | 12.5 km | $\frac{5 \times 6}{1} \times \frac{25}{60} = 30 \times \frac{5}{12}$ |
| 12 | 20 km | $\frac{40 \times 50}{10} \times \frac{6}{60} = 200 \times \frac{1}{10}$ |
| 13 | 35 min | $D = \frac{3 \times 4}{1} \times \frac{10}{60} = 2\text{ km}$; Time at $3\text{ km/h} = \frac{2}{3}\text{ hr} = 40\text{ min}$; $40 - 5$ |
| 14 | 12 min | $\frac{60 - 48}{60} \times 60$ |
| 15 | 12 min | $\frac{80 - 64}{80} \times 60 = \frac{16}{80} \times 60$ |
| 16 | 3 hours | $\frac{240}{45 + 35} = \frac{240}{80}$ |
| 17 | 4:00 PM | Lead $= 40 \times 0.5 = 20\text{ km}$; $T = \frac{20}{50 - 40} = 2\text{ hrs after 2:00 PM}$ |
| 18 | 2000 m | $T = \frac{200}{1 \times \frac{5}{18}} = 720\text{ s}$; $10 \times \frac{5}{18} \times 720 = 2000\text{ m}$ |
| 19 | $5:4$ | $\frac{S_A}{S_B} = \sqrt{\frac{25}{16}} = \frac{5}{4}$ |
| 20 | 24 km/h | $S_B = 36 \times \sqrt{\frac{4}{9}} = 36 \times \frac{2}{3}$ |
| 21 | 48 km | $8t + 16(8 - t) = 80 \implies 8t = 48 \implies t = 6$; $6 \times 8$ |
| 22 | 36 km | $6(7 - t) + 12t = 60 \implies 6t = 18 \implies t = 3$; $3 \times 12$ |
| 23 | 56 km | $8t + 17(9 - t) = 90 \implies 9t = 63 \implies t = 7$; $7 \times 8$ |
| 24 | 60 seconds | $\frac{600}{4 + 6} = \frac{600}{10}$ |
| 25 | 240 seconds | $\frac{1200}{15 - 10} = \frac{1200}{5}$ |
| 26 | 300 seconds | $\text{LCM}\left(\frac{300}{3}, \frac{300}{5}, \frac{300}{6}\right) = \text{LCM}(100, 60, 50) = 300\text{ s}$ |
| 27 | 50 m | Ratio B:C $= 80:72 = 10:9$; when B runs $500\text{ m}$, C runs $450\text{ m}$; $500 - 450$ |
| 28 | 190 m | A:B $= 10:9$, B:C $= 10:9 \implies \text{A:C} = 100:81$; when A $= 1000$, C $= 810$; $1000 - 810$ |
| 29 | 92 seconds | B speed $= \frac{40}{8} = 5\text{ m/s}$; B time $= \frac{500}{5} = 100\text{ s}$; A time $= 100 - 8$ |
| 30 | 120 steps | $N = 20(2 + e) = 15(4 + e) \implies e = 4\text{ steps/s}$; $N = 20(2 + 4)$ |
| 31 | 90 km | $T_{\text{air-full}} = 2\text{ hrs} \implies \text{Air speed} = 180\text{ km/h}$; $T_t = 2.5\text{ hrs}, T_a = 1.5\text{ hrs}$; Train $D = 360 - (1.5 \times 180)$ |
| 32 | 2:15 PM | Rem $D = 390 - 65 = 325\text{ km}$; $T = \frac{325}{100} = 3.25\text{ hrs after 11:00 AM}$ |
