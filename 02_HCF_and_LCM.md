# HCF and LCM

> Read this like a class, not like a formula list. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" boxes with a pen before reading the answer next to them.

## 0. Start here: what is this topic really about?

Imagine you have two pieces of rope — one 48 cm long and one 72 cm long. You want to cut both into equal pieces without any waste. What is the longest piece you can cut? That is the **HCF**.

Now imagine two buses leave the same stop — one every 12 minutes and the other every 18 minutes. How long before they depart together again? That is the **LCM**.

Both ideas come from the same source: **how numbers share factors**. HCF is about the largest factor they share. LCM is about the smallest multiple they share.

Questions in the exam look like these:

- "Find the HCF and LCM of 48 and 72."
- "Three bells ring at 6, 8, 12 minute intervals. When do they ring together?"
- "Find the largest number that divides 245, 1029 and 1365 leaving the same remainder."
- "Two numbers have HCF 12 and LCM 180. One number is 36. Find the other."
- "A floor of 525 cm × 315 cm is to be tiled with the largest possible square tiles. How many tiles?"

**What the exam gives you:** two or more numbers, or a clue about their HCF or LCM, sometimes a word problem about tiles, ropes, bells or sharing. **What it asks for:** the HCF, the LCM, a missing number, or a count of objects.

**How many marks to expect:** SSC CGL, CHSL and RRB NTPC carry 1 to 3 questions. IBPS and SBI carry 1 to 2 questions, sometimes hidden inside Data Interpretation. APPSC and PSU papers carry 2 to 3 questions. Together, HCF and LCM are among the most reliable sources of quick marks.

## 1. The only ideas you must understand

### What is HCF?

The **Highest Common Factor** (also called GCD, Greatest Common Divisor) of two numbers is the largest number that divides both of them exactly.

Picture it: the factors of 48 are 1, 2, 3, 4, 6, 8, 12, 16, 24, 48. The factors of 72 are 1, 2, 3, 4, 6, 8, 9, 12, 18, 24, 36, 72. The common ones are 1, 2, 3, 4, 6, 8, 12, 24. The **largest** is 24. So $\text{HCF}(48, 72) = 24$.

### What is LCM?

The **Lowest Common Multiple** is the smallest number that both numbers divide into exactly.

The multiples of 12 are 12, 24, 36, 48, 60, 72 … The multiples of 18 are 18, 36, 54, 72 … The first one they share is 36. So $\text{LCM}(12, 18) = 36$.

### The golden rule connecting HCF and LCM

For **any two** numbers $a$ and $b$:

$$\text{HCF}(a, b) \times \text{LCM}(a, b) = a \times b$$

**This rule is true for exactly two numbers. It does NOT extend to three or more numbers.** Exams set traps on this.

**Sense check:** always verify using this rule. If you found HCF = 24 and LCM = 144 for 48 and 72, check: $24 \times 144 = 3456 = 48 \times 72$. Correct.

### Your turn

$\text{HCF}(36, 48) = 12$. Find $\text{LCM}(36, 48)$. (Answer: $\frac{36 \times 48}{12} = $ **144**.)

## 2. The shortcuts that save 30 seconds in every question

### Finding HCF: the division method (Euclidean algorithm)

Divide the larger number by the smaller. Then divide the divisor by the remainder. Keep going until the remainder is 0. The last non-zero divisor is the HCF.

**Example:** $\text{HCF}(84, 112)$.
- $112 = 84 \times 1 + 28$
- $84 = 28 \times 3 + 0$
- Remainder is 0. HCF = **28**.

**Why this works:** any factor of both 112 and 84 must also be a factor of $112 - 84 = 28$. The algorithm peels away layers until only the HCF is left.

### Finding LCM: the common division method

Divide repeatedly by prime numbers until all quotients are 1. Multiply all the divisors together.

**Example:** $\text{LCM}(12, 18, 24)$.

```
2 | 12  18  24
2 |  6   9  12
2 |  3   9   6
3 |  3   9   3
3 |  1   3   1
  |  1   1   1
```

$\text{LCM} = 2 \times 2 \times 2 \times 3 \times 3 = $ **72**.

### Finding HCF and LCM from prime factorisation

**Prime factorise each number.** Then:
- **HCF:** take each prime to the **lowest** power it appears in any number.
- **LCM:** take each prime to the **highest** power it appears in any number.

