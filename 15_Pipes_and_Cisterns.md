# Pipes and Cisterns: Model-wise Notes

## Part 1. What comes from this topic

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Model |
|---|---|
| Multiple inlet pipes filling together | 1 |
| Inlets and outlets operating simultaneously | 2 |
| Leak in the tank | 3 |
| Finding the capacity of the tank | 4 |
| Pipes opened at staggered times | 5 |
| Pipe closed midway or before tank fills | 6 |
| Alternating hours and helper cycles | 7 |
| Pipe efficiency and diameter ratios | 8 |
| Fraction of tank filled or emptied | 9 |
| Time difference and quadratic equations | 10 |
| Clogging and partial flow rates | 11 |
| Taps fitted at different heights | 12 |

## Part 2. What data is usually given

| Data you will see | What it means |
|---|---|
| "Pipe A fills in $x$ hours" | Rate is $+\dfrac{1}{x}$ of tank per hour |
| "Pipe B empties in $y$ hours" | Rate is $-\dfrac{1}{y}$ of tank per hour |
| "With a leak it takes $t$ hours longer" | $\text{Leak rate} = \dfrac{1}{\text{normal}} - \dfrac{1}{\text{with leak}}$ |
| "Leak empties at $k$ liters per minute" | $\text{Capacity} = \text{Leak rate in L/min} \times \text{Emptying time in min}$ |
| "Pipe B closed 4 min before full" | B runs for $(T - 4)$ minutes while A runs for $T$ minutes |
| "Diameter is doubled" | Flow rate is quadrupled ($\text{Rate} \propto d^2$) |
| "Alternating hours starting with A" | 2-hour cycles until near full, then turn-by-turn |

## Part 3. The base idea (read once)

- Inlets have positive rates ($+\text{units/hr}$); outlets and leaks have negative rates ($-\text{units/hr}$).
- **Fast method:** assume total capacity as the $\text{LCM}$ of given times.
- $\text{Time} = \dfrac{\text{Total Capacity}}{\text{Net Rate}}$. If net rate is positive, tank fills; if negative, tank empties.
- **Diameter rule:** rate of flow is directly proportional to the area of cross-section, hence $\text{Rate} \propto d^2$.

## Part 4. Models

### Model 1. Multiple inlet pipes filling together

**Idea:** add individual filling rates: $T = \dfrac{\text{LCM}}{\text{Sum of efficiencies}}$.

**Example 1:** Pipe A fills a tank in 10 hours and Pipe B in 15 hours. Both together?
- LCM $= 30$. Rates: A $= 3$, B $= 2$. Net rate $= 5$ units/hr.
- $T = \dfrac{30}{5} =$ **6 hours**.

**Example 2:** Three pipes A, B, and C fill a tank in 12, 15, and 20 hours. All three together?
- LCM $= 60$. Rates: A $= 5$, B $= 4$, C $= 3$. Combined rate $= 12$ units/hr.
- $T = \dfrac{60}{12} =$ **5 hours**.

### Model 2. Inlets and outlets operating simultaneously

**Idea:** $\text{Net Rate} = \sum \text{Inlet Rates} - \sum \text{Outlet Rates}$.

**Example 1:** An inlet fills a tank in 12 hours and an outlet empties it in 18 hours. Both open?
- LCM $= 36$. Inlet $= +3$, Outlet $= -2$. Net rate $= +1$ unit/hr.
- $T = \dfrac{36}{1} =$ **36 hours**.

**Example 2:** Inlets A and B fill in 10 and 12 hours; outlet C empties in 15 hours. All open?
- LCM $= 60$. Rates: A $= +6$, B $= +5$, C $= -4$. Net rate $= 6 + 5 - 4 = +7$ units/hr.
- $T = \dfrac{60}{7} =$ **$8\frac{4}{7}$ hours**.

### Model 3. Leak in the tank

**Idea:** $\text{Leak Rate} = \text{Inlet Rate} - \text{Net Rate with leak}$.

**Example:** A pump fills a tank in 8 hours. Due to a leak at the bottom, it takes 10 hours to fill. The leak alone empties a full tank in?
- LCM $= 40$. Inlet $= +5$, Net with leak $= +4$.
- Leak rate $= 5 - 4 = 1$ unit/hr.
- Time for leak $= \dfrac{40}{1} =$ **40 hours**.

### Model 4. Finding the capacity of the tank

