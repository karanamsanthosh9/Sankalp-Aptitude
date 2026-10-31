# Data Interpretation: Model-wise Notes

## Part 1. What comes from this topic

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Model |
|---|---|
| Tabular charts (simple and multi-column tables) | 1 |
| Bar charts (single, clustered, and stacked bars) | 2 |
| Line graphs and time-series trend analysis | 3 |
| Single pie charts (percentage and degree distribution) | 4 |
| Double / two-tier pie charts | 5 |
| Radar / spider web charts | 6 |
| Mixed / combined charts (table + pie, bar + line) | 7 |
| Caselet DI: Venn diagram / set theory based | 8 |
| Caselet DI: Paragraph and equation based | 9 |
| Missing data interpretation tables | 10 |
| Percentage change, growth rate, and CAGR approximation | 11 |
| Ratio and proportion based data sets | 12 |
| Weighted averages and aggregate marks / sales | 13 |
| Data sufficiency in DI | 14 |

## Part 2. What data is usually given

| Data you will see | What it means |
|---|---|
| "Pie chart angle $\theta^\circ$" | Value $= \dfrac{\theta}{360} \times \text{Total}$ |
| "Pie chart percentage $P\%$" | Value $= \dfrac{P}{100} \times \text{Total}$; Angle $= P \times 3.6^\circ$ |
| "What percent is $A$ of $B$?" | $\dfrac{A}{B} \times 100\%$ |
| "$A$ is what percent more/less than $B$?" | $\dfrac{A - B}{B} \times 100\%$ (divide by the reference term after 'than') |
| "Percentage change over previous year" | $\dfrac{\text{Current} - \text{Previous}}{\text{Previous}} \times 100\%$ |
| "Ratio of $X$ to $Y$" | $\dfrac{X}{Y}$ simplified to lowest integer terms |
| "Weighted average of groups" | $\dfrac{n_1 A_1 + n_2 A_2 + \dots}{n_1 + n_2 + \dots}$ |
| "Both $P$ and $Q$" in Venn sets | Intersection $P \cap Q$ |

## Part 3. The base idea (read once)

- **Core arithmetic tools:** Almost every DI question tests three fundamental operations: **Percentages** ($\frac{\text{part}}{\text{whole}} \times 100$), **Ratios** ($\frac{A}{B}$), and **Averages** ($\frac{\text{sum}}{n}$).
- **Pie chart conversions:** $100\% = 360^\circ \implies 1\% = 3.6^\circ \implies 10\% = 36^\circ$. To find difference between sectors, subtract percentages/degrees first before multiplying by total.
- **Speed calculation techniques:** Use fractional equivalents ($12.5\% = \frac{1}{8}$, $16.67\% = \frac{1}{6}$, $33.33\% = \frac{1}{3}$) and ratio cancellation instead of computing raw absolute values first.

## Part 4. Models

### Model 1. Tabular charts

**Idea:** Extract rows and columns cleanly. Sum rows/columns for totals before computing requested ratios or percentages.

**Data for Examples:**

| School | Arts | Science | Commerce | Total |
|---|---|---|---|---|
| A | 120 | 180 | 100 | 400 |
| B | 150 | 120 | 130 | 400 |
| C | 90 | 210 | 150 | 450 |

**Example 1:** What percentage of total students in School A are in the Science stream?
- Science students in School A $= 180$, Total in School A $= 400$.
- Percentage $= \dfrac{180}{400} \times 100 =$ **45%**.

**Example 2:** Find the ratio of total Arts students to total Commerce students across all three schools.
- Total Arts $= 120 + 150 + 90 = 360$.
- Total Commerce $= 100 + 130 + 150 = 380$.
- $\text{Ratio} = 360 : 380 =$ **18 : 19**.

### Model 2. Bar charts

**Idea:** Compare heights/values across discrete categories or years.

**Data for Examples (Production of Cars in thousands):**