**Example:** HCF and LCM of 36 and 60.
- $36 = 2^2 \times 3^2$, $60 = 2^2 \times 3 \times 5$.
- HCF: $2^2 \times 3^1 = 12$.
- LCM: $2^2 \times 3^2 \times 5 = 180$.

### HCF and LCM of fractions

$$\text{HCF of fractions} = \frac{\text{HCF of numerators}}{\text{LCM of denominators}}$$

$$\text{LCM of fractions} = \frac{\text{LCM of numerators}}{\text{HCF of denominators}}$$

**Example:** $\text{HCF}\!\left(\dfrac{3}{5}, \dfrac{6}{7}, \dfrac{9}{14}\right)$.
- HCF of 3, 6, 9 = 3. LCM of 5, 7, 14 = 70. Answer: $\dfrac{3}{70}$.

**Example:** $\text{LCM}\!\left(\dfrac{2}{3}, \dfrac{4}{9}, \dfrac{8}{27}\right)$.
- LCM of 2, 4, 8 = 8. HCF of 3, 9, 27 = 3. Answer: $\dfrac{8}{3}$.

### Your turn

Find $\text{LCM}\!\left(\dfrac{3}{4}, \dfrac{5}{8}, \dfrac{7}{12}\right)$. (LCM of 3, 5, 7 = 105; HCF of 4, 8, 12 = 4. **Answer: $\frac{105}{4}$**.)

## 3. Types of questions and how to crack each one

### Type 1. Find HCF and LCM of given numbers

**How you spot it:** "Find the HCF and LCM of 48 and 72."

**Think:** use the division method for HCF, then use $\text{LCM} = \frac{a \times b}{\text{HCF}}$ for two numbers.

**Solved example:** HCF and LCM of 84 and 112.
- $112 = 84 \times 1 + 28$; $84 = 28 \times 3 + 0$. **HCF = 28**.
- $\text{LCM} = \frac{84 \times 112}{28} = $ **336**.
- Check: $28 \times 336 = 9408 = 84 \times 112$. Correct.

**Your turn:** find HCF and LCM of 36 and 48. (HCF = 12; LCM = $36 \times 48 / 12$ = **144**.)

### Type 2. Find a missing number given HCF, LCM and one number

**How you spot it:** "HCF of two numbers is 12, LCM is 144, one number is 36. Find the other."

**Think:** use $a \times b = \text{HCF} \times \text{LCM}$.

**Solved example:** HCF = 12, LCM = 144, first number = 36.
- Other number $= \frac{12 \times 144}{36} = $ **48**.
- Check: $\text{HCF}(36, 48) = 12$, $\text{LCM}(36, 48) = 144$. Correct.

**Exam twist:** "The product of two numbers is 2028 and their HCF is 13. Find their LCM."
- $\text{LCM} = \frac{2028}{13} = $ **156**.

**Your turn:** HCF of two numbers is 8, LCM is 240, one number is 40. Find the other. ($\frac{8 \times 240}{40} = $ **48**. Check: HCF(40,48) = 8, LCM(40,48) = 240.)

### Type 3. Largest number that divides given numbers leaving the same remainder

**How you spot it:** "Find the largest number that divides 245, 1029, and 1365 leaving the same remainder."

**Think:** if all three numbers leave the same remainder when divided by $N$, then the differences between any two numbers are exactly divisible by $N$. So $N = \text{HCF}$ of all pairwise differences.

**Solved example:** numbers 245, 1029, 1365.
- Differences: $1029 - 245 = 784$; $1365 - 1029 = 336$; $1365 - 245 = 1120$.
- $\text{HCF}(784, 336, 1120)$:
  - $\text{HCF}(784, 336)$: $784 = 336 \times 2 + 112$; $336 = 112 \times 3 + 0$. HCF = 112.
  - $\text{HCF}(112, 1120) = 112$.
- **Largest number = 112**.
- Check: $245 \div 112 = 2$ r 21; $1029 \div 112 = 9$ r 21; $1365 \div 112 = 12$ r 21. All same. Correct.

**Exam twist:** "Largest number that divides 98 and 128, leaving remainder 2 each time."
- Subtract the remainder first: $96$ and $126$. $\text{HCF}(96, 126) = 6$. **Answer: 6**.
- Check: $98 \div 6 = 16$ r 2; $128 \div 6 = 21$ r 2. Correct.

