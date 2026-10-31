# Trains

> Read this like a class: sketch the track, mark the lengths, and decide what distance must pass the other object.

## 0. Start here: what does “cross” mean?

Imagine watching a whole train pass a pole. The engine reaching the pole is not the end of the crossing; the rear of the train must pass it too. So it travels its own full length. To clear a platform, it must travel its length plus the platform’s length. Questions build on this picture: two trains pass, one catches another, or trains meet between stations.

The central question is always **how quickly is the gap closing, and how much distance must close?** Use relative speed for the closing rate. As a sense check, opposite-moving trains should close the gap faster than either one alone; same-direction trains close it only at the difference of their speeds.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Train crossing a stationary point object (pole, tree, person) | 1 |
| Train crossing a stationary extended object (platform, bridge, tunnel) | 2 |
| Train crossing a moving person (same or opposite direction) | 3 |
| Two trains crossing in opposite directions | 4 |
| Two trains crossing in same direction (overtaking) | 5 |
| Train crossing a passenger inside another train | 6 |
| Finding speed and length from two crossing events | 7 |
| Two trains starting simultaneously from opposite stations | 8 |
| Two trains starting at different times from opposite stations | 9 |
| Speed ratio after meeting | 10 |
| Breakdown or accident midway and speed reduction | 11 |
| Train crossing two moving persons or cyclists | 12 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Crosses a telegraph pole in $t$ seconds" | Distance covered $= \text{Length of train } L_t$ |
| "Crosses a platform of length $P$" | Distance covered $= L_t + P$ |
| "Crosses a man walking at $u\text{ km/h}$" | Use relative speed $S_{\text{train}} \pm u$ and distance $L_t$ |
| "Crosses a man sitting in another train" | Distance is ONLY the length of the passing train |
| "Two trains running in opposite directions" | Relative speed $= S_1 + S_2$, Distance $= L_1 + L_2$ |
| "Two trains running in same direction" | Relative speed $= \lvert S_1 - S_2\rvert$, Distance $= L_1 + L_2$ |
| "After meeting, they reach destinations in $T_1, T_2$" | $\dfrac{S_1}{S_2} = \sqrt{\dfrac{T_2}{T_1}}$ |

## 3. The core idea

- Always convert speeds to $\text{m/s}$ when lengths are in meters: $1\text{ km/h} = \dfrac{5}{18}\text{ m/s}$, $1\text{ m/s} = \dfrac{18}{5}\text{ km/h}$.
- **Point object (pole/standing person):** $\text{Time} = \dfrac{L_{\text{train}}}{S_{\text{train}}}$.
- **Extended object (platform/bridge/tunnel):** $\text{Time} = \dfrac{L_{\text{train}} + L_{\text{object}}}{S_{\text{train}}}$.
- **Two trains crossing:** $\text{Time} = \dfrac{L_1 + L_2}{S_{\text{rel}}}$, where $S_{\text{rel}} = S_1 + S_2$ (opposite) or $|S_1 - S_2|$ (same direction).

## 4. Question-type walkthroughs

### Question type 1. Train crossing a stationary point object

**Idea:** distance covered equals the length of the train: $T = \dfrac{L_t}{S}$.

**Example:** A train $180\text{ m}$ long is running at $54\text{ km/h}$. In what time will it cross a telegraph post?
- $\text{Speed} = 54 \times \dfrac{5}{18} = 15\text{ m/s}$.
- $T = \dfrac{180}{15}$ = **12 seconds**.

### Question type 2. Train crossing a stationary extended object

**Idea:** distance covered equals the length of train plus length of object: $T = \dfrac{L_t + L_p}{S}$.

**Example:** A train $200\text{ m}$ long moving at $72\text{ km/h}$ crosses a bridge of length $300\text{ m}$. Find the time taken.
- $\text{Speed} = 72 \times \dfrac{5}{18} = 20\text{ m/s}$.
- $\text{Total distance} = 200 + 300 = 500\text{ m}$.
- $T = \dfrac{500}{20}$ = **25 seconds**.

