# Set Theory and Venn Diagrams: Model-wise Notes

## Part 1. What comes from this topic

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Model |
|---|---|
| Find union or intersection of two sets | 1 |
| Three-set union using the inclusion-exclusion formula | 2 |
| Find the count in only one or only two sets (three-set) | 3 |
| Find the count who like/use none of the options | 4 |
| Find the count who like/use at least one | 5 |
| Find a missing intersection value | 6 |
| Subsets, power set, number of subsets | 7 |
| Cartesian product of two sets | 8 |
| Set difference and complement | 9 |
| Word problems with exactly one, exactly two, all three | 10 |
| Relations and ordered pairs | 11 |
| De Morgan's laws and complement of union/intersection | 12 |

## Part 2. What data is usually given

| Data you will see | What it means |
|---|---|
| "$n(A) = 30$" | Set A has 30 elements |
| "$n(A \cap B) = 10$" | 10 elements belong to both A and B |
| "$n(A \cup B) = ?$" | Find the total in either A or B |
| "Neither A nor B" | Elements outside $A \cup B$; subtract from total |
| "At least one of A, B, C" | $n(A \cup B \cup C)$ |
| "Exactly one of A, B, C" | Use the formula: $\sum n(A_i) - 2\sum n(A_i \cap A_j) + 3n(A \cap B \cap C)$ |
| "Exactly two of A, B, C" | $\sum n(A_i \cap A_j) - 3n(A \cap B \cap C)$ |
| "$n(A \times B)$" | Product of cardinalities: $n(A)\times n(B)$ |
| "Proper subsets" | $2^n - 1$, where $n$ is the number of elements |
| "Power set" | Set of all subsets; has $2^n$ elements |

## Part 3. The base idea (read once)

- **Two-set formula:** $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.
- **Three-set formula:** $n(A \cup B \cup C) = n(A)+n(B)+n(C) - n(A \cap B) - n(B \cap C) - n(C \cap A) + n(A \cap B \cap C)$.
- **Only A** (in three-set) $= n(A) - n(A \cap B) - n(A \cap C) + n(A \cap B \cap C)$.
- **Exactly two sets** $= n(A \cap B) + n(B \cap C) + n(C \cap A) - 3\,n(A \cap B \cap C)$.
- **Exactly one set** $= n(A)+n(B)+n(C) - 2[n(A \cap B)+n(B \cap C)+n(C \cap A)] + 3\,n(A \cap B \cap C)$.

## Part 4. Models

### Model 1. Union and intersection of two sets

**Idea:** use $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.

**Example 1:** $n(A)=30$, $n(B)=25$, $n(A \cap B)=10$. Find $n(A \cup B)$.
- $n(A \cup B) = 30 + 25 - 10 =$ **45**.

**Example 2:** $n(A \cup B)=50$, $n(A)=32$, $n(B)=28$. Find $n(A \cap B)$.
- $n(A \cap B) = 32 + 28 - 50 =$ **10**.

### Model 2. Three-set union

**Idea:** $n(A \cup B \cup C) = n(A)+n(B)+n(C) - n(A \cap B) - n(B \cap C) - n(C \cap A) + n(A \cap B \cap C)$.

**Example 1:** $n(A)=40$, $n(B)=35$, $n(C)=30$, $n(A \cap B)=10$, $n(B \cap C)=8$, $n(C \cap A)=6$, $n(A \cap B \cap C)=3$.
- $n(A \cup B \cup C) = 40+35+30 - 10-8-6 + 3 =$ **84**.

**Example 2:** $n(A)=50$, $n(B)=40$, $n(C)=30$, each pairwise intersection $=5$, $n(A \cap B \cap C)=2$.
- $n(A \cup B \cup C) = 50+40+30 - 5-5-5 + 2 =$ **107**.

### Model 3. Only one set or only two sets (three-set)

**Idea:** Only $A = n(A) - n(A \cap B) - n(A \cap C) + n(A \cap B \cap C)$. Exactly two $= \sum(\text{pairwise}) - 3\,n(\text{all three})$.

**Example:** $n(A)=40$, $n(B)=35$, $n(C)=30$, $n(A \cap B)=10$, $n(B \cap C)=8$, $n(C \cap A)=6$, $n(A \cap B \cap C)=3$.
- Only $A = 40 - 10 - 6 + 3 =$ **27**.
- Only $B = 35 - 10 - 8 + 3 =$ **20**.
- Only $C = 30 - 8 - 6 + 3 =$ **19**.
- Exactly two $= (10+8+6) - 3\times3 = 24 - 9 =$ **15**.