**Your turn:** find the largest number that divides 23, 29, and 41 leaving the same remainder. (Differences: 6, 12, 18. $\text{HCF}(6,12,18) = 6$. **Answer: 6**. Check: $23 \div 6 = 3$ r 5; $29 \div 6 = 4$ r 5; $41 \div 6 = 6$ r 5.)

### Type 4. Smallest number divisible by given numbers / leaving given remainders

**How you spot it:** "Find the smallest number divisible by 4, 5, 6, and 7" or "smallest number that when divided by 4, 5, 6, 7 leaves remainder 3."

**Think:** smallest divisible by all = LCM. If they all leave the same remainder $r$, add $r$ to the LCM.

**Solved example:** smallest number divisible by 4, 5, 6, 7 = $\text{LCM}(4,5,6,7) = 420$.

**Solved example:** smallest number that when divided by 5, 6, 7, 8 leaves remainder 4.
- $\text{LCM}(5, 6, 7, 8) = 840$.
- Answer: $840 + 4 = $ **844**.
- Check: $844 \div 5 = 168$ r 4; $844 \div 8 = 105$ r 4. Correct.

**Exam twist:** "smallest number that when divided by 2, 3, 4, 5 leaves remainder 1, and is divisible by 7."
- $\text{LCM}(2,3,4,5) = 60$; numbers: $61, 121, 181, 241, 301, \ldots$
- $301 \div 7 = 43$, no remainder. **Answer: 301**.

**Your turn:** smallest number divisible by 4, 6, 8, 10, 12? ($\text{LCM}(4,6,8,10,12) = $ **120**.)

### Type 5. HCF and LCM of fractions

**How you spot it:** "Find the HCF of $\frac{3}{5}$, $\frac{6}{7}$, $\frac{9}{14}$."

**Think:** use the formula: $\text{HCF} = \frac{\text{HCF of numerators}}{\text{LCM of denominators}}$ and $\text{LCM} = \frac{\text{LCM of numerators}}{\text{HCF of denominators}}$.

**Solved example:** $\text{HCF}\!\left(\dfrac{3}{5}, \dfrac{6}{7}, \dfrac{9}{14}\right)$.
- HCF(3, 6, 9) = 3. LCM(5, 7, 14) = 70.
- **HCF = $\frac{3}{70}$.**

**Solved example:** $\text{LCM}\!\left(\dfrac{2}{3}, \dfrac{4}{9}, \dfrac{8}{27}\right)$.
- LCM(2, 4, 8) = 8. HCF(3, 9, 27) = 3.
- **LCM = $\frac{8}{3}$.**

**Your turn:** find HCF of $\frac{3}{4}$, $\frac{5}{8}$, $\frac{7}{12}$. (HCF(3,5,7)=1; LCM(4,8,12)=24. **Answer: $\frac{1}{24}$**.)

### Type 6. Tiles, ropes, or equal pieces (HCF word problem)

**How you spot it:** "A floor of 525 cm × 315 cm is to be tiled with the largest possible square tiles. How many tiles are needed?"

**Think:** the tile side = HCF of the floor dimensions (to fit exactly without cutting). Number of tiles = (length / side) × (width / side).

**Solved example:** floor 525 cm × 315 cm.
- $\text{HCF}(525, 315)$: $525 = 315 \times 1 + 210$; $315 = 210 \times 1 + 105$; $210 = 105 \times 2 + 0$. HCF = **105**.
- Tiles: $(525/105) \times (315/105) = 5 \times 3 = $ **15 tiles**.

**Solved example:** floor 528 cm × 252 cm.
- $\text{HCF}(528, 252) = 12$. Tiles $= 44 \times 21 = $ **924 tiles**.

**Your turn:** a room 429 cm × 143 cm is to be tiled with the largest possible square tiles. How many tiles? ($\text{HCF}(429,143)$: $429 = 143 \times 3 + 0$. HCF = 143. Tiles $= (429/143) \times (143/143) = 3 \times 1 = $ **3 tiles**.)

### Type 7. Bells, traffic lights, circular motion (LCM word problem)

**How you spot it:** "Three bells ring at intervals of 6, 8, and 18 minutes. They ring together at noon. When do they next ring together?"

**Think:** they ring together after LCM minutes.

**Solved example:** intervals 6, 8, 18.
- $\text{LCM}(6, 8, 18) = 72$ minutes.
- They ring together again **72 minutes after noon**, i.e., at 1:12 pm.

**Solved example:** intervals 20, 28, 35.
- $\text{LCM}(20, 28, 35) = 140$ minutes.

