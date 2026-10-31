# Simple Interest

> Read this like a class, not like a formula list. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" boxes with a pen before reading the answer next to them.

## 0. Start here: what is this topic really about?

Imagine you lend Rs 100 to a friend for a year, and he says, "Thank you. Here is Rs 108 back." The extra Rs 8 is the price of using your money for a year. That price is called **interest**. The Rs 100 you lent is the **principal**. The Rs 108 you got back is the **amount**.

**Simple interest** is the plainest version: the interest is worked out on the **original principal only**, and the same rupees are added every year. Nothing grows on top of earlier interest.

Questions look like these:

- "Find the simple interest on Rs 8000 at 6% per annum for 3 years."
- "At what rate will Rs 5000 earn Rs 1200 in 3 years?"
- "In how many years will a sum double itself at 12.5%?"
- "A sum is lent in two parts at 6% and 9%. Find the parts."
- "A man borrows at 6% and lends at 9%. Find his gain."

**What the exam gives you:** any three of principal, rate, time, interest, amount. Sometimes a sum is split, or rates change from year to year. **What it asks for:** the missing one of those, or a gain, a split, or a comparison.

**How many marks to expect:** SSC CGL and CHSL carry 1 to 2 questions that need simple interest, often mixed with compound interest. RRB NTPC and Group D carry 1 or 2. IBPS and SBI Clerk and PO papers carry 1 or 2 in arithmetic or data sets, and simple interest is the base of many loan and EMI situations. PSU and APPSC papers carry 1 or 2. The formula is tiny. The marks are in reading the question correctly.

## 1. The only ideas you must understand

### What "8% per annum" really means

**Per annum** means "per year". **8% per annum** means: for every Rs 100 lent, you earn Rs 8 each year.

- On Rs 100, interest for 1 year is Rs 8.
- On Rs 5000, which is fifty hundreds, interest for 1 year is $50\times8=$ Rs 400.
- For 3 years, the same Rs 400 is earned each year, so $400\times3=$ Rs 1200.

That small story is the whole formula:

$$\text{SI}=\dfrac{P\times R\times T}{100}$$

$P$ is the principal, $R$ the rate in percent per year, $T$ the time in years. It says: (number of hundreds) $\times$ (rupees per hundred per year) $\times$ (years).

### Amount

Amount is what you get back in total.

$$A=P+\text{SI}=P\left(1+\dfrac{RT}{100}\right)$$

### Why interest is "simple"

Every year the interest is the same, because it is always charged on the original $P$. So the amount grows in a **straight line**: same rupees added each year. This one fact makes half the questions in this chapter easy, because you can find the yearly interest and multiply or divide by years.

### Trying it: Rs 5000 at 8% for 3 years. SI and amount?

Step 1. Interest in one year $=\dfrac{5000\times8}{100}=400$.

Step 2. For 3 years: $400\times3=1200$.

Step 3. Amount $=5000+1200=6200$.

**Answer: SI = Rs 1200 and amount = Rs 6200.**

**Sense check you should always do:** time must be in **years** and rate must be **per year**. If the question says 9 months, turn it into $\dfrac{9}{12}$ year first. And the amount must always be bigger than the principal.

### Your turn

Find the SI on Rs 7500 at 4% per annum for 3 years. (Answer: Rs 900. One year gives Rs 300.)

## 2. The shortcuts that save time

### Shortcut 1. Find one year first

Always ask: "How much interest does this earn in ONE year?" That is $\dfrac{P\times R}{100}$. Then multiply by years. This avoids big products in one go.

**Example.** Rs 6000 at 10% for 9 months. One year gives Rs 600. Nine months is $\dfrac{9}{12}=\dfrac{3}{4}$ of a year, so $600\times\dfrac{3}{4}=$ **Rs 450**.

### Shortcut 2. Rate times time is all that matters

In $\dfrac{P\times R\times T}{100}$, only the **product** $R\times T$ matters. So 6% for 5 years is the same as 10% for 3 years (both give 30% of the principal).

$$\text{SI}=P\times\dfrac{R\times T}{100}$$

Think of $R\times T$ as "the total percent earned". Rs 5000 at 6% for 5 years earns 30% of 5000, which is Rs 1500.

### Shortcut 3. Amount as a multiple of principal

