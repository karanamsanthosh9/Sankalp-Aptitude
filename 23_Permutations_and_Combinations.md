# Permutations and Combinations

> Read this like a class: before counting, decide what counts as a different outcome.

## 0. Start here: choose or arrange?

Imagine choosing three students for a team, then imagine seating those same three students in a row. The team is unchanged when you swap two names, but the seating is different. That is the heart of this chapter: **selection** ignores order; **arrangement** cares about order. Other questions add rules such as “together,” “never together,” or “at least.”

Start by naming the slots or the group, then check whether changing the order changes the answer. For example, choosing A and B is the same group as choosing B and A, so it is one selection, not two. A useful sense check is that an arrangement count should be at least as large as the corresponding selection count.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Fundamental counting principle and digit formation | 1 |
| Linear arrangements and $^n P_r$ formula | 2 |
| Word arrangements with repeated letters | 3 |
| Items must come together (Tie / Block method) | 4 |
| Items never come together / Gap method | 5 |
| Combinations and selection of groups ($^n C_r$) | 6 |
| Selections with constraints ("at least", "at most", inclusions/exclusions) | 7 |
| Geometry problems (lines, triangles, diagonals, handshakes) | 8 |
| Circular permutations and necklaces | 9 |
| Distribution of identical items (Stars and bars) and division into groups | 10 |
| Rank of a word in dictionary order | 11 |
| Number and sum of factors | 12 |
| Sum of all numbers formed by given digits | 13 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "Without repetition" | Digits or items cannot be reused once chosen |
| "Vowels always together" | Bundle vowels into a single block, permute inside and outside |
| "No two girls sit together" | Place boys first, place girls in the resulting gaps |
| "At least 2 women in committee" | Sum cases: 2 women, 3 women, ..., up to maximum |
| "Particular person is always included" | Pre-place that person, select remaining from $(n-1)$ |
| "Collinear points given" | Subtract invalid lines or triangles formed by collinear set |
| "Seated around a circular table" | Fix 1 person to eliminate rotational symmetry: $(n-1)!$ |
| "Identical coins among children" | Stars and bars: $^{n+r-1}C_{r-1}$ |

## 3. The core idea

- **Permutation:** order matters $\implies ^n P_r = \dfrac{n!}{(n-r)!}$.
- **Combination:** order does not matter $\implies ^n C_r = \dfrac{n!}{r!(n-r)!}$.
- **Multiplication rule (AND):** sequential independent operations multiply ($m \times n$).
- **Addition rule (OR):** mutually exclusive cases add ($m + n$).
- **Complement rule:** $\text{Ways without condition} = \text{Total ways} - \text{Ways with forbidden condition}$.

## 4. Question-type walkthroughs

### Question type 1. Fundamental counting principle and digit formation

**Idea:** fill positional slots from left to right respecting given constraints (zero cannot be the leading digit).

**Example 1:** How many 3-digit numbers can be formed using digits 1, 2, 3, 4, 5 without repetition?
- Hundreds place: 5 choices. Tens place: 4 choices. Units place: 3 choices.
- Total $= 5 \times 4 \times 3 =$ **60**.

**Example 2:** How many 4-digit numbers can be formed using digits 0, 1, 2, 3, 4, 5 without repetition?
- Thousands place: cannot be 0, so 5 choices (1 to 5).
- Hundreds: 5 choices (including 0). Tens: 4 choices. Units: 3 choices.
- Total $= 5 \times 5 \times 4 \times 3 =$ **300**.

### Question type 2. Linear arrangements and $^n P_r$ formula

**Idea:** $n$ distinct objects can be arranged in a line in $n!$ ways; selecting and arranging $r$ objects from $n$ is $^n P_r$.

**Example:** In how many ways can 4 students sit in a row of 7 chairs?
- Choosing and ordering 4 chairs out of 7 is $^7 P_4 = \dfrac{7!}{(7-4)!} = 7 \times 6 \times 5 \times 4$.
- Total $=$ **840**.

### Question type 3. Word arrangements with repeated letters

**Idea:** for $n$ total letters where letter 1 repeats $p$ times, letter 2 repeats $q$ times, total arrangements $= \dfrac{n!}{p!\,q!\,r!\dots}$.

**Example 1:** How many words can be formed from the letters of LEADER?
- Total letters $= 6$; 'E' repeats 2 times.
- $\dfrac{6!}{2!} = \dfrac{720}{2} =$ **360**.

**Example 2:** How many words can be formed from MISSISSIPPI?
- Total letters $= 11$; M: 1, I: 4, S: 4, P: 2.
- $\dfrac{11!}{4!\,4!\,2!} = \dfrac{39916800}{24 \times 24 \times 2} =$ **34650**.

### Question type 4. Items must come together (Tie / Block method)