### Question type 3. Train crossing a moving person

**Idea:** distance covered is $L_t$; speed is relative speed between train and person.

**Example:** A train $150\text{ m}$ long running at $68\text{ km/h}$ crosses a man running at $8\text{ km/h}$ in the same direction. Find the time taken.
- Relative speed $= 68 - 8 = 60\text{ km/h} = 60 \times \dfrac{5}{18} = \dfrac{50}{3}\text{ m/s}$.
- $T = \dfrac{150}{50/3} = 150 \times \dfrac{3}{50}$ = **9 seconds**.

### Question type 4. Two trains crossing in opposite directions

**Idea:** $\text{Total distance} = L_1 + L_2$; Relative speed $= S_1 + S_2$.

**Example:** Two trains of lengths $120\text{ m}$ and $180\text{ m}$ are running in opposite directions at $40\text{ km/h}$ and $50\text{ km/h}$. Find the crossing time.
- $\text{Total distance} = 120 + 180 = 300\text{ m}$.
- Relative speed $= 40 + 50 = 90\text{ km/h} = 90 \times \dfrac{5}{18} = 25\text{ m/s}$.
- $T = \dfrac{300}{25}$ = **12 seconds**.

### Question type 5. Two trains crossing in same direction (overtaking)

**Idea:** $\text{Total distance} = L_1 + L_2$; Relative speed $= |S_1 - S_2|$.

**Example:** Two trains of lengths $100\text{ m}$ and $150\text{ m}$ run on parallel tracks in the same direction at $70\text{ km/h}$ and $52\text{ km/h}$. Time taken by faster train to overtake slower?
- $\text{Total distance} = 100 + 150 = 250\text{ m}$.
- Relative speed $= 70 - 52 = 18\text{ km/h} = 18 \times \dfrac{5}{18} = 5\text{ m/s}$.
- $T = \dfrac{250}{5}$ = **50 seconds**.

### Question type 6. Train crossing a passenger inside another train

**Idea:** distance is only the length of the passing train (passenger is treated as a moving point).

**Example:** A train $150\text{ m}$ long moving at $72\text{ km/h}$ passes a man sitting in another train moving in the opposite direction at $36\text{ km/h}$. Find the time taken.
- Relative speed $= 72 + 36 = 108\text{ km/h} = 108 \times \dfrac{5}{18} = 30\text{ m/s}$.
- Distance $= 150\text{ m}$ (length of passing train only).
- $T = \dfrac{150}{30}$ = **5 seconds**.

### Question type 7. Finding speed and length from two crossing events

**Idea:** $\text{Speed} = \dfrac{\Delta \text{Distance}}{\Delta \text{Time}}$, then $\text{Length} = (\text{Speed} \times T_1) - L_1$.

**Example:** A train crosses a $162\text{ m}$ long platform in 18 seconds and a $120\text{ m}$ long platform in 15 seconds. Find speed and length of the train.
- $\text{Speed} = \dfrac{162 - 120}{18 - 15} = \dfrac{42}{3} = 14\text{ m/s}$ ($50.4\text{ km/h}$).
- $\text{Length} = (14 \times 15) - 120 = 210 - 120$ = **90 m**.

### Question type 8. Two trains starting simultaneously from opposite stations

**Idea:** $\text{Meeting Time} = \dfrac{\text{Distance between stations}}{S_1 + S_2}$.

**Example:** Stations A and B are $450\text{ km}$ apart. Train 1 leaves A at $50\text{ km/h}$ and Train 2 leaves B at $40\text{ km/h}$ towards each other at the same time. Find meeting time and distance from A.
- Time to meet $= \dfrac{450}{50 + 40} = \dfrac{450}{90}$ = **5 hours**.
- Distance from A $= 5 \times 50$ = **250 km**.

