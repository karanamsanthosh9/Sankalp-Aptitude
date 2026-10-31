# Averages

> Read this like a class: picture the situation, understand the idea, and then choose a calculation. Try the questions in the guide before peeking at their answers.

## 0. Start here: what is an average really?

Imagine sharing a group’s total marks equally among everyone. The equal share is the average. That picture is useful because an average is not a mysterious new number: it is a compact way to describe a total. Questions ask you to find a missing score, combine classes, work out who joined or left, correct a record, or compare performance over time. In each case, first recover the total with **average × count**, then adjust the total or count that changed.

For example, if 5 scores average 28, together they make 140 points. A missing score is simply whatever is needed to bring the known scores up to 140. Check your answer by dividing the new total by the new count.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Basic average and finding a missing value | 1 |
| Weighted average and combined groups | 2 |
| Inclusion (a new member joins) | 3 |
| Exclusion (a member leaves) | 4 |
| Replacement (one member replaces another) | 5 |
| Correction of incorrect entries | 6 |
| Overlapping numbers and middle value | 7 |
| Consecutive numbers and arithmetic progressions | 8 |
| Cricket batting and bowling averages | 9 |
| Group expenditure and sharing bill | 10 |
| Average age over time and family changes | 11 |
| Alligation method for averages | 12 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Average of $n$ items is $A$" | $\text{Total sum} = n \times A$ |
| "A new person joins and average increases by $x$" | New person brings $x$ extra units for every member |
| "A person leaves and average decreases" | Departing person took more than the old average |
| "A person of weight $W$ is replaced" | Net change in sum $= \text{new} - W = n \times \Delta A$ |
| "Value $a$ misread as $b$" | Correction $= \text{Old Sum} + \text{Correct} - \text{Wrong}$ |
| "Average of first $k$ and last $k$ numbers" | Middle number is counted twice (overlap) |
| "Consecutive odd or even numbers" | Numbers form an AP; average is the exact middle value |
| "Bowling average improves by $x$" | Runs conceded per wicket decreases by $x$ |

## 3. The core idea

- **Average** $=\dfrac{\text{Sum of all observations}}{\text{Number of observations}}$, so $\text{Sum} = \text{Average} \times \text{Count}$.
- **Deviation method:** when values change, $\text{New Value} = \text{Old Average} + (\text{New Count} \times \text{Increase})$.
- For an AP with odd count, the average is the exact middle term; for even count, it is the mean of the two middle terms.
- **Combined Average:** $A_{\text{comb}} = \dfrac{n_1 A_1 + n_2 A_2}{n_1 + n_2}$.

## 4. Question-type walkthroughs

### Question type 1. Basic average and finding a missing value

**Idea:** $\text{Missing value} = (\text{Total count} \times \text{Overall average}) - \text{Sum of known values}$.

**Example 1:** The average of 5 numbers is 28. Four of the numbers are 22, 26, 30, and 34. Find the 5th number.
- $\text{Total sum} = 5 \times 28 = 140$.
- $\text{Sum of 4 numbers} = 22 + 26 + 30 + 34 = 112$.
- $\text{5th number} = 140 - 112$ = **28**.

**Example 2:** The average score of a batsman in 7 innings is 48 runs. Find his total runs.
- $\text{Total runs} = 7 \times 48$ = **336 runs**.

### Question type 2. Weighted average and combined groups

**Idea:** $A_{\text{comb}} = \dfrac{n_1 A_1 + n_2 A_2 + \dots}{n_1 + n_2 + \dots}$.

**Example 1:** Class A has 30 students with an average score of 60. Class B has 20 students with an average score of 70. Find the combined average.
- $\text{Total marks} = (30 \times 60) + (20 \times 70) = 1800 + 1400 = 3200$.
- $\text{Combined average} = \dfrac{3200}{50}$ = **64**.

