# Compound Interest

> Read this like a class, not like a formula list. Every idea comes with a picture in your head, then a solved example, then one for you to try. Do the "Your turn" boxes with a pen before reading the answer next to them.

## 0. Start here: what is this topic really about?

Suppose you put Rs 5000 in a bank that pays 10% a year. After one year you have Rs 5500. Now the clever part: in year two the bank pays 10% on **Rs 5500**, not on the original Rs 5000. Your earlier interest has started earning interest of its own. That snowball is **compound interest** (CI).

In simple interest, the interest each year is the same. In compound interest, the interest each year is **bigger than the last**, because the base keeps growing.

Questions look like these:

- "Find the compound interest on Rs 8000 at 10% per annum for 2 years."
- "What sum becomes Rs 9261 in 3 years at 5% compound interest?"
- "Find the difference between CI and SI on Rs 5000 at 10% for 2 years."
- "Interest is compounded half-yearly. Find the amount."
- "A town's population grows 10% a year. What is it after 2 years?"
- "A loan is cleared in two equal instalments. Find each instalment."

**What the exam gives you:** principal, rate, time, and whether interest is yearly, half-yearly or quarterly. Sometimes the amount, or the difference between CI and SI, is given instead. **What it asks for:** the amount, the CI, the principal, the rate, the time, or an instalment.

**How many marks to expect:** SSC CGL and CHSL carry 2 to 3 questions on CI and SI together. RRB NTPC and Group D carry 1 or 2. IBPS and SBI Clerk and PO papers carry 1 to 3, often hidden inside data sets, and almost always in a form where the CI-SI difference or the half-yearly rule helps. PSU and APPSC papers carry 1 or 2. The chapter is fast if you remember that one formula and a few multiplication tables.

## 1. The only ideas you must understand

### Year-by-year, the long way

Rs 5000 at 10% for 2 years, the way a bank does it.

- Year 1 interest: 10% of 5000 $=500$. Amount at the end of year 1: $5500$.
- Year 2 interest: 10% of 5500 $=550$. Amount at the end of year 2: $6050$.
- Compound interest $=6050-5000=1050$.

For comparison, simple interest would give $500+500=1000$. The extra Rs 50 is **interest on interest**: 10% of the first year's Rs 500.

### Turning that into one formula

Every year the money gets multiplied by the same number. At 10%, that number is $1.10$. So:

$$A=P\left(1+\dfrac{R}{100}\right)^{n}\qquad\text{CI}=A-P$$

$P$ is the principal, $R$ the rate per year, $n$ the number of years.

Check: $5000\times1.1\times1.1=6050$. Same answer as the long way.

### What the formula really says

"Multiply by $(1+\frac{R}{100})$, once for each year." That is all. If you remember that picture, you never mix up the formula.

### The key difference from simple interest

- **Simple interest:** same rupees every year. Straight line.
- **Compound interest:** more rupees every year. Curve that bends upward.
- For **one year**, CI and SI are exactly equal. The difference only starts from year 2.

### Trying it: Rs 5000 at 10% for 2 years. Amount and CI?

Step 1. Multiplier for one year $=1.10$.

Step 2. Amount $=5000\times1.1\times1.1=5000\times1.21=6050$.

Step 3. CI $=6050-5000=1050$.

**Answer: Amount = Rs 6050 and CI = Rs 1050.**

**Sense check you should always do:** CI must be a little **more** than SI for the same sum and rate when $n\ge2$. If your CI is smaller than the SI, something is wrong. Also, the amount must be bigger than the principal.

### Your turn

Find the amount on Rs 4000 at 5% per annum for 2 years. (Answer: Rs 4410. $4000\times1.05\times1.05=4000\times1.1025$.)

## 2. The shortcuts that save time

### Shortcut 1. Learn the multiplier table

The chapter is mostly multiplication of the same number by itself. If you know these values cold, most sums finish in seconds.

| Rate | Multiplier | After 2 years | After 3 years |
|---|---|---|---|
| 5% | $\frac{21}{20}$ | $\frac{441}{400}$ | $\frac{9261}{8000}$ |
| 10% | $\frac{11}{10}$ | $\frac{121}{100}$ | $\frac{1331}{1000}$ |
| 20% | $\frac{6}{5}$ | $\frac{36}{25}$ | $\frac{216}{125}$ |
| 25% | $\frac{5}{4}$ | $\frac{25}{16}$ | $\frac{125}{64}$ |
| 12.5% | $\frac{9}{8}$ | $\frac{81}{64}$ | $\frac{729}{512}$ |

