# Calendars

> Read this like a class: a calendar question is a counting question, and the only part that matters for weekdays is the remainder after groups of seven days.

## 0. Start here: why do weekdays shift?

A week has 7 days. After 7, 14, or 21 days, the weekday is unchanged; only the leftover days move it forward. An ordinary year has 365 days, or 52 weeks and 1 extra day, so the same date shifts by one weekday. A leap year has 2 extra days, so it shifts by two.

Questions ask for a weekday on a date, a matching calendar, or the number of times a weekday can occur. First identify the time span, count the days that are actually crossed, and keep only the remainder upon division by 7. As a sense check, moving forward by a positive number of days should never move backward through the week.

## 1. Choose the question type

Questions on this topic fall into a few fixed types. Spot the type, then use that model.

| Type of question | Walkthrough |
|---|---|
| Day of the week for an absolute date | 1 |
| Reference date given within the same year | 2 |
| Reference date given in different years | 3 |
| Repetition of calendar years | 4 |
| Same calendar months within a year | 5 |
| Odd days in century spans (100, 200, 300, 400 years) | 6 |
| Leap year and century leap year rules | 7 |
| First and last days of a century | 8 |
| Frequency of weekdays and 53 Sundays | 9 |
| Birthday and anniversary day shifts | 10 |
| Relative day language (days before yesterday/after tomorrow) | 11 |
| Finding all dates of a given weekday in a month | 12 |

## 2. Translate the wording

| Data you will see | What it means |
|---|---|
| "What day was 15 August 1947?" | Find odd days from year 0 to given date |
| "If 10 March is Tuesday, what is 25 August?" | Count intervening days $\pmod 7$ within the same year |
| "If 5 March 2011 is Saturday, find 5 March 2012" | Add 1 day for ordinary year, 2 days if Feb 29 is crossed |
| "Which year has the same calendar as 2017?" | Repetition rule: $+6$, $+11$, or $+28$ years |
| "Which two months have identical calendars?" | Months whose intervening days sum to a multiple of 7 |
| "Day before yesterday was Thursday" | Reference day algebra relative to Today $= 0$ |

## 3. The core idea

- **Odd days:** the remainder when total days are divided by 7 ($\text{Days} \pmod 7$).
- **Ordinary year:** 365 days $= 52\text{ weeks} + 1\text{ odd day}$. **Leap year:** 366 days $= 52\text{ weeks} + 2\text{ odd days}$.
- **Century odd days:** 100 yrs $= 5$, 200 yrs $= 3$, 300 yrs $= 1$, 400 yrs $= 0$.
- **Day codes:** $0 = \text{Sunday}, 1 = \text{Monday}, 2 = \text{Tuesday}, 3 = \text{Wednesday}, 4 = \text{Thursday}, 5 = \text{Friday}, 6 = \text{Saturday}$.

## 4. Question-type walkthroughs

### Question type 1. Day of the week for an absolute date

**Idea:** split into completed centuries $+$ completed years $+$ days in the current year, then take $\text{total odd days} \pmod 7$.

**Example 1:** What day of the week was 15 August 1947?
- Completed period: 1946 years $+ 1\text{ Jan to }15\text{ Aug 1947}$.
- $1600\text{ yrs} = 0$, $300\text{ yrs} = 1$.
- 46 years has $\lfloor 46/4 \rfloor = 11$ leap years and 35 ordinary years: $11\times 2 + 35\times 1 = 57 \equiv 1\pmod 7$.
- 1947 days (Jan to Aug): $31 + 28 + 31 + 30 + 31 + 30 + 31 + 15 = 227 \equiv 3\pmod 7$.
- Total odd days $= 1 + 1 + 3 = 5\implies$ **Friday**.

**Example 2:** What day of the week was 26 January 1950?
- 1949 completed: $1600 (0) + 300 (1) + 49\text{ yrs } (12\times 2 + 37\times 1 = 61 \equiv 5) = 6\text{ odd days}$.
- Jan 1950: 26 days $\equiv 5\text{ odd days}$.
- Total $= 6 + 5 = 11 \equiv 4\implies$ **Thursday**.

### Question type 2. Reference date given within the same year

**Idea:** count days between dates and take remainder modulo 7.

**Example:** If 15 March of a non-leap year is Tuesday, what day is 15 August of the same year?
- Days remaining in March: $31 - 15 = 16$.
- April: 30, May: 31, June: 30, July: 31, August: 15.
- Total $= 16 + 30 + 31 + 30 + 31 + 15 = 153$ days.
- $153 \div 7 = 21$ weeks $+ 6$ odd days.
- $\text{Tuesday} + 6\text{ days} =$ **Monday**.