**Idea:** $\text{Capacity} = \text{Emptying/Filling time (min)} \times \text{Rate (liters/min)}$.

**Example:** A pipe fills a tank in 15 hours. A leak empties water at 4 L/min. With both open, the tank fills in 20 hours. Find tank capacity.
- LCM $= 60$. Pipe rate $= 4$, Net rate $= 3 \implies \text{Leak rate} = 1$ unit/hr.
- Leak takes $\dfrac{60}{1} = 60\text{ hours} = 3600\text{ minutes}$ to empty full tank.
- $\text{Capacity} = 3600 \times 4 =$ **14400 liters**.

### Model 5. Pipes opened at staggered times

**Idea:** calculate volume filled during initial intervals, subtract from total, then divide remainder by active combined rate.

**Example:** Pipes A and B fill a tank in 12 and 18 hours. Pipe A is opened at 8:00 AM and Pipe B is opened at 10:00 AM. When is the tank full?
- LCM $= 36$. A $= 3$, B $= 2$.
- From 8:00 to 10:00 AM (2 hours), A fills $2 \times 3 = 6$ units. Remaining $= 30$ units.
- From 10:00 AM, both run at $3 + 2 = 5$ units/hr: $\text{Time} = \dfrac{30}{5} = 6\text{ hours}$.
- Tank is full at $10:00\text{ AM} + 6\text{ hours} =$ **4:00 PM**.

### Model 6. Pipe closed midway or before tank fills

**Idea:** let unknown time be $T$. Set $\sum (\text{Rate}_i \times \text{Time}_i) = \text{Total Capacity}$.

**Example 1 (closed midway):** Pipe A fills in 12 min, B in 16 min. Both open. After how many min should B be closed so tank is full in 9 min?
- A runs all 9 min: fills $9 \times \dfrac{1}{12} = \dfrac{3}{4}$ of the tank.
- B must fill $1 - \dfrac{3}{4} = \dfrac{1}{4}$ of the tank.
- Time for B $= \dfrac{1}{4} \times 16 =$ **4 min**.

**Example 2 (closed before end):** Pipe A fills in 20 min, B in 30 min. Pipe A is closed 5 min before full. Total time?
- LCM $= 60$. A $= 3$, B $= 2$. B works $T$ min, A works $(T - 5)$ min.
- $3(T - 5) + 2T = 60 \implies 5T = 75 \implies T =$ **15 min**.

### Model 7. Alternating hours and helper cycles

**Idea:** calculate work done in 1 cycle. Multiply for maximum full cycles without overflowing, then solve turn by turn.