**Exam twist:** "4 bells ring at 4, 6, 8, 10, 12 seconds. How many times do they ring together in 3 hours?"
- $\text{LCM}(4,6,8,10,12) = 120$ seconds.
- 3 hours = 10800 seconds.
- Times: $10800 \div 120 = $ **90 times** (not counting the start).

**Your turn:** two buses leave the same stop, one every 20 minutes and one every 28 minutes. They leave together at 8 am. When is the next time they leave together? ($\text{LCM}(20,28) = 140$ minutes. **Answer: 10:20 am**.)

### Type 8. Numbers in a ratio with a given HCF

**How you spot it:** "Three numbers are in the ratio 2 : 3 : 5 and their HCF is 6. Find their LCM."

**Think:** if the HCF is $h$ and the ratio is $a:b:c$, then the numbers are $ha$, $hb$, $hc$. The LCM is $h \times \text{LCM}(a,b,c)$.

**Solved example:** ratio 2:3:5, HCF = 6.
- Numbers: 12, 18, 30.
- $\text{LCM}(2,3,5) = 30$. $\text{LCM}(12,18,30) = 6 \times 30 = $ **180**.

**Solved example:** ratio 3:4:5, HCF = 4. Numbers = 12, 16, 20.
- LCM(12, 16, 20) = **240**.
- Sum = $12 + 16 + 20 = 48$.

**Your turn:** two numbers in ratio 3:4 with HCF = 12. Find their LCM. (Numbers: 36, 48. $\text{LCM}(36,48) = $ **144**.)

### Type 9. Largest / smallest n-digit number divisible by given numbers

**How you spot it:** "Find the largest 3-digit number divisible by both 18 and 24."

**Think:** divisible by both = divisible by LCM. Then apply the "slide to extremes" trick.

**Solved example:** largest 3-digit number divisible by both 18 and 24.
- $\text{LCM}(18, 24) = 72$.
- $999 \div 72 = 13.875$. Largest whole multiple: $13 \times 72 = $ **936**.

**Solved example:** smallest 4-digit number divisible by 8, 10, 12, 14.
- $\text{LCM}(8,10,12,14) = 840$.
- $840 < 1000$; $2 \times 840 = $ **1680**.

**Your turn:** find the largest 4-digit number divisible by 18, 24, and 32. ($\text{LCM}(18,24,32) = 288$. $9999 \div 288 = 34.7$; $34 \times 288 = $ **9792**.)

### Type 10. Smallest number N such that (N + k) is divisible by given numbers

**How you spot it:** "Find the smallest number which when added to 3 is divisible by 5, 7, 9, 11."

**Think:** $N + k = \text{LCM}$, so $N = \text{LCM} - k$.

**Solved example:** $N + 3$ divisible by 5, 7, 9, 11.
- $\text{LCM}(5,7,9,11) = 3465$.
- $N = 3465 - 3 = $ **3462**.

**Solved example:** smallest N such that $(N+1)$ is divisible by 12, 16, 18, 21.
- $\text{LCM}(12,16,18,21) = 1008$.
- $N = 1008 - 1 = $ **1007**.
- Check: $1008 \div 12 = 84$; $1008 \div 21 = 48$. Correct.

**Your turn:** find the smallest number that when increased by 7 is exactly divisible by 12, 16, and 24. ($\text{LCM}(12,16,24) = 48$. $N = 48 - 7 = $ **41**. Check: $48 \div 12 = 4$.)

### Type 11. LCM : HCF ratio problems

**How you spot it:** "The LCM of two numbers is 20 times their HCF. The HCF is 5 and one number is 20. Find the other."

**Think:** $\text{LCM} = 20 \times \text{HCF} = 20 \times 5 = 100$. Then $\text{other} = \frac{\text{HCF} \times \text{LCM}}{\text{one number}}$.

**Solved example:** HCF = 5, LCM = 100, one number = 20.
- Other $= \frac{5 \times 100}{20} = $ **25**.
- Check: $\text{HCF}(20, 25) = 5$, $\text{LCM}(20, 25) = 100$. Correct.

**Solved example:** HCF = 30, LCM = 2310, one number = 210.
- Other $= \frac{30 \times 2310}{210} = $ **330**.
- Check: $\text{HCF}(210, 330) = 30$, $\text{LCM}(210, 330) = 2310$. Correct.