### Question type 9. Two trains starting at different times from opposite stations

**Idea:** calculate distance covered by first train before second starts, subtract from total, then divide remainder by $(S_1 + S_2)$.

**Example:** Stations A and B are $200\text{ km}$ apart. Train 1 starts from A at 7:00 AM at $20\text{ km/h}$. Train 2 starts from B at 8:00 AM at $25\text{ km/h}$ towards A. When do they meet?
- By 8:00 AM (1 hour), Train 1 covers $1 \times 20 = 20\text{ km}$.
- Remaining distance $= 200 - 20 = 180\text{ km}$.
- Relative speed $= 20 + 25 = 45\text{ km/h} \implies \text{Time} = \dfrac{180}{45} = 4\text{ hours}$.
- Meeting time $= 8:00\text{ AM} + 4\text{ hours}$ = **12:00 noon**.

### Question type 10. Speed ratio after meeting

**Idea:** $\dfrac{S_1}{S_2} = \sqrt{\dfrac{T_2}{T_1}}$.

**Example:** Trains X and Y start at the same time towards each other. After meeting, X takes $4\text{ hrs } 48\text{ min}$ ($4.8\text{ hrs}$) to reach destination and Y takes $3\text{ hrs } 20\text{ min}$ ($\dfrac{10}{3}\text{ hrs}$). Find the ratio of their speeds.
- $\dfrac{S_X}{S_Y} = \sqrt{\dfrac{10/3}{24/5}} = \sqrt{\dfrac{50}{72}} = \sqrt{\dfrac{25}{36}}$ = **$5:6$**.

### Question type 11. Breakdown or accident midway and speed reduction

**Idea:** compare the delay produced over the shifted distance segment.

**Example:** A train meets with an accident after $50\text{ km}$ and travels at $\dfrac{3}{4}$ speed, arriving 35 min late. If the accident happened $24\text{ km}$ further on, it would be only 25 min late. Find normal speed.
- Travelling $24\text{ km}$ at $\dfrac{3}{4}$ speed causes $35 - 25 = 10\text{ min} = \dfrac{1}{6}\text{ hr}$ extra time.
- $\text{Extra time} = \dfrac{24}{(3/4)S} - \dfrac{24}{S} = \dfrac{32}{S} - \dfrac{24}{S} = \dfrac{8}{S}\text{ hr}$.
- $\dfrac{8}{S} = \dfrac{1}{6} \implies S$ = **48 km/h**.

### Question type 12. Train crossing two moving persons or cyclists

**Idea:** equate train length $L = (S - u_1) \times t_1 = (S - u_2) \times t_2$ (for same direction).

**Example:** A train passes two men walking in the same direction at $2\text{ km/h}$ and $4\text{ km/h}$ in 9 s and 10 s. Find speed and length of the train.
- $9(S - 2) = 10(S - 4) \implies 9S - 18 = 10S - 40 \implies S$ = **22 km/h**.
- Length $= (22 - 2) \times \dfrac{5}{18} \times 9 = 20 \times \dfrac{5}{2}$ = **50 m**.

## 5. Before you practise

**Your turn:** A 150 m train travels at 54 km/h. How long does it take to pass a 50 m platform?

**Think it through:** It must cover $150+50=200$ m. Convert $54$ km/h to $15$ m/s, then divide: $200\div15=13\frac{1}{3}$ seconds. Check: a platform crossing takes longer than passing a pole.

### Quick revision

- Pole or standing person: distance is the train length.
- Platform or bridge: distance is train length plus object length.
- Two trains passing: distance is the sum of their lengths.
- Relative speed is a sum for opposite directions and a difference for the same direction.
- Convert to m/s when lengths are in metres.

### Common mistakes

1. Using only one train’s length when two complete trains pass each other.
2. Adding speeds when trains move in the same direction.
3. Forgetting the platform length.
4. Mixing units, especially km/h and m/s.
5. Treating a passenger in another train like the entire second train.