**Idea:** treat the items that must stay together as a single super-item. Permute the resulting items, then multiply by the internal permutations of the block.

**Example:** In how many ways can the letters of EQUATION be arranged so that all vowels are together?
- Vowels (E, U, A, I, O): 5. Consonants (Q, T, N): 3.
- Bundle 5 vowels into 1 block. Total units to arrange: 3 consonants $+ 1\text{ block} = 4\text{ units}$.
- Units arrange in $4! = 24$ ways; vowels inside block arrange in $5! = 120$ ways.
- Total $= 24 \times 120 =$ **2880**.

### Question type 5. Items never come together / Gap method

**Idea:** either subtract "all together" from total, or arrange unrestricted items first and place restricted items into the available gaps.

**Example 1 (total minus together):** In how many ways can letters of LEADING be arranged such that vowels never come together?
- Total arrangements of 7 letters $= 7! = 5040$.
- Vowels (E, A, I) together: bundle as 1 unit with 4 consonants $\implies 5! \times 3! = 120 \times 6 = 720$.
- Never together $= 5040 - 720 =$ **4320**.

**Example 2 (gap method - no two together):** In how many ways can 5 boys and 4 girls sit in a row such that no two girls sit together?
- Arrange 5 boys first: $5! = 120$ ways.
- Number of gaps created around 5 boys: $5 + 1 = 6$ gaps.
- Place 4 girls into 6 gaps: $^6 P_4 = 6 \times 5 \times 4 \times 3 = 360$ ways.
- Total $= 120 \times 360 =$ **43200**.

### Question type 6. Combinations and selection of groups ($^n C_r$)

**Idea:** when order of selection does not matter, use $^n C_r = \dfrac{n!}{r!(n-r)!}$.

**Example:** Out of 7 men and 6 women, a committee of 5 is to be formed consisting of 3 men and 2 women. How many ways?
- Ways to select 3 men from 7: $^7 C_3 = \dfrac{7 \times 6 \times 5}{3 \times 2 \times 1} = 35$.
- Ways to select 2 women from 6: $^6 C_2 = \dfrac{6 \times 5}{2 \times 1} = 15$.
- Total $= 35 \times 15 =$ **525**.

### Question type 7. Selections with constraints

**Idea:** split into mutually exclusive cases for "at least" or "at most"; reduce available pool for fixed inclusions or exclusions.

**Example:** From 6 men and 4 women, a committee of 5 is formed with at least 3 men. How many ways?
- Case 1 (3 men, 2 women): $^6 C_3 \times ^4 C_2 = 20 \times 6 = 120$.
- Case 2 (4 men, 1 woman): $^6 C_4 \times ^4 C_1 = 15 \times 4 = 60$.
- Case 3 (5 men, 0 women): $^6 C_5 \times ^4 C_0 = 6 \times 1 = 6$.
- Total $= 120 + 60 + 6 =$ **186**.

### Question type 8. Geometry problems

**Idea:** straight lines from $n$ points $= ^n C_2$; triangles $= ^n C_3$; diagonals of $n$-sided polygon $= ^n C_2 - n = \dfrac{n(n-3)}{2}$; handshakes $= ^n C_2$.

**Example 1:** How many diagonals does an octagon (8 sides) have?
- $\dfrac{8(8-3)}{2} = \dfrac{8 \times 5}{2} =$ **20**.

**Example 2:** There are 12 points in a plane, of which 5 are collinear. How many triangles can be formed?
- Total triangles without collinearity $= ^{12} C_3 = \dfrac{12 \times 11 \times 10}{6} = 220$.
- Collinear points cannot form triangles: $^5 C_3 = 10$.
- Valid triangles $= 220 - 10 =$ **210**.

### Question type 9. Circular permutations and necklaces

**Idea:** $n$ distinct objects in a circle $= (n-1)!$. If clockwise and counter-clockwise arrangements are identical (necklaces, garlands), divide by 2: $\dfrac{(n-1)!}{2}$.

**Example 1:** In how many ways can 6 people sit around a circular table?
- $(6 - 1)! = 5! =$ **120**.

**Example 2:** In how many ways can 8 different beads be strung into a necklace?
- $\dfrac{(8-1)!}{2} = \dfrac{7!}{2} = \dfrac{5040}{2} =$ **2520**.

### Question type 10. Distribution of items (Stars and bars) and division

**Idea:** distributing $n$ identical items into $r$ distinct bins gives $^{n+r-1}C_{r-1}$ ways (non-negative) or $^{n-1}C_{r-1}$ ways (each gets at least 1).

**Example:** In how many ways can 10 identical coins be distributed among 3 children so that each gets at least 1 coin?
- Stars and bars for positive integers: $^{10-1} C_{3-1} = ^9 C_2 = \dfrac{9 \times 8}{2} =$ **36**.

