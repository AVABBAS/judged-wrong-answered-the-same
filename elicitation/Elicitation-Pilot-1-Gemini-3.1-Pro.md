**A. Clarify the quantities**
Given conditional probabilities:

* Prevalence $P(Disease) = 0.001$
* Sensitivity $P(Positive \vert{} Disease) = 0.99$
* False Positive Rate $P(Positive \vert{} No \ Disease) = 0.05$

Probability asked for:

* Positive Predictive Value $P(Disease \vert{} Positive)$

Easily confused quantity: $P(Disease \vert{} Positive)$ is commonly confused with the provided sensitivity $P(Positive \vert{} Disease)$ (99%), a cognitive bias known as the base rate fallacy.

**B. Algebraic method**
Using Bayes' Theorem:
$P(D\vert{}+) = \frac{P(+\vert{}D) \times P(D)}{P(+\vert{}D) \times P(D) + P(+\vert{}D') \times P(D')}$

Where $P(D') = 1 - 0.001 = 0.999$:
$P(D\vert{}+) = \frac{0.99 \times 0.001}{(0.99 \times 0.001) + (0.05 \times 0.999)}$
$P(D\vert{}+) = \frac{0.00099}{0.00099 + 0.04995}$
$P(D\vert{}+) = \frac{0.00099}{0.05094}$
$P(D\vert{}+) \approx 0.0194346$

**C. Entirely different method**
Using natural frequencies for a hypothetical population of 100,000 people:

* Total with the disease: $100,000 \times 0.001 = 100$
* Total without the disease: $100,000 - 100 = 99,900$
* True positives (have disease, test positive): $100 \times 0.99 = 99$
* False positives (no disease, test positive): $99,900 \times 0.05 = 4,995$
* Total positive results: $99 + 4,995 = 5,094$

Probability = $\frac{\text{True Positives}}{\text{Total Positives}} = \frac{99}{5,094} \approx 0.0194346$

**D. Cross-check**
The algebraic method outputs the ratio $\frac{0.00099}{0.05094}$, which mathematically simplifies exactly to $\frac{99}{5094}$. The natural frequency method directly yields $\frac{99}{5094}$. Both methods compute identical values.

**E. Plausibility test**
(i) ~1.94% is a valid probability strictly bounded between 0% and 100%.
(ii) It aligns perfectly with the empirical ratio ($\frac{99}{5,094}$) in a 100,000-person hypothetical population.
(iii) Its numerator (99) equals exactly the number of true positives calculated.
(iv) It logically satisfies all given parameters; a 5% false positive rate applied to a 99.9% healthy population creates an overwhelming majority of false positives relative to true positives.

**F. Final answer**
1.94%


**A. Clarify the bases**
The first percentage (25%) applies to the original, undiscounted price of the coat. The second percentage (20%) applies to the new, intermediate price (the price after the first 25% discount). A common misreading is adding the two percentages together to assume a single 45% discount applied to the original price. This combined reading is unjustified because the problem explicitly states the second discount applies to the "already reduced price," meaning the mathematical bases for the two percentages are distinct.

**B. Algebraic method**
Let $P$ represent the original price.
The price after the first 25% discount is $P - 0.25P = 0.75P$.
The price after the second 20% discount is $0.75P - 0.20(0.75P)$, which simplifies to $0.75P \times 0.80 = 0.60P$.
Set this final expression equal to the known final price:
$0.60P = 156$
$P = \frac{156}{0.60}$
$P = 260$

**C. Entirely different method**
Using a 100-unit proportional model:
Assume the original price is exactly 100 units.
A 25% discount removes 25 units, leaving an intermediate price of 75 units.
A 20% discount applied to those 75 units removes 15 units ($75 \times 0.20 = 15$), leaving a final price of 60 units.
These final 60 units correspond to the actual final price of $156.
The value of a single unit is $\frac{156}{60} = 2.6$.
The original price is 100 units, so $100 \times 2.6 = 260$.

**D. Cross-check**
The formal algebraic method yields $260. The proportional unit model also yields $260. Both distinct approaches result in the exact same answer.

**E. Plausibility test**
(i) $260 is a positive price.
(ii) $260 is strictly higher than the final price of $156.
(iii) Applying a 25% discount to $260 yields $195 ($260 - $65). Applying a subsequent 20% discount to $195 yields $156 ($195 - $39). This matches the required final amount exactly.
(iv) The intermediate price is $195, which is positive and lower than the original $260.

**F. Final answer**
The coat's original price before any discount was $260.

**A. Clarify the definition**
The average speed for an entire trip is strictly defined as the total distance traveled divided by the total time taken to complete the trip. It is frequently mistaken for the simple arithmetic mean of the two speeds, which in this case would be incorrectly calculated as $(28 + 42) / 2 = 35$ km/h.

**B. Algebraic method**
Let $d_1 = 84$ km and $v_1 = 28$ km/h for the outbound leg.
Let $d_2 = 84$ km and $v_2 = 42$ km/h for the return leg.
The time for the outbound leg is $t_1 = d_1 / v_1 = 84 / 28 = 3$ hours.
The time for the return leg is $t_2 = d_2 / v_2 = 84 / 42 = 2$ hours.
The total distance is $d_{total} = 84 + 84 = 168$ km.
The total time is $t_{total} = 3 + 2 = 5$ hours.
The average speed is $v_{avg} = d_{total} / t_{total} = 168 / 5 = 33.6$ km/h.

**C. Entirely different method**
Because the distances of both legs are identical, the average speed can be calculated using the harmonic mean of the two speeds, independent of the actual distance traveled.
The harmonic mean formula for two speeds is $v_{avg} = \frac{2v_1v_2}{v_1 + v_2}$.
Substituting the speeds: $v_{avg} = \frac{2(28)(42)}{28 + 42} = \frac{2352}{70} = 33.6$ km/h.

**D. Cross-check**
Both the time-distance algebraic calculation ($168 / 5$) and the distance-independent harmonic mean approach ($\frac{2352}{70}$) yield the exact same result of $33.6$ km/h.

**E. Plausibility test**
(i) The value $33.6$ km/h correctly lies between the two bounding speeds of 28 km/h and 42 km/h. It is logically closer to the slower speed because more time is spent driving at 28 km/h.
(ii) Multiplying the answer by the total travel time: $33.6 \text{ km/h} \times 5 \text{ hours} = 168$ km, which matches the total distance.
(iii) The total travel time implied by dividing the distances by their respective speeds ($3$ hours $+ 2$ hours) equals exactly $5$ hours.
(iv) The result is perfectly mathematically consistent with the given outbound distance (84), outbound speed (28), and return speed (42).

**F. Final answer**
The van's average speed for the entire round trip is 33.6 km/h.

**A. Clarify the rate**
A single pump fills $\frac{1}{12}$ of a tank per minute. The pumps work perfectly in parallel without interfering with one another. The number of pumps (six) and their individual rates remain fixed, while the total volume of work (number of tanks) changes from 6 to 18.

**B. Algebraic method**
Let $P$ be the number of pumps, $V$ be the volume in tanks, $t$ be time in minutes, and $r$ be the rate of one pump. The work equation is $V = P \cdot r \cdot t$.
Given the initial state, $6 = 6 \cdot r \cdot 12$, which simplifies to $6 = 72r$, meaning $r = \frac{1}{12}$ tanks per pump-minute.
For the new scenario with 18 tanks and 6 pumps, the equation is $18 = 6 \cdot \frac{1}{12} \cdot t$. Simplifying this gives $18 = 0.5t$, which solves to $t = 36$.

**C. Entirely different method**
Using logical scaling, a system of six pumps completes a full "batch" of six tanks in exactly 12 minutes. Filling eighteen tanks requires exactly three of these six-tank batches ($\frac{18}{6} = 3$). Since the pumps work at a constant rate and process batches sequentially, three batches take $3 \times 12 = 36$ minutes.

**D. Cross-check**
The algebraic approach (solving for the single-pump rate variable) and the logical scaling approach (multiplying the batch duration by the workload factor) both independently result in exactly 36 minutes.

**E. Plausibility test**
(i) 36 minutes is a positive duration.
(ii) At $\frac{1}{12}$ tank per minute each, 6 pumps working for 36 minutes yields $6 \times \frac{1}{12} \times 36 = 18$ tanks.
(iii) One pump working alone would fill 18 tanks in $18 \times 12 = 216$ minutes, which is exactly six times the 36-minute answer for six pumps.
(iv) 36 minutes is appropriately longer than the original 12 minutes required to fill fewer tanks.

**F. Final answer**
36 minutes.