### Shortcut 2. Use the fraction form so the principal cancels

Pick a principal that cancels with the denominator. Sums in the exam are almost always built that way.

**Example.** Rs 4096 at 12.5% for 3 years. 12.5% is $\frac{1}{8}$, so the multiplier is $\frac{9}{8}$.
- $4096\times\left(\dfrac{9}{8}\right)^3=4096\times\dfrac{729}{512}=8\times729=$ **Rs 5832**.

**Example.** Rs 6250 at 8% for 2 years. 8% is $\frac{2}{25}$, so the multiplier is $\frac{27}{25}$.
- $6250\times\dfrac{729}{625}=10\times729=$ **Rs 7290**.

If the principal is a multiple of $20^n$, or $10^n$, or $8^n$, or $25^n$, the fractions cancel. That is a strong hint that you are using the right method.

### Shortcut 3. Net percentage growth

Over $n$ years the money grows by a fixed **net percent**. For 2 years at $r\%$:

$$\text{Net growth}=r+r+\dfrac{r\times r}{100}$$

At 10%: $10+10+1=21\%$. At 20%: $20+20+4=44\%$. At 5%: $5+5+0.25=10.25\%$.

For 3 years, apply the same idea twice. At 10%: 21% for two years, then $21+10+\frac{21\times10}{100}=33.1\%$. At 20%: 44% for two years, then $44+20+\frac{44\times20}{100}=72.8\%$.

**Example.** Rs 5000 at 20% for 2 years. Net growth 44%, so CI $=0.44\times5000=$ **Rs 2200**.

### Shortcut 4. CI is SI plus interest on interest

For 2 years, CI $=$ SI $+$ interest on the first year's interest. That tells you the exact difference:

$$\text{CI}-\text{SI (2 years)}=P\left(\dfrac{R}{100}\right)^2$$

Use this whenever a question gives or asks for the difference. We use it in Type 7 and Type 8.

## 3. Types of questions and how to crack each one

Every type you can meet is below. Each has: how you spot it, how to think, an example, and an exam twist where useful.

### Type 1. Direct: find the amount and the CI

**How you spot it:** "Find the compound interest on Rs 8000 at 10% per annum for 2 years."

**Think:** multiply by $(1+\frac{R}{100})$ once for each year. Subtract the principal for the CI.

**Example 1.** Rs 8000, 10%, 2 years.
- Amount $=8000\times1.21=$ **Rs 9680**. CI $=9680-8000=$ **Rs 1680**.

**Example 2.** Rs 5000 at 20% for 3 years.
- Amount $=5000\times1.728=$ **Rs 8640**.

**Example 3.** Rs 4096 at 12.5% for 3 years.
- $4096\times\dfrac{729}{512}=$ **Rs 5832**.

**Example 4.** CI on Rs 2000 at 10% for 2 years.
- $2000\times1.21=2420$. CI $=$ **Rs 420**.

**Your turn:** CI on Rs 5000 at 20% for 2 years. (Answer: Rs 2200. $5000\times1.44=7200$, minus 5000.)

### Type 2. Finding the principal

**How you spot it:** "What sum becomes Rs 9261 in 3 years at 5% compound interest?"

**Think:** work backwards. Divide the amount by the growth multiplier.

$$P=\dfrac{A}{\left(1+\frac{R}{100}\right)^n}$$

**Example 1.** Rs 9261 after 3 years at 5%.
- $P=9261\div\dfrac{9261}{8000}=$ **Rs 8000**. (Notice $9261=21^3$, a sign you are on track.)

**Example 2.** The CI for 2 years at 10% is Rs 1260. Find the sum.
- CI is 21% of $P$. $P=\dfrac{1260}{0.21}=$ **Rs 6000**.

**Example 3.** The CI for 2 years at 5% is Rs 1025. Find the sum.
- Net growth $=10.25\%$. $P=\dfrac{1025}{0.1025}=$ **Rs 10000**.

**Your turn:** a sum becomes Rs 9680 in 2 years at 10%. Find it. (Answer: Rs 8000. $9680\div1.21$.)

### Type 3. Finding the rate

**How you spot it:** "Rs 5000 becomes Rs 7200 in 2 years at compound interest. Find the rate."

**Think:** find the growth ratio $\frac{A}{P}$. Then ask: "what number multiplied by itself $n$ times gives this?"