If $R\times T=30$, the amount is $1.30$ times the principal. In general:

$$A=P\times\dfrac{100+RT}{100}$$

**Example.** Rs 7800 is the amount after 5 years at 6%. $RT=30$, so $P=\dfrac{7800}{1.3}=$ **Rs 6000**.

### Shortcut 4. The 365 and 73 trick for days

For days, use $\dfrac{\text{days}}{365}$ as the fraction of a year. If the principal is a multiple of 7300 ($=20\times365$), the day fraction cancels cleanly.

**Example.** Rs 7300 at 10% for 73 days. One year $=730$. $\dfrac{73}{365}=\dfrac{1}{5}$ of a year. $730\div5=$ **Rs 146**.

## 3. Types of questions and how to crack each one

Every type you can meet is below. Each has: how you spot it, how to think, an example, and an exam twist where useful.

### Type 1. Direct: find SI and amount

**How you spot it:** "Find the simple interest on Rs 8000 at 6% per annum for 3 years."

**Think:** one year's interest, then multiply by the years.

**Example 1.** Rs 8000, 6%, 3 years.
- One year: $\dfrac{8000\times6}{100}=480$.
- Three years: **Rs 1440**. Amount $=8000+1440=$ **Rs 9440**.

**Example 2.** Rs 12500 at 8% for 2 years.
- One year: $1000$. Two years: **Rs 2000**.

**Example 3.** Rs 4500 at 12% for $2\frac{1}{2}$ years.
- One year: $540$. For 2.5 years: $540\times2.5=$ **Rs 1350**.

**Your turn:** SI on Rs 7500 at 4% for 3 years. (Answer: Rs 900)

### Type 2. Finding the principal, rate or time

**How you spot it:** "At what rate will Rs 5000 earn Rs 1200 in 3 years?", "In how many years will Rs 2000 earn Rs 900 at 9%?", "What sum earns Rs 1800 at 12% in 3 years?"

**Think:** rearrange the same formula. Whatever is missing, divide the interest by the rest.

$$P=\dfrac{100\times\text{SI}}{R\,T}\qquad R=\dfrac{100\times\text{SI}}{P\,T}\qquad T=\dfrac{100\times\text{SI}}{P\,R}$$

**Example 1 (principal).** SI Rs 1800, rate 12%, time 3 years.
- $P=\dfrac{1800\times100}{12\times3}=$ **Rs 5000**.

**Example 2 (time).** Rs 2000 earns Rs 900 at 9%.
- $T=\dfrac{900\times100}{2000\times9}=$ **5 years**.

**Example 3 (rate).** Rs 3500 earns Rs 1260 in 9 years.
- $R=\dfrac{1260\times100}{3500\times9}=$ **4%**.

**Your turn:** Rs 8000 earns Rs 2400 in 5 years. Rate? (Answer: 6%. One year gives 480, and $\dfrac{480}{8000}=6\%$.)

### Type 3. Time in months or days

**How you spot it:** "for 9 months", "for 146 days", "from 10 January to 20 March".

**Think:** turn time into years first. Months over 12. Days over 365.

**Example 1.** Rs 6000 at 10% for 9 months.
- $\dfrac{6000\times10}{100}\times\dfrac{9}{12}=600\times\dfrac{3}{4}=$ **Rs 450**.

**Example 2.** Rs 9125 at 8% for 73 days.
- One year: $730$. $\dfrac{73}{365}=\dfrac{1}{5}$. Interest $=730\div5=$ **Rs 146**.

**Example 3 (dates).** Rs 7300 at 10% from 10 January to 20 March in a normal year.
- Days: 21 more days of January, 28 of February, 20 of March: $21+28+20=69$ days.
- One year: $730$. $730\times\dfrac{69}{365}=$ **Rs 138**.

**Exam twist:** when two dates are given, count the day of lending or the day of return, **not both**. A rate may also be "per month", which is covered in Type 15.

**Your turn:** SI on Rs 8000 at 9% for 8 months. (Answer: Rs 480. One year gives 720, and $720\times\dfrac{8}{12}$.)

### Type 4. The amount is given

**How you spot it:** "A sum becomes Rs 6200 in 3 years. If P was Rs 5000, find the rate", or "What sum amounts to Rs 7800 in 5 years at 6%?"