**Example:** Pipe A fills in 6 hours, B in 8 hours. They operate alternately for 1 hour each, starting with A. Total time?
- LCM $= 24$. Rates: A $= 4$, B $= 3$. A 2-hour cycle fills $4 + 3 = 7$ units.
- 3 full cycles (6 hours) fill $3 \times 7 = 21$ units. Remaining $= 3$ units.
- Hour 7 (A's turn): A needs $\dfrac{3}{4}\text{ hour} = 45\text{ min}$.
- Total time $= 6 + \dfrac{3}{4} =$ **$6\frac{3}{4}$ hours** (6 hrs 45 min).

### Model 8. Pipe efficiency and diameter ratios

**Idea:** flow rate is proportional to the square of the diameter: $\text{Rate} \propto d^2$.

**Example:** Three pipes have diameters 1 cm, 2 cm, 3 cm. The largest fills a tank in 42 min. Time for all three together?
- Flow rates: $1^2 : 2^2 : 3^2 = 1 : 4 : 9$. Total rate $= 1 + 4 + 9 = 14$ units/min.
- Total capacity $= 9 \times 42 = 378$ units.
- Combined time $= \dfrac{378}{14} =$ **27 min**.

### Model 9. Fraction of tank filled or emptied

**Idea:** if a pipe fills fraction $f$ in time $t$, its full time is $\dfrac{t}{f}$.

**Example:** Pipe A fills $\dfrac{1}{3}$ of a tank in 4 hours. Pipe B fills $\dfrac{1}{2}$ of it in 9 hours. Both together for the full tank?
- A alone takes $4 \div \dfrac{1}{3} = 12\text{ hours}$. B alone takes $9 \div \dfrac{1}{2} = 18\text{ hours}$.
- $T = \dfrac{12 \times 18}{12 + 18} = \dfrac{216}{30} =$ **7.2 hours** (7 hrs 12 min).

### Model 10. Time difference and quadratic equations

**Idea:** if Pipe A is $k$ hours faster than Pipe B, set $\dfrac{1}{x} + \dfrac{1}{x+k} = \dfrac{1}{T_{\text{together}}}$.

**Example:** Pipe A fills a tank 5 hours faster than Pipe B. Together they fill it in 6 hours. Time taken by Pipe A alone?
- $\dfrac{1}{x} + \dfrac{1}{x+5} = \dfrac{1}{6} \implies 6(2x+5) = x(x+5) \implies x^2 - 7x - 30 = 0$.
- $(x-10)(x+3) = 0 \implies x =$ **10 hours** (Pipe B takes 15 hours).

### Model 11. Clogging and partial flow rates

**Idea:** multiply normal efficiencies by the reduction fraction during the clogged period.

**Example:** Pipe A fills in 20 min, B in 30 min. Due to clogging, A flows at $\dfrac{2}{3}$ and B at $\dfrac{1}{2}$ normal flow for 8 min, after which full flow is restored. Total time?
- LCM $= 60$. Normal: A $= 3$, B $= 2$. Clogged: A $= 2$, B $= 1$ (combined $= 3$ units/min).
- First 8 min fills $8 \times 3 = 24$ units. Remaining $= 36$ units.
- Restored flow rate $= 3 + 2 = 5$ units/min: $\text{Time} = \dfrac{36}{5} = 7.2\text{ min}$.
- Total time $= 8 + 7.2 =$ **15.2 min** (15 min 12 s).

### Model 12. Taps fitted at different heights

**Idea:** each section of height is emptied only by the taps situated at or below that water level.

**Example:** A tank has 4 identical taps at equal vertical intervals (bottom, $\frac{1}{4}, \frac{2}{4}, \frac{3}{4}$ height). One tap empties full tank in 12 hours. Time to empty full tank with all taps open?
- Each quarter requires $12 \div 4 = 3\text{ tap-hours}$.
- Top quarter (4 taps): $\dfrac{3}{4}\text{ hr}$; 2nd quarter (3 taps): $\dfrac{3}{3} = 1\text{ hr}$; 3rd (2 taps): $\dfrac{3}{2} = 1.5\text{ hrs}$; Bottom (1 tap): $\dfrac{3}{1} = 3\text{ hrs}$.
- Total time $= 0.75 + 1 + 1.5 + 3 =$ **6.25 hours** (6 hrs 15 min).

## Part 5. Practice

1. Pipe A fills a tank in 20 hours and Pipe B in 30 hours. How long will they take working together?
2. Three pipes A, B, and C can fill a tank in 10, 12, and 15 hours respectively. In how many hours will they fill it together?
3. Pipe A takes 15 hours, Pipe B takes 10 hours, and Pipe C takes 30 hours to fill a cistern. If all are opened together, find the time taken.
4. An inlet pipe fills a tank in 12 hours while an outlet pipe empties it in 20 hours. If both pipes are opened together, in how many hours is the tank filled?
5. Two inlet pipes fill a reservoir in 15 and 20 hours respectively, while a waste pipe empties it in 12 hours. If all three are opened together, how long to fill the reservoir?
6. Pipe A fills a tank in 8 hours, Pipe B fills it in 12 hours, and Pipe C empties it in 6 hours. In how many hours will the tank fill when all three run together?
7. A tap fills a tank in 6 hours. A leak empties the full tank in 15 hours. If both are open, in how many hours will the tank fill?
8. A tap fills a cistern in 9 hours. Because of a leak in the bottom, it takes 10 hours to fill. How long will the leak take to empty the full cistern?
9. A pump can fill a tank in 3 hours. Due to a leak, it takes $3\frac{1}{2}$ hours. How many hours will the leak alone take to empty the full tank?
10. A pipe can fill a tank in 10 hours. Due to a leak emptying 5 liters per minute, it takes 15 hours to fill. Find the capacity of the tank.
11. An inlet pipe fills a pool in 8 hours. A waste pipe empties water at 6 liters per minute. If both run, the pool fills in 12 hours. Find the pool capacity.
12. Pipes A and B fill a tank in 12 hours and 15 hours respectively. Pipe A is opened at 7:00 AM and Pipe B at 10:00 AM. At what time will the tank be full?
13. Pipes A and B fill a cistern in 24 min and 32 min respectively. Both are opened together. After how many minutes should B be closed so that the tank is full in 18 minutes?
14. Pipe A fills a tank in 12 hours and Pipe B in 16 hours. Both are opened together, but Pipe A is closed 2 hours before the tank is completely full. What is the total time taken?
15. Pipes A and B fill a tank in 8 hours and 12 hours respectively. If they are opened for 1 hour alternately, Pipe A being opened first, in how many hours will the tank be full?
16. Pipe A can fill a tank in 6 hours and Pipe B can empty it in 8 hours. If they are opened alternately for 1 hour each, starting with Pipe A, in how many hours will the tank be filled?
17. Pipe A is 3 times as fast as Pipe B and takes 36 minutes running together with B to fill a cistern. How long will Pipe B alone take to fill it?
18. Two pipes have circular cross sections with diameters in the ratio $1:2$. If the smaller pipe alone fills a tank in 50 minutes, how long will both pipes take together?
19. Pipe A fills $\dfrac{2}{5}$ of a cistern in 6 hours and Pipe B fills $\dfrac{1}{3}$ of it in 4 hours. How long will they take together to fill the whole cistern?
20. Pipe A fills a tank 10 hours faster than Pipe B. Together they fill the tank in 12 hours. How many hours will Pipe B alone take to fill the tank?
21. Pipe A is 4 times faster than Pipe B and fills a cistern in 45 minutes less time than B. How long will B alone take to fill it?
22. Pipes A and B together fill a tank in 12 minutes. Due to a leak, they take 15 minutes. In how many minutes can the leak alone empty the full tank?
23. Three pipes A, B, and C can fill a tank in 12, 15, and 20 hours. Pipe A is kept open all the time, and B and C are opened alternately for 1 hour each. In how many hours will the tank be filled?
24. A cistern has three pipes: A and B fill it in 3 hours and 4 hours respectively, while C empties it in 1 hour. If they are opened at 3:00 PM, 4:00 PM, and 5:00 PM respectively, at what time will the cistern be empty?
25. Pipes A and B can fill a tank in 15 hours and 20 hours respectively. Both pipes are opened together, but after 4 hours Pipe A is closed. How much more time will Pipe B take to fill the remaining tank?
26. A tap fills a bath in 20 min and another in 30 min. A boy opens both and returns when the bath should be full, but finds the waste pipe open. He closes it, and the bath fills in 4 more minutes. How long would the waste pipe take to empty the full bath?
27. Two inlet pipes fill a reservoir in 12 hours and 16 hours respectively. How many hours will it take to fill $\dfrac{7}{8}$ of the reservoir if both pipes run together?
28. Pipe A fills in 10 hours, Pipe B fills in 12 hours, and Pipe C empties in 20 hours. If all three operate together, how long will they take to fill half the tank?
29. A tank is filled by three pipes whose diameters are $1\text{ cm}$, $\dfrac{4}{3}\text{ cm}$, and $2\text{ cm}$. The largest pipe alone fills the tank in 61 minutes. How long will all three pipes take together?
30. Eight taps are fitted to a water tank. Some are inlet taps filling the tank in 12 hours each, and the rest are outlet taps emptying it in 36 hours each. If all taps are opened together, the tank fills in 3 hours. Find the number of inlet taps.
31. A tank is fitted with 4 identical taps at equal vertical heights. The lowest tap is at the bottom and the others are at $\dfrac{1}{4}$, $\dfrac{2}{4}$, and $\dfrac{3}{4}$ height. If one tap can empty the full tank in 24 hours, find the total time to empty the full tank when all taps are open.
32. Pipes A and B can fill a tank in 16 hours and 24 hours respectively, while Pipe C can empty it in 48 hours. Pipes A and B are opened for 6 hours, after which Pipe C is also opened. What is the total time taken to fill the tank?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 12 hours | $\frac{20 \times 30}{20 + 30} = \frac{600}{50}$ |
| 2 | 4 hours | LCM 60: $6 + 5 + 4 = 15$; $\frac{60}{15}$ |
| 3 | 5 hours | LCM 30: $2 + 3 + 1 = 6$; $\frac{30}{6}$ |
| 4 | 30 hours | LCM 60: $5 - 3 = 2$; $\frac{60}{2}$ |
| 5 | 30 hours | LCM 60: $4 + 3 - 5 = 2$; $\frac{60}{2}$ |
| 6 | 24 hours | LCM 24: $3 + 2 - 4 = 1$; $\frac{24}{1}$ |
| 7 | 10 hours | LCM 30: $5 - 2 = 3$; $\frac{30}{3}$ |
| 8 | 90 hours | $\frac{1}{9} - \frac{1}{10} = \frac{1}{90}$ |
| 9 | 21 hours | $\frac{1}{3} - \frac{2}{7} = \frac{1}{21}$ |
| 10 | 9000 liters | $\text{Leak rate} = \frac{1}{10} - \frac{1}{15} = \frac{1}{30}$; $30 \times 60 \times 5$ |
| 11 | 8640 liters | $\text{Waste rate} = \frac{1}{8} - \frac{1}{12} = \frac{1}{24}$; $24 \times 60 \times 6$ |
| 12 | 3:00 PM | LCM 60: A fills 15 in 3 hrs; remaining $\frac{45}{9} = 5\text{ hrs after 10:00 AM}$ |
| 13 | 8 min | A does $\frac{18}{24} = \frac{3}{4}$; B does $\frac{1}{4} \implies \frac{1}{4} \times 32$ |
| 14 | 8 hours | LCM 48: $3T + 4(T - 2) = 48 \implies 7T = 56$ |
| 15 | 9.5 hours | LCM 24: 4 cycles (8 hrs) $= 20$; Hr 9 (A) $= 3$; Hr 10 (B) $= \frac{1}{2}\text{ hr}$ |
| 16 | 21 hours | LCM 24: 10 cycles (20 hrs) $= 20$; Hr 21 (A) adds $4 = 24$ |
| 17 | 144 min | Ratio $3:1 \implies \text{Total} = 4 \times 36 = 144$; B $= \frac{144}{1}$ |
| 18 | 10 min | Ratio $d^2 = 1:4$; Total $= 1 \times 50$; Together $= \frac{50}{5}$ |
| 19 | $6\frac{2}{3}$ hours | A alone: $6 \times \frac{5}{2} = 15$; B alone: $4 \times 3 = 12$; $\frac{15 \times 12}{27}$ |
| 20 | 30 hours | $\frac{1}{x} + \frac{1}{x+10} = \frac{1}{12} \implies x = 20$, B $= x + 10$ |
| 21 | 60 min | Efficiency $4:1 \implies \text{Time } 1:4$; $3\text{ parts} = 45 \implies 4\text{ parts} = 60$ |
| 22 | 60 min | $\text{Leak rate} = \frac{1}{12} - \frac{1}{15} = \frac{1}{60}$ |
| 23 | 7 hours | LCM 60: Hr 1 (A+B) $= 9$, Hr 2 (A+C) $= 8$; 3 cycles (6 hrs) $= 51$, Hr 7 $= 9$ |
| 24 | 7:12 PM | LCM 12: by 5 PM filled $= 11$; net rate at 5 PM $= -5$; $\frac{11}{5} = 2.2\text{ hrs}$ |
| 25 | $10\frac{2}{3}$ hours | LCM 60: 4 hrs of (A+B) $= 28$; remaining $\frac{32}{3}\text{ hrs}$ |
| 26 | 36 min | Full in 12 min; in 4 min taps give $\frac{4}{12} = \frac{1}{3}$; waste rate $= \frac{1/3}{12} = \frac{1}{36}$ |
| 27 | 6 hours | LCM 48: combined $= 7$; target $= \frac{7}{8} \times 48 = 42$; $\frac{42}{7}$ |
| 28 | 3.75 hours | LCM 60: net $= 6 + 5 - 3 = 8$; half tank $= \frac{30}{8}$ |
| 29 | 36 min | Rate ratio $9:16:36$ (sum 61); capacity $= 36 \times 61$; time $= \frac{36 \times 61}{61}$ |
| 30 | 5 taps | $\frac{n}{12} - \frac{8 - n}{36} = \frac{1}{3} \implies 4n - 8 = 12 \implies n = 5$ |
| 31 | 12.5 hours | $6\text{ tap-hrs/quarter}$; $\frac{6}{4} + \frac{6}{3} + \frac{6}{2} + \frac{6}{1} = 1.5 + 2 + 3 + 6$ |
| 32 | 10.5 hours | First 6 hrs: $6 \times 5 = 30$; remaining $\frac{18}{4} = 4.5\text{ hrs}$; total $6 + 4.5$ |