**Example 1.** Rs 5000 becomes Rs 7200 in 2 years.
- Ratio $=\dfrac{7200}{5000}=1.44$. Square root of $1.44$ is $1.2$. Rate $=$ **20%**.

**Example 2.** Rs 12500 becomes Rs 15125 in 2 years.
- Ratio $=1.21$. Square root is $1.1$. Rate $=$ **10%**.

**Example 3 (consecutive amounts).** A sum is Rs 8820 after 2 years and Rs 9261 after 3 years.
- The third year multiplied the amount by $\dfrac{9261}{8820}=1.05$. Rate $=$ **5%**.

**Exam twist:** with two consecutive amounts, you do not need the principal. One year's growth ratio is the rate. In Example 3 you can also recover the principal: $\dfrac{8820}{1.05^2}=$ Rs 8000.

**Your turn:** Rs 6250 becomes Rs 7290 in 2 years. Rate? (Answer: 8%. Ratio $1.1664$, square root $1.08$.)

### Type 4. Finding the time

**How you spot it:** "In how many years will Rs 4000 become Rs 5324 at 10% CI?"

**Think:** find the ratio $\frac{A}{P}$. Then match it to the multiplier table: which power of $(1+\frac{R}{100})$ equals it?

**Example 1.** Rs 4000 becomes Rs 5324 at 10%.
- Ratio $=1.331=1.1^3$. Time $=$ **3 years**.

**Example 2.** Rs 10000 becomes Rs 14400 at 20%.
- Ratio $=1.44=1.2^2$. Time $=$ **2 years**.

**Example 3.** Rs 8000 becomes Rs 9261 at 5%.
- Ratio $=1.157625=1.05^3$. Time $=$ **3 years**.

**Exam twist:** if the numbers do not match the table, use the options. Try each option as $n$ and see which gives the amount.

**Your turn:** Rs 2500 becomes Rs 3600 at 20%. Time? (Answer: 2 years. $\frac{3600}{2500}=1.44=1.2^2$.)

### Type 5. Interest compounded half-yearly or quarterly

**How you spot it:** "compounded half-yearly", "compounded quarterly", "interest is paid every six months".

**Think:** interest is added more often. So **halve the rate and double the periods** for half-yearly. **Quarter the rate and multiply the periods by 4** for quarterly.

$$A=P\left(1+\dfrac{R/2}{100}\right)^{2n}\quad(\text{half-yearly})\qquad A=P\left(1+\dfrac{R/4}{100}\right)^{4n}\quad(\text{quarterly})$$

**Example 1.** Rs 8000 at 10% per annum compounded half-yearly for 1 year.
- Half-yearly rate $=5\%$. Periods $=2$.
- $8000\times1.05^2=8000\times1.1025=$ **Rs 8820**.

**Example 2.** Rs 160000 at 8% per annum compounded quarterly for 6 months.
- Quarterly rate $=2\%$. Periods $=2$.
- $160000\times1.02^2=$ **Rs 166464**.

**Example 3.** Rs 16000 at 10% per annum compounded half-yearly for $1\frac{1}{2}$ years.
- Rate $5\%$, periods $3$. $16000\times1.157625=$ **Rs 18522**.

**Exam twist:** the **effective** annual rate of 10% compounded half-yearly is $1.05^2-1=10.25\%$, which is more than 10%. More frequent compounding always gives more money.

**Your turn:** CI on Rs 20000 at 10% per annum compounded half-yearly for 1 year. (Answer: Rs 2050. Amount $20000\times1.1025=22050$.)

### Type 6. Time that includes a fraction of a year

**How you spot it:** "for $2\frac{1}{2}$ years", "for 2 years 6 months".

**Think:** compound for the whole years. Then add **simple interest** on that amount for the leftover fraction.

**Example 1.** Rs 8000 at 10% for $2\frac{1}{2}$ years.
- After 2 years: $8000\times1.21=9680$.
- Extra half year at simple interest: $9680\times\left(1+\dfrac{10}{100}\times\dfrac{1}{2}\right)=9680\times1.05=$ **Rs 10164**.

**Example 2.** Rs 4000 at 10% for $1\frac{1}{2}$ years.
- After 1 year: $4400$. Half year more: $4400\times1.05=$ **Rs 4620**.

**Exam twist:** the exam may say "compounded annually" but give a fractional time. The rule above is what they expect. If it says "compounded half-yearly", use the half-yearly rule from Type 5 instead.

**Your turn:** Rs 10000 at 10% for $2\frac{1}{2}$ years. Amount? (Answer: Rs 12705. $12100\times1.05$.)