**Think:** subtract to get the SI, or use Amount $=P(1+\frac{RT}{100})$.

**Example 1.** Rs 5000 becomes Rs 6200 in 3 years. Rate?
- SI $=1200$. $R=\dfrac{1200\times100}{5000\times3}=$ **8%**.

**Example 2.** What sum becomes Rs 7800 in 5 years at 6%?
- $RT=30$. $P=\dfrac{7800}{1.3}=$ **Rs 6000**.

**Example 3.** Rs 9000 becomes Rs 11880 in 8 years. Rate?
- SI $=2880$. $R=\dfrac{2880\times100}{9000\times8}=$ **4%**.

**Your turn:** Rs 6000 becomes Rs 8400 in 5 years. Rate? (Answer: 8%. SI is 2400, and $\dfrac{2400\times100}{6000\times5}$.)

### Type 5. A sum becomes n times (doubling, tripling)

**How you spot it:** "A sum doubles itself in 8 years. Find the rate", "In how many years will it become 3 times at 10%?"

**Think:** if a sum becomes $n$ times, the **interest equals $(n-1)$ times the principal**. So $RT=100(n-1)$.

- Doubling: $RT=100$.
- Tripling: $RT=200$.
- Becoming 4 times: $RT=300$.

**Example 1.** Doubles in 8 years. $R=\dfrac{100}{8}=$ **12.5%**.

**Example 2.** At 10%, in how many years does it triple? $T=\dfrac{200}{10}=$ **20 years**.

**Example 3.** Becomes 4 times in 15 years. $R=\dfrac{300}{15}=$ **20%**.

**Exam twist:** "A sum doubles in 8 years. In how many years will it become 5 times?" Interest per year is $\frac{1}{8}$ of $P$. Four times $P$ needs $4\times8=$ **32 years**. The time grows with $(n-1)$, not with $n$.

**Your turn:** at 20%, in how many years does a sum become 3 times? (Answer: 10 years. $RT=200$.)

### Type 6. Two amounts at two different times

**How you spot it:** "A sum amounts to Rs 5800 in 2 years and Rs 7000 in 5 years. Find the sum and the rate."

**Think:** the extra years add the same interest each year. The gap between the two amounts is the interest for the extra years.

**Example 1.** Rs 5800 after 2 years, Rs 7000 after 5 years.
- Gap $=1200$ for 3 years, so one year $=400$.
- $P=5800-2\times400=$ **Rs 5000**. Rate $=\dfrac{400}{5000}=$ **8%**.

**Example 2.** Rs 8800 after 2 years, Rs 10400 after 6 years.
- Gap $=1600$ for 4 years, so one year $=400$.
- $P=8800-800=$ **Rs 8000**. Rate $=\dfrac{400}{8000}=$ **5%**.

**Your turn:** Rs 5900 after 3 years, Rs 6800 after 6 years. Sum and rate? (Answer: Rs 5000 and 6%. One year is 300, and $5900-900=5000$.)

### Type 7. Rate equals time

**How you spot it:** "A sum lent at R% for R years", "the rate of interest and the number of years are equal".

**Think:** $R=T$, so $\text{SI}=\dfrac{P\times R^2}{100}$. Find $R^2$, then take the square root.

**Example 1.** SI on Rs 4000 is Rs 1440 and rate equals time.
- $R^2=\dfrac{1440\times100}{4000}=36$. $R=$ **6%**.

**Example 2.** The interest earned is $\frac{1}{4}$ of the sum, and rate equals time.
- $\dfrac{R^2}{100}=\dfrac{1}{4}$, so $R^2=25$. $R=$ **5%** (and 5 years).

**Your turn:** SI on Rs 2500 is Rs 900 and rate equals time. Rate? (Answer: 6%. $R^2=\dfrac{900\times100}{2500}=36$.)

### Type 8. Same interest on two different sums

**How you spot it:** "The SI on Rs 3000 at 4% for 5 years equals the SI on Rs 2500 at 6% for how many years?"

**Think:** the interest is $P\times R\times T$ divided by 100, so equal interest means $P_1R_1T_1=P_2R_2T_2$. Cancel 100 and solve.

**Example 1.** $3000\times4\times5=2500\times6\times T$, so $60000=15000T$, and $T=$ **4 years**.

