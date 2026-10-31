# Probability: Model-wise Notes

## Part 1. What comes from this topic

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Model |
|---|---|
| Single and multiple coin tosses | 1 |
| Single and multiple dice throws | 2 |
| Pack of 52 cards | 3 |
| Balls drawn from an urn or bag | 4 |
| Addition theorem and non-mutually exclusive events | 5 |
| Independent events and problem solving | 6 |
| Conditional probability | 7 |
| At least one event occurs (Complement rule) | 8 |
| Probability with odds in favour and odds against | 9 |
| Truth and lie / Contradiction problems | 10 |
| Total probability and Bayes' theorem | 11 |
| Leap year and calendar probability | 12 |
| Selection of numbers and divisibility | 13 |

## Part 2. What data is usually given

| Data you will see | What it means |
|---|---|
| "At least one head in 3 tosses" | Total minus all tails: $1 - P(\text{all } T)$ |
| "Sum of numbers on two dice is 8" | Count ordered pairs $(a, b)$ with $a+b=8$ over 36 |
| "A card is drawn: King or Spade" | Union formula: $P(K) + P(S) - P(K \cap S)$ |
| "2 balls drawn without replacement" | Use combinations: $\dfrac{^r C_k \times ^b C_m}{^N C_n}$ |
| "A and B solve independently" | $P(A \cap B) = P(A) \times P(B)$ |
| "Odds in favour are $a:b$" | Probability is $\dfrac{a}{a+b}$ |
| "A speaks truth in 75%, B in 80%" | Contradiction $= P(A\bar{B}) + P(\bar{A}B)$ |

## Part 3. The base idea (read once)

