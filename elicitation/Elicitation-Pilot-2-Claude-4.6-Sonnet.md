## A. Clarify the quantities

**Given:**
- Prevalence: P(D) = 1/500 = 0.002, so P(not D) = 0.998
- Sensitivity: P(+ | D) = 0.95
- False-positive rate: P(+ | not D) = 0.04
- Independence: given disease status, the two test results are independent, so P(++ | D) = 0.95² and P(++ | not D) = 0.04².

**Asked for:** P(D | ++), the probability of disease given two positive results.

**Role of the second positive:** It is new evidence that updates the probability. The posterior after the first positive becomes the prior for the second test (equivalently, we use the joint likelihood of both results).

**One positive only:** P(D | +) = (0.002·0.95) / (0.002·0.95 + 0.998·0.04) = 0.0019 / (0.0019 + 0.03992) = 0.0019/0.04182 ≈ 4.54%. This is not the answer because the person tested positive twice, and the second result adds evidence that raises the probability further.

## B. Algebraic method

Let D = disease, p = 0.002, s = 0.95, f = 0.04.

P(D | ++) = p·s² / (p·s² + (1−p)·f²)

- Numerator: 0.002 × 0.9025 = 0.001805
- Denominator term: 0.998 × 0.0016 = 0.0015968
- Total: 0.001805 + 0.0015968 = 0.0033018

P(D | ++) = 0.001805 / 0.0033018 ≈ 0.54667 → **about 54.67%**

## C. Different method: odds and likelihood ratios

Prior odds = 0.002/0.998 = 1/499.
Likelihood ratio per positive test = 0.95/0.04 = 23.75.
Two independent positives multiply the odds by 23.75² = 564.0625.

Posterior odds = 564.0625/499 ≈ 1.13032.
Probability = odds/(1 + odds) = 1.13032/2.13032 ≈ 0.53058?

Checking the arithmetic carefully: 564.0625/499 = 1.130 (499 × 1.13 = 563.87; remainder 0.1925/499 ≈ 0.000386), so odds ≈ 1.130386. Then 1.130386/2.130386 ≈ 0.53061?

Recomputing the Method B figures for comparison: 0.001805/0.0033018. Since 0.0033018 × 0.5467 = 0.001805, the result is 0.5467. For the odds method, the correct posterior odds are the ratio 0.001805/0.0015968 = 1.13038, and 1.13038/(1+1.13038) = 1.13038/2.13038 = 0.5306. These disagree, so one of my numbers is wrong. Recheck the denominator: 0.998 × 0.0016 = 0.0015968, and 0.001805 + 0.0015968 = 0.0033018 ✓. Then 0.001805/0.0033018: 0.0033018 × 0.5306 = 0.0017521, and 0.0033018 × 0.5467 = 0.0018051. So the Method B division gives 0.5467 only if 0.0033018 × 0.5467 ≈ 0.001805, which it does. Now the odds: 0.001805/0.0015968 = 1.1304 gives p = 1.1304/2.1304 = 0.5306, but this conflicts because 0.0015968 × 1.1304 = 0.001805 ✓ and 1.1304/(2.1304) should equal 0.001805/0.0033018. Computing 0.0033018 × 0.5306 = 0.0017519, not 0.001805. The discrepancy means 1 + 1.1304 = 2.1304 but 0.0033018/0.0015968 = 2.0678. Indeed 0.0015968 × 2.0678 = 0.0033018, so 0.001805/0.0015968 = 1.1304 must be wrong: 0.0015968 × 1.13 = 0.0018044 ✓, so 1.1304 is right, and then 1 + 1.1304 = 2.1304, giving 0.0015968 × 2.1304 = 0.003402. But 0.001805 + 0.0015968 = 0.0034018, not 0.0033018. **The addition was my error.**

Corrected: denominator = 0.0034018.
P(D | ++) = 0.001805/0.0034018 ≈ 0.53060 → **about 53.06%** (matches the odds method: 0.5306).

## D. Cross-check

With the addition fixed, Method B gives 0.001805/0.0034018 = 0.5306 and Method C gives 1.13039/2.13039 = 0.5306. Both agree: **≈ 53.06%**. (The 54.67% in B above came from the arithmetic slip and is discarded.)