| Year | Production (in '000s) |
|---|---|
| 2020 | 40 |
| 2021 | 50 |
| 2022 | 65 |
| 2023 | 80 |

**Example 1:** Find the percentage increase in car production from 2020 to 2023.
- $\text{Increase} = 80 - 40 = 40$.
- Percentage increase $= \dfrac{40}{40} \times 100 =$ **100%**.

**Example 2:** Find the average annual production over the 4 years.
- $\text{Average} = \dfrac{40 + 50 + 65 + 80}{4} = \dfrac{235}{4} =$ **58.75 thousand**.

### Model 3. Line graphs and time-series trends

**Idea:** Track upward and downward slopes across continuous periods to spot growth rates and turning points.

**Data for Examples (Company ABC Revenue in Rs Lakh):**

| Year | Y1 | Y2 | Y3 | Y4 | Y5 |
|---|---|---|---|---|---|
| Revenue (Rs Lakh) | 120 | 150 | 135 | 180 | 225 |

**Example 1:** In which year was the percentage increase in revenue maximum over its preceding year?
- $\text{Y1} \to \text{Y2}: \dfrac{30}{120} \times 100 = 25\%$.
- $\text{Y2} \to \text{Y3}:$ Decrease.
- $\text{Y3} \to \text{Y4}: \dfrac{45}{135} \times 100 = 33.33\%$.
- $\text{Y4} \to \text{Y5}: \dfrac{45}{180} \times 100 = 25\%$.
- Maximum percentage increase was in **Y4 (33.33%)**.

### Model 4. Single pie charts

**Idea:** Degree values sum to $360^\circ$; percentages sum to $100\%$. Compute differences in degrees/percents first before multiplying by the total.

**Data for Examples (Total Monthly Budget = Rs 72,000):**

| Category | Food | Rent | Education | Savings | Others |
|---|---|---|---|---|---|
| Angle | 120^\circ | 90^\circ | 60^\circ | 50^\circ | 40^\circ |

**Example 1:** How much money is allocated for Food?
- $\text{Amount} = \dfrac{120}{360} \times 72000 = \dfrac{1}{3} \times 72000 =$ **Rs 24000**.

**Example 2:** Find the difference between the expenditure on Rent and Education.
- Degree difference $= 90^\circ - 60^\circ = 30^\circ$.
- $\text{Difference} = \dfrac{30}{360} \times 72000 = \dfrac{1}{12} \times 72000 =$ **Rs 6000**.

### Model 5. Double / two-tier pie charts

**Idea:** First pie gives the universal total distribution; second pie gives a sub-group (e.g., females). Subtract to find the complementary sub-group (e.g., males).

**Data for Examples:**
- Total Employees $= 1800$ (IT $= 30\%$, HR $= 20\%$, Sales $= 25\%$, Operations $= 25\%$).
- Total Females $= 800$ (IT $= 25\%$, HR $= 35\%$, Sales $= 20\%$, Operations $= 20\%$).

**Example 1:** Find the number of male employees working in the IT department.
- Total IT employees $= 30\% \text{ of } 1800 = 540$.
- Female IT employees $= 25\% \text{ of } 800 = 200$.
- Male IT employees $= 540 - 200 =$ **340**.

### Model 6. Radar / spider web charts

**Idea:** Multi-axis comparison of multiple entities across standardized performance metrics.

**Data for Examples (Scores out of 100):**

| Skill | Speed | Stamina | Agility | Power | Technique |
|---|---|---|---|---|---|
| Player A | 80 | 70 | 85 | 90 | 75 |
| Player B | 75 | 85 | 80 | 70 | 90 |

**Example 1:** By what percentage does Player A's Power score exceed Player B's Power score?
- $\text{Difference} = 90 - 70 = 20$.
- Percentage excess $= \dfrac{20}{70} \times 100 = \dfrac{200}{7}\% \approx$ **28.57%**.

### Model 7. Mixed / combined charts

**Idea:** Cross-reference information from one representation (e.g., total production pie) with another (e.g., defect rate table).

**Data for Examples (Total production = 2400 units):**

| Model | P | Q | R | S |
|---|---|---|---|---|
| Share of Production | 25% | 35% | 20% | 20% |
| Defect Rate | 4% | 5% | 10% | 5% |

**Example 1:** Find the total number of defective units produced across all four models.
- Model P: $25\% \times 2400 \times 4\% = 600 \times 0.04 = 24$.
- Model Q: $35\% \times 2400 \times 5\% = 840 \times 0.05 = 42$.
- Model R: $20\% \times 2400 \times 10\% = 480 \times 0.10 = 48$.
- Model S: $20\% \times 2400 \times 5\% = 480 \times 0.05 = 24$.
- $\text{Total defective} = 24 + 42 + 48 + 24 =$ **138 units**.

### Model 8. Caselet DI: Venn diagram / set theory

**Idea:** Fill standard 3-circle Venn regions starting from the central intersection of all three sets outwards: $\text{Only } A = n(A) - n(A \cap B) - n(A \cap C) + n(A \cap B \cap C)$.

**Data for Examples:**
In a college of $500$ students: Football ($F$) $= 240$, Cricket ($C$) $= 220$, Basketball ($B$) $= 180$.
$F \cap C = 90$, $C \cap B = 80$, $F \cap B = 70$, All three ($F \cap C \cap B$) $= 40$.

**Example 1:** Find the number of students who play exactly ONE sport.
- Only $F = 240 - (50 + 40 + 30) = 120$.
- Only $C = 220 - (50 + 40 + 40) = 90$.
- Only $B = 180 - (30 + 40 + 40) = 70$.
- Exactly one sport $= 120 + 90 + 70 =$ **280 students**.

**Example 2:** How many students play NONE of the three sports?
- Total playing at least one $= 120 + 90 + 70 + 50 + 40 + 30 + 40 = 440$.
- Playing none $= 500 - 440 =$ **60 students**.

### Model 9. Caselet DI: Paragraph and equation based

**Idea:** Convert paragraph statements into a clean table step-by-step using given proportions and equations.

**Data for Examples:**
A company has $600$ employees in departments A, B, and C. Dept A has $40\%$ of all employees. The ratio of employees in B to C is $5:4$. In Dept A, $60\%$ are males. In Dept B, male to female ratio is $3:2$. In Dept C, the number of males equals females.

**Example 1:** Find the total number of female employees in the entire company.
- Dept A: Total $= 240 \implies \text{Males} = 144, \text{Females} = 96$.
- Depts B + C $= 600 - 240 = 360$. Ratio $5:4 \implies \text{B} = 200, \text{C} = 160$.
- Dept B Females $= \dfrac{2}{5} \times 200 = 80$.
- Dept C Females $= \dfrac{160}{2} = 80$.
- $\text{Total females} = 96 + 80 + 80 =$ **256 females**.

### Model 10. Missing data interpretation

**Idea:** Solve for unknown table cells using row sums, column sums, or stated algebraic conditions.

**Data for Examples:**

| Employee | Basic Pay (Rs) | HRA | DA | Total Salary (Rs) |
|---|---|---|---|---|
| Emp 1 | 20000 | 4000 | [Blank] | 30000 |
| Emp 2 | 25000 | 5000 | 30% of Basic | [Blank] |

**Example 1:** Find the DA received by Emp 1 and the Total Salary of Emp 2.
- Emp 1 DA $= 30000 - (20000 + 4000) =$ **Rs 6000**.
- Emp 2 DA $= 30\% \times 25000 = 7500 \implies \text{Total} = 25000 + 5000 + 7500 =$ **Rs 37500**.

### Model 11. Percentage change and growth rates

**Idea:** Growth rate $= \dfrac{\text{Final} - \text{Initial}}{\text{Initial}} \times 100\%$. Annual simple growth rate $= \dfrac{\text{Overall Growth Rate}}{n}$.

**Data for Examples (Annual Revenue in Rs Crore):**

| Year | 2020 | 2021 | 2022 | 2023 |
|---|---|---|---|---|
| Revenue | 100 | 120 | 150 | 180 |

**Example 1:** Find the overall percentage growth from 2020 to 2023.
- $\text{Growth} = \dfrac{180 - 100}{100} \times 100 =$ **80%**.

### Model 12. Ratio and proportion based DI

**Idea:** Split totals into component ratios and combine across categories.

**Data for Examples:**
- Section A: $80$ students, Boy : Girl $= 5 : 3 \implies 50\text{ Boys}, 30\text{ Girls}$.
- Section B: $100$ students, Boy : Girl $= 3 : 2 \implies 60\text{ Boys}, 40\text{ Girls}$.
- Section C: $120$ students, Boy : Girl $= 7 : 5 \implies 70\text{ Boys}, 50\text{ Girls}$.

**Example 1:** Find the overall ratio of boys to girls across all three sections.
- Total Boys $= 50 + 60 + 70 = 180$.
- Total Girls $= 30 + 40 + 50 = 120$.
- $\text{Ratio} = 180 : 120 =$ **3 : 2**.

### Model 13. Average and weighted average DI

**Idea:** Combined average $\bar{X} = \dfrac{\sum n_i x_i}{\sum n_i}$.

**Data for Examples:**
- Class 1: $40$ students, Average marks $= 60$.
- Class 2: $60$ students, Average marks $= 70$.
- Class 3: $50$ students, Average marks $= 80$.

**Example 1:** Find the combined average marks of all three classes.
- $\text{Combined average} = \dfrac{(40 \times 60) + (60 \times 70) + (50 \times 80)}{40 + 60 + 50} = \dfrac{2400 + 4200 + 4000}{150} = \dfrac{10600}{150} \approx$ **70.67 marks**.

### Model 14. Data sufficiency in DI

**Idea:** Determine whether Statement I alone, Statement II alone, or both together are sufficient to find a unique numeric answer without unnecessary full calculations.

**Example 1:** What is the total salary of A and B?
- Statement I: A's salary is $20\%$ more than B's salary.
- Statement II: B's salary is Rs $25,000$.
- From I alone: Ratio is known ($1.2 : 1$), but no absolute value $\implies$ Not sufficient.
- From II alone: B is known, but A is unknown $\implies$ Not sufficient.
- Combining I and II: $\text{B} = 25000, \text{A} = 1.2 \times 25000 = 30000 \implies \text{Total} = 55000 \implies$ **Both statements together are sufficient**.

## Part 5. Practice

**Questions 1–3 refer to the following table (Marks out of 100 scored by students in 3 subjects):**

| Student | Mathematics | Science | English |
|---|---|---|---|
| Amit | 80 | 75 | 85 |
| Priya | 90 | 85 | 75 |
| Rahul | 70 | 80 | 90 |
| Sneha | 85 | 90 | 80 |

1. Find Amit's average marks across all three subjects.
2. Find the total marks scored by all four students in English.
3. What is the difference between Priya's total marks and Rahul's total marks across all three subjects?

**Questions 4–6 refer to the following sales table (Mobile phones sold in thousands):**

| Year | Brand P | Brand Q |
|---|---|---|
| 2021 | 40 | 50 |
| 2022 | 60 | 55 |
| 2023 | 75 | 70 |

4. Find the percentage increase in the sales of Brand P from 2021 to 2023.
5. Find the ratio of total sales of Brand P to total sales of Brand Q over the three years.
6. What is the average annual sales of Brand Q over the 3 years?

**Questions 7–9 refer to the following table of annual profits of Company ABC (in Rs Lakh):**

| Year | 2019 | 2020 | 2021 | 2022 | 2023 |
|---|---|---|---|---|---|
| Profit (Rs Lakh) | 50 | 80 | 60 | 90 | 120 |

7. Find the percentage growth in profit from 2019 to 2020.
8. Find the average annual profit of Company ABC over the 5 years.
9. What is the percentage increase in profit in 2023 compared to 2021?

**Questions 10–12 refer to a family's monthly budget of Rs 60,000 represented in a pie chart:**
(Sectors: Food $= 144^\circ$, Rent $= 108^\circ$, Education $= 54^\circ$, Savings $= 54^\circ$)

10. What is the monthly expenditure on Food?
11. How much more is spent on Rent than on Education?
12. What percentage of the total budget is allocated to Savings?

**Questions 13–15 refer to University enrollment data:**
(Total students $= 4000$ with streams: Engineering $40\%$, Medical $20\%$, Arts $25\%$, Commerce $15\%$; Total Female students $= 1600$ with streams: Engineering $25\%$, Medical $30\%$, Arts $30\%$, Commerce $15\%$)

13. Find the number of male students enrolled in Engineering.
14. What percentage of total Medical students are females?
15. Find the ratio of male students in Arts to male students in Commerce.

**Questions 16–17 refer to Smartphone ratings (out of 10):**

| Feature | Battery | Camera | Display | Performance |
|---|---|---|---|---|
| Phone X | 8 | 9 | 7 | 8 |
| Phone Y | 9 | 7 | 8 | 10 |

16. Find the overall average rating of Phone X and Phone Y across the four features.
17. By what percentage is Phone Y's Performance score higher than Phone X's Performance score?

**Questions 18–19 refer to production and defect rates of 3 machines:**
(Total production: Machine $1 = 1200$ with $5\%$ defects, Machine $2 = 1500$ with $4\%$ defects, Machine $3 = 1300$ with $6\%$ defects)

18. Find the total number of defective items produced by all three machines.
19. Find the total number of non-defective items produced across all three machines.

**Questions 20–22 refer to employee beverage preferences:**
(In an office of $300$ employees, $180$ drink Tea, $140$ drink Coffee, and $60$ drink both Tea and Coffee)

20. How many employees drink Tea only?
21. How many employees drink Coffee only?
22. How many employees drink neither Tea nor Coffee?

**Questions 23–24 refer to a store sales caselet:**
(A clothing store sold $500$ items comprising Shirts and Trousers. Shirts sold were $100$ more than Trousers. Selling price of a Shirt is Rs $400$ and a Trouser is Rs $800$)

23. Find the total number of shirts sold.
24. Find the total revenue generated from the sale of all shirts and trousers.

**Questions 25–26 refer to missing data in branch performance:**

| Branch | Production (units) | Sales (units) |
|---|---|---|
| Branch A | 500 | 400 |
| Branch B | [Missing] | 600 (Given: Sales is 75% of Production) |
| Branch C | 700 | [Missing] (Given: Unsold is 20% of Production) |

25. Find the production of Branch B.
26. Find the sales of Branch C.

**Questions 27–28 refer to wheat exports (in metric tonnes):**
(2020: $250$, 2021: $300$, 2022: $360$, 2023: $450$)

27. Find the overall percentage growth in wheat exports from 2020 to 2023.
28. Find the percentage growth in exports in 2022 over 2021.

**Questions 29–30 refer to staff distribution in three offices:**
(Office X has $100$ staff with Officer : Clerk $= 1 : 4$; Office Y has $150$ staff with Officer : Clerk $= 2 : 3$; Office Z has $200$ staff with Officer : Clerk $= 1 : 3$)

29. Find the total number of officers across all three offices.
30. Find the ratio of total officers to total clerks across all three offices.

**Question 31 refers to class test score averages:**
31. Section A has $30$ students with average score $70$, Section B has $20$ students with average score $80$, and Section C has $50$ students with average score $75$. Find the combined average score of all three sections.

**Question 32 refers to data sufficiency:**
32. What is the ratio of male to female employees in Company K?
- Statement I: The total number of employees is $500$.
- Statement II: Females constitute $40\%$ of the total employees.
Determine whether Statement I alone is sufficient, Statement II alone is sufficient, or both are required.

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | 80 marks | Amit's average $= \frac{80 + 75 + 85}{3} = \frac{240}{3} = 80$ |
| 2 | 330 marks | $\text{Total English} = 85 + 75 + 90 + 80 = 330$ |
| 3 | 10 marks | Priya total $= 250$, Rahul total $= 240$, difference $= 250 - 240 = 10$ |
| 4 | 87.5% | $\frac{75 - 40}{40} \times 100 = \frac{35}{40} \times 100 = 87.5\%$ |
| 5 | 1 : 1 | Brand P total $= 175$, Brand Q total $= 175$, ratio $= 175 : 175 = 1 : 1$ |
| 6 | 58.33 thousand | $\text{Average} = \frac{50 + 55 + 70}{3} = \frac{175}{3} \approx 58.33$ thousand |
| 7 | 60% | $\frac{80 - 50}{50} \times 100 = \frac{30}{50} \times 100 = 60\%$ |
| 8 | Rs 80 Lakh | $\text{Average} = \frac{50 + 80 + 60 + 90 + 120}{5} = \frac{400}{5} = 80$ |
| 9 | 100% | $\frac{120 - 60}{60} \times 100 = \frac{60}{60} \times 100 = 100\%$ |
| 10 | Rs 24000 | $\text{Food} = \frac{144}{360} \times 60000 = \frac{2}{5} \times 60000 = 24000$ |
| 11 | Rs 9000 | $\frac{108 - 54}{360} \times 60000 = \frac{54}{360} \times 60000 = 9000$ |
| 12 | 15% | $\frac{54}{360} \times 100 = 15\%$ |
| 13 | 1200 | $\text{Male Engg} = (0.40 \times 4000) - (0.25 \times 1600) = 1600 - 400 = 1200$ |
| 14 | 60% | $\text{Female Med} = 480$, $\text{Total Med} = 800$, $\frac{480}{800} \times 100 = 60\%$ |
| 15 | 13 : 9 | $\text{Male Arts} = 1000 - 480 = 520$, $\text{Male Comm} = 600 - 240 = 360$, ratio $= 520 : 360 = 13 : 9$ |
| 16 | 8.0 and 8.5 | Phone X average $= \frac{32}{4} = 8.0$, Phone Y average $= \frac{34}{4} = 8.5$ |
| 17 | 25% | $\frac{10 - 8}{8} \times 100 = \frac{2}{8} \times 100 = 25\%$ |
| 18 | 198 units | $\text{Defects} = (1200 \times 0.05) + (1500 \times 0.04) + (1300 \times 0.06) = 60 + 60 + 78 = 198$ |
| 19 | 3802 units | $\text{Non-defective} = 4000 - 198 = 3802$ (or $1140 + 1440 + 1222 = 3802$) |
| 20 | 120 | $\text{Only Tea} = 180 - 60 = 120$ |
| 21 | 80 | $\text{Only Coffee} = 140 - 60 = 80$ |
| 22 | 40 | $\text{Neither} = 300 - (120 + 80 + 60) = 300 - 260 = 40$ |
| 23 | 300 | $S + T = 500$, $S - T = 100 \implies S = 300, T = 200$ |
| 24 | Rs 2,80,000 | $\text{Revenue} = (300 \times 400) + (200 \times 800) = 120000 + 160000 = 280000$ |
| 25 | 800 units | $\text{Production} = \frac{600}{0.75} = 800$ |
| 26 | 560 units | $\text{Sales} = 700 \times (1 - 0.20) = 700 \times 0.80 = 560$ |
| 27 | 80% | $\frac{450 - 250}{250} \times 100 = \frac{200}{250} \times 100 = 80\%$ |
| 28 | 20% | $\frac{360 - 300}{300} \times 100 = \frac{60}{300} \times 100 = 20\%$ |
| 29 | 130 | $\text{Total Officers} = 20 + 60 + 50 = 130$ |
| 30 | 13 : 32 | Officers $= 130$, Clerks $= 80 + 90 + 150 = 320$, ratio $= 130 : 320 = 13 : 32$ |
| 31 | 74.5 marks | $\text{Combined average} = \frac{(30 \times 70) + (20 \times 80) + (50 \times 75)}{100} = \frac{7450}{100} = 74.5$ |
| 32 | Statement II alone is sufficient | From II: Females $= 40\% \implies \text{Males} = 60\%$, ratio $= 60:40 = 3:2$. Statement II alone is sufficient |