- **Probability:** $P(E) = \dfrac{\text{Number of favourable outcomes } n(E)}{\text{Total number of outcomes } n(S)}$.
- **Complement:** $P(E') = 1 - P(E) \implies P(\text{at least one}) = 1 - P(\text{none})$.
- **Addition rule:** $P(A \cup B) = P(A) + P(B) - P(A \cap B)$. If mutually exclusive, $P(A \cap B) = 0$.
- **Multiplication rule:** for independent events, $P(A \cap B) = P(A) \times P(B)$.
- **Odds:** odds in favour $a:b \implies P = \dfrac{a}{a+b}$; odds against $b:a \implies P = \dfrac{a}{a+b}$.

## Part 4. Models

### Model 1. Single and multiple coin tosses

**Idea:** for $n$ coins, total outcomes $= 2^n$. Favourable cases with $r$ heads $= ^n C_r$.

**Example 1:** Three unbiased coins are tossed. What is the probability of getting at least 2 heads?
- Total outcomes $= 2^3 = 8$.
- Favourable (2 heads or 3 heads): $^3 C_2 + ^3 C_3 = 3 + 1 = 4$.
- $P = \dfrac{4}{8} =$ **$\dfrac{1}{2}$**.

**Example 2:** Four coins are tossed. What is the probability of getting exactly 2 heads?
- Total outcomes $= 2^4 = 16$. Favourable $= ^4 C_2 = 6$.
- $P = \dfrac{6}{16} =$ **$\dfrac{3}{8}$**.

### Model 2. Single and multiple dice throws

**Idea:** for 2 dice, total outcomes $= 36$. Sum ranges from 2 to 12. Sum $S$ frequencies: $2(1), 3(2), 4(3), 5(4), 6(5), 7(6), 8(5), 9(4), 10(3), 11(2), 12(1)$.

**Example 1:** Two dice are thrown. Find the probability of getting a sum of 8.
- Favourable pairs: $(2,6), (3,5), (4,4), (5,3), (6,2) \implies 5$ pairs.
- $P = \mathbf{\dfrac{5}{36}}$.

**Example 2:** Two dice are thrown. What is the probability that the sum is at least 10?
- Sums 10, 11, 12 have frequencies $3 + 2 + 1 = 6$.
- $P = \dfrac{6}{36} =$ **$\dfrac{1}{6}$**.

### Model 3. Pack of 52 cards

**Idea:** 52 cards $= 4$ suits of 13 each (26 Red, 26 Black); 12 face cards (4 J, 4 Q, 4 K); 4 Aces.

**Example 1:** One card is drawn from 52 cards. What is the probability of getting a King or a Spade?
- $P(\text{King}) = \dfrac{4}{52}$, $P(\text{Spade}) = \dfrac{13}{52}$, $P(\text{King of Spades}) = \dfrac{1}{52}$.
- $P = \dfrac{4}{52} + \dfrac{13}{52} - \dfrac{1}{52} = \dfrac{16}{52} =$ **$\dfrac{4}{13}$**.

**Example 2:** Two cards are drawn together from 52 cards. Find the probability that both are Aces.
- Favourable $= ^4 C_2 = 6$. Total $= ^{52} C_2 = 1326$.
- $P = \dfrac{6}{1326} =$ **$\dfrac{1}{221}$**.

### Model 4. Balls drawn from an urn or bag

**Idea:** total balls $N$, selecting $n$ balls gives $^{N} C_n$ sample space; count combinations of each colour.

**Example 1:** A bag contains 4 red, 5 blue, and 6 green balls. If 2 balls are drawn, what is the probability that both are red?
- Total balls $= 15$. Total ways $= ^{15} C_2 = 105$.
- Favourable ways $= ^4 C_2 = 6$.
- $P = \dfrac{6}{105} =$ **$\dfrac{2}{35}$**.

**Example 2:** A box contains 3 red, 4 white, and 5 blue marbles. If 3 marbles are drawn, find the probability of getting exactly one of each colour.
- Favourable ways $= ^3 C_1 \times ^4 C_1 \times ^5 C_1 = 3 \times 4 \times 5 = 60$.
- Total ways $= ^{12} C_3 = \dfrac{12 \times 11 \times 10}{6} = 220$.
- $P = \dfrac{60}{220} =$ **$\dfrac{3}{11}$**.

### Model 5. Addition theorem and non-mutually exclusive events

**Idea:** $P(A \cup B) = P(A) + P(B) - P(A \cap B)$.

**Example:** If $P(A) = \dfrac{1}{3}$, $P(B) = \dfrac{1}{4}$, and $P(A \cap B) = \dfrac{1}{6}$, find $P(A \cup B)$.
- $P(A \cup B) = \dfrac{1}{3} + \dfrac{1}{4} - \dfrac{1}{6} = \dfrac{4 + 3 - 2}{12} = \mathbf{\dfrac{5}{12}}$.

### Model 6. Independent events and problem solving

**Idea:** for independent events, $P(\text{problem solved}) = 1 - P(\text{all fail}) = 1 - P(\bar{A})P(\bar{B})P(\bar{C})$.

**Example 1:** A problem is given to A, B, and C whose chances of solving are $\dfrac{1}{2}, \dfrac{1}{3}, \dfrac{1}{4}$. What is the probability that the problem is solved?
- $P(\bar{A}) = \dfrac{1}{2}$, $P(\bar{B}) = \dfrac{2}{3}$, $P(\bar{C}) = \dfrac{3}{4}$.
- $P(\text{none solves}) = \dfrac{1}{2} \times \dfrac{2}{3} \times \dfrac{3}{4} = \dfrac{1}{4}$.
- $P(\text{solved}) = 1 - \dfrac{1}{4} =$ **$\dfrac{3}{4}$**.

**Example 2:** With the same probabilities, what is the probability that exactly one solves it?
- $P(A\bar{B}\bar{C}) + P(\bar{A}B\bar{C}) + P(\bar{A}\bar{B}C) = \left(\dfrac{1}{2}\times\dfrac{2}{3}\times\dfrac{3}{4}\right) + \left(\dfrac{1}{2}\times\dfrac{1}{3}\times\dfrac{3}{4}\right) + \left(\dfrac{1}{2}\times\dfrac{2}{3}\times\dfrac{1}{4}\right)$.
- Sum $= \dfrac{6}{24} + \dfrac{3}{24} + \dfrac{2}{24} = \mathbf{\dfrac{11}{24}}$.

### Model 7. Conditional probability

**Idea:** $P(A|B) = \dfrac{P(A \cap B)}{P(B)} = \dfrac{n(A \cap B)}{n(B)}$.

**Example:** A die is rolled. Find the probability of getting a prime number given that the outcome is odd.
- Odd outcomes $B = \{1, 3, 5\} \implies n(B) = 3$.
- Prime outcomes $A = \{2, 3, 5\} \implies A \cap B = \{3, 5\} \implies n(A \cap B) = 2$.
- $P(A|B) = \mathbf{\dfrac{2}{3}}$.

### Model 8. At least one event occurs (Complement rule)

**Idea:** $P(\text{at least one success in } n \text{ trials}) = 1 - [P(\text{failure in 1 trial})]^n$.

**Example:** An unbiased die is thrown 3 times. What is the probability of getting at least one 6?
- $P(\text{no 6 in 1 throw}) = \dfrac{5}{6}$.
- $P(\text{no 6 in 3 throws}) = \left(\dfrac{5}{6}\right)^3 = \dfrac{125}{216}$.
- $P(\text{at least one 6}) = 1 - \dfrac{125}{216} = \mathbf{\dfrac{91}{216}}$.

### Model 9. Probability with odds in favour and odds against

**Idea:** odds in favour $a:b \implies P(E) = \dfrac{a}{a+b}$; odds against $b:a \implies P(E) = \dfrac{a}{a+b}$.

**Example:** The odds in favour of an event are $3:5$. Find its probability.
- $P(E) = \dfrac{3}{3 + 5} = \mathbf{\dfrac{3}{8}}$.

### Model 10. Truth and lie / Contradiction problems

**Idea:** contradiction occurs when one speaks truth and the other lies: $P(A)P(\bar{B}) + P(\bar{A})P(B)$.

**Example:** A speaks truth in 75% cases ($\frac{3}{4}$) and B in 80% cases ($\frac{4}{5}$). What is the probability that they contradict each other?
- $P(A\bar{B}) + P(\bar{A}B) = \left(\dfrac{3}{4} \times \dfrac{1}{5}\right) + \left(\dfrac{1}{4} \times \dfrac{4}{5}\right) = \dfrac{3}{20} + \dfrac{4}{20} = \dfrac{7}{20} =$ **35%** (or $\mathbf{\dfrac{7}{20}}$).

### Model 11. Total probability and Bayes' theorem

**Idea:** $P(B_1|A) = \dfrac{P(B_1)P(A|B_1)}{P(B_1)P(A|B_1) + P(B_2)P(A|B_2)}$.

**Example:** Bag 1 contains 4 white and 2 black balls. Bag 2 contains 3 white and 5 black balls. A bag is chosen at random and a white ball is drawn. Find the probability that it came from Bag 1.
- $P(B_1) = P(B_2) = \dfrac{1}{2}$. $P(W|B_1) = \dfrac{4}{6} = \dfrac{2}{3}$, $P(W|B_2) = \dfrac{3}{8}$.
- Numerator $= \dfrac{1}{2} \times \dfrac{2}{3} = \dfrac{1}{3}$.
- Denominator $= \left(\dfrac{1}{2} \times \dfrac{2}{3}\right) + \left(\dfrac{1}{2} \times \dfrac{3}{8}\right) = \dfrac{1}{3} + \dfrac{3}{16} = \dfrac{25}{48}$.
- $P(B_1|W) = \dfrac{1/3}{25/48} = \dfrac{16}{25} =$ **$\dfrac{16}{25}$**.

### Model 12. Leap year and calendar probability

**Idea:** ordinary year has 1 extra day ($\frac{1}{7}$ probability); leap year has 2 extra days ($\frac{2}{7}$ probability of 53 specified weekdays).

**Example:** What is the probability that a leap year selected at random has 53 Sundays?
- Extra 2 days form 7 possible pairs; 2 pairs contain Sunday.
- Probability $= \mathbf{\dfrac{2}{7}}$.

### Model 13. Selection of numbers and divisibility

**Idea:** count multiples within range using floor division: $n(k) = \lfloor \text{limit}/k \rfloor$.

**Example:** A number is chosen at random from 1 to 50. What is the probability that it is a multiple of 3 or 5?
- $n(3) = \lfloor 50/3 \rfloor = 16$, $n(5) = \lfloor 50/5 \rfloor = 10$, $n(15) = \lfloor 50/15 \rfloor = 3$.
- Favourable $= 16 + 10 - 3 = 23$. Total $= 50$.
- Probability $= \mathbf{\dfrac{23}{50}}$.

## Part 5. Practice

1. Two unbiased coins are tossed. Find the probability of getting at least one head.
2. Three unbiased coins are tossed. Find the probability of getting exactly two tails.
3. Four coins are tossed simultaneously. What is the probability of getting at least 3 heads?
4. A single die is rolled. Find the probability of getting a prime number.
5. Two dice are thrown simultaneously. What is the probability of getting a sum of 9?
6. Two dice are thrown simultaneously. What is the probability of getting a doublet (both dice showing the same number)?
7. Two dice are thrown. What is the probability that the sum is greater than 8?
8. One card is drawn from a well-shuffled pack of 52 cards. What is the probability of getting a face card?
9. One card is drawn from 52 cards. What is the probability of getting a red card or a Queen?
10. Two cards are drawn together from 52 cards. Find the probability that both are Kings.
11. A bag contains 6 red, 4 white, and 5 blue balls. If a ball is drawn at random, what is the probability that it is not white?
12. A bag contains 5 red, 4 green, and 3 blue balls. If 2 balls are drawn at random, find the probability that both are green.
13. A bag contains 4 red and 6 black balls. If 2 balls are drawn at random, find the probability that one is red and one is black.
14. A box contains 3 red, 4 white, and 5 blue marbles. If 3 marbles are drawn at random, what is the probability of getting 1 of each colour?
15. In a class, 40% of students study Math, 30% study Physics, and 15% study both. Find the probability that a student chosen at random studies Math or Physics.
16. If $P(A) = \dfrac{2}{5}$, $P(B) = \dfrac{1}{3}$, and $P(A \cap B) = \dfrac{1}{5}$, find $P(A \cup B)$.
17. A problem in mathematics is given to two students A and B whose chances of solving it are $\dfrac{1}{2}$ and $\dfrac{1}{3}$ respectively. What is the probability that the problem is solved?
18. A target is shot at by A, B, and C independently with probabilities $\dfrac{1}{2}$, $\dfrac{1}{3}$, and $\dfrac{1}{4}$. What is the probability that at least one hits the target?
19. Two students A and B solve a problem independently with probabilities $\dfrac{2}{3}$ and $\dfrac{3}{4}$. What is the probability that exactly one of them solves it?
20. A die is rolled. Find the probability of getting an even number given that the number obtained is greater than 2.
21. A family has two children. What is the conditional probability that both are boys given that at least one is a boy?
22. An unbiased die is thrown 3 times. What is the probability of getting at least one 6?
23. The odds in favour of an event A are $4:7$. Find the probability of occurrence of A.
24. The odds against a horse winning a race are $5:2$. What is the probability that the horse wins?
25. A speaks truth in 75% of cases and B in 80% of cases. In what percentage of cases are they likely to contradict each other in stating the same fact?
26. A speaks truth in 60% of cases and B in 70% of cases. What is the probability that they agree in stating the same fact?
27. Bag A has 3 red and 4 black balls. Bag B has 5 red and 6 black balls. One bag is selected at random and a ball is drawn. Find the probability that the ball drawn is red.
28. Bag 1 contains 4 white and 2 black balls. Bag 2 contains 3 white and 5 black balls. A bag is chosen at random and a ball is drawn and found to be white. What is the probability that it was drawn from Bag 1?
29. What is the probability that a leap year selected at random contains 53 Mondays?
30. What is the probability that a non-leap year contains 53 Sundays?
31. Two people are selected at random. What is the probability that they have the same birthday (ignoring leap years)?
32. A number is chosen at random from 1 to 50. What is the probability that it is a multiple of 3 or 5?
33. A number is selected from 1 to 100. Find the probability that it is a perfect square.
34. What is the probability of getting a total of at least 17 in a single throw of three dice?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | $\frac{3}{4}$ | Favourable outcomes: $\{\text{HH, HT, TH}\} = 3$; $\frac{3}{4}$ |
| 2 | $\frac{3}{8}$ | $^3 C_2 = 3$ outcomes out of 8; $\frac{3}{8}$ |
| 3 | $\frac{5}{16}$ | $\frac{^4 C_3 + ^4 C_4}{16} = \frac{4 + 1}{16} = \frac{5}{16}$ |
| 4 | $\frac{1}{2}$ | Primes in single die $= \{2, 3, 5\} \implies \frac{3}{6} = \frac{1}{2}$ |
| 5 | $\frac{1}{9}$ | Pairs summing to 9: $(3,6),(4,5),(5,4),(6,3) \implies \frac{4}{36} = \frac{1}{9}$ |
| 6 | $\frac{1}{6}$ | 6 doublets $(1,1)\dots(6,6) \implies \frac{6}{36} = \frac{1}{6}$ |
| 7 | $\frac{5}{18}$ | Sums 9, 10, 11, 12 give $4 + 3 + 2 + 1 = 10$ pairs; $\frac{10}{36} = \frac{5}{18}$ |
| 8 | $\frac{3}{13}$ | 12 face cards; $\frac{12}{52} = \frac{3}{13}$ |
| 9 | $\frac{7}{13}$ | $\frac{26 + 4 - 2}{52} = \frac{28}{52} = \frac{7}{13}$ |
| 10 | $\frac{1}{221}$ | $\frac{^4 C_2}{^{52} C_2} = \frac{6}{1326} = \frac{1}{221}$ |
| 11 | $\frac{11}{15}$ | Not white $= 6 + 5 = 11$; $\frac{11}{15}$ |
| 12 | $\frac{1}{11}$ | $\frac{^4 C_2}{^{12} C_2} = \frac{6}{66} = \frac{1}{11}$ |
| 13 | $\frac{8}{15}$ | $\frac{^4 C_1 \times ^6 C_1}{^{10} C_2} = \frac{24}{45} = \frac{8}{15}$ |
| 14 | $\frac{3}{11}$ | $\frac{3 \times 4 \times 5}{^{12} C_3} = \frac{60}{220} = \frac{3}{11}$ |
| 15 | $\frac{11}{20}$ | $0.40 + 0.30 - 0.15 = 0.55 = \frac{11}{20}$ |
| 16 | $\frac{8}{15}$ | $\frac{2}{5} + \frac{1}{3} - \frac{1}{5} = \frac{1}{5} + \frac{1}{3} = \frac{8}{15}$ |
| 17 | $\frac{2}{3}$ | $1 - P(\text{neither}) = 1 - \left(\frac{1}{2} \times \frac{2}{3}\right) = 1 - \frac{1}{3} = \frac{2}{3}$ |
| 18 | $\frac{3}{4}$ | $1 - \left(\frac{1}{2} \times \frac{2}{3} \times \frac{3}{4}\right) = 1 - \frac{1}{4} = \frac{3}{4}$ |
| 19 | $\frac{5}{12}$ | $\left(\frac{2}{3} \times \frac{1}{4}\right) + \left(\frac{1}{3} \times \frac{3}{4}\right) = \frac{2}{12} + \frac{3}{12} = \frac{5}{12}$ |
| 20 | $\frac{1}{2}$ | Favourable $\{4, 6\}$ out of given $\{3, 4, 5, 6\}$; $\frac{2}{4} = \frac{1}{2}$ |
| 21 | $\frac{1}{3}$ | Given space $\{\text{BB, BG, GB}\} \implies P(\text{BB}) = \frac{1}{3}$ |
| 22 | $\frac{91}{216}$ | $1 - \left(\frac{5}{6}\right)^3 = 1 - \frac{125}{216} = \frac{91}{216}$ |
| 23 | $\frac{4}{11}$ | $\frac{4}{4 + 7} = \frac{4}{11}$ |
| 24 | $\frac{2}{7}$ | $\frac{2}{5 + 2} = \frac{2}{7}$ |
| 25 | 35% | $\left(\frac{3}{4}\times\frac{1}{5}\right) + \left(\frac{1}{4}\times\frac{4}{5}\right) = \frac{7}{20} = 35\%$ |
| 26 | 54% | $(0.6 \times 0.7) + (0.4 \times 0.3) = 0.42 + 0.12 = 0.54 = 54\%$ |
| 27 | $\frac{34}{77}$ | $\left(\frac{1}{2}\times\frac{3}{7}\right) + \left(\frac{1}{2}\times\frac{5}{11}\right) = \frac{33 + 35}{154} = \frac{34}{77}$ |
| 28 | $\frac{16}{25}$ | $\frac{\frac{1}{2}\times\frac{4}{6}}{\left(\frac{1}{2}\times\frac{4}{6}\right) + \left(\frac{1}{2}\times\frac{3}{8}\right)} = \frac{1/3}{25/48} = \frac{16}{25}$ |
| 29 | $\frac{2}{7}$ | Leap year has 2 extra days; 2 of 7 pairs contain Monday |
| 30 | $\frac{1}{7}$ | Ordinary year has 1 extra day; $\frac{1}{7}$ probability of Sunday |
| 31 | $\frac{1}{365}$ | 2nd person matches 1st person's day: $\frac{1}{365}$ |
| 32 | $\frac{23}{50}$ | $n(3) = 16, n(5) = 10, n(15) = 3 \implies \frac{16 + 10 - 3}{50} = \frac{23}{50}$ |
| 33 | $\frac{1}{10}$ | 10 perfect squares from $1^2$ to $10^2$; $\frac{10}{100} = \frac{1}{10}$ |
| 34 | $\frac{1}{54}$ | Sum 17 (3 ways) $+$ Sum 18 (1 way) $= \frac{4}{216} = \frac{1}{54}$ |