### Type 7. Difference between CI and SI

**How you spot it:** "Find the difference between CI and SI on Rs 5000 at 10% for 2 years."

**Think:** use the ready formulas. They save a lot of time.

$$\text{2 years: } P\left(\dfrac{R}{100}\right)^2\qquad\text{3 years: } P\left(\dfrac{R}{100}\right)^2\left(3+\dfrac{R}{100}\right)$$

**Why the 2-year formula works:** in year 2 the extra interest is the interest on year 1's interest. Year 1's interest is $P\cdot\frac{R}{100}$, and the interest on that is $P\cdot\frac{R}{100}\cdot\frac{R}{100}$.

**Example 1.** Rs 5000 at 10% for 2 years.
- $5000\times0.01=$ **Rs 50**.

**Example 2.** Rs 8000 at 5% for 2 years.
- $8000\times0.0025=$ **Rs 20**.

**Example 3.** Rs 10000 at 10% for 3 years.
- $10000\times0.01\times3.1=$ **Rs 310**.
- Check: CI $=13310-10000=3310$, SI $=3000$, difference $=310$.

**Your turn:** Rs 6000 at 10% for 2 years. Difference between CI and SI? (Answer: Rs 60.)

### Type 8. Difference given, find the sum or the rate

**How you spot it:** "The difference between CI and SI for 2 years is Rs 40. The rate is 5%. Find the sum."

**Think:** put the given numbers into the same formula and solve for the missing one.

**Example 1 (find the sum).** Difference Rs 40, rate 5%, 2 years.
- $P\times(0.05)^2=40$, so $P=\dfrac{40}{0.0025}=$ **Rs 16000**.

**Example 2 (find the rate).** The difference on Rs 8000 for 2 years is Rs 20.
- $\left(\dfrac{R}{100}\right)^2=\dfrac{20}{8000}=0.0025$, so $\dfrac{R}{100}=0.05$. Rate $=$ **5%**.

**Example 3 (3 years).** Rs 310 is the difference for 3 years at 10%. Find the sum.
- $P\times0.01\times3.1=310$, so $P=\dfrac{310}{0.031}=$ **Rs 10000**.

**Your turn:** difference for 2 years at 6% is Rs 72. Find the sum. (Answer: Rs 20000. $\dfrac{72}{0.0036}$.)

### Type 9. Both SI and CI are given for 2 years

**How you spot it:** "The SI for 2 years on a sum is Rs 1200 and the CI is Rs 1260. Find the rate and the sum."

**Think:** the first year's interest is half the SI. The CI-SI difference is the interest on that first year's interest. So the rate is

$$R=\dfrac{\text{CI}-\text{SI}}{\tfrac{1}{2}\text{SI}}\times100=\dfrac{2(\text{CI}-\text{SI})}{\text{SI}}\times100$$

**Example.** SI $=1200$, CI $=1260$ for 2 years.
- $R=\dfrac{2\times60}{1200}\times100=$ **10%**.
- Sum: SI $=\dfrac{P\times10\times2}{100}=1200$, so $P=$ **Rs 6000**.

**Your turn:** SI $=1000$ and CI $=1050$ for 2 years. Rate and sum? (Answer: 10% and Rs 5000. $\frac{2\times50}{1000}=10\%$, and $\frac{1000\times100}{2\times10}=5000$.)

### Type 10. Different rates for different years

**How you spot it:** "10% for the first year, 20% for the second year."

**Think:** multiply the multipliers year by year. Do not average the rates.

**Example 1.** Rs 10000 at 10% for the first year and 20% for the second.
- $10000\times1.1\times1.2=$ **Rs 13200**.

**Example 2.** Same sum, and 10% again in the third year.
- $13200\times1.1=$ **Rs 14520**.

**Example 3.** Rs 4000 at 5%, 10% and 20% in three successive years.
- $4000\times1.05\times1.1\times1.2=$ **Rs 5544**.

**Your turn:** Rs 5000 at 10% in year 1 and 20% in year 2. Amount? (Answer: Rs 6600. $5000\times1.1\times1.2$.)

### Type 11. Population growth and depreciation

**How you spot it:** "The population of a town increases by 10% every year", "a machine loses 10% of its value every year".

**Think:** exactly the same as CI. Growth uses $1+\frac{r}{100}$. A **fall** uses $1-\frac{r}{100}$.

**Example 1.** Population 50000, grows 10% a year. After 2 years?
- $50000\times1.21=$ **60500**.