## 6. Practice

1. A train $300\text{ m}$ long is running at a speed of $90\text{ km/h}$. How many seconds will it take to cross a telegraph post?
2. A $120\text{ m}$ long train crosses a tree in 6 seconds. Find the speed of the train in $\text{km/h}$.
3. A train running at $54\text{ km/h}$ crosses a signal post in 14 seconds. What is the length of the train?
4. A train $250\text{ m}$ long running at $72\text{ km/h}$ crosses a platform $150\text{ m}$ long. How much time does it take?
5. A train $180\text{ m}$ long passes through a tunnel $320\text{ m}$ long in 25 seconds. Find the speed of the train in $\text{km/h}$.
6. A train running at $60\text{ km/h}$ crosses a bridge of length $200\text{ m}$ in 27 seconds. What is the length of the train?
7. A train $125\text{ m}$ long passes a man running at $5\text{ km/h}$ in the same direction in 10 seconds. Find the speed of the train.
8. A train $150\text{ m}$ long running at $65\text{ km/h}$ crosses a man walking at $7\text{ km/h}$ in the opposite direction. How long does it take to cross him?
9. Two trains $140\text{ m}$ and $160\text{ m}$ long are running towards each other on parallel tracks at $60\text{ km/h}$ and $48\text{ km/h}$. In how many seconds will they clear each other?
10. Two trains $130\text{ m}$ and $120\text{ m}$ long are running in the same direction at $62\text{ km/h}$ and $44\text{ km/h}$. Find the time taken by the faster train to cross the slower train.
11. Two trains of equal length running at $46\text{ km/h}$ and $36\text{ km/h}$ in the same direction pass each other in 36 seconds. What is the length of each train?
12. A faster train $100\text{ m}$ long running at $50\text{ km/h}$ overtakes a man sitting in a slower train running at $32\text{ km/h}$ in the same direction. How many seconds does it take to pass the man?
13. A train $120\text{ m}$ long running at $54\text{ km/h}$ passes a passenger sitting in another train moving in the opposite direction at $36\text{ km/h}$. How long does it take to pass the passenger?
14. A train crosses a pole in 9 seconds and a $140\text{ m}$ long platform in 16 seconds. Find the length of the train.
15. A train passes two bridges of lengths $800\text{ m}$ and $400\text{ m}$ in 100 seconds and 60 seconds respectively. Find the length of the train.
16. A train passes a standing man in 8 seconds and crosses completely through a $260\text{ m}$ long platform in 21 seconds. Find the speed of the train in $\text{km/h}$.
17. Stations A and B are $110\text{ km}$ apart. Train 1 starts from A at 7:00 AM at $20\text{ km/h}$ towards B. Train 2 starts from B at 8:00 AM at $25\text{ km/h}$ towards A. At what time will they meet?
18. Two trains start simultaneously from Delhi and Jaipur ($300\text{ km}$ apart) towards each other at $60\text{ km/h}$ and $40\text{ km/h}$. What is the distance from Delhi when they meet?
19. Two trains leave Varanasi and Patna towards each other at $50\text{ km/h}$ and $60\text{ km/h}$. When they meet, the second train has travelled $120\text{ km}$ more than the first. Find the distance between Varanasi and Patna.
20. Two trains A and B start at the same time from points P and Q towards each other. After passing each other, they take 9 hours and 16 hours to reach Q and P respectively. If the speed of train A is $48\text{ km/h}$, find the speed of train B.
21. Two trains start at the same time from two stations towards each other. After meeting, they reach their destinations in $2\text{ hrs } 15\text{ min}$ and 4 hours respectively. If the first train's speed is $64\text{ km/h}$, find the speed of the second train.
22. A train passes two persons walking in the same direction at $4\text{ km/h}$ and $8\text{ km/h}$ in 9 seconds and 10 seconds respectively. Find the speed and length of the train.
23. A train travelling at $48\text{ km/h}$ completely crosses another train of half its length travelling in the opposite direction at $42\text{ km/h}$ in 12 seconds. It also passes a platform in 45 seconds. Find the length of the platform.
24. A train overtakes two cyclists riding in the same direction at $6\text{ km/h}$ and $10\text{ km/h}$ in 18 seconds and 20 seconds respectively. Find the length of the train.
25. Two trains of lengths $160\text{ m}$ and $140\text{ m}$ take 30 seconds to cross each other when running in the same direction, and 6 seconds when running in opposite directions. Find the speeds of the two trains in $\text{km/h}$.
26. A train passes a platform $120\text{ m}$ long in 15 seconds and a telegraph pole in 9 seconds. Find the speed of the train in $\text{km/h}$.
27. A train $150\text{ m}$ long passes another train $100\text{ m}$ long moving in the opposite direction in 10 seconds. If the speed of the first train is $30\text{ km/h}$, find the speed of the second train.
28. A train running at $36\text{ km/h}$ takes 24 seconds to pass completely through a $150\text{ m}$ tunnel. How many seconds will it take to pass a man walking at $9\text{ km/h}$ in the opposite direction?
29. A train $240\text{ m}$ long passes a pole in 24 seconds. How long will it take to pass a platform $650\text{ m}$ long?
30. A passenger train $200\text{ m}$ long and a goods train $300\text{ m}$ long run on parallel tracks in the same direction at $60\text{ km/h}$ and $40\text{ km/h}$ respectively. How long does the driver of the passenger train take to completely pass the goods train?
31. A train after travelling $60\text{ km}$ meets with an accident and proceeds at $\dfrac{2}{3}$ of its original speed, reaching $40\text{ min}$ late. Had the accident occurred $30\text{ km}$ further, it would have been only $20\text{ min}$ late. Find the original speed of the train.
32. Two trains X and Y start at 6:00 AM from stations A and B towards each other. Train X reaches B in 4 hours and Train Y reaches A in 5 hours. At what time do they cross each other?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 12 seconds | $\frac{300}{90 \times \frac{5}{18}} = \frac{300}{25}$ |
| 2 | 72 km/h | $\frac{120}{6} = 20\text{ m/s}$; $20 \times \frac{18}{5}$ |
| 3 | 210 m | $54 \times \frac{5}{18} = 15\text{ m/s}$; $15 \times 14$ |
| 4 | 20 seconds | $\frac{250 + 150}{72 \times \frac{5}{18}} = \frac{400}{20}$ |
| 5 | 72 km/h | $\frac{180 + 320}{25} = 20\text{ m/s}$; $20 \times \frac{18}{5}$ |
| 6 | 250 m | $60 \times \frac{5}{18} = \frac{50}{3}\text{ m/s}$; $\frac{50}{3} \times 27 - 200 = 450 - 200$ |
| 7 | 50 km/h | Relative $= \frac{125}{10} \times \frac{18}{5} = 45\text{ km/h}$; Train $= 45 + 5$ |
| 8 | 7.5 seconds | $S_{\text{rel}} = 65 + 7 = 72\text{ km/h} = 20\text{ m/s}$; $\frac{150}{20}$ |
| 9 | 10 seconds | Distance $= 300\text{ m}$; $S_{\text{rel}} = 60 + 48 = 108\text{ km/h} = 30\text{ m/s}$; $\frac{300}{30}$ |
| 10 | 50 seconds | Distance $= 250\text{ m}$; $S_{\text{rel}} = 62 - 44 = 18\text{ km/h} = 5\text{ m/s}$; $\frac{250}{5}$ |
| 11 | 50 m | $S_{\text{rel}} = 10 \times \frac{5}{18} = \frac{25}{9}\text{ m/s}$; $2L = \frac{25}{9} \times 36 = 100 \implies L = 50$ |
| 12 | 20 seconds | Distance $= 100\text{ m}$; $S_{\text{rel}} = 50 - 32 = 18\text{ km/h} = 5\text{ m/s}$; $\frac{100}{5}$ |
| 13 | 4.8 seconds | Distance $= 120\text{ m}$; $S_{\text{rel}} = 54 + 36 = 90\text{ km/h} = 25\text{ m/s}$; $\frac{120}{25}$ |
| 14 | 180 m | Speed $= \frac{140}{16 - 9} = 20\text{ m/s}$; Length $= 20 \times 9$ |
| 15 | 200 m | Speed $= \frac{800 - 400}{100 - 60} = 10\text{ m/s}$; Length $= 10 \times 60 - 400$ |
| 16 | 72 km/h | Speed $= \frac{260}{21 - 8} = 20\text{ m/s}$; $20 \times \frac{18}{5}$ |
| 17 | 10:00 AM | Rem $D = 110 - 20 = 90\text{ km}$; $T = \frac{90}{20 + 25} = 2\text{ hrs after 8:00 AM}$ |
| 18 | 180 km | Meeting time $= \frac{300}{60 + 40} = 3\text{ hrs}$; Distance $= 60 \times 3$ |
| 19 | 1320 km | $T = \frac{120}{60 - 50} = 12\text{ hrs}$; Total $D = 12 \times (50 + 60)$ |
| 20 | 36 km/h | $\frac{S_A}{S_B} = \sqrt{\frac{16}{9}} = \frac{4}{3} \implies S_B = 48 \times \frac{3}{4}$ |
| 21 | 48 km/h | $\frac{S_1}{S_2} = \sqrt{\frac{4}{9/4}} = \frac{4}{3} \implies S_2 = 64 \times \frac{3}{4}$ |
| 22 | 44 km/h, 100 m | $9(S - 4) = 10(S - 8) \implies S = 44\text{ km/h}$; $L = (44 - 4) \times \frac{5}{18} \times 9$ |
| 23 | 400 m | $1.5L = 25 \times 12 = 300 \implies L = 200$; $L + L_p = \frac{40}{3} \times 45 = 600 \implies L_p = 400$ |
| 24 | 200 m | $18(S - 6) = 20(S - 10) \implies S = 46\text{ km/h}$; $L = (46 - 6) \times \frac{5}{18} \times 18$ |
| 25 | 108 km/h, 72 km/h | $S_1 - S_2 = 36$, $S_1 + S_2 = 180$; $\frac{180 \pm 36}{2}$ |
| 26 | 72 km/h | Speed $= \frac{120}{15 - 9} = 20\text{ m/s}$; $20 \times \frac{18}{5}$ |
| 27 | 60 km/h | $S_{\text{rel}} = \frac{250}{10} \times \frac{18}{5} = 90\text{ km/h}$; $S_2 = 90 - 30$ |
| 28 | 7.2 seconds | Train $L = 10 \times 24 - 150 = 90\text{ m}$; $S_{\text{rel}} = 36 + 9 = 45\text{ km/h} = 12.5\text{ m/s}$; $\frac{90}{12.5}$ |
| 29 | 89 seconds | Speed $= \frac{240}{24} = 10\text{ m/s}$; Total $D = 890\text{ m}$; $\frac{890}{10}$ |
| 30 | 54 seconds | Driver crosses goods length ($300\text{ m}$); $S_{\text{rel}} = 20\text{ km/h} = \frac{50}{9}\text{ m/s}$; $\frac{300}{50/9}$ |
| 31 | 45 km/h | $\frac{30}{(2/3)S} - \frac{30}{S} = \frac{15}{S}\text{ hr} = 20\text{ min} = \frac{1}{3}\text{ hr} \implies S = 45$ |
| 32 | 8:13:20 AM | Let $D = 20\text{ km}$; speeds $5, 4\text{ km/h}$; $T = \frac{20}{9}\text{ hrs} = 2\text{ hrs } 13\text{ min } 20\text{ s}$ |