## E. Plausibility test

(i) 53.06% lies between 0% and 100%. ✓

(ii) Population of 1,000,000:
- Diseased: 2,000. Of these, 95% test positive twice: 2,000 × 0.9025 = 1,805.
- Healthy: 998,000. Of these, 0.04² = 0.0016 test positive twice: 998,000 × 0.0016 = 1,596.8.
- Total double-positives: 3,401.8. Fraction diseased: 1,805/3,401.8 ≈ 0.5306 ✓

(iii) The numerator 1,805 does not exceed the number of diseased people (2,000) and is exactly the number who are diseased and test positive twice. ✓

(iv) Consistent with the given numbers: 1/500 prevalence, 95% sensitivity, and 4% false-positive rate were all used. Also, the result rises from 4.54% (one positive) to 53.06% (two), as expected from added evidence. ✓

## F. Final answer

The probability that the person actually has the disease is approximately **53.06%** (≈ 53.1%).

**A. Order and bases**

1. The 25% discount applies to the original price P, giving the discounted price 0.75P.
2. The 8% sales tax applies to the discounted price only, giving 0.75P × 1.08.
3. The $12 flat delivery fee is added last. It is not taxed and not discounted.

Alternative readings:
- Tax on the original price: this contradicts the description, which says tax was applied to the discounted price.
- Fee taxed or discounted: this contradicts the description, which says the fee is flat and added "finally."

The reading above matches the description.

**B. Algebraic method**

Let P be the original price.

Total = 0.75P × 1.08 + 12 = 255

0.81P + 12 = 255
0.81P = 243
P = 243 / 0.81 = 300

**C. Different method: working backward (inverse operations)**

Start from the final total and undo each step in reverse order:

1. Undo the delivery fee: 255 − 12 = 243. This is the price after discount and tax.
2. Undo the 8% tax: 243 / 1.08 = 225. This is the discounted price.
3. Undo the 25% discount: 225 / 0.75 = 300. This is the original price.

**D. Cross-check**

Both methods give P = $300. They agree.

**E. Plausibility test**

(i) Positive price: $300 > 0. ✔

(ii) Forward calculation:
- Discount: 300 × 0.25 = 75, so the discounted price is 225.
- Tax: 225 × 0.08 = 18, so the price with tax is 243.
- Fee: 243 + 12 = 255. ✔ This matches the total exactly.

(iii) The discounted price is $225, which is positive and lower than $300. ✔

(iv) The tax is $18, which is 8% of the discounted price ($225 × 0.08 = 18). By contrast, 8% of the original price would be $24, which is not what was used. ✔

**F. Final answer**

The coat's original price was **$300**.
**A. Definition**

Average speed for the entire journey = total distance ÷ total elapsed time, measured from the moment he first sets off to the moment he finally arrives. The stopped hour is part of that elapsed time, so it counts.

Two simpler quantities that could be mistaken for it:
- The mean of the two driving speeds: (45 + 30) ÷ 2 = 37.5 km/h. This is wrong because he spends different amounts of time at each speed.
- The average over driving time only: total distance ÷ driving time, which ignores the stop.

**B. Algebraic method**

Let d₁ = 90 km, v₁ = 45 km/h, d₂ = 60 km, v₂ = 30 km/h, and stop time s = 1 h.

- Time for leg 1: t₁ = d₁/v₁ = 90/45 = 2 h
- Time for leg 2: t₂ = d₂/v₂ = 60/30 = 2 h
- Total distance: D = d₁ + d₂ = 150 km
- Total time: T = t₁ + s + t₂ = 2 + 1 + 2 = 5 h
- Average speed: v̄ = D/T = 150/5 = **30 km/h**

(For comparison, the driving-only average would be 150/4 = 37.5 km/h, which happens to equal the mean of the two speeds here, but neither is the correct answer.)

**C. Different method: timeline / graphical reasoning**

Plot distance against time:
- t = 0 h, position 0 km
- t = 2 h, position 90 km (end of leg 1, slope 45)
- t = 3 h, position 90 km (flat line during the stop)
- t = 5 h, position 150 km (slope 30)