### Question type 3. Reference date given in different years

**Idea:** each ordinary year adds $+1$ day; each leap year whose February 29 is included adds $+2$ days.

**Example 1:** If 5 March 2011 was Saturday, what day of the week was 5 March 2012?
- 2012 is a leap year, and 29 February 2012 falls within this period.
- Period has 366 days $= 52\text{ weeks} + 2\text{ odd days}$.
- $\text{Saturday} + 2\text{ days} =$ **Monday**.

**Example 2:** If 15 August 2013 was Thursday, what day of the week was 15 August 2021?
- Number of years $= 2021 - 2013 = 8$ years.
- Leap years crossed: 2016, 2020 $= 2$ leap years.
- Total odd days $= 8 + 2 = 10 \equiv 3\pmod 7$.
- $\text{Thursday} + 3\text{ days} =$ **Sunday**.

### Question type 4. Repetition of calendar years

**Idea:** a year immediately after a leap year repeats in $+6$ years; other ordinary years repeat in $+11$ years; leap years repeat in $+28$ years.

**Example 1:** Which year will have the same calendar as 2017?
- $2017 = 2016 (\text{leap}) + 1\implies +6$ years.
- $2017 + 6 =$ **2023**.

**Example 2:** Which year will have the same calendar as 2024?
- 2024 is a leap year $\implies +28$ years.
- $2024 + 28 =$ **2052**.

### Question type 5. Same calendar months within a year

**Idea:** two months have identical calendars if the total odd days between their starting days is a multiple of 7.

**Example:** In an ordinary year, which month has the same calendar as January?
- Jan (31): 3, Feb (28): 0, Mar (31): 3, Apr (30): 2, May (31): 3, Jun (30): 2, Jul (31): 3, Aug (31): 3, Sep (30): 2.
- Sum Jan to Sep $= 3 + 0 + 3 + 2 + 3 + 2 + 3 + 3 + 2 = 21 \equiv 0\pmod 7$.
- Answer: **October**.

### Question type 6. Odd days in century spans

**Idea:** 100 years has 24 leap years and 76 ordinary years $= 24\times 2 + 76\times 1 = 124 \equiv 5\pmod 7$.

**Example:** How many odd days are in 300 years?
- $100\text{ yrs} = 5$ odd days.
- $300\text{ yrs} = 3 \times 5 = 15 \equiv 1\pmod 7$.
- Answer: **1 odd day**.

### Question type 7. Leap year and century leap year rules

**Idea:** non-century years are leap if divisible by 4; century years are leap only if divisible by 400.

**Example:** Is 1900 a leap year? Is 2000 a leap year?
- $1900 \div 400 = 4.75$ (not divisible by 400) $\implies$ **1900 is an ordinary year**.
- $2000 \div 400 = 5$ (divisible by 400) $\implies$ **2000 is a leap year**.

### Question type 8. First and last days of a century

**Idea:** last day of 100th, 200th, 300th, 400th century has odd days 5, 3, 1, 0, which correspond to Friday, Wednesday, Monday, Sunday.

**Example:** Which days can never be the last day of a century?
- Possible last days: Friday (5), Wednesday (3), Monday (1), Sunday (0).
- Impossible last days: **Tuesday, Thursday, Saturday**.

### Question type 9. Frequency of weekdays and 53 Sundays

**Idea:** ordinary year has $365 = 52\times 7 + 1$ (1 extra day); leap year has $366 = 52\times 7 + 2$ (2 extra days).

**Example:** What is the probability that a leap year has 53 Sundays?
- 52 weeks guarantee 52 Sundays. The 2 extra days can be (Sun, Mon), (Mon, Tue), (Tue, Wed), (Wed, Thu), (Thu, Fri), (Fri, Sat), (Sat, Sun).
- Out of 7 pairs, 2 contain Sunday: (Sat, Sun) and (Sun, Mon).
- Probability $= \mathbf{\dfrac{2}{7}}$.

### Question type 10. Birthday and anniversary day shifts

**Idea:** each non-leap birthday advances by $+1$ day; leap year birthday advances by $+2$ days if Feb 29 falls between the two dates.

**Example:** A person celebrated their birthday on Tuesday, 15 October 2019. In which year will the birthday fall on Tuesday again?
- Odd days: 2020 (leap, Oct to Oct crosses Feb 2020) $+2$, 2021 $+1$, 2022 $+1$, 2023 $+1$, 2024 (crosses Feb 2024) $+2$.
- Cumulative odd days: 2020: 2, 2021: 3, 2022: 4, 2023: 5, 2024: $5 + 2 = 7 \equiv 0\pmod 7$.
- Answer: **2024**.