**Example 2.** SI on Rs 3000 at 5% for 4 years equals SI on Rs 1500 at 8% for how many years?
- $3000\times5\times4=60000$. $1500\times8=12000$ per year.
- $T=60000\div12000=$ **5 years**.

**Your turn:** SI on Rs 2000 at 6% for 5 years equals SI on Rs 3000 at 4% for how many years? (Answer: 5 years. Both sides are 600.)

### Type 9. Splitting a sum so that the interests are equal

**How you spot it:** "Rs 5500 is divided into two parts. One is lent at 4% for 5 years and the other at 6% for 4 years, and the interests are equal. Find the parts."

**Think:** equal interest means $P_1R_1T_1=P_2R_2T_2$, so $P_1:P_2$ is the **inverse** of $R_1T_1:R_2T_2$. Then share the total in that ratio.

**Example 1.** Rs 5500 into parts at 4% for 5 years and 6% for 4 years.
- $R_1T_1=20$, $R_2T_2=24$. Equal interest means $P_1\times20=P_2\times24$, so $P_1:P_2=24:20=6:5$.
- That gives parts $3000$ and $2500$. Check: $3000\times20=60000$ and $2500\times24=60000$.
- Larger part: **Rs 3000**.

**Example 2.** Rs 5400 into parts at 10% for 4 years and 12% for 5 years, equal interest.
- $R_1T_1=40$, $R_2T_2=60$. $P_1:P_2=60:40=3:2$.
- Parts: $3240$ and $2160$. Smaller part: **Rs 2160**.

**Your turn:** Rs 3300 into parts at 5% for 4 years and 6% for 5 years, equal interest. Smaller part? (Answer: Rs 1320. $20P_1=30P_2$, so $P_1:P_2=3:2$, giving 1980 and 1320.)

### Type 10. A sum split in two rates with total interest given

**How you spot it:** "Rs 12000 is lent in two parts at 6% and 9%. The yearly interest is Rs 840. Find the parts."

**Think:** this is a mixture. Find the average rate $=\dfrac{\text{total interest}}{\text{total sum}}$. Then the parts are in the ratio of the distances from the average (alligation).

**Example 1.** Rs 12000 at 6% and 9%, yearly interest Rs 840.
- Average rate $=\dfrac{840}{12000}=7\%$.
- Distances: $9-7=2$ and $7-6=1$. Ratio part at 6% : part at 9% $=2:1$.
- Part at 6% $=$ **Rs 8000**. Part at 9% $=$ Rs 4000.

**Example 2.** Rs 10000 at 5% and 8%, yearly interest Rs 740.
- Average $=7.4\%$. Ratio of 5% : 8% $=(8-7.4):(7.4-5)=0.6:2.4=1:4$.
- Part at 5% is **Rs 2000**, part at 8% is Rs 8000.

**Your turn:** Rs 15000 at 6% and 10%, yearly interest Rs 1000. Part at 10%? (Answer: Rs 2500. Average is $\frac{20}{3}\%$, ratio 6% : 10% is $5:1$, giving 12500 and 2500.)

### Type 11. Rates that change from year to year

**How you spot it:** "Interest is 5% for the first 2 years, 8% for the next 3 years and 10% for the last 2 years."

**Think:** the principal never changes, so just add the percentages earned in each period.

**Example 1.** Rs 5000 for 7 years at 6% for 2, 8% for 3, 10% for 2.
- Total percent $=12+24+20=56$.
- SI $=56\%$ of $5000=$ **Rs 2800**.

**Example 2.** Rs 4000 at 5% for 3 years then 7% for 2 years.
- $15+14=29\%$ of 4000 $=$ **Rs 1160**.

**Your turn:** Rs 2000 at 4% for 2 years, 6% for 3 years, 8% for 2 years. SI? (Answer: Rs 840. $8+18+16=42\%$ of 2000.)

### Type 12. Borrow at one rate, lend at another (gain)

**How you spot it:** "A man borrows Rs 8000 at 6% and lends it at 9% for 3 years. Find his gain."

**Think:** he gains the **difference in rates** on the same sum for the same time.

**Example 1.** Gain $=\dfrac{8000\times(9-6)\times3}{100}=$ **Rs 720**.

**Example 2 (find the sum).** Gain of Rs 360 in 2 years from a rate difference of 3%.
- $P=\dfrac{360\times100}{3\times2}=$ **Rs 6000**.