### Question type 11. Rank of a word in dictionary order

**Idea:** list letters in alphabetical order, count words starting with preceding letters, then step through prefix matches.

**Example:** What is the rank of the word RANK in a dictionary?
- Letters in alphabetical order: A, K, N, R.
- Words starting with A: $3! = 6$.
- Words starting with K: $3! = 6$.
- Words starting with N: $3! = 6$.
- Words starting with R: alphabetical order gives RAKN (1st), RANK (2nd).
- Rank $= 6 + 6 + 6 + 2 =$ **20**.

### Question type 12. Number and sum of factors

**Idea:** for $N = p_1^{a} p_2^{b} p_3^{c}$, total factors $= (a+1)(b+1)(c+1)$.

**Example:** Find the total number of factors of 360.
- Prime factorisation: $360 = 2^3 \times 3^2 \times 5^1$.
- Total factors $= (3+1)(2+1)(1+1) = 4 \times 3 \times 2 =$ **24**.

### Question type 13. Sum of all numbers formed by given digits

**Idea:** sum of all $n$-digit numbers formed by $n$ distinct non-zero digits without repetition $= (\text{Sum of digits}) \times (n-1)! \times \underbrace{11\dots 1}_{n\text{ ones}}$.

**Example:** Find the sum of all 3-digit numbers formed using digits 1, 2, 3 without repetition.
- Sum of digits $= 1 + 2 + 3 = 6$.
- Formula: $6 \times (3-1)! \times 111 = 6 \times 2 \times 111 =$ **1332**.

## 5. Before you practise

**Your turn:** From 6 students, how many different 2-person teams can you choose? How many 2-person line-ups can you make?

**Think it through:** For a team, order does not matter: $\binom{6}{2}=15$. For a line-up, first choose the first person (6 choices), then the second (5): $6\times5=30$. The arrangement count is twice the team count because each team can line up in two orders.

### Quick revision

- Selection: order does not matter, so use combinations.
- Arrangement: order matters, so use permutations.
- “Together” often means make a block; “no two together” often means arrange the others first and use gaps.
- “At least” and “at most” usually mean split into non-overlapping cases or use a complement.

### Common mistakes

1. Counting the same committee more than once by treating its members as ordered.
2. Forgetting the leading-zero restriction when making numbers.
3. Forgetting to arrange the objects inside a block.
4. Using combinations for placing distinct objects into positions.
5. Applying stars and bars before checking whether each recipient must get at least one.

## 6. Practice