### Question type 11. Relative day language

**Idea:** set $\text{Today} = 0$. Yesterday $= -1$, Tomorrow $= +1$. Add or subtract days algebraically.

**Example:** If 3 days before yesterday was Wednesday, what day will be 2 days after tomorrow?
- 3 days before yesterday $= -1 - 3 = -4 \implies \text{Day } -4 = \text{Wednesday}$.
- 2 days after tomorrow $= +1 + 2 = +3$.
- Difference $= +3 - (-4) = 7$ days $\equiv 0\pmod 7$.
- Answer: **Wednesday**.

### Question type 12. Finding all dates of a given weekday in a month

**Idea:** find the day of the week on the 1st of the month, then locate the first required weekday and add 7 repeatedly.

**Example:** On what dates of April 2001 did Wednesday fall?
- 1 April 2001: 2000 yrs $= 0$. 2001 days up to 1 Apr $= 31 (\text{Jan}) + 28 (\text{Feb}) + 31 (\text{Mar}) + 1 = 91 \equiv 0\pmod 7\implies$ Sunday.
- 1st is Sunday $\implies$ 2nd is Monday, 3rd is Tuesday, 4th is Wednesday.
- Wednesdays: **4th, 11th, 18th, 25th April**.

## 5. Before you practise

**Your turn:** If today is Wednesday, what weekday will it be 100 days from today?

**Think it through:** $100=14\times7+2$. The full weeks do not change the weekday; move two days ahead: Wednesday → Thursday → **Friday**.

### Quick revision

- Count crossed days, then reduce the total modulo 7.
- An ordinary year shifts a date by one weekday; a leap year shifts it by two only when February 29 is crossed.
- Apply the century leap-year rule: divisible by 4, except century years must also be divisible by 400.
- For weekday frequency, a normal year has 52 of each weekday and one extra; a leap year has two extra consecutive weekdays.

### Common mistakes

1. Counting both endpoint dates when counting the gap between dates.
2. Forgetting whether February 29 lies inside the interval.
3. Treating every century year as a leap year.
4. Adding all days without reducing modulo 7.
5. Assuming that 53 occurrences can only happen for Sunday; it depends on the weekday(s) left over.

## 6. Practice

1. What day of the week was 15 August 1947?
2. What day of the week was 26 January 1950?
3. What day of the week was 2 October 1869?
4. What day of the week was 1 January 2001?
5. If 15 March of an ordinary year is Tuesday, what day of the week is 15 August of the same year?
6. If 1 January 2024 was Monday, what day of the week was 31 December 2024?
7. If 12 April of an ordinary year is Wednesday, what day of the week is 28 July of the same year?
8. If 5 March 2011 was Saturday, what day of the week was 5 March 2012?
9. If 10 January 2004 was Saturday, what day of the week was 10 January 2005?
10. If 15 August 2013 was Thursday, what day of the week was 15 August 2021?
11. If 1 January 2007 was Monday, what day of the week was 1 January 2008?
12. If 8 February 2020 was Saturday, what day of the week was 8 February 2021?
13. Which year will have the same calendar as 2017?
14. Which year will have the same calendar as 2024?
15. Which year will have the same calendar as 2018?
16. Which year will have the same calendar as 2019?
17. In an ordinary year, which month has the same calendar as January?
18. In a leap year, which month has the same calendar as January?
19. How many odd days are there in 100 years?
20. How many odd days are there in 200 years?
21. How many odd days are there in 300 years?
22. How many odd days are there in 400 years?
23. Which of the following is a leap year: 1700, 1800, 1900, or 2000?
24. How many leap years are there between 2001 and 2100 inclusive?
25. Which days of the week can never be the last day of a century?
26. Which days of the week can never be the first day of a century?
27. What is the probability that an ordinary year has 53 Sundays?
28. What is the probability that a leap year chosen at random has 53 Sundays?
29. A month of 31 days has 5 Sundays. If the month starts on Sunday, what day of the week is the 31st day?
30. If today is Monday, what day of the week will it be after 61 days?
31. If the day before yesterday was Thursday, what day of the week will be the day after tomorrow?
32. If 3 days before yesterday was Wednesday, what day of the week will be 2 days after tomorrow?
33. On what dates of April 2001 did Wednesday fall?
34. On what date was the first Friday of July 2024?

## Answers