**Your turn:** two numbers have HCF 12 and LCM 720. One number is 144. Find the other. ($\frac{12 \times 720}{144} = $ **60**.)

### Type 12. HCF conditions with sum or difference

**How you spot it:** "The HCF of two numbers is 12 and their sum is 108. Their difference is 12. Find the numbers."

**Think:** let the numbers be $12a$ and $12b$ with $\gcd(a,b)=1$. Then $12a+12b=108$ gives $a+b=9$, and the condition $12a-12b=12$ gives $a-b=1$. Solve to get $a=5$, $b=4$.

**Solved example:** HCF = 12, sum = 108, difference = 12.
- $a + b = 9$, $a - b = 1$. So $a = 5$, $b = 4$.
- Numbers: $12 \times 5 = 60$ and $12 \times 4 = 48$.
- $\text{LCM}(48, 60) = $ **240**.

**Your turn:** HCF of two numbers is 8 and their sum is 88. One possible pair is (24, 64). Find their LCM. ($\text{LCM}(24, 64) = $ **192**. Check: $\text{HCF}(24,64)=8$; $24+64=88$.)

### Type 13. Maximum number of students / groups (equal distribution)

**How you spot it:** "312 boys and 256 girls are to be seated in rows with an equal number in each row. Find the maximum row size."

**Think:** the largest number that divides both counts = HCF.

**Solved example:** 312 boys and 256 girls.
- $\text{HCF}(312, 256)$: $312 = 256 \times 1 + 56$; $256 = 56 \times 4 + 32$; $56 = 32 \times 1 + 24$; $32 = 24 \times 1 + 8$; $24 = 8 \times 3 + 0$. **HCF = 8**.
- Rows of boys: $312/8 = 39$. Rows of girls: $256/8 = 32$.

**Your turn:** a man has 429 apples and 273 oranges. He wants to pack them in boxes with the same number of each fruit in every box. Maximum number of apples per box? ($\text{HCF}(429, 273)$: $429 = 273 \times 1 + 156$; $273 = 156 \times 1 + 117$; $156 = 117 \times 1 + 39$; $117 = 39 \times 3 + 0$. HCF = 39. **Answer: 39 apples per box**.)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Find HCF | Division method: keep dividing until remainder is 0 |
| Find LCM for two numbers | $\text{LCM} = \frac{a \times b}{\text{HCF}(a,b)}$ |
| Find LCM for many numbers | Common division method |
| Given HCF, LCM and one number | Other $= \frac{\text{HCF} \times \text{LCM}}{\text{one number}}$ |
| Same remainder, find divisor | HCF of all pairwise differences |
| Specific remainder, find smallest N | $\text{LCM} + r$ |
| (N + k) divisible | $N = \text{LCM} - k$ |
| Tiles / equal pieces | Tile side = HCF of dimensions |
| Bells / buses / circular | Ring together after LCM time |
| Numbers in ratio with HCF | Multiply each ratio part by HCF to get the numbers |
| Largest n-digit divisible | $\lfloor \text{max}/\text{LCM} \rfloor \times \text{LCM}$ |
| Smallest n-digit divisible | Next multiple of LCM $\ge$ smallest n-digit number |
| HCF of fractions | $\frac{\text{HCF of numerators}}{\text{LCM of denominators}}$ |
| LCM of fractions | $\frac{\text{LCM of numerators}}{\text{HCF of denominators}}$ |

### Key number facts to remember

- HCF × LCM = product of **two** numbers (not three or more)
- Numbers in ratio $a:b$ with HCF $h$ → actual numbers $ha$ and $hb$
- If HCF$(a,b) = 1$, then $a$ and $b$ are co-prime and LCM$(a,b) = a \times b$
- LCM of consecutive integers $n$ and $n+1$ is always $n(n+1)$

## 5. Mistakes that cost marks