### Model 4. How many are in none of the sets

**Idea:** $\text{neither} = \text{total} - n(A \cup B)$ for two sets; subtract $n(A \cup B \cup C)$ from the total for three sets.

**Example 1:** In a survey of 100 people, 60 like tea, 50 like coffee, and 20 like both. How many like neither?
- $n(\text{tea} \cup \text{coffee}) = 60 + 50 - 20 = 90$. Neither $= 100 - 90 =$ **10**.

**Example 2:** 80 students: Maths $= 55$, Science $= 45$, both $= 30$. How many study neither?
- $n(\text{M} \cup \text{S}) = 55 + 45 - 30 = 70$. Neither $= 80 - 70 =$ **10**.

### Model 5. At least one of two or three sets

**Idea:** "at least one" is the same as the union. Use the inclusion-exclusion formula directly.

**Example:** In a class of 40, cricket $= 25$, football $= 20$, both $= 10$. How many play at least one sport?
- $n(\text{C} \cup \text{F}) = 25 + 20 - 10 =$ **35**.
- Neither $= 40 - 35 =$ **5**.

### Model 6. Finding a missing intersection

**Idea:** rearrange the union formula: $n(A \cap B) = n(A) + n(B) - n(A \cup B)$. If neither is given, $n(A \cup B) = \text{total} - \text{neither}$.

**Example:** In a group of 70, 45 read newspaper A, 30 read newspaper B, and 10 read neither. Find $n(A \cap B)$.
- $n(A \cup B) = 70 - 10 = 60$. $n(A \cap B) = 45 + 30 - 60 =$ **15**.

### Model 7. Subsets, proper subsets and power set

**Idea:** a set with $n$ elements has $2^n$ subsets (including the empty set) and $2^n - 1$ proper subsets.

**Example 1:** How many subsets does $\{1, 2, 3, 4\}$ have? How many are proper subsets?
- Total subsets $= 2^4 =$ **16**. Proper subsets $= 16 - 1 =$ **15**.

**Example 2:** A set has 5 elements. How many subsets contain exactly 2 elements?
- $\binom{5}{2} = \dfrac{5\times4}{2} =$ **10**.

### Model 8. Cartesian product

**Idea:** $n(A \times B) = n(A)\times n(B)$.

**Example:** $n(A)=3$ and $n(B)=4$. Find $n(A \times B)$.
- $n(A \times B) = 3\times4 =$ **12**.

### Model 9. Set difference and complement

**Idea:** $A - B$ (elements in A but not in B) $= n(A) - n(A \cap B)$. Complement $A' = n(U) - n(A)$.

**Example:** $n(U)=10$, $n(A)=6$, $n(B)=5$, $n(A \cap B)=3$.
- $A - B = 6 - 3 =$ **3** (only in A).
- $B - A = 5 - 3 =$ **2** (only in B).
- $(A \cup B)' = 10 - (6+5-3) =$ **2** (in neither).

### Model 10. Exactly one, exactly two, all three

**Idea:** use the direct formulas. "Exactly one" and "exactly two" are favourite exam types.

**Example:** In a class of 100 students: English $=60$, French $=50$, German $=40$, E and F $=20$, F and G $=15$, E and G $=25$, all three $=10$.
- Exactly one $= 60+50+40 - 2(20+15+25) + 3\times10 = 150 - 120 + 30 =$ **60**.
- Exactly two $= (20+15+25) - 3\times10 = 60 - 30 =$ **30**.
- All three $=$ **10**.
- Total in at least one $= 60 + 30 + 10 = 100$ (all students).

### Model 11. Relations and ordered pairs

**Idea:** the number of relations from set $A$ to set $A$ (i.e., subsets of $A \times A$) is $2^{n^2}$, where $n = n(A)$.

**Example:** How many relations can be defined on the set $A = \{1, 2, 3\}$?
- $n(A) = 3$. Number of relations $= 2^{3^2} = 2^9 =$ **512**.

### Model 12. De Morgan's laws

**Idea:** $(A \cup B)' = A' \cap B'$ and $(A \cap B)' = A' \cup B'$.

