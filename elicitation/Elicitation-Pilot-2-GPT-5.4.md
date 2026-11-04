## A. Clarify the quantities

The problem gives three conditional probabilities:

1\. Prevalence (prior probability): 1 in 500 people has the disease.

\\[ P(D)=\frac{1}{500}=0.002=0.2\\% \\]

2\. Sensitivity (true positive rate): The test correctly identifies 95% of people who have the disease.

\\[ P(+|D)=0.95 \\]

3\. False positive rate: Among people without the disease, 4% nevertheless test positive.

\\[ P(+|\neg D)=0.04 \\]

The person tests positive twice. Because the two results are independent given the person's disease status, we multiply the corresponding probabilities:

\- Probability of two positive results if the person has the disease:

\\[ P(++|D)=0.95\times0.95=0.9025 \\]

\- Probability of two positive results if the person does not have the disease:

\\[ P(++|\neg D)=0.04\times0.04=0.0016 \\]

Important distinction: We are looking for the probability of having the disease given two positive results:

\\[ P(D|++) \\]

This is different from the probability after only one positive result.

For one positive result, the probability would be approximately 4.55%. That is not the answer here because the second positive result provides additional evidence.

## B. Algebraic method

Step 1: Define the variables.

Let:

- \\(D\\) = person has the disease.
- \\(\neg D\\) = person does not have the disease.
- \\(++\\) = both tests return positive.

We know:

\\[ P(D)=0.002 \\]

\\[ P(\neg D)=0.998 \\]

\\[ P(++|D)=0.9025 \\]

\\[ P(++|\neg D)=0.0016 \\]

Step 2: Apply Bayes' theorem.

\\[ P(D|++)= \frac{P(++|D)P(D)} {P(++|D)P(D)+P(++|\neg D)P(\neg D)} \\]

Step 3: Substitute the values.

\\[ P(D|++)= \frac{0.9025(0.002)} {0.9025(0.002)+0.0016(0.998)} \\]

Step 4: Calculate the numerator.

\\[ 0.9025\times0.002=0.001805 \\]

Step 5: Calculate the denominator.

\\[ 0.001805+(0.0016\times0.998) \\]

\\[ =0.001805+0.0015968 \\]

\\[ =0.0034018 \\]

Step 6: Calculate the final probability.

\\[ P(D|++)=\frac{0.001805}{0.0034018} \\]

\\[ =0.5302898\ldots \\]

Therefore:

\\[ \boxed{53.03\\%} \\]

## C. Entirely different method: Frequency-based reasoning

Instead of using Bayes' theorem directly, imagine testing a population of 1,000,000 people.

We can count how many people fall into each category.

Step 1: Divide the population according to disease status.

Since 1 in 500 has the disease:

\- People with the disease:

\\[ 1,000,000/500=2,000 \\]

\- People without the disease:

\\[ 1,000,000-2,000=998,000 \\]

Step 2: Count people with the disease who test positive twice.

95% test positive on each test, independently:

\\[ 2,000\times0.95\times0.95 \\]

\\[ =1,805 \\]

Step 3: Count people without the disease who test positive twice.

4% test positive on each test, independently:

\\[ 998,000\times0.04\times0.04 \\]

\\[ =1,596.8 \\]

Step 4: Count everyone who tests positive twice.

\\[ 1,805+1,596.8=3,401.8 \\]

Step 5: Calculate the proportion who actually have the disease.

Among everyone who tests positive twice, 1,805 have the disease.

\\[ \frac{1,805}{3,401.8}\times100 \\]

\\[ =\boxed{53.03\\%} \\]

This approach reaches the answer by counting hypothetical people rather than manipulating conditional-probability equations.

## D. Cross-check

Both methods produce the same result:

| Method                      | Probability |
| --------------------------- | ----------- |
| Algebraic (Bayes' theorem)  | 53.03%      |
| Frequency-based calculation | 53.03%      |

The underlying calculations are identical in their treatment of the two independent tests.

\\[ 53.02898\ldots\\%\approx53.03\\% \\]

Both methods agree

## E. Plausibility test

(i) Is the answer a valid probability?

Yes.

\\[ 0\\%<53.03\\%<100\\% \\]

It is a valid probability.

(ii) Does it agree with the frequency calculation for 1,000,000 people?

Yes.

- 2,000 people have the disease.
- 1,805 have the disease and test positive twice.
- 1,596.8 people without the disease test positive twice.
- Total double-positive cases: 3,401.8.

Therefore:

\\[ \frac{1,805}{3,401.8}\times100=53.03\\% \\]

(iii) Does the numerator exceed the number of people who have the disease and test positive twice?

No.

The numerator is 1,805, exactly the number of people who have the disease and test positive twice.

It does not exceed that number.

(iv) Is the answer consistent with every number in the problem?

Yes.

- Disease prevalence is exactly 1 in 500.
- Sensitivity is 95% on each test.
- False positive rate is 4% on each test.
- Independence is applied separately to people with and without the disease.
- Both tests have the same accuracy.

All given conditions are satisfied.

## F. Final answer

Probability that the person actually has the disease

# 53.03%

After testing positive twice, the probability of actually having the disease is approximately 53.03%.
## A. Clarify the order and the bases

The three operations are applied in the following order:

1. 25% discount: Applied to the coat's original price. Therefore, 75% of the original price remains.
2. 8% sales tax: Applied to the discounted price, not the original price.
3. $12 delivery fee: Added as a flat amount after the sales tax. It is neither discounted nor taxed.

The total is therefore:

\\[ \text{Total}=(\text{Original Price}\times0.75)\times1.08+12 \\]

Applying the tax to the original price or applying a discount or tax to the delivery fee would contradict the stated order.

## B. Algebraic method

Let:

- \\(x\\) = original price of the coat.
- \\(0.75x\\) = price after the 25% discount.
- \\(1.08(0.75x)\\) = price after the 8% tax.

The total paid is $255:

\\[ 1.08(0.75x)+12=255 \\]

Subtract $12 from both sides:

\\[ 1.08(0.75x)=243 \\]

Multiply the coefficients:

\\[ 0.81x=243 \\]

Divide both sides by 0.81:

\\[ x=\frac{243}{0.81} \\]

\\[ \boxed{x=300} \\]

## C. Entirely different method: Reverse calculation

Instead of constructing an equation from the original price, work backward from the final payment.

Step 1: Remove the delivery fee.

\\[ 255-12=243 \\]

The amount of $243 represents the coat price after discount and tax.

Step 2: Reverse the 8% tax.

Since the taxed price is 108% of the discounted price:

\\[ 243\div1.08=225 \\]

The discounted coat price was $225.

Step 3: Reverse the 25% discount.

After a 25% discount, the remaining price is 75% of the original price:

\\[ 225\div0.75=300 \\]

Therefore:

\\[ \boxed{\\$300} \\]

## D. Cross-check

Both methods produce the same result:

| Method              | Original price |
| ------------------- | -------------- |
| Algebraic method    | $300           |
| Reverse calculation | $300           |

Both methods agree

## E. Plausibility test

(i) Is the original price positive?

\\[ 300>0 \\]

Yes.

(ii) Does applying all three operations return exactly $255?

Starting with $300:

\- 25% discount:

\\[ 300\times0.75=225 \\]

\- 8% sales tax:

\\[ 225\times0.08=18 \\]

\\[ 225+18=243 \\]

\- Add delivery fee:

\\[ 243+12=\boxed{255} \\]

Yes, the final amount is exactly $255.

(iii) Is the discounted price positive and lower than the original price?

\\[ 0<225<300 \\]

Yes.

(iv) Is the tax calculated on the discounted price?

\\[ 225\times0.08=18 \\]

Yes. The tax is $18, calculated on $225 rather than the original $300.

All four conditions satisfied

## F. Final answer

THE COAT'S ORIGINAL PRICE

# $300.00

The original price before the discount was $300.
## A. Clarify the definition

The average speed for the entire journey is:

\\[ \text{Average speed}= \frac{\text{Total distance}}{\text{Total elapsed time}} \\]

The total elapsed time includes both driving time and the 1-hour stop.

Two other quantities must not be confused with the requested average speed:

1\. Mean of the two driving speeds:\
\\[\
\frac{45+30}{2}=37.5\text{ km/h}\
\\]\
This is not the correct answer because the driver spends different amounts of time travelling at each speed.

2\. Average speed during driving time only: This excludes the stopped hour and therefore does not represent the entire journey.

## B. Algebraic method

Step 1: Define the variables.

Let:

- \\(d_1=90\\) km (first distance).
- \\(v_1=45\\) km/h (first speed).
- \\(d_2=60\\) km (second distance).
- \\(v_2=30\\) km/h (second speed).
- \\(t_s=1\\) hour (stopping time).

Step 2: Calculate the driving times.

Using:

\\[ t=\frac{d}{v} \\]

First driving time:

\\[ t_1=\frac{90}{45}=2\text{ hours} \\]

Second driving time:

\\[ t_2=\frac{60}{30}=2\text{ hours} \\]

Step 3: Calculate total distance.

\\[ D=d_1+d_2 \\]

\\[ D=90+60=150\text{ km} \\]

Step 4: Calculate total elapsed time.

\\[ T=t_1+t_s+t_2 \\]

\\[ T=2+1+2=5\text{ hours} \\]

Step 5: Calculate average speed.

Let \\(v\_{\text{avg}}\\) represent the average speed.

\\[ v\_{\text{avg}}=\frac{D}{T} \\]

\\[ v\_{\text{avg}}=\frac{150}{5} \\]

\\[ \boxed{v\_{\text{avg}}=30\text{ km/h}} \\]

## C. Entirely different method: Numerical timeline

Instead of using an algebraic formula directly, construct a timeline of the journey.

| Time interval | Activity           | Distance covered |
| ------------- | ------------------ | ---------------- |
| 0–1 hour      | Driving at 45 km/h | 45 km            |
| 1–2 hours     | Driving at 45 km/h | 45 km            |
| 2–3 hours     | Stopped            | 0 km             |
| 3–4 hours     | Driving at 30 km/h | 30 km            |
| 4–5 hours     | Driving at 30 km/h | 30 km            |
| Total         | 5 hours            | 150 km           |

The driver covers 150 kilometres in five hours.

If the journey were completed at one constant speed, that speed would need to cover exactly 30 kilometres in each hour.

Therefore:

\\[ 30+30+30+30+30=150 \\]

The equivalent constant speed is:

\\[ \boxed{30\text{ km/h}} \\]

## D. Cross-check

Both methods produce the same result:

| Method             | Average speed |
| ------------------ | ------------- |
| Algebraic method   | 30 km/h       |
| Numerical timeline | 30 km/h       |

Thus:

\\[ 30=30 \\]

Both methods agree

## E. Plausibility test

(i) Positive speed no greater than 45 km/h

\\[ 0<30\leq45 \\]

&#x20;Satisfied.

(ii) Multiplying average speed by total elapsed time gives total distance

\\[ 30\times5=150\text{ km} \\]

&#x20;Satisfied.

(iii) Total elapsed time includes the one-hour stop

\\[ 2+1+2=5\text{ hours} \\]

&#x20;Satisfied.

(iv) Consistency with every number in the problem

- First journey: \\(45\times2=90\\) km.
- Stop: exactly 1 hour, covering 0 km.
- Second journey: \\(30\times2=60\\) km.
- Total distance: \\(90+60=150\\) km.
- Total elapsed time: 5 hours.

&#x20;All given information is consistent.

## F. Final answer

FINAL ANSWER

# 30 km/h

The driver's average speed for the entire journey, including the one-hour stop, is 30 kilometres per hour.

## A. Clarify the work

The total work is:

\\[ 6\times10=60\text{ painter-days} \\]

This means six painters working together for ten days complete the entire building.

The following remain fixed:

- Total work: 60 painter-days.
- Individual productivity: Each painter works at the same constant rate throughout the project.

What changes after the fourth day is the crew size:

- First phase: 6 painters for 4 days.
- Second phase: 4 painters until completion.

The total time cannot be calculated simply by dividing 60 painter-days by 4 painters because the first four days of work were already completed by six painters.

## B. Algebraic method

Let \\(x\\) represent the number of additional days required by the remaining four painters.

Step 1: Calculate the work completed during the first phase.

\\[ 6\times4=24\text{ painter-days} \\]

Step 2: Calculate the remaining work.

\\[ 60-24=36\text{ painter-days} \\]

Step 3: Calculate the duration of the second phase.

Since four painters complete 36 painter-days of work:

\\[ 4x=36 \\]

\\[ x=\frac{36}{4}=9 \\]

Step 4: Calculate the total duration.

\\[ T=4+x \\]

\\[ T=4+9=\boxed{13\text{ days}} \\]

## C. Entirely different method: Work-rate reasoning

Instead of using an algebraic equation, consider the work completed per day.

1. Six painters complete \\(1/10\\) of the building each day.
2. During four days, they complete:

\\[ \frac{4}{10}=40\\% \\]

3. Therefore, 60% of the building remains.
4. Four painters work at two-thirds of the original crew's daily productivity:

\\[ \frac{4}{6}\times\frac{1}{10} =\frac{1}{15} \\]

Thus, four painters complete \\(1/15\\) of the building per day.

5\. The time required to complete the remaining 60% is:

\\[ \frac{60\\%}{1/15}=9\text{ days} \\]

6\. Add the first four days:

\\[ 4+9=\boxed{13\text{ days}} \\]

## D. Cross-check

Both independent methods produce exactly the same result:

| Calculation  | Algebraic method | Work-rate method |
| ------------ | ---------------- | ---------------- |
| First phase  | 4 days           | 4 days           |
| Second phase | 9 days           | 9 days           |
| Total        | 13 days          | 13 days          |

The results are identical.

## E. Plausibility test

(i) Positive and longer than the first phase

\\[ 13>4>0 \\]

Pass

(ii) Total work completed equals 60 painter-days

\\[ (6\times4)+(4\times9) \\]

\\[ 24+36=60 \\]

Pass

(iii) The second phase covers exactly the remaining work

After four days, 36 painter-days remain.

\\[ 4\times9=36 \\]

The remaining four painters complete exactly the unfinished work.

Pass

(iv) Total time is longer than the original 10 days

\\[ 13>10 \\]

The smaller crew takes longer to finish the project than the original six-person crew would have taken.

Pass

## F. Final answer

FINAL ANSWER

# 13 days

The building takes 13 days in total to paint: 4 days with six painters and 9 additional days with four painters.

We can solve this using Bayes' Theorem.

### Step 1: Identify the given probabilities

Let:

- \\(D\\) = The person has the disease.
- \\(+\\) = The person tests positive.

We are given:

- Probability of having the disease (prevalence):\
  \\[\
  P(D)=\frac{1}{1000}=0.001\
  \\]
- Probability of not having the disease:\
  \\[\
  P(\neg D)=0.999\
  \\]
- True positive rate (sensitivity):\
  \\[\
  P(+|D)=0.99\
  \\]
- False positive rate:\
  \\[\
  P(+|\neg D)=0.05\
  \\]

### Step 2: Apply Bayes' Theorem

Bayes' Theorem states:

\\[ P(D|+)=\frac{P(+|D)\times P(D)}{P(+)} \\]

The total probability of testing positive is:

\\[ P(+)=P(+|D)P(D)+P(+|\neg D)P(\neg D) \\]

### Step 3: Substitute the values

\\[ P(D|+)= \frac{0.99\times0.001} {(0.99\times0.001)+(0.05\times0.999)} \\]

### Step 4: Calculate the numerator and denominator

Numerator:

\\[ 0.99\times0.001=0.00099 \\]

Denominator:

\\[ 0.00099+(0.05\times0.999) \\]

\\[ =0.00099+0.04995 \\]

\\[ =0.05094 \\]

### Step 5: Calculate the posterior probability

\\[ P(D|+)=\frac{0.00099}{0.05094} \\]

\\[ P(D|+)\approx0.0194346 \\]

### Step 6: Convert to a percentage

\\[ 0.0194346\times100=1.94346\\% \\]

Final answer: 1.94%

Interpretation: Despite the test being 99% accurate at identifying people who have the disease, someone who tests positive has only approximately a 1.94% probability of actually having the disease.

Why? Because the disease is very rare (1 in 1,000), the number of false positives among healthy people substantially exceeds the number of true positives. This is an example of the base-rate fallacy.
The notebook costs $0.15 (15 cents).

Step-by-step solution:

1. Let \\(x\\) be the notebook's price.
2. The pen costs $3.00 more, so its price is \\(x+3.00\\).
3. Their combined price is $3.30:

\\[ x+(x+3.00)=3.30 \\]

4\. Simplify:

\\[ 2x+3.00=3.30 \\]

5\. Subtract $3.00:

\\[ 2x=0.30 \\]

6\. Divide by 2:

\\[ x=0.15 \\]

Verification:

- Notebook: $0.15
- Pen: $3.15
- Total: $3.30

Final answer: $0.15