1. **Extending HCF × LCM = product to three numbers.** This formula works only for two numbers. For three numbers, $\text{HCF} \times \text{LCM} \ne a \times b \times c$.
2. **Forgetting to subtract the remainder before finding HCF.** In "largest divisor leaving remainder 2 in both 98 and 128," subtract 2 first: $\text{HCF}(96, 126) = 6$, not HCF(98,128).
3. **Adding the remainder to the LCM in a "same remainder" question.** When the question says "leaves remainder $r$ each time," the answer is $\text{LCM} + r$, not just LCM.
4. **Wrong formula for fractions.** HCF of fractions = HCF(numerators) / LCM(denominators), not the other way round.
5. **Counting the number of times bells ring together including the start.** Usually the question asks for "how many times after starting." That is $\text{total time} \div \text{LCM}$, without adding 1.
6. **Not checking that gcd(a, b) = 1 when splitting numbers in ratio.** If the ratio is $a:b$, the actual numbers are $ha$ and $hb$, and HCF($a,b$) must equal 1. If it does not, you have not simplified the ratio.
7. **Using addition instead of LCM for "both divisible."** "Divisible by both 6 and 9" means divisible by LCM(6,9) = 18, not by 15.

## 6. Practice questions

Do these on paper. Do the first 10 untimed. Do the next 15 with 90 seconds each. Do the last 15 like an exam.

### Level 1: single idea

1. Find $\text{HCF}(36, 48)$.
2. Find $\text{LCM}(12, 18, 24)$.
3. $\text{HCF}$ of two numbers is 12 and $\text{LCM}$ is 144. One number is 36. Find the other.
4. Find $\text{HCF}\!\left(\dfrac{3}{5}, \dfrac{6}{7}, \dfrac{9}{14}\right)$.
5. Find $\text{LCM}\!\left(\dfrac{2}{3}, \dfrac{4}{9}, \dfrac{8}{27}\right)$.
6. Find the largest number that divides both 98 and 128 leaving remainder 2 each time.
7. Find the largest number that divides 245, 1029, and 1365 leaving the same remainder.
8. Find the smallest number which when divided by 5, 6, 7, and 8 leaves remainder 4 each time.
9. Three numbers in ratio 3:4:5 have HCF 4. Find their LCM.
10. Find $\text{LCM}(4, 6, 8, 10, 12)$.

### Level 2: mixed

11. Two numbers have $\text{HCF} = 8$. Their sum is 88 and one is 24. Find their LCM.
12. A rope of 429 cm is cut into pieces each exactly 13 cm long. How many pieces?
13. Find the smallest number such that when 1 is added it is divisible by 12, 16, 18, and 21.
14. A floor of 528 cm × 252 cm is tiled with the largest possible square tiles. How many tiles are needed?
15. The LCM of two numbers is 2310 and their HCF is 30. One number is 210. Find the other.
16. Two numbers in ratio 3:4 have HCF 12. Find their LCM.
17. Three bells ring at intervals of 20, 28, and 35 minutes. They ring together at 9 am. When do they next ring together?
18. Find the largest 3-digit number divisible by both 18 and 24.
19. Find the smallest 4-digit number divisible by 8, 10, 12, and 14.
20. Find the smallest number such that when divided by 2, 3, 4, and 5 it leaves remainder 1, and is also divisible by 7.
21. 312 boys and 256 girls are arranged in rows of equal size. What is the maximum row size?
22. A number when divided by 12 leaves remainder 7 and when divided by 8 leaves remainder 3. Find the smallest such positive number.
23. Find the other number if $\text{HCF}(a,b) = 12$ and $\text{LCM}(a,b) = 240$ and one number is 48.
24. Three numbers in ratio 2:3:4 have HCF 9. Find their sum.
25. Four bells ring at 6, 8, 12, and 18 second intervals. How many times do they ring together in 3 hours (not counting the start)?

### Level 3: exam style