1. How many 3-digit numbers can be formed using digits 1, 2, 3, 4, 5 without repetition?
2. How many 4-digit numbers can be formed using digits 0, 1, 2, 3, 4, 5 without repetition?
3. How many 3-digit even numbers can be formed using digits 1, 2, 3, 4, 5 without repetition?
4. In how many ways can 5 books be arranged on a shelf?
5. In how many ways can 4 students be seated in a row of 7 chairs?
6. In how many ways can the letters of the word LEADER be arranged?
7. In how many ways can the letters of the word MATHEMATICS be arranged?
8. In how many ways can the letters of the word DETAIL be arranged so that vowels occupy odd positions?
9. In how many ways can the letters of the word OPTICAL be arranged so that the vowels always come together?
10. In how many ways can 4 boys and 3 girls sit in a row such that all girls sit together?
11. In how many ways can the letters of the word LEADING be arranged such that vowels never come together?
12. In how many ways can 5 boys and 4 girls sit in a row such that no two girls sit together?
13. In how many ways can a committee of 5 be chosen from 9 people?
14. Out of 7 men and 6 women, a committee of 5 is to be formed with 3 men and 2 women. In how many ways can this be done?
15. Out of 5 red and 4 blue balls, 3 balls are drawn. In how many ways can exactly 2 red and 1 blue ball be drawn?
16. From a group of 6 men and 4 women, a committee of 4 is to be formed containing at least 2 women. In how many ways?
17. In how many ways can a team of 4 be chosen from 8 players if a particular player is always included?
18. In how many ways can a team of 4 be chosen from 8 players if a particular player is always excluded?
19. There are 10 points in a plane, of which no 3 are collinear. How many straight lines can be formed?
20. There are 12 points in a plane, of which 5 are collinear. How many triangles can be formed?
21. How many diagonals does a regular polygon with 10 sides (decagon) have?
22. At a party, 15 people shake hands with each other once. How many handshakes take place?
23. In how many ways can 6 people be seated around a circular table?
24. In how many ways can 5 boys and 5 girls sit around a round table such that boys and girls alternate?
25. In how many ways can 8 different beads be strung into a necklace?
26. In how many ways can 10 identical coins be distributed among 3 children so that each child may get any number of coins?
27. In how many ways can 12 identical apples be distributed among 4 boys such that each boy gets at least 1 apple?
28. In how many ways can 9 different toys be divided equally among 3 children?
29. What is the rank of the word MOTHER in a dictionary?
30. Find the total number of factors (divisors) of 720.
31. Find the number of even factors of 720.
32. What is the sum of all 4-digit numbers that can be formed using digits 1, 2, 3, 4 without repetition?
33. How many 4-letter words (with or without meaning) can be formed using letters of LOGARITHMS without repetition?
34. In how many ways can a student choose 5 questions out of 8 if questions 1 and 2 are compulsory?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 60 | $5 \times 4 \times 3 = 60$ |
| 2 | 300 | Thousands place has 5 choices; $5 \times 5 \times 4 \times 3 = 300$ |
| 3 | 24 | Units place in 2 ways (2 or 4); first two in $4 \times 3 = 12$ ways; $12 \times 2 = 24$ |
| 4 | 120 | $5! = 120$ |
| 5 | 840 | $^7 P_4 = 7 \times 6 \times 5 \times 4 = 840$ |
| 6 | 360 | $\frac{6!}{2!} = \frac{720}{2} = 360$ |
| 7 | 4989600 | $\frac{11!}{2!\,2!\,2!} = \frac{39916800}{8} = 4989600$ |
| 8 | 36 | 3 vowels in 3 odd positions ($3! = 6$), 3 consonants in 3 even positions ($3! = 6$); $6 \times 6 = 36$ |
| 9 | 720 | Block of 3 vowels + 4 consonants: $5! \times 3! = 120 \times 6 = 720$ |
| 10 | 720 | Block of 3 girls + 4 boys: $5! \times 3! = 120 \times 6 = 720$ |
| 11 | 4320 | $\text{Total} - \text{together} = 7! - (5! \times 3!) = 5040 - 720 = 4320$ |
| 12 | 43200 | 5 boys in $5! = 120$ ways; 4 girls in 6 gaps = $^6 P_4 = 360$; $120 \times 360 = 43200$ |
| 13 | 126 | $^9 C_5 = \frac{9 \times 8 \times 7 \times 6}{4 \times 3 \times 2 \times 1} = 126$ |
| 14 | 525 | $^7 C_3 \times ^6 C_2 = 35 \times 15 = 525$ |
| 15 | 40 | $^5 C_2 \times ^4 C_1 = 10 \times 4 = 40$ |
| 16 | 115 | $^4 C_2 \times ^6 C_2 + ^4 C_3 \times ^6 C_1 + ^4 C_4 \times ^6 C_0 = 90 + 24 + 1 = 115$ |
| 17 | 35 | Must pick 3 from remaining 7: $^7 C_3 = 35$ |
| 18 | 35 | Must pick 4 from remaining 7: $^7 C_4 = 35$ |
| 19 | 45 | $^{10} C_2 = \frac{10 \times 9}{2} = 45$ |
| 20 | 210 | $^{12} C_3 - ^5 C_3 = 220 - 10 = 210$ |
| 21 | 35 | $^{10} C_2 - 10 = 45 - 10 = 35$ |
| 22 | 105 | $^{15} C_2 = \frac{15 \times 14}{2} = 105$ |
| 23 | 120 | $(6 - 1)! = 5! = 120$ |
| 24 | 2880 | Fix boys in $(5-1)! = 24$ ways; girls in 5 gaps in $5! = 120$ ways; $24 \times 120 = 2880$ |
| 25 | 2520 | $\frac{(8 - 1)!}{2} = \frac{5040}{2} = 2520$ |
| 26 | 66 | $^{10 + 3 - 1} C_{3 - 1} = ^{12} C_2 = 66$ |
| 27 | 165 | $^{12 - 1} C_{4 - 1} = ^{11} C_3 = 165$ |
| 28 | 1680 | $\frac{9!}{(3!)^3} = \frac{362880}{216} = 1680$ |
| 29 | 309 | $2(5!) + 2(4!) + 3(3!) + 3 = 240 + 48 + 18 + 3 = 309$ |
| 30 | 30 | $720 = 2^4 \times 3^2 \times 5^1 \implies (4+1)(2+1)(1+1) = 30$ |
| 31 | 24 | $4 \times (2+1) \times (1+1) = 4 \times 3 \times 2 = 24$ |
| 32 | 66660 | $(1+2+3+4) \times (4-1)! \times 1111 = 10 \times 6 \times 1111 = 66660$ |
| 33 | 5040 | $^{10} P_4 = 10 \times 9 \times 8 \times 7 = 5040$ |
| 34 | 20 | Choose remaining 3 from 6: $^6 C_3 = 20$ |