**Example 2.** A machine worth Rs 80000 loses 10% of its value each year. Value after 2 years?
- $80000\times0.9\times0.9=$ **Rs 64800**.

**Example 3.** Population grows 20% in one year and falls 10% in the next. Starting from 10000?
- $10000\times1.2\times0.9=$ **10800**.

**Example 4 (find the starting value).** After a growth of 10% each year for 2 years, a town has 24200 people. Starting population?
- $\dfrac{24200}{1.21}=$ **20000**.

**Exam twist:** an increase of 20% followed by a fall of 10% is **not** a net rise of 10%. It is $1.2\times0.9=1.08$, a net rise of 8%. In Example 3, it is 8% of 10000, which is 800 more.

**Your turn:** a car worth Rs 80000 depreciates 15% a year. Value after 2 years? (Answer: Rs 57800. $80000\times0.85\times0.85$.)

### Type 12. A sum becomes n times (doubling and tripling)

**How you spot it:** "A sum doubles in 5 years at CI. In how many years will it become 8 times?"

**Think:** if a sum doubles in $t$ years, it doubles **again** in the next $t$ years (multiply by 2 each time). So 4 times in $2t$, 8 times in $3t$, 16 times in $4t$.

- Doubles: $t$ years.
- 4 times: $2t$ years. 8 times: $3t$ years. 16 times: $4t$ years.
- Triples in $t$ years: becomes 9 times in $2t$, 27 times in $3t$.

**Example 1.** Doubles in 5 years. 8 times in $3\times5=$ **15 years**.

**Example 2.** Becomes 4 times in 4 years. 16 times in $2\times4=$ **8 years**.

**Example 3.** Triples in 3 years. 27 times in $3\times3=$ **9 years**.

**Exam twist:** this is a pure CI trick. With simple interest the logic is different (see the Simple Interest chapter). If an exam says "doubles at CI", use the repeated-doubling method.

**Your turn:** a sum becomes 4 times in 6 years at CI. In how many years does it become 16 times? (Answer: 12 years.)

### Type 13. Equal annual instalments

**How you spot it:** "A loan is repaid in two equal annual instalments of Rs 2420 each at 10% CI. Find the loan."

**Think:** the loan is the **present value** of the instalments. Bring each instalment back to today by dividing by the multiplier once for each year.

$$\text{Loan}=\dfrac{X}{1+r}+\dfrac{X}{(1+r)^2}+\dots$$

**Example 1.** Two equal instalments of Rs 2420 each at 10%.
- First: $\dfrac{2420}{1.1}=2200$. Second: $\dfrac{2420}{1.21}=2000$.
- Loan $=$ **Rs 4200**.

**Example 2.** Three equal instalments of Rs 1331 each at 10%.
- $1210+1100+1000=$ **Rs 3310**.

**Example 3.** Two equal instalments of Rs 1440 each at 20%.
- $\dfrac{1440}{1.2}+\dfrac{1440}{1.44}=1200+1000=$ **Rs 2200**.

**Your turn:** two equal instalments of Rs 2205 each at 5%. Loan? (Answer: Rs 4100. $2100+2000$.)

### Type 14. Splitting a sum so the amounts are equal after different times

**How you spot it:** "Rs 4200 is divided into two parts. After 2 years the first part equals the second part after 1 year, at 10% CI."

**Think:** equal amounts means $P_1\times(\text{multiplier for }n_1)=P_2\times(\text{multiplier for }n_2)$. So $P_1:P_2$ is the inverse ratio of the multipliers.

**Example 1.** Rs 4200 into two parts, amounts equal after 2 years and 1 year at 10%.
- $P_1\times1.21=P_2\times1.1$, so $P_1:P_2=1.1:1.21=10:11$.
- Parts: **Rs 2000** and Rs 2200. Check: $2000\times1.21=2420=2200\times1.1$.

**Example 2.** Rs 5500 into two parts, amounts equal after 3 years and 2 years at 20%.
- $P_1:P_2=1.44:1.728=5:6$. Parts: **Rs 2500** and Rs 3000.
- Check: $2500\times1.728=4320=3000\times1.44$.

**Your turn:** Rs 4100 into two parts, amounts equal after 2 years and 1 year at 5%. Find the parts. (Answer: Rs 2000 and Rs 2100. Ratio $1.05:1.1025=20:21$.)

### Type 15. Part payment during the loan

**How you spot it:** "A man borrows Rs 5000 at 10% CI. He pays Rs 2000 at the end of the first year. How much must he pay at the end of the second year to clear the loan?"