**Example 2:** Three sections with 25, 35, and 40 students have average marks of 40, 50, and 60. Overall average?
- $\text{Total marks} = (25 \times 40) + (35 \times 50) + (40 \times 60) = 1000 + 1750 + 2400 = 5150$.
- $\text{Average} = \dfrac{5150}{100}$ = **51.5**.

### Question type 3. Inclusion (a new member joins)

**Idea:** $\text{New Member} = \text{Old Average} + (\text{New Total Members} \times \text{Increase in Average})$.

**Example 1:** The average age of 24 students is 15 years. When the teacher joins, the average becomes 16 years. Teacher's age?
- Teacher's age $= 15 + (25 \times 1)$ = **40 years**.

**Example 2:** The average weight of 19 people is 55 kg. A new person joins and the average drops by 0.5 kg. New person's weight?
- New weight $= 55 - (20 \times 0.5) = 55 - 10$ = **45 kg**.

### Question type 4. Exclusion (a member leaves)

**Idea:** $\text{Departed Member} = \text{Old Sum} - \text{New Sum} = \text{Old Average} + (\text{New Count} \times \text{Decrease in Average})$.

**Example 1:** The average age of 30 students and a teacher is 16 years. When the teacher leaves, the average becomes 15 years. Teacher's age?
- $\text{Teacher's age} = (31 \times 16) - (30 \times 15) = 496 - 450$ = **46 years**.

**Example 2:** The average of 10 numbers is 25. If one number is removed, the average becomes 24. Find the removed number.
- $\text{Removed number} = (10 \times 25) - (9 \times 24) = 250 - 216$ = **34**.

### Question type 5. Replacement (one member replaces another)

**Idea:** $\text{New Value} = \text{Replaced Value} + (\text{Count} \times \text{Change in Average})$.

**Example 1:** The average weight of 12 men increases by 2 kg when a man weighing 60 kg is replaced. Weight of the new man?
- $\text{New weight} = 60 + (12 \times 2) = 60 + 24$ = **84 kg**.

**Example 2:** The average age of 8 women decreases by 1 year when a 40-year-old woman is replaced. Age of the newcomer?
- $\text{New age} = 40 - (8 \times 1)$ = **32 years**.

### Question type 6. Correction of incorrect entries

**Idea:** $\text{Correct Average} = \text{Old Average} + \dfrac{\text{Correct Values} - \text{Wrong Values}}{\text{Total Count}}$.

**Example 1:** The average of 25 numbers is 40. A number 36 was wrongly entered as 61. Find the correct average.
- $\text{Difference} = 36 - 61 = -25$.
- $\text{Correct average} = 40 + \dfrac{-25}{25} = 40 - 1$ = **39**.

**Example 2:** The average of 50 items is 30. Two items 45 and 35 were misread as 25 and 15. Correct average?
- $\text{Difference} = (45 + 35) - (25 + 15) = 80 - 40 = +40$.
- $\text{Correct average} = 30 + \dfrac{40}{50} = 30 + 0.8$ = **30.8**.

### Question type 7. Overlapping numbers and middle value

**Idea:** $\text{Middle Number} = (\text{Sum of first } k) + (\text{Sum of last } k) - (\text{Total Sum})$.

**Example 1:** The average of 11 numbers is 50. The average of the first 6 is 49 and the last 6 is 52. Find the 6th number.
- $\text{Sum of first 6} = 6 \times 49 = 294$; $\text{Sum of last 6} = 6 \times 52 = 312$.
- $\text{Total sum} = 11 \times 50 = 550$.
- $\text{6th number} = 294 + 312 - 550$ = **56**.

**Example 2:** The average of 9 numbers is 32. The average of the first 4 is 30 and the last 4 is 35. Find the 5th number.
- $\text{Total sum} = 9 \times 32 = 288$.
- $\text{Sum of 8 numbers} = (4 \times 30) + (4 \times 35) = 120 + 140 = 260$.
- $\text{5th number} = 288 - 260$ = **28**.

### Question type 8. Consecutive numbers and arithmetic progressions

**Idea:** For consecutive numbers in AP, $\text{Average} = \dfrac{\text{First} + \text{Last}}{2} = \text{Middle term}$.

**Example 1:** The average of 5 consecutive odd numbers is 27. Find the largest number.
- The middle (3rd) number is 27. The numbers are $23, 25, 27, 29, 31$.
- Largest number = **31**.

**Example 2:** The average of 6 consecutive even numbers is 35. Find the smallest number.
- The two middle numbers average to 35, so they are 34 and 36.
- The numbers are $30, 32, 34, 36, 38, 40$. Smallest = **30**.

### Question type 9. Cricket batting and bowling averages

**Idea:** $\text{Batting Average} = \dfrac{\text{Total Runs}}{\text{Innings Dismissed}}$. $\text{Bowling Average} = \dfrac{\text{Runs Conceded}}{\text{Wickets Taken}}$.

**Example 1 (batting):** A batsman has an average of 40 in 15 innings. He scores 88 in the 16th inning. New average?
- $\text{Total runs} = (15 \times 40) + 88 = 600 + 88 = 688$.
- $\text{New average} = \dfrac{688}{16}$ = **43**.

**Example 2 (bowling):** A bowler's average is 12.4 runs/wicket. He takes 5 wickets for 26 runs, improving his average by 0.4. Total wickets before this match?
- Let previous wickets be $w$. Total runs $= 12.4w + 26$.
- $12.4w + 26 = 12.0(w + 5) \implies 0.4w = 34 \implies w$ = **85 wickets**.

### Question type 10. Group expenditure and sharing bill

**Idea:** If one person pays extra over the overall average $A$, that extra is distributed among the remaining members.

**Example:** 9 friends go for dinner. 8 spend Rs 30 each. The 9th spends Rs 16 more than the average of all 9. Total money spent?
- Let overall average be $A$. $A = 30 + \dfrac{16}{8} = 30 + 2 = 32$.
- $\text{Total spent} = 9 \times 32$ = **Rs 288**.

### Question type 11. Average age over time and family changes

**Idea:** If no members change, average increases by $t$ years after $t$ years. Adjust for newborns or departed members.

**Example:** 3 years ago, the average age of a family of 5 members was 17 years. A baby is born, and the average age of the family is the same today. Age of the baby?
- Present sum of the 5 original members $= 5 \times (17 + 3) = 100\text{ years}$.
- Present sum of 6 members $= 6 \times 17 = 102\text{ years}$.
- Baby's age $= 102 - 100$ = **2 years**.

### Question type 12. Alligation method for averages

**Idea:** Ratio of counts $n_1 : n_2 = (A_2 - A_{\text{comb}}) : (A_{\text{comb}} - A_1)$.

**Example:** The average salary of 60 employees is Rs 12000. Officers earn an average of Rs 20000 and non-officers earn Rs 10000. Find the number of officers.
- Ratio Officers : Non-officers $= (12000 - 10000) : (20000 - 12000) = 2000 : 8000 = 1 : 4$.
- Number of officers $= \dfrac{1}{5} \times 60$ = **12**.

## 5. Before you practise

**Your turn:** Six students have an average score of 12. Five scores add up to 55. Find the sixth score.

**Think it through:** the group total is $6 \times 12=72$, so the missing score is $72-55=\mathbf{17}$. Check: $55+17=72$, and $72\div6=12$.

### Quick revision

- Turn an average into a total with $\text{total}=\text{average}\times\text{count}$.
- If a group changes, calculate the old and new totals separately; their difference is the person or value added or removed.
- For combined groups, add their totals first, then divide by the combined count.
- For an AP, the average lies at its middle (or halfway between the middle pair).

### Common mistakes

1. Averaging group averages without weighting by the group sizes.
2. Using the old count after someone joins or leaves.
3. Reversing the correction: add correct-minus-wrong, not wrong-minus-correct.
4. Counting an overlapping middle value twice without subtracting the overall total.

## 6. Practice

1. The average of 8 numbers is 14. If seven of them are 12, 15, 11, 18, 10, 16, and 13, find the eighth number.
2. The average monthly income of a person for 12 months is Rs 8500. What is the total annual income?
3. Find the average of the first 15 positive multiples of 6.
4. A class of 20 boys has an average score of 75, and a class of 30 girls has an average score of 85. Find the combined average score.
5. A batsman scored at an average of 45 in 6 matches of tournament A and at an average of 55 in 4 matches of tournament B. What is his overall average?
6. Three sections of a grade with 25, 35, and 40 students have average marks of 60, 70, and 80 respectively. What is the average mark of the entire grade?
7. The average age of 29 students is 14 years. If the teacher age is included, the average increases by 1 year. Find the age of the teacher.
8. The average weight of 15 members in a club is 62 kg. A new member joins and the average becomes 61 kg. Find the weight of the new member.
9. The average score of 11 players is 32. When the coach score is added, the average increases by 3 runs. What did the coach score?
10. The average weight of 25 students is 48 kg. If the teacher weight is excluded from a group of 26 (including teacher), the average drops from 50 kg to 48 kg. What is the teacher weight?
11. The average of 10 numbers is 38. If one number is excluded, the average of the remaining numbers becomes 36. Find the excluded number.
12. The average age of 6 members is 22 years. If the youngest member aged 7 years is excluded, what is the average age of the remaining members?
13. The average weight of 8 persons increases by 2.5 kg when a person weighing 56 kg is replaced by a new person. Find the weight of the new person.
14. The average age of 12 men decreases by 1.5 years when two men aged 28 and 32 are replaced by two women. What is the average age of the two women?
15. A group of 10 persons has an average weight. When one person weighing 70 kg is replaced by a newcomer, the average decreases by 2 kg. Find the weight of the newcomer.
16. The average of 20 numbers was calculated as 35. Later it was found that a number 42 was misread as 24. Find the correct average.
17. The average marks of 40 students was found to be 68. Later it was discovered that two marks 84 and 46 were wrongly entered as 48 and 64. What is the correct average?
18. The mean of 50 items was 40. Later it was noted that an item 73 was misread as 23, and another item 38 was misread as 88. Find the true mean.
19. The average of 13 numbers is 60. The average of the first 7 numbers is 57 and that of the last 7 numbers is 65. Find the 7th number.
20. The average of 9 observations is 45. The average of the first 4 is 42 and the average of the last 4 is 48. Find the 5th observation.
21. The average of 15 numbers is 30. The average of the first 8 numbers is 27 and that of the last 8 numbers is 32. Find the middle (8th) number.
22. The average of 7 consecutive natural numbers is 20. Find the largest number.
23. The average of 4 consecutive even numbers is 27. Find the product of the smallest and largest numbers.
24. The average of 9 consecutive odd numbers is 53. Find the least odd number.
25. A batsman has a certain average for 11 innings. In the 12th inning, he scores 90 runs and thereby increases his average by 5 runs. Find his new average.
26. A batsman has a batting average of 42 runs in 19 innings. How many runs must he score in the 20th inning to increase his average to 45?
27. A cricketer whose bowling average is 24.85 runs per wicket takes 5 wickets for 52 runs in his last match and decreases his average by 0.85. Find the total number of wickets taken before the last match.
28. 10 friends went to a hotel. 9 of them spent Rs 40 each on their meal, and the 10th spent Rs 18 more than the average of all 10. Find the total expenditure of all 10 friends.
29. 6 persons went for lunch. 5 of them spent Rs 32 each and the 6th spent Rs 80 more than the average of all six. What was the total amount spent?
30. 5 years ago, the average age of a family of 4 members was 21 years. A baby was born, and today the average age of the family is still 21 years. Find the present age of the baby.
31. The average age of husband and wife was 23 years at the time of their marriage 5 years ago. The average age of husband, wife, and a child born during the interval is 20 years today. Find the child age.
32. In an exam, the average marks of all 120 candidates was 35. The average of passed candidates was 39 and failed candidates was 15. How many candidates passed?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 17 | $8 \times 14 - (12+15+11+18+10+16+13) = 112 - 95$ |
| 2 | Rs 1,02,000 | $12 \times 8500$ |
| 3 | 48 | $\frac{6 \times (1 + 15)}{2} = \frac{6 \times 16}{2}$ |
| 4 | 81 | $\frac{20 \times 75 + 30 \times 85}{50} = \frac{1500 + 2550}{50}$ |
| 5 | 49 | $\frac{6 \times 45 + 4 \times 55}{10} = \frac{270 + 220}{10}$ |
| 6 | 71.5 | $\frac{25 \times 60 + 35 \times 70 + 40 \times 80}{100} = \frac{1500 + 2450 + 3200}{100}$ |
| 7 | 44 years | $14 + 30 \times 1 = 44$ |
| 8 | 46 kg | $62 - 16 \times 1 = 46$ |
| 9 | 68 | $32 + 12 \times 3 = 68$ |
| 10 | 100 kg | $26 \times 50 - 25 \times 48 = 1300 - 1200$ |
| 11 | 56 | $10 \times 38 - 9 \times 36 = 380 - 324$ |
| 12 | 25 years | $\frac{6 \times 22 - 7}{5} = \frac{125}{5}$ |
| 13 | 76 kg | $56 + 8 \times 2.5 = 56 + 20$ |
| 14 | 21 years | $\frac{(28 + 32) - 12 \times 1.5}{2} = \frac{60 - 18}{2}$ |
| 15 | 50 kg | $70 - 10 \times 2$ |
| 16 | 35.9 | $35 + \frac{42 - 24}{20} = 35 + 0.9$ |
| 17 | 68.45 | $68 + \frac{(84 + 46) - (48 + 64)}{40} = 68 + \frac{18}{40}$ |
| 18 | 40 | $40 + \frac{(73 - 23) + (38 - 88)}{50} = 40 + \frac{50 - 50}{50}$ |
| 19 | 74 | $7 \times 57 + 7 \times 65 - 13 \times 60 = 399 + 455 - 780$ |
| 20 | 45 | $9 \times 45 - (4 \times 42 + 4 \times 48) = 405 - 360$ |
| 21 | 22 | $8 \times 27 + 8 \times 32 - 15 \times 30 = 216 + 256 - 450$ |
| 22 | 23 | Middle is $20$; $20 + 3 = 23$ |
| 23 | 720 | Numbers: $24, 26, 28, 30$; $24 \times 30 = 720$ |
| 24 | 45 | $53 - (9 - 1) = 53 - 8 = 45$ |
| 25 | 35 | $90 - 11 \times 5 = 35$ |
| 26 | 102 | $45 + 19 \times (45 - 42) = 45 + 57$ |
| 27 | 80 | $24.85w + 52 = 24.00(w + 5) \implies 0.85w = 68 \implies w = 80$ |
| 28 | Rs 420 | $\text{Avg} = 40 + \frac{18}{9} = 42$; $10 \times 42 = 420$ |
| 29 | Rs 288 | $\text{Avg} = 32 + \frac{80}{5} = 48$; $6 \times 48 = 288$ |
| 30 | 1 year | $5 \times 21 - 4 \times (21 + 5) = 105 - 104 = 1$ |
| 31 | 4 years | $3 \times 20 - 2 \times (23 + 5) = 60 - 56 = 4$ |
| 32 | 100 | Ratio: $(35-15):(39-35) = 20:4 = 5:1$; $\frac{5}{6} \times 120 = 100$ |