26. Find $\text{HCF}\!\left(\dfrac{3}{4}, \dfrac{5}{8}, \dfrac{7}{12}\right)$.
27. The product of two numbers is 2028 and their HCF is 13. Find their LCM.
28. Find the largest 4-digit number divisible by 18, 24, and 32.
29. Two numbers have LCM 192 and HCF 8, and their sum is 88. Find the numbers.
30. Find the sum of distinct prime factors of 360.
31. LCM of $x$ and 18 is 36; HCF of $x$ and 18 is 2. Find $x$.
32. Find the HCF of two numbers if their LCM is 144 and they are in ratio 3:4.
33. Find the other number if HCF = 12, LCM = 720, and one number is 144.
34. Find the smallest number that when increased by 7 is exactly divisible by 12, 16, and 24.
35. Three people can complete a circuit in 18, 24, and 32 seconds respectively. When do they all meet at the start if they begin together?
36. A man has 429 apples and 273 oranges. He packs them in identical boxes with the same number of each fruit. What is the maximum number of apples per box?
37. Find the number of integers from 1 to 100 divisible by 3 or 5 (or both).
38. Two numbers in ratio 4:5 have LCM 180. Find their HCF.
39. Find the smallest number which when divided by 9, 12, and 15 leaves remainder 8 each time.
40. The HCF of two numbers is 16 and their LCM is 160. If one number is 32, find the other number and their sum.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | 12 | $48 = 36 \times 1 + 12$; $36 = 12 \times 3 + 0$ |
| 2 | 72 | Common division: $2^3 \times 3^2$ |
| 3 | 48 | $12 \times 144 / 36 = 48$; check $\text{HCF}(36,48)=12$ |
| 4 | $\frac{3}{70}$ | $\text{HCF}(3,6,9)/\text{LCM}(5,7,14) = 3/70$ |
| 5 | $\frac{8}{3}$ | $\text{LCM}(2,4,8)/\text{HCF}(3,9,27) = 8/3$ |
| 6 | 6 | Subtract rem: $\text{HCF}(96,126)=6$; $98\%6=2$ |
| 7 | 112 | Diffs: 784, 336, 1120; $\text{HCF}=112$; rem 21 each |
| 8 | 844 | $\text{LCM}(5,6,7,8)=840$; $840+4$ |
| 9 | 240 | Numbers: 12,16,20; $\text{LCM}(12,16,20)$ |
| 10 | 120 | $2^3 \times 3 \times 5 = 120$ |
| 11 | 192 | Other = 64; $\text{LCM}(24,64) = 192$ |
| 12 | 33 | $429 \div 13$ |
| 13 | 1007 | $\text{LCM}(12,16,18,21)=1008$; $1008-1$ |
| 14 | 924 | $\text{HCF}(528,252)=12$; $(44 \times 21)$ |
| 15 | 330 | $30 \times 2310/210$; check $\text{HCF}(210,330)=30$ |
| 16 | 144 | Numbers: 36, 48; $\text{LCM}(36,48)$ |
| 17 | 11:20 am | $\text{LCM}(20,28,35)=140$ min; $9\text{am}+140\text{min}$ |
| 18 | 936 | $\text{LCM}(18,24)=72$; $13\times72$ |
| 19 | 1680 | $\text{LCM}(8,10,12,14)=840$; $2\times840$ |
| 20 | 301 | $\text{LCM}(2,3,4,5)=60$; $60k+1$ div by 7; $k=5$ gives 301 |
| 21 | 8 | $\text{HCF}(312,256)=8$ |
| 22 | 19 | $N=12a+7=8b+3$; trial $a=1$: $N=19$; $19\%8=3$ |
| 23 | 60 | $12 \times 240/48$; check $\text{HCF}(48,60)=12$ |
| 24 | 81 | Numbers: 18,27,36; sum $=81$ |
| 25 | 150 | $\text{LCM}(6,8,12,18)=72$ s; $3\times3600/72$ |
| 26 | $\frac{1}{24}$ | $\text{HCF}(3,5,7)/\text{LCM}(4,8,12)=1/24$ |
| 27 | 156 | $\text{LCM}=2028/13$ |
| 28 | 9792 | $\text{LCM}(18,24,32)=288$; $34\times288$ |
| 29 | 24 and 64 | $\text{HCF}=8$; let $8a,8b$ with $a+b=11$, $ab=24$: $a=3,b=8$ |
| 30 | 10 | $360=2^3\times3^2\times5$; $2+3+5$ |
| 31 | 4 | $x \times 18 = 2 \times 36 = 72$; $x=4$ |
| 32 | 12 | Numbers $3k$ and $4k$; $\text{LCM}=12k=144 \Rightarrow k=12$; HCF = $k$ = **12** |
| 33 | 60 | $12 \times 720/144$ |
| 34 | 41 | $\text{LCM}(12,16,24)=48$; $48-7$ |
| 35 | 288 seconds | $\text{LCM}(18,24,32)=288$ |
| 36 | 39 | $\text{HCF}(429,273)=39$ |
| 37 | 47 | Div by 3: 33; div by 5: 20; div by 15: 6; $33+20-6$ |
| 38 | 9 | Numbers $4k,5k$; LCM $=20k=180 \Rightarrow k=9$; HCF = $k$ = 9 |
| 39 | 188 | $\text{LCM}(9,12,15)=180$; $180+8$ |
| 40 | 80; sum 112 | $16 \times 160/32=80$; $32+80=112$; $\text{HCF}(32,80)=16$ |
