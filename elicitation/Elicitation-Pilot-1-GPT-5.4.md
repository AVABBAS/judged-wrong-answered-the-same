## A. Clarify the quantities

We are given three probabilities:

1\. Prevalence of the disease:

&#x20;  1 person in 1,000 has the disease.

\\[ P(D)=\frac{1}{1000}=0.001=0.1\\% \\]

2\. Sensitivity (true positive rate):

&#x20;  The test correctly identifies 99% of people who have the disease.

\\[ P(+|D)=0.99=99\\% \\]

3\. False positive rate:

&#x20;  Among people who do not have the disease, 5% test positive.

\\[ P(+|\neg D)=0.05=5\\% \\]

What we are asked to calculate:

The probability that a person actually has the disease, given that their test result is positive:

\\[ P(D|+)=? \\]

Important distinction:

The problem gives \\(P(+|D)\\), but asks for \\(P(D|+)\\).

These are different conditional probabilities. A 99% probability of testing positive when someone is sick does NOT mean that someone who tests positive has a 99% probability of being sick.

\\(P(A|B) = \frac{P(A \cap B)}{P(B)}\\)

\\(P(A\mid B)=\frac{P(A\cap B)}{P(B)}=\frac{\text{0.00}}{\text{0.06}}=\text{0.02}\\)

\\(P(B)\\)

\\(P(A\cap B)\\)

P(B)=0.06P(A∩B)=0.00P(A|B) ≈ 0.02A∩B is the part of B where A also happens

Give feedback

## B. Algebraic method

We define:

- \\(D\\): The person has the disease.
- \\(\neg D\\): The person does not have the disease.
- \\(+\\): The person tests positive.

We know:

\\[ P(D)=0.001 \\]

\\[ P(\neg D)=0.999 \\]

\\[ P(+|D)=0.99 \\]

\\[ P(+|\neg D)=0.05 \\]

Using Bayes' theorem:

\\[ P(D|+)= \frac{P(+|D)P(D)}{P(+)} \\]

First, calculate the total probability of a positive test:

\\[ P(+)=P(+|D)P(D)+P(+|\neg D)P(\neg D) \\]

Substitute the known values:

\\[ P(+)=(0.99)(0.001)+(0.05)(0.999) \\]

\\[ P(+)=0.00099+0.04995 \\]

\\[ P(+)=0.05094 \\]

Now substitute into Bayes' theorem:

\\[ P(D|+)=\frac{0.99\times0.001}{0.05094} \\]

\\[ P(D|+)=\frac{0.00099}{0.05094} \\]

\\[ P(D|+)=0.0194346\ldots \\]

Therefore:

\\[ P(D|+)\approx1.94346\\% \\]

## C. Entirely different method: Numerical frequency calculation

Instead of using probability formulas, imagine testing a population of exactly 100,000 people.

This method uses actual numbers of people rather than algebraic probability calculations.

Step 1: Identify people who have the disease.

1 in 1,000 people has the disease:

\\[ \frac{100,000}{1,000}=100 \\]

Therefore:

- 100 people have the disease.
- 99,900 people do not have the disease.

Step 2: Calculate true positives.

The test correctly identifies 99% of the 100 sick people:

\\[ 100\times0.99=99 \\]

Therefore, 99 people test positive and actually have the disease.

Step 3: Calculate false positives.

5% of the 99,900 healthy people test positive:

\\[ 99,900\times0.05=4,995 \\]

Therefore, 4,995 healthy people also test positive.

Step 4: Calculate all positive results.

\\[ 99+4,995=5,094 \\]

Step 5: Calculate the proportion of positive results that are true positives.

\\[ \frac{99}{5,094}\times100 \\]

\\[ =1.94346\ldots\\% \\]

Therefore, approximately 1.94346% of people who test positive actually have the disease.

## D. Cross-check

Both methods produce the same result:

| Method                            | Result   |
| --------------------------------- | -------- |
| Algebraic method (Bayes' theorem) | 1.94346% |
| Numerical frequency method        | 1.94346% |

The results are identical.

\\[ \boxed{1.94346\\%\approx1.94\\%} \\]

## E. Plausibility test

Let's evaluate the answer against all four requested conditions.

(i) Is it a valid probability?

Yes.

\\[ 0\\%<1.94346\\%<100\\% \\]

It is a mathematically valid probability.

(ii) Does it agree with the hypothetical population of 100,000?

Yes.

- Total population: 100,000
- Total positive results: 5,094
- True positive results: 99

Thus:

\\[ \frac{99}{5,094}\times100=1.94346\\% \\]

This agrees with our answer.

(iii) Does its numerator exceed the number of true positives?

No.

The numerator is 99, representing the true positives.

The denominator is 5,094, representing everyone who tests positive.

Therefore:

\\[ 99\leq5,094 \\]

The condition is satisfied.

(iv) Is it consistent with every number in the problem?

Yes.

| Given condition                              | Numerical verification |
| -------------------------------------------- | ---------------------- |
| 1 in 1,000 has the disease                   | 100 out of 100,000     |
| 99% of sick people test positive             | 99 out of 100          |
| 5% of healthy people test positive           | 4,995 out of 99,900    |
| Probability of disease given positive result | 99 out of 5,094        |

All four conditions are satisfied.

## F. Final answer

FINAL RESULT

# 1.94346%

The probability that a randomly selected person who tests positive actually has the disease is approximately 1.94%.

Key insight: Despite the test having 99% sensitivity, the disease is so rare that false positives among the much larger healthy population vastly outnumber true positives. This is why a positive test does not imply a high probability of actually having the disease.



## A. Clarify the bases

The two discounts are applied to different amounts:

1. The first discount of 25% applies to the coat's original price.
2. The second discount of 20% applies to the already reduced price after the first discount.

Therefore, the discounts are sequential, not directly additive.

It would be incorrect to simply add 25% + 20% = 45% and subtract 45% from the original price. The second discount is calculated on a smaller amount.

## B. Algebraic method

Step 1: Define the variable.

Let \\(x\\) represent the original price of the coat.

Step 2: Apply the first discount.

A 25% discount means the customer pays 75% of the original price:

\\[ x \times 0.75 = 0.75x \\]

Step 3: Apply the second discount.

A further 20% discount means the customer pays 80% of the reduced price:

\\[ 0.75x \times 0.80 = 156 \\]

Step 4: Solve the equation.

\\[ 0.60x = 156 \\]

\\[ x = \frac{156}{0.60} \\]

\\[ \boxed{x=260} \\]

## C. Entirely different method: Working backwards

Instead of calculating discounts forward, we can reverse them.

Step 1: Reverse the second discount.

After a 20% discount, the customer pays 80% of the previous price.

Therefore, $156 represents 80% of the price after the first discount.

\\[ 156 \div 0.80 = 195 \\]

The price after the first discount was $195.

Step 2: Reverse the first discount.

After a 25% discount, the customer pays 75% of the original price.

Therefore:

\\[ 195 \div 0.75 = 260 \\]

The original price was $260.

## D. Cross-check

Both methods produce exactly the same result:

| Method            | Original price |
| ----------------- | -------------- |
| Algebraic method  | $260           |
| Working backwards | $260           |

\\[ 260=260 \\]

Both methods agree

## E. Plausibility test

Let's verify all four conditions.

(i) Is the original price positive?

\\[ 260>0 \\]

Pass

(ii) Is it higher than the final price?

\\[ 260>156 \\]

Pass

(iii) Do both discounts return exactly $156?

First discount:

\\[ 260\times0.75=195 \\]

Second discount:

\\[ 195\times0.80=156 \\]

Pass

(iv) Is the intermediate price positive and lower than the original price?

\\[ 0<195<260 \\]

Pass

All four conditions are satisfied.

## F. Final answer

ORIGINAL PRICE

# $260.00

The coat originally cost $260 before either discount.

## A. Clarify the definition

The average speed for the entire trip is defined as:

\\[ \text{Average Speed}=\frac{\text{Total Distance}}{\text{Total Time}} \\]

The van completes two journeys:

- Outbound: 84 km at 28 km/h.
- Return: 84 km at 42 km/h.

Therefore:

- Total distance = \\(84+84=168\\) km.
- Total time = outbound time + return time.

Important distinction: Average speed is not the arithmetic mean of the two speeds:

\\[ \frac{28+42}{2}=35\text{ km/h} \\]

That calculation is incorrect here because the van spends different amounts of time travelling at each speed.

## B. Algebraic method

Step 1: Define the variables.

Let:

- \\(d=84\\) km represent the distance of each leg.
- \\(v_1=28\\) km/h represent the outbound speed.
- \\(v_2=42\\) km/h represent the return speed.
- \\(V\\) represent the average speed of the entire trip.

Step 2: Calculate the time for each leg.

Using:

\\[ t=\frac{d}{v} \\]

Outbound time:

\\[ t_1=\frac{84}{28}=3\text{ hours} \\]

Return time:

\\[ t_2=\frac{84}{42}=2\text{ hours} \\]

Step 3: Calculate total time.

\\[ T=t_1+t_2 \\]

\\[ T=3+2=5\text{ hours} \\]

Step 4: Calculate average speed.

\\[ V=\frac{\text{Total Distance}}{\text{Total Time}} \\]

\\[ V=\frac{84+84}{3+2} \\]

\\[ V=\frac{168}{5} \\]

\\[ \boxed{V=33.6\text{ km/h}} \\]

## C. Entirely different method

We can solve this using a logical deduction based on equal distances.

The van travels exactly the same distance in both directions: 84 km.

Consider the time spent at each speed:

| Direction | Speed   | Time    |
| --------- | ------- | ------- |
| Outbound  | 28 km/h | 3 hours |
| Return    | 42 km/h | 2 hours |

The van travels:

- 84 km in the first 3 hours.
- 84 km in the next 2 hours.

Now imagine distributing the entire 168 km equally across the 5 hours.

\\[ 168\div5=33.6 \\]

Thus, the average speed must be 33.6 km/h.

This method uses the actual travel times rather than averaging the two speeds.

## D. Cross-check

Both methods produce the same result:

| Method                        | Average speed |
| ----------------------------- | ------------- |
| Algebraic method              | 33.6 km/h     |
| Equal-distance logical method | 33.6 km/h     |

Therefore:

\\[ 33.6=33.6 \\]

Both methods agree

## E. Plausibility test

(i) Is the answer between 28 and 42 km/h?

\\[ 28<33.6<42 \\]

Pass

(ii) Does multiplying the average speed by total time give 168 km?

\\[ 33.6\times5=168\text{ km} \\]

Pass

(iii) Is the total travel time 5 hours?

\\[ \frac{84}{28}+\frac{84}{42} =3+2=5\text{ hours} \\]

Pass

(iv) Is the answer consistent with every number in the problem?

- Outbound distance: 84 km.
- Return distance: 84 km.
- Outbound speed: 28 km/h.
- Return speed: 42 km/h.
- Total distance: 168 km.
- Total time: 5 hours.
- Calculated average speed: 33.6 km/h.

All given values are satisfied.

Pass

## F. Final answer

Average speed for the entire round trip

# 33.6 km/h

The van travels 168 kilometres in a total of 5 hours.

\\[ \boxed{\frac{168}{5}=33.6\text{ km/h}} \\]


## A. Clarify the rate

We are given:

- 6 identical pumps fill 6 identical tanks in 12 minutes.
- All pumps work simultaneously (in parallel).
- The pumps operate at constant rates without interfering with one another.

Therefore, the combined rate of the six pumps is:

\\[ \frac{6\text{ tanks}}{12\text{ minutes}} =0.5\text{ tank/minute} \\]

Since the pumps are identical, one pump fills:

\\[ \frac{0.5}{6}=\frac{1}{12} \\]

tank per minute.

What stays fixed: Six pumps, their individual rates, and the tank sizes.

What changes: The number of tanks increases from 6 to 18.

## B. Algebraic method

Let:

- \\(r\\) = rate of one pump, in tanks per minute.
- \\(t\\) = time required to fill 18 tanks, in minutes.

From the original situation:

\\[ 6\times 12\times r=6 \\]

Solving for \\(r\\):

\\[ 72r=6 \\]

\\[ r=\frac{1}{12} \\]

For the new situation:

\\[ 6\times t\times \frac{1}{12}=18 \\]

Simplifying:

\\[ \frac{t}{2}=18 \\]

\\[ \boxed{t=36} \\]

## C. Entirely different method: Proportional reasoning

Think about the relationship between the number of tanks and the time required.

With the same six pumps:

- Filling 6 tanks takes 12 minutes.
- Filling 12 tanks takes 24 minutes.
- Filling 18 tanks takes 36 minutes.

The number of tanks triples:

\\[ 6\times 3=18 \\]

Therefore, the time must also triple:

\\[ 12\times 3=36 \\]

This method uses direct proportional reasoning rather than solving an algebraic equation.

## D. Cross-check

Both independent methods produce the same result:

| Method                 | Result     |
| ---------------------- | ---------- |
| Algebraic method       | 36 minutes |
| Proportional reasoning | 36 minutes |

Both methods agree

## E. Plausibility test

(i) Is the answer positive?

Yes.

\\[ 36>0 \\]

(ii) Do six pumps fill exactly 18 tanks in 36 minutes?

Each pump fills \\(1/12\\) of a tank per minute.

Therefore:

\\[ 6\times36\times\frac{1}{12}=18 \\]

Yes, exactly 18 tanks.

(iii) Would one pump working alone need six times as long?

Yes. One pump would require:

\\[ 36\times6=216\text{ minutes} \\]

At its rate:

\\[ 216\times\frac{1}{12}=18\text{ tanks} \\]

(iv) Does filling 18 tanks take longer than filling 6 tanks?

Yes.

- 6 tanks: 12 minutes.
- 18 tanks: 36 minutes.

The new task takes three times as long, as expected.

All four conditions are satisfied.

## F. Final answer

FINAL ANSWER

# 36 minutes

Six identical pumps will take 36 minutes to fill eighteen identical tanks.