**Think:** do it in stages. Grow the loan one year, subtract the payment, and grow what is left.

**Example 1.** Rs 5000 at 10%, Rs 2000 paid after year 1.
- After year 1: $5000\times1.1=5500$. After the payment: $3500$.
- After year 2: $3500\times1.1=$ **Rs 3850**.

**Example 2.** Rs 10000 at 20%, Rs 6000 paid after year 1.
- $10000\times1.2=12000$. Balance $6000$. Year 2: $6000\times1.2=$ **Rs 7200**.

**Your turn:** Rs 8000 at 10%, Rs 3000 paid after year 1. Final payment? (Answer: Rs 6380. $8800-3000=5800$, then $\times1.1$.)

### Type 16. Interest earned in one particular year

**How you spot it:** "Find the CI earned in the third year", "interest for the second year only".

**Think:** that year's interest $=$ amount at its end minus amount at its start. It equals $r$ times the amount at the start of that year.

**Example 1.** Rs 10000 at 10%. Interest of the third year.
- Amount after 2 years $=12100$. Third-year interest $=10\%$ of $12100=$ **Rs 1210**.

**Example 2.** Rs 3000 at 10%. Interest for the second year.
- Amount after year 1 $=3300$. Second-year interest $=$ **Rs 330**.

**Your turn:** Rs 5000 at 20%. Interest for the third year? (Answer: Rs 1440. Amount after 2 years is 7200, and 20% of 7200.)

## 4. One page to revise before the exam

| Situation | What to do |
|---|---|
| Find amount | $A=P\left(1+\frac{R}{100}\right)^n$ |
| Find CI | $A-P$ |
| Find principal | Divide the amount by the multiplier |
| Find rate | Ratio $\frac{A}{P}$, then take the $n$th root |
| Find time | Match $\frac{A}{P}$ to a power of the multiplier |
| Half-yearly | Half the rate, double the periods |
| Quarterly | Quarter the rate, four times the periods |
| Fractional years | Compound the whole years, then SI on the rest |
| CI minus SI, 2 years | $P\left(\frac{R}{100}\right)^2$ |
| CI minus SI, 3 years | $P\left(\frac{R}{100}\right)^2\left(3+\frac{R}{100}\right)$ |
| SI and CI both given | $R=\frac{2(\text{CI}-\text{SI})}{\text{SI}}\times100$ |
| Different rates each year | Multiply the multipliers |
| Population or depreciation | Growth $1+r$, fall $1-r$ |
| Doubles in $t$ years | 4 times in $2t$, 8 times in $3t$ |
| Equal instalments | Divide each by the multiplier, then add |
| Equal amounts after different times | Parts in inverse ratio of multipliers |
| Part payment | Grow, subtract, grow again |
| Interest of one year | $r\times$ amount at the start of that year |

Memory table: $\left(1+\frac{r}{100}\right)^n$

| Rate | $n=1$ | $n=2$ | $n=3$ | $n=4$ | $n=5$ |
|---|---|---|---|---|---|
| 4% | 1.04 | 1.0816 | 1.124864 | 1.169859 | 1.216653 |
| 5% | 1.05 | 1.1025 | 1.157625 | 1.215506 | 1.276282 |
| 6% | 1.06 | 1.1236 | 1.191016 | 1.262477 | 1.338226 |
| 8% | 1.08 | 1.1664 | 1.259712 | 1.360489 | 1.469328 |
| 10% | 1.1 | 1.21 | 1.331 | 1.4641 | 1.61051 |
| 12.5% | 1.125 | 1.265625 | 1.423828 | 1.601807 | 1.802032 |
| 15% | 1.15 | 1.3225 | 1.520875 | 1.749006 | 2.011357 |
| 20% | 1.2 | 1.44 | 1.728 | 2.0736 | 2.48832 |
| 25% | 1.25 | 1.5625 | 1.953125 | 2.441406 | 3.051758 |

Rates as fractions (so the principal cancels):

| Rate | Fraction | Multiplier |
|---|---|---|
| 5% | $\frac{1}{20}$ | $\frac{21}{20}$ |
| 10% | $\frac{1}{10}$ | $\frac{11}{10}$ |
| 12.5% | $\frac{1}{8}$ | $\frac{9}{8}$ |
| 20% | $\frac{1}{5}$ | $\frac{6}{5}$ |
| 25% | $\frac{1}{4}$ | $\frac{5}{4}$ |
| $6\frac{1}{4}\%$ | $\frac{1}{16}$ | $\frac{17}{16}$ |