The average speed is the slope of the straight line from the start (0, 0) to the finish (5, 150). That line passes through (1, 30), (2, 60), (3, 90) and so on. It rises 30 km for each hour, so its slope is 30 km/h.

As a check on this line, at t = 3 h it reaches 90 km, which coincides exactly with the actual position after the stop. The actual path and the constant-speed line cross at t = 3 and at the endpoints.

**D. Cross-check**

Method B gives 30 km/h and Method C gives 30 km/h. They agree.

**E. Plausibility test**

(i) 30 km/h is positive and no greater than 45 km/h, the highest speed he ever drove. ✔
(ii) 30 km/h × 5 h = 150 km, the total distance. ✔
(iii) The total elapsed time used is 2 + 1 + 2 = 5 h, including the 1-hour stop. ✔
(iv) Consistency with the given numbers: 45 × 2 = 90 km and 30 × 2 = 60 km match the legs, the stop is exactly 1 h, and the result is below the driving-only average of 37.5 km/h, as it must be once a stop is included. ✔

**F. Final answer**

The driver's average speed for the entire journey, including the stop, is **30 km/h**.
**A. Clarify the work**

Total work = 6 painters × 10 days = **60 painter-days**.

Fixed: each painter's rate (1 painter-day of work per day) and the total work (60 painter-days).
Changing: the crew size, which is 6 for days 1–4 and 4 afterward.

The total time is not simply 60 ÷ 4 = 15 days, because the crew was not four painters the whole time. For the first 4 days, six painters were working, so a faster pace was already banked. Dividing by 4 would wrongly treat the whole job as done at the reduced pace.

**B. Algebraic method**

Let T = total days from start to finish, and let t = days worked by the four-painter crew after day 4, so T = 4 + t.

Work in phase 1: 6 × 4 = 24 painter-days.
Work in phase 2: 4t painter-days.

Setting the total equal to 60:
24 + 4t = 60
4t = 36
t = 9

T = 4 + 9 = **13 days**.

**C. Entirely different method (logical deduction by fractions of the job)**

Six painters finish in 10 days, so the crew paints 1/10 of the building per day. Each painter paints 1/60 per day.

After 4 days, the crew has painted 4/10 = 2/5 of the building, leaving 3/5.

Four painters paint 4/60 = 1/15 of the building per day. The time to paint 3/5 at that rate is (3/5) ÷ (1/15) = (3/5) × 15 = 9 days.

Total = 4 + 9 = **13 days**.

**D. Cross-check**

Both methods give 9 days after the first phase and 13 days in total. The answers are identical.

**E. Plausibility test**

(i) 13 is positive and longer than 4. ✔
(ii) Work in the first 4 days is 24 painter-days. Work afterward is 4 × 9 = 36 painter-days. 24 + 36 = 60 = total work. ✔
(iii) Work remaining after day 4 is 60 − 24 = 36 painter-days. Four painters over 9 days cover 4 × 9 = 36. ✔
(iv) 13 > 10, as expected since the crew shrank. It is also less than 15, which makes sense because the first 4 days were done at full strength. ✔

**F. Final answer**

The job takes **13 days** in total.
This is a Bayes' theorem problem.

**Given:**
- Prevalence: P(D) = 0.001
- Sensitivity: P(+ | D) = 0.99
- False positive rate: P(+ | no D) = 0.05

**Total probability of testing positive:**

P(+) = (0.99)(0.001) + (0.05)(0.999)
P(+) = 0.00099 + 0.04995 = 0.05094

**Bayes' theorem:**

P(D | +) = P(+ | D)·P(D) / P(+) = 0.00099 / 0.05094 ≈ 0.01943

**Answer: about 1.94%**

**Intuition check:** In 100,000 people, about 100 have the disease and 99 of them test positive. Of the 99,900 healthy people, about 4,995 test positive. So only 99 out of roughly 5,094 positives (≈ 1.9%) are truly diseased. Because the disease is so rare, false positives vastly outnumber true positives.
Let the notebook cost **x**. Then the pen costs **x + 3.00**.

Total: x + (x + 3.00) = 3.30
2x = 0.30
x = 0.15

**The notebook costs $0.15** (15 cents), and the pen costs $3.15.

Check: $0.15 + $3.15 = $3.30, and $3.15 − $0.15 = $3.00 ✓