**Your turn:** a man borrows Rs 5000 at a rate 3% lower than the rate at which he lends it. Over 4 years, what is his gain? (Answer: Rs 600. $5000\times3\times4\div100$.)

### Type 13. "If the rate were higher, interest would be more"

**How you spot it:** "If the rate were 2% higher, the interest in 3 years would be Rs 480 more. Find the sum."

**Think:** the extra interest comes only from the extra rate. So extra $=\dfrac{P\times(\text{extra rate})\times T}{100}$.

**Example 1.** Extra rate 2%, 3 years, Rs 480 more.
- $P=\dfrac{480\times100}{2\times3}=$ **Rs 8000**.

**Example 2.** Extra rate 3%, 4 years, Rs 540 more.
- $P=\dfrac{540\times100}{3\times4}=$ **Rs 4500**.

**Your turn:** extra rate 2%, 5 years, Rs 600 more. Sum? (Answer: Rs 6000. $\dfrac{600\times100}{2\times5}$.)

### Type 14. Paying a debt in equal yearly instalments

**How you spot it:** "A sum is to be cleared in two equal yearly instalments at SI."

**Think:** work out what the debt would be if left for the full time. The instalment paid early is treated as earning interest until the debt ends. Equate the two.

**Example.** Rs 3500 at 10% SI for 2 years. Cleared in two equal yearly instalments, the first at the end of year 1. Find each.
- Debt at end of 2 years: $3500\times1.2=4200$.
- First instalment $x$ earns interest for 1 year: $1.1x$. Second instalment: $x$.
- $1.1x+x=4200$, so $2.1x=4200$ and $x=$ **Rs 2000**.

**Your turn:** Rs 7000 at 10% SI for 2 years, cleared in two equal yearly instalments. Each instalment? (Answer: Rs 4000. Debt 8400, and $2.1x=8400$.)

### Type 15. Rate per month or per paise

**How you spot it:** "1.5% per month", "2 paise per rupee per month", "interest at Rs 2 per hundred per month".

**Think:** turn a monthly rate into a yearly one by multiplying by 12, or keep the time in months and use the monthly rate directly.

**Example 1.** Rs 5000 at 1.5% per month for 8 months.
- $5000\times\dfrac{1.5}{100}\times8=$ **Rs 600**.

**Example 2.** 2 paise per rupee per month. Yearly rate?
- 2 paise per rupee is 2%. That is 2% every month, so per year $2\times12=$ **24%**.

**Example 3.** Rs 2400 at 2.5% per month for 1 year.
- Yearly rate $=30\%$. Interest $=30\%$ of $2400=$ **Rs 720**.

**Your turn:** Rs 4000 at 1.5% per month for 10 months. SI? (Answer: Rs 600. $1.5\times10=15\%$ of 4000.)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Find SI | $\frac{PRT}{100}$. One year first, then multiply. |
| Find amount | $P+\text{SI}$, or $P\times\frac{100+RT}{100}$. |
| Missing P, R or T | Divide $100\times\text{SI}$ by the other two. |
| Months or days | Months over 12. Days over 365. |
| Amount given, P not | Use $A=P(1+\frac{RT}{100})$. |
| Becomes n times | $RT=100(n-1)$. |
| Two amounts at two times | Gap divided by extra years gives yearly interest. |
| Rate equals time | $R^2=\frac{100\,\text{SI}}{P}$. |
| Equal interest on two sums | $P_1R_1T_1=P_2R_2T_2$. |
| Splitting for equal interest | Ratio of parts is inverse of $RT$. |
| Total interest, two rates | Find average rate, then alligation. |
| Changing rates by year | Add the percentages earned in each period. |
| Borrow low, lend high | Gain $=P\times$ difference in rate $\times T\div100$. |
| Extra rate gives extra interest | Use only the extra rate in the formula. |
| Equal instalments | Early instalments earn interest until the end. |
| Rate per month | Multiply by 12 for the yearly rate. |

Doubling table to learn (SI):

| Becomes | Needs $RT$ |
|---|---|
| 2 times | 100 |
| 3 times | 200 |
| 4 times | 300 |
| 5 times | 400 |

Rate and time in which a sum doubles:

| Rate | 5% | 10% | 12.5% | 20% | 25% |
|---|---|---|---|---|---|
| Years to double | 20 | 10 | 8 | 5 | 4 |

## 5. Mistakes that cost marks

1. **Not changing months or days into years.** 9 months is $\frac{9}{12}$ year. Writing 9 will give an answer twelve times too big.
2. **Treating "becomes 3 times" as interest equal to $3P$.** The sum becomes 3 times, so the interest is $2P$.
3. **Forgetting to subtract the principal.** If the question gives the amount, the SI is amount minus principal.
4. **Mixing rate per month with rate per year.** Check the time unit and rate unit match.
5. **Counting both end days in a date question.** Count only one of them.
6. **Using the gap between two amounts as the interest for the whole time.** It is the interest for the **extra** years only.
7. **Averaging two rates directly when the sums are unequal.** Use the weighted average, total interest over total sum.

## 6. Practice questions

Do these on paper. Do the first 10 untimed. Do the next 15 with 90 seconds each. Do the last group like an exam.

### Level 1: single idea

1. Find the SI on Rs 4800 at 7% per annum for 5 years.
2. Find the amount on Rs 6500 at 8% per annum for 3 years.
3. At what rate will Rs 5000 earn Rs 1500 in 5 years?
4. In how many years will Rs 4800 earn Rs 1344 at 7%?
5. What sum earns Rs 2100 in 5 years at 6%?
6. Find the SI on Rs 9000 at 12% for 8 months.
7. A sum doubles in 10 years at SI. Find the rate.
8. Find the SI on Rs 7300 at 5% for 146 days.
9. Rs 8000 becomes Rs 10400 in 3 years. Find the rate.
10. Find the SI on Rs 12000 at 7.5% for 1 year.

### Level 2: mixed

11. A sum triples in 8 years at SI. Find the rate.
12. A sum becomes 4 times in 15 years at SI. Find the rate.
13. A sum amounts to Rs 6050 in 3 years and Rs 7100 in 6 years. Find the rate.
14. The SI on a sum at 6% for 2 years is Rs 540. Find the sum.
15. Rs 10000 is lent in two parts at 4% and 9%. The total yearly interest is Rs 700. Find the part lent at 9%.
16. Find the SI on Rs 20000 at 2.5% per annum for 3 years.
17. Rs 4000 is lent at 5% for 2 years and Rs 4000 at 6% for 3 years. Find the total interest.
18. Rs 1800 is the SI on a sum at 6% for 3 years. Find the sum.
19. Find the difference between the SI on Rs 4000 at 9% for 2 years and the SI on Rs 3000 at 6% for 3 years.
20. A sum of Rs 1600 gives SI of Rs 1024 when the rate equals the time. Find the rate.
21. Two-thirds of a sum is lent at 6% and the rest at 9%. Find the average rate on the whole sum.
22. Find the amount on Rs 5100 at 8% for $1\frac{1}{2}$ years.
23. Find the SI on Rs 8000 at 9% for 9 months.
24. Find the SI on Rs 7300 at 10% from 15 January to 10 March in a normal year.
25. The SI on Rs 1600 at 5% is Rs 640. Find the time.

### Level 3: exam style