| Q | Answer | Key step |
|---|---|---|
| 1 | Friday | $1946\text{ yrs} + 227\text{ days} = 1 + 1 + 3 = 5\text{ odd days}$ |
| 2 | Thursday | $1949\text{ yrs} + 26\text{ days} = 6 + 5 = 11 \equiv 4\text{ odd days}$ |
| 3 | Saturday | $1868\text{ yrs} + 275\text{ days} = 3 + 1 + 2 = 6\text{ odd days}$ |
| 4 | Monday | $2000\text{ yrs} + 1\text{ day} = 0 + 1 = 1\text{ odd day}$ |
| 5 | Monday | $153\text{ days between dates} \equiv 6\pmod 7$; $\text{Tue} + 6 = \text{Mon}$ |
| 6 | Tuesday | Leap year has 366 days; day 366 is $\text{Mon} + 365 \pmod 7 = \text{Mon} + 1 = \text{Tue}$ |
| 7 | Friday | $18 + 31 + 30 + 28 = 107 \equiv 2\pmod 7$; $\text{Wed} + 2 = \text{Fri}$ |
| 8 | Monday | 2012 is leap year crossing Feb 29; $+2$ days $\implies \text{Sat} + 2 = \text{Mon}$ |
| 9 | Monday | 2004 is leap year crossing Feb 29; $+2$ days $\implies \text{Sat} + 2 = \text{Mon}$ |
| 10 | Sunday | 8 years $+ 2\text{ leap years} = 10 \equiv 3\pmod 7$; $\text{Thu} + 3 = \text{Sun}$ |
| 11 | Tuesday | 2007 is ordinary year; $+1$ day $\implies \text{Mon} + 1 = \text{Tue}$ |
| 12 | Monday | 2020 leap year crosses Feb 29; $+2$ days $\implies \text{Sat} + 2 = \text{Mon}$ |
| 13 | 2023 | $\text{Leap} + 1$ repeats in $+6$ years: $2017 + 6 = 2023$ |
| 14 | 2052 | Leap year repeats in $+28$ years: $2024 + 28 = 2052$ |
| 15 | 2029 | $\text{Leap} + 2$ repeats in $+11$ years: $2018 + 11 = 2029$ |
| 16 | 2030 | $\text{Leap} + 3$ repeats in $+11$ years: $2019 + 11 = 2030$ |
| 17 | October | Odd days from 1 Jan to 1 Oct $= 21 \equiv 0\pmod 7$ |
| 18 | April (and July) | In leap year, Jan to Apr odd days $= 3 + 1 + 3 = 7 \equiv 0\pmod 7$ |
| 19 | 5 odd days | $76\times 1 + 24\times 2 = 124 \equiv 5\pmod 7$ |
| 20 | 3 odd days | $2 \times 5 = 10 \equiv 3\pmod 7$ |
| 21 | 1 odd day | $3 \times 5 = 15 \equiv 1\pmod 7$ |
| 22 | 0 odd days | $4 \times 5 + 1 = 21 \equiv 0\pmod 7$ |
| 23 | 2000 | Century years must be divisible by 400 |
| 24 | 24 | $\lfloor 100/4 \rfloor - 1\text{ (2100 is not leap)} = 24$ |
| 25 | Tue, Thu, Sat | Century last day odd days can only be 5 (Fri), 3 (Wed), 1 (Mon), 0 (Sun) |
| 26 | Wed, Fri, Sun | Century first day odd days can only be 1 (Mon), 2 (Tue), 4 (Thu), 6 (Sat) |
| 27 | $\frac{1}{7}$ | 1 extra day in 365 days; $\frac{1}{7}$ probability of Sunday |
| 28 | $\frac{2}{7}$ | 2 extra days form 7 possible pairs; 2 contain Sunday |
| 29 | Tuesday | 1st is Sunday; $31 - 1 = 30 \equiv 2\pmod 7$; $\text{Sun} + 2 = \text{Tue}$ |
| 30 | Saturday | $61 \equiv 5\pmod 7$; $\text{Mon} + 5 = \text{Sat}$ |
| 31 | Monday | $\text{Day } -2 = \text{Thu} \implies \text{Today} = \text{Sat} \implies \text{Day } +2 = \text{Mon}$ |
| 32 | Wednesday | $\text{Day } -4 = \text{Wed} \implies \text{Day } +3 = \text{Wed} + 7\text{ days} = \text{Wed}$ |
| 33 | 4th, 11th, 18th, 25th | 1 Apr 2001 is Sunday $\implies$ 1st Wed is 4 Apr |
| 34 | 5 July 2024 | 1 July 2024 is Monday $\implies$ first Friday is $1 + 4 = 5$ July |