## 5. Mistakes that cost marks

1. **Giving the amount when the CI is asked.** CI is the amount minus the principal. Read the last line of the question.
2. **Using the same interest every year.** That is simple interest. In CI each year's interest is bigger.
3. **Forgetting to halve the rate and double the periods** in half-yearly sums. Both changes are needed, not just one.
4. **Compounding a fractional year.** For $2\frac{1}{2}$ years, compound two years and use simple interest on the half year, unless the question says half-yearly.
5. **Averaging rates in a changing-rate question.** 10% then 20% is not 15% twice. Multiply $1.1\times1.2$.
6. **Adding growth and fall percentages.** Up 20% then down 10% is up 8%, not 10%.
7. **Using $\frac{100}{R}$ for the time to double.** That is the simple interest rule. In CI, repeat the doubling: 4 times takes twice as long, 8 times takes three times as long.
8. **Using the 3-year difference formula for 2 years.** The 2-year formula has no $(3+\frac{R}{100})$ part.

## 6. Practice questions

Do these on paper. Do the first 10 untimed. Do the next 15 with 90 seconds each. Do the last group like an exam.

### Level 1: single idea

1. Find the CI on Rs 6000 at 10% per annum for 2 years.
2. Find the amount on Rs 3000 at 20% per annum for 3 years.
3. Find the CI on Rs 10000 at 5% per annum for 2 years.
4. Find the amount on Rs 6250 at 8% per annum for 2 years.
5. What sum becomes Rs 5324 in 3 years at 10% CI?
6. In how many years will Rs 5000 become Rs 6050 at 10% CI?
7. Rs 5000 becomes Rs 5832 in 2 years at CI. Find the rate.
8. Find the amount on Rs 8000 at 10% per annum compounded half-yearly for 1 year.
9. Find the difference between CI and SI on Rs 12000 at 5% for 2 years.
10. A sum doubles in 5 years at CI. In how many years does it become 8 times?

### Level 2: mixed

11. Find the CI on Rs 16000 at 5% per annum for 3 years.
12. The difference between CI and SI on a sum for 2 years at 10% is Rs 60. Find the sum.
13. The difference between CI and SI for 2 years on a sum is Rs 32 and the SI for 2 years is Rs 800. Find the rate.
14. Find the amount on Rs 6000 if the rate is 10% in the first year and 5% in the second.
15. Find the amount on Rs 8000 if the rates are 5%, 10% and 20% in three successive years.
16. Find the amount on Rs 6000 at 10% for 2 years, then 5% in the third year.
17. A town has population 125000 and grows 4% a year. What is the population after 2 years?
18. A machine bought for Rs 40000 depreciates 5% a year. Find its value after 2 years.
19. A loan is repaid in two equal annual instalments of Rs 2420 each at 10% CI. Find the loan.
20. Find the amount on Rs 6000 at 20% per annum for 1 year 4 months, compounded annually.
21. A sum becomes Rs 8820 in 2 years at 5% CI. Find the sum.
22. Find the CI earned in the third year on Rs 10000 at 10% per annum.
23. Rs 4200 is divided into two parts such that the first part after 2 years and the second part after 1 year give equal amounts at 10% CI. Find the first part.
24. A man borrows Rs 10000 at 10% CI and pays Rs 4000 at the end of the first year. How much must he pay at the end of the second year to clear the loan?
25. A town's population is 10000. It rises 20% in one year and falls 10% in the next. Find the population after 2 years.

### Level 3: exam style

26. The difference between CI and SI for 2 years at 4% is Rs 24. Find the sum.
27. Find the difference between CI and SI on Rs 5000 at 20% for 3 years.
28. A sum becomes 4 times in 6 years at CI. In how many years does it become 16 times?
29. Two equal annual instalments of Rs 3969 each are paid at 5% CI. Find the loan.
30. A loan is repaid in three equal annual instalments of Rs 2662 each at 10% CI. Find the loan.
31. Find the CI on Rs 8000 at 12.5% per annum for 2 years.
32. Find the amount on Rs 32000 at 5% per annum for 3 years.
33. Find the amount on Rs 80000 at 4% per annum compounded half-yearly for 1 year.
34. The CI on a sum for 2 years at 4% is Rs 816. Find the sum.
35. The CI on a sum for 2 years at 10% is Rs 2100. Find the SI on the same sum for the same period.
36. Find the amount on Rs 2000 if the rates are 10%, 20% and 25% in three successive years.
37. A man borrows Rs 5000 at 20% CI and pays Rs 2000 at the end of the first year. How much must he pay at the end of the second year to clear the loan?
38. A sum becomes Rs 33275 in 3 years at 10% CI. Find the sum.
39. A sum amounts to Rs 3600 in 2 years at 20% CI. What will it amount to after 2 more years?
40. Find the difference between CI and SI on Rs 3000 at 10% for 2 years.
41. Find the interest earned in the second year on Rs 3000 at 10% CI.
42. A car worth Rs 250000 depreciates 20% every year. Find its value after 2 years.

