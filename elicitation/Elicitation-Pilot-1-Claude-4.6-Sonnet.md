**A. Clarify the quantities**

Given:
- Prevalence: P(D) = 1/1000 = 0.001
- Sensitivity: P(+ | D) = 0.99
- False-positive rate: P(+ | no D) = 0.05

Asked for: P(D | +), the probability of having the disease given a positive test.

Easily confused quantities: P(+ | D) = 99% (the sensitivity) is *not* P(D | +). The sensitivity conditions on disease status, while the question conditions on the test result. Also, the 5% is P(+ | no D), not P(no D | +).

**B. Algebraic method (Bayes' theorem)**

Define D = has the disease, + = positive test.

P(D | +) = P(+ | D)·P(D) / [P(+ | D)·P(D) + P(+ | no D)·P(no D)]

- Numerator: 0.99 × 0.001 = 0.00099
- P(no D) = 0.999, so the false-positive term is 0.05 × 0.999 = 0.04995
- Denominator: 0.00099 + 0.04995 = 0.05094

P(D | +) = 0.00099 / 0.05094 ≈ 0.019435 ≈ **1.94%**

**C. Different method: natural frequencies (counting a hypothetical population)**

Take 1,000,000 people.
- Diseased: 1,000, of whom 99% test positive → 990 true positives.
- Healthy: 999,000, of whom 5% test positive → 49,950 false positives.
- Total positives: 990 + 49,950 = 50,940.

Fraction of positives who are diseased: 990 / 50,940 ≈ 0.019435 ≈ **1.94%**

**D. Cross-check**

Method B: 0.00099 / 0.05094. Multiplying numerator and denominator by 1,000,000 gives 990 / 50,940, which is exactly Method C. Both give ≈ 1.9435%. ✔

**E. Plausibility test**

(i) 1.94% lies between 0% and 100%. ✔

(ii) In a population of 100,000: 100 have the disease, 99 test positive (true positives); 99,900 are healthy, and 4,995 test positive (false positives). Total positives = 5,094. 99 / 5,094 ≈ 1.94%. ✔

(iii) The numerator in this calculation is 99, the number of true positives, so it does not exceed 99. ✔

(iv) Consistency with the givens:
- Prevalence: 100 / 100,000 = 1 in 1,000 ✔
- Sensitivity: 99 / 100 = 99% ✔
- False-positive rate: 4,995 / 99,900 = 5% ✔

The low result makes sense because the disease is so rare that false positives from the large healthy group (4,995) vastly outnumber true positives (99).

**F. Final answer**

The probability that a person who tests positive actually has the disease is approximately **1.94%**.

**A. Clarify the bases**

- The first discount (25%) applies to the original price, P.
- The second discount (20%) applies to the already reduced price, 0.75P, not to the original price.
- Combined reading: adding the percentages to get a single 45% discount is not justified. The discounts are sequential and apply to different bases, so they compound. The true combined discount is 1 − (0.75 × 0.80) = 40%, not 45%.

**B. Algebraic method**

Let P = original price.

- After the first discount: 0.75P
- After the second discount: 0.80 × 0.75P = 0.60P
- Set equal to the final price: 0.60P = 156
- P = 156 / 0.60 = **260**

**C. Different method: working backwards (inverse operations)**

Undo each step in reverse order.

- Final price: $156 is 80% of the price before the second discount, so that price = 156 / 0.80 = $195.
- $195 is 75% of the original price, so the original = 195 / 0.75 = $260.

(Quick numerical check of the same logic: 156 ÷ 4 × 5 = 195, and 195 ÷ 3 × 4 = 260.)

**D. Cross-check**

The algebraic method gives $260 and the backward-working method gives $260. The two answers are identical.

**E. Plausibility test**

(i) Positive price: $260 > 0. ✔
(ii) Higher than the final price: $260 > $156. ✔
(iii) Apply the discounts in order: 260 × 0.75 = 195; 195 × 0.80 = 156. This returns exactly $156. ✔
(iv) The intermediate price after the first discount is $195, which is positive and lower than $260. ✔

All four conditions are satisfied.

**F. Final answer**

The coat's original price was **$260**.

**A. Definition**

Average speed for the entire trip = total distance travelled ÷ total time taken. It is not the average of the two speeds. The simple arithmetic mean (28 + 42)/2 = 35 km/h is the tempting but wrong quantity, because the van spends more time at the slower speed, so the slower speed carries more weight.

**B. Algebraic method**

Let d = 84 km (one-way distance), v₁ = 28 km/h, v₂ = 42 km/h.

- Time out: t₁ = d/v₁ = 84/28 = 3 h
- Time back: t₂ = d/v₂ = 84/42 = 2 h
- Total time: T = t₁ + t₂ = 5 h
- Total distance: D = 2d = 168 km

v_avg = D/T = 168/5 = **33.6 km/h**

(General form: v_avg = 2v₁v₂/(v₁+v₂) = 2·28·42/70 = 2352/70 = 33.6, the harmonic mean.)

**C. Different method: weighted-average reasoning**

Think of time-weighting. Over the whole trip, the van spends 3 hours at 28 km/h and 2 hours at 42 km/h (found by logical deduction: 84 km at 28 km/h takes 3 h, since 28 × 3 = 84; 84 km at 42 km/h takes 2 h, since 42 × 2 = 84). The average speed is the time-weighted mean of the speeds:

v_avg = (3·28 + 2·42)/(3 + 2) = (84 + 84)/5 = 168/5 = 33.6 km/h

Alternatively, by a test-of-constant-speed argument: a van travelling steadily at 33.6 km/h would cover 168 km in 168/33.6 = 5 h, matching the real trip's duration. Any steady speed above or below 33.6 would give a shorter or longer time than 5 h, so 33.6 is the unique equivalent steady speed.

**D. Cross-check**

Method B gives 33.6 km/h and Method C gives 33.6 km/h. The answers are identical.

**E. Plausibility test**

- (i) 28 < 33.6 < 42 ✓. It lies between the two leg speeds.
- (ii) 33.6 × 5 = 168 km ✓. This matches the total distance of 2 × 84 km.
- (iii) 84/28 + 84/42 = 3 + 2 = 5 h ✓. This matches the stated total time.
- (iv) It uses every given number (84 km, 28 km/h, 42 km/h, same road both ways) and is consistent with all of them. It is also below the arithmetic mean of 35 km/h, as expected, because more time is spent at the slower speed ✓.

**F. Final answer**

The van's average speed for the entire round trip is **33.6 km/h**.


**A. Clarify the rate**

- Each pump works at the same constant rate r (tanks per minute), and all pumps work in parallel without interfering with one another. Each pump fills its own tank, or equivalently, the combined output is simply the sum of the individual rates.
- Fixed: the number of pumps (6), the rate of each pump, and the identical size of every tank.
- Changed: the number of tanks to fill, from 6 to 18.
- From the given situation: 6 pumps fill 6 tanks in 12 minutes, so the total output is 6 tanks / 12 min = 0.5 tanks per minute. Per pump, r = 0.5 / 6 = 1/12 tank per minute (one pump alone needs 12 minutes per tank).

**B. Algebraic method**

Let r = rate of one pump (tanks/min), t = time needed for 18 tanks (min).

- Given: 6 · r · 12 = 6, so 72r = 6, giving r = 1/12.
- Required: 6 · r · t = 18, so 6 · (1/12) · t = 18, so t/2 = 18, giving **t = 36**.

**C. Entirely different method (logical deduction by proportional reasoning)**

Without defining any rate, use scaling: the pumps are unchanged, and the work is 18 / 6 = 3 times as large. With the same crew working at the same constant rate, tripling the work triples the time: 12 × 3 = 36 minutes.

Equivalent "batch" view: the six pumps fill 6 tanks every 12 minutes. Three batches of 6 tanks make 18 tanks, so 3 × 12 = 36 minutes.

**D. Cross-check**

Method B gave 36 minutes and Method C gave 36 minutes. Both methods agree.

**E. Plausibility test**

(i) 36 is a positive number of minutes. ✔

(ii) Six pumps at 1/12 tank per minute each produce 0.5 tanks per minute. In 36 minutes: 0.5 × 36 = 18 tanks. ✔

(iii) One pump at 1/12 tank per minute needs 18 ÷ (1/12) = 216 minutes for eighteen tanks, and 216 = 6 × 36. ✔

(iv) 36 minutes for eighteen tanks is longer than the 12 minutes needed for six tanks with the same pumps. ✔

**F. Final answer**

The six pumps will take **36 minutes** to fill eighteen tanks.