**Example:** $n(U)=30$, $n(A)=18$, $n(B)=14$, $n(A \cap B)=7$. Find $n((A \cap B)')$.
- $n((A \cap B)') = n(U) - n(A \cap B) = 30 - 7 =$ **23**.
- Verify by De Morgan: $n(A' \cup B') = n(U) - n(A \cap B) = 23$. Consistent.

## Part 5. Practice

1. $n(A)=20$, $n(B)=15$, $n(A \cup B)=30$. Find $n(A \cap B)$.
2. In a class of 50 students, 30 read Hindi, 25 read English, and 10 read both. How many read neither?
3. $n(A \cup B \cup C)=80$, $n(A)=40$, $n(B)=35$, $n(C)=30$, $n(A \cap B)=15$, $n(A \cap C)=12$, $n(B \cap C)=10$. Find $n(A \cap B \cap C)$.
4. In a group of 60, 35 drink tea, 25 drink coffee, 10 drink both. How many drink neither?
5. How many subsets does the set $\{a, b, c\}$ have?
6. $n(A)=3$, $n(B)=5$. Find $n(A \times B)$.
7. $n(U)=25$, $n(A)=14$, $n(B)=11$, $n(A \cap B)=6$. Find the number of elements only in A, only in B, and in neither.
8. In a class of 200 students, 120 pass English, 90 pass Maths, and 50 fail both. How many pass both?
9. $n(A)=40$, $n(B)=30$, $n(C)=25$, $n(A \cap B)=10$, $n(A \cap C)=8$, $n(B \cap C)=6$, $n(A \cap B \cap C)=3$. Find the count in exactly two sets.
10. A survey of 500 people: like A $=250$, B $=200$, C $=150$, A and B $=80$, B and C $=60$, A and C $=70$, all three $=40$. Find $n(A \cup B \cup C)$.
11. $n(U)=100$, $n(A')=35$, $n(B)=40$, $n(A \cap B)=20$. Find $n(A \cup B)$.
12. A set has 4 elements. Find the total number of subsets and the number of proper subsets.
13. $A=\{1,2,3,4,5\}$, $B=\{3,4,5,6,7\}$. Find $n(A \cap B)$, $n(A - B)$, and $n(A \cup B)$.
14. $n(A)=45$, $n(B)=38$, $n(C)=29$, $n(A \cap B)=12$, $n(A \cap C)=10$, $n(B \cap C)=9$, $n(A \cap B \cap C)=4$. Find $n(A \cup B \cup C)$.
15. $n(U)=30$, $n(A)=18$, $n(B)=14$, $n(A \cap B)=7$. Find $n((A \cap B)')$.
16. $n(A)=28$, $n(B)=22$, $n(A \cap B)=10$. Find the count in exactly one of the two sets.
17. $n(A)=12$, $n(B)=16$, $n(A \cup B)=22$. Find $n(A \cap B)$.
18. In a group of 150 workers, 90 know English, 70 know Hindi, and 30 know both. How many know neither?
19. $A = \{x : x \text{ is a factor of } 12\}$, $B = \{x : x \text{ is a factor of } 18\}$. Find $n(A \cap B)$ and $n(A \cup B)$.
20. In a group of 60 families, 45 buy milk, 30 buy juice, and 20 buy both. How many buy neither?
21. In a class of 200, 120 pass Physics, 100 pass Chemistry, and 20 fail both. How many pass both?
22. $n(A)=35$, $n(B)=28$, $n(C)=22$, $n(A \cap B)=10$, $n(B \cap C)=8$, $n(A \cap C)=7$, $n(A \cap B \cap C)=3$. Find the count only in C.
23. $n(A)=50$, $n(B)=45$, $n(C)=40$, all pairwise intersections $=15$, $n(A \cap B \cap C)=0$. Find $n(A \cup B \cup C)$.
24. A set has 6 elements. How many subsets have at least 1 element?
25. $n(U)=120$, $n(A)=65$, $n(B)=55$, $n(A \cap B)=25$. Find $n(A' \cap B')$.
26. In a school of 500, 300 study Maths, 250 study Science, and 100 study neither. How many study both?
27. $n(A)=15$, $n(B)=12$, $n(A \cap B)=5$. Find $n(A \triangle B)$ (symmetric difference).
28. $A=\{1,2,3,4\}$, $B=\{2,3,5\}$, $C=\{3,4,6\}$. Find $n(A \cap (B \cup C))$.
29. In a train of 80 passengers, 50 read an English paper, 45 read a Hindi paper, and 25 read both. How many read neither?
30. $n(A)=30$, $n(B)=25$, $n(C)=20$, $n(A \cap B)=10$, $n(A \cap C)=8$, $n(B \cap C)=6$, $n(A \cap B \cap C)=3$. How many are in exactly two sets?
31. $n(A)=n(B)=n(C)=30$, each pairwise intersection $=12$, $n(A \cap B \cap C)=5$. Find $n(A \cup B \cup C)$.
32. $n(U)=50$, $n(A')=20$, $n(B')=25$, $n(A \cap B)=10$. Find $n((A \cup B)')$.
33. 120 athletes: run $=75$, swim $=55$, cycle $=40$, run and swim $=20$, swim and cycle $=15$, run and cycle $=10$, all three $=5$. Find $n(\text{run} \cup \text{swim} \cup \text{cycle})$.
34. $n(A)=20$, $n(B)=16$, $n(A \cup B)=30$. How many elements are only in A?
35. In a survey of 1000 people: like A $=550$, B $=450$, C $=300$, A and B $=150$, A and C $=100$, B and C $=80$, all three $=30$. Find $n(A \cup B \cup C)$ and the count only in A.
36. Sets A and B have 4 and 5 elements respectively. What is the maximum possible value of $n(A \cap B)$ and the maximum possible value of $n(A \cup B)$?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 5 | $n(A \cap B)=20+15-30$ |
| 2 | 5 | $n(H \cup E)=30+25-10=45$; neither $=50-45$ |
| 3 | 12 | $80=40+35+30-15-12-10+x$; $x=12$ |
| 4 | 10 | $n(T \cup C)=35+25-10=50$; neither $=60-50$ |
| 5 | 8 | $2^3$ |
| 6 | 15 | $3\times5$ |
| 7 | Only A $=8$, only B $=5$, neither $=6$ | $14-6=8$; $11-6=5$; $25-(14+11-6)$ |
| 8 | 60 | At least one $=200-50=150$; both $=120+90-150$ |
| 9 | 15 | $(10+8+6)-3\times3$ |
| 10 | 430 | $250+200+150-80-60-70+40$ |
| 11 | 85 | $n(A)=100-35=65$; $65+40-20$ |
| 12 | 16 subsets, 15 proper | $2^4=16$; $16-1$ |
| 13 | $n(A \cap B)=3$, $n(A-B)=2$, $n(A \cup B)=7$ | $\{3,4,5\}$; $\{1,2\}$; $5+5-3$ |
| 14 | 85 | $45+38+29-12-10-9+4$ |
| 15 | 23 | $n(U)-n(A \cap B)=30-7$ |
| 16 | 30 | $(28-10)+(22-10)=18+12$ |
| 17 | 6 | $12+16-22$ |
| 18 | 20 | $n(E \cup H)=90+70-30=130$; neither $=150-130$ |
| 19 | $n(A \cap B)=4$, $n(A \cup B)=8$ | $A \cap B=\{1,2,3,6\}$; $A \cup B$ has 8 elements |
| 20 | 5 | $n(M \cup J)=45+30-20=55$; neither $=60-55$ |
| 21 | 40 | At least one $=200-20=180$; both $=120+100-180$ |
| 22 | 10 | Only $C=22-8-7+3$ |
| 23 | 90 | $50+45+40-15-15-15+0$ |
| 24 | 63 | $2^6-1$ |
| 25 | 25 | $n((A \cup B)')=120-(65+55-25)$ |
| 26 | 150 | At least one $=500-100=400$; both $=300+250-400$ |
| 27 | 17 | $A \triangle B=(A-B)+(B-A)=(15-5)+(12-5)$ |
| 28 | 3 | $B \cup C=\{2,3,4,5,6\}$; $A \cap (B \cup C)=\{2,3,4\}$ |
| 29 | 10 | $n(E \cup H)=50+45-25=70$; neither $=80-70$ |
| 30 | 15 | $(10+8+6)-3\times3$ |
| 31 | 59 | $3\times30-3\times12+5$ |
| 32 | 5 | $n(A)=30$, $n(B)=25$; $n(A \cup B)=30+25-10=45$; neither $=50-45$ |
| 33 | 130 | $75+55+40-20-15-10+5$ |
| 34 | 14 | $n(A \cap B)=20+16-30=6$; only A $=20-6$ |
| 35 | $n(A \cup B \cup C)=1000$; only A $=330$ | $550+450+300-150-100-80+30=1000$; only A $=550-150-100+30$ |
| 36 | Max $n(A \cap B)=4$; max $n(A \cup B)=9$ | Smaller set fully inside larger for max $\cap$; disjoint for max $\cup$ |