## 7. Answers with the reasoning

| Q | Answer | Quick working |
|---|---|---|
| 1 | Rs 1260 | $6000\times1.21=7260$, minus 6000 |
| 2 | Rs 5184 | $3000\times1.728$ |
| 3 | Rs 1025 | $10000\times1.1025=11025$, minus 10000 |
| 4 | Rs 7290 | $6250\times\frac{729}{625}$ |
| 5 | Rs 4000 | $\frac{5324}{1.331}$ |
| 6 | 2 years | $\frac{6050}{5000}=1.21=1.1^2$ |
| 7 | 8% | $\frac{5832}{5000}=1.1664$, root $1.08$ |
| 8 | Rs 8820 | Rate $5\%$, 2 periods: $8000\times1.1025$ |
| 9 | Rs 30 | $12000\times0.0025$ |
| 10 | 15 years | Doubling 3 times: $3\times5$ |
| 11 | Rs 2522 | $16000\times1.157625=18522$, minus 16000 |
| 12 | Rs 6000 | $\frac{60}{0.01}$ |
| 13 | 8% | $R=\frac{2\times32}{800}\times100$ |
| 14 | Rs 6930 | $6000\times1.1\times1.05$ |
| 15 | Rs 11088 | $8000\times1.05\times1.1\times1.2$ |
| 16 | Rs 7623 | $6000\times1.21\times1.05$ |
| 17 | 135200 | $125000\times1.0816$ |
| 18 | Rs 36100 | $40000\times0.95\times0.95$ |
| 19 | Rs 4200 | $\frac{2420}{1.1}+\frac{2420}{1.21}=2200+2000$ |
| 20 | Rs 7680 | $6000\times1.2=7200$, then $7200\times\left(1+\frac{20}{100}\times\frac{1}{3}\right)$ |
| 21 | Rs 8000 | $\frac{8820}{1.1025}$ |
| 22 | Rs 1210 | $10\%$ of $12100$ |
| 23 | Rs 2000 | Ratio $1.1:1.21=10:11$, so $\frac{10}{21}\times4200$ |
| 24 | Rs 7700 | $10000\times1.1=11000$, minus $4000$ leaves $7000$, then $7000\times1.1$ |
| 25 | 10800 | $10000\times1.2\times0.9$ |
| 26 | Rs 15000 | $\frac{24}{0.0016}$ |
| 27 | Rs 640 | CI $=8640-5000=3640$, SI $=5000\times0.2\times3=3000$, difference $640$ |
| 28 | 12 years | 4 times in 6 years, 16 times in $2\times6$ |
| 29 | Rs 7380 | $\frac{3969}{1.05}+\frac{3969}{1.1025}=3780+3600$ |
| 30 | Rs 6620 | $2420+2200+2000$ |
| 31 | Rs 2125 | $8000\times1.265625=10125$, minus 8000 |
| 32 | Rs 37044 | $32000\times1.157625$ |
| 33 | Rs 83232 | Rate $2\%$, 2 periods: $80000\times1.0404$ |
| 34 | Rs 10000 | Net growth $8.16\%$, $\frac{816}{0.0816}$ |
| 35 | Rs 2000 | CI is $21\%$ of $P$, so $P=\frac{2100}{0.21}=10000$. SI $=20\%$ of $10000$ |
| 36 | Rs 3300 | $2000\times1.1\times1.2\times1.25$ |
| 37 | Rs 4800 | $5000\times1.2=6000$, minus $2000=4000$, then $\times1.2$ |
| 38 | Rs 25000 | $\frac{33275}{1.331}$ |
| 39 | Rs 5184 | $3600\times1.44$ |
| 40 | Rs 30 | $3000\times0.01$ |
| 41 | Rs 330 | $10\%$ of $3300$ |
| 42 | Rs 160000 | $250000\times0.8\times0.8$ |