26. The SI on Rs 2500 at 6% for 4 years equals the SI on Rs 3000 for 5 years. Find the second rate.
27. A sum amounts to Rs 14400 in 4 years at 5%. Find the sum.
28. The SI on a sum for 2 years at 5% is Rs 400. Find the sum.
29. The SI on a sum for 3 years at 4% is Rs 360. Find the sum.
30. Find the SI on Rs 4000 at 1.5% per month for 10 months.
31. A sum amounts to Rs 6200 in 2 years at 12%. Find the sum.
32. A sum amounts to Rs 9800 in 3 years and Rs 11600 in 6 years. Find the rate.
33. The SI on Rs 5000 at R% for R years is Rs 1250. Find R.
34. Rs 6200 is divided into two parts. The first is lent at 5% for 3 years and the second at 8% for 2 years, and the interests are equal. Find the larger part.
35. If the rate had been 2% higher, a sum would have earned Rs 300 more in 3 years. Find the sum.
36. Rs 60000 is divided in the ratio 25 : 35 : 40 and lent at 4%, 8% and 10% respectively. Find the total yearly interest.
37. Rs 2500 is lent for 7 years at 4% for the first 2 years, 6% for the next 3 years and 8% for the last 2 years. Find the total interest.
38. Find the difference between the SI on Rs 4000 at 8% for 5 years and the SI on Rs 5000 at 6% for 4 years.
39. A sum doubles in 8 years at SI. In how many years will it become 5 times?
40. A sum becomes 1.5 times in 5 years at SI. Find the rate.
41. A sum amounts to Rs 13200 in 4 years at 8%. Find the sum.
42. Find the SI on Rs 7300 at 12% from 10 January to 5 April in a normal year.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | Rs 1680 | $\frac{4800\times7\times5}{100}$ |
| 2 | Rs 8060 | SI $=1560$, so $6500+1560$ |
| 3 | 6% | $\frac{1500\times100}{5000\times5}$ |
| 4 | 4 years | $\frac{1344\times100}{4800\times7}$ |
| 5 | Rs 7000 | $\frac{2100\times100}{6\times5}$ |
| 6 | Rs 720 | One year $=1080$, times $\frac{8}{12}$ |
| 7 | 10% | $RT=100$, so $R=\frac{100}{10}$ |
| 8 | Rs 146 | One year $=365$, times $\frac{146}{365}$, which is $\frac{2}{5}$ |
| 9 | 10% | SI $=2400$, $\frac{2400\times100}{8000\times3}$ |
| 10 | Rs 900 | $12000\times0.075$ |
| 11 | 25% | $RT=200$, $R=\frac{200}{8}$ |
| 12 | 20% | $RT=300$, $R=\frac{300}{15}$ |
| 13 | 7% | Gap $=1050$ for 3 years, so 350 a year. $P=6050-1050=5000$, $\frac{350}{5000}$ |
| 14 | Rs 4500 | $\frac{540\times100}{6\times2}$ |
| 15 | Rs 6000 | Average $7\%$, ratio 4% : 9% $=2:3$, so 4000 and 6000 |
| 16 | Rs 1500 | $20000\times7.5\%$ |
| 17 | Rs 1120 | $400+720$ |
| 18 | Rs 10000 | $\frac{1800\times100}{6\times3}$ |
| 19 | Rs 180 | $720-540$ |
| 20 | 8% | $R^2=\frac{1024\times100}{1600}=64$ |
| 21 | 7% | $\frac{2}{3}\times6+\frac{1}{3}\times9$ |
| 22 | Rs 5712 | $RT=12$, $5100\times1.12$ |
| 23 | Rs 540 | One year $=720$, times $\frac{9}{12}$ |
| 24 | Rs 108 | $16+28+10=54$ days; $730\times\frac{54}{365}$ |
| 25 | 8 years | $\frac{640\times100}{1600\times5}$ |
| 26 | 4% | SI $=600$, $\frac{600\times100}{3000\times5}$ |
| 27 | Rs 12000 | $RT=20$, $\frac{14400}{1.2}$ |
| 28 | Rs 4000 | $\frac{400\times100}{5\times2}$ |
| 29 | Rs 3000 | $\frac{360\times100}{4\times3}$ |
| 30 | Rs 600 | $1.5\times10=15\%$ of 4000 |
| 31 | Rs 5000 | $RT=24$, $\frac{6200}{1.24}$ |
| 32 | 7.5% | Gap $=1800$ for 3 years, so 600 a year. $P=9800-1800=8000$, $\frac{600}{8000}$ |
| 33 | 5% | $R^2=\frac{1250\times100}{5000}=25$ |
| 34 | Rs 3200 | $15P_1=16P_2$, ratio $16:15$, so $6200\times\frac{16}{31}$ |
| 35 | Rs 5000 | $\frac{300\times100}{2\times3}$ |
| 36 | Rs 4680 | $600+1680+2400$ |
| 37 | Rs 1050 | $8+18+16=42\%$ of 2500 |
| 38 | Rs 400 | $1600-1200$ |
| 39 | 32 years | Doubling needs 8 years for $P$; 5 times needs $4P$, so $4\times8$ |
| 40 | 10% | $RT=50$, $R=\frac{50}{5}$ |
| 41 | Rs 10000 | $RT=32$, $\frac{13200}{1.32}$ |
| 42 | Rs 204 | $21+28+31+5=85$ days; $876\times\frac{85}{365}$ |
