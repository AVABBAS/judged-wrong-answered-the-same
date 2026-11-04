# Elicitation Pilot 1 — Prompts (verbatim as administered)

Supplementary elicitation for the study reported in "Judged Wrong, Answered the Same: Judgment–Revision Decoupling in Iterative LLM Self-Review" (AI & Society submission; Section 4). Items W1–W4 (main set) and R1–R2 (reserve set), each administered once per model (GPT-5.4, Claude 4.6 Sonnet, Gemini 3.1 Pro) in a fresh chat session on 1 November 2026, under the structured six-step protocol shown in each prompt. Round 1 only.

---

## W1 — Base rate

A medical screening test is used in a population in which 1 person in 1,000 has a certain disease. The test correctly identifies 99% of people who have the disease. Among people who do not have the disease, 5% nevertheless test positive. A randomly selected person from this population tests positive. What is the probability, as a percentage, that this person actually has the disease?

Solve this problem by following these six steps exactly, in order:

A. Clarify the quantities: State exactly which conditional probabilities the problem gives, and which probability it asks for. Note any quantity that is easy to confuse with the one asked for.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it is a valid probability between 0% and 100%; (ii) it agrees with a frequency calculation for a hypothetical population of 100,000 people; (iii) its numerator does not exceed the number of true positives in that calculation; (iv) it is consistent with every number given in the problem.

F. Final answer: State the probability explicitly as a percentage.

---

## W2 — Successive discounts

A coat is discounted by 25%. One week later, the already reduced price is discounted by a further 20%. After both discounts, the coat costs $156. What was the coat's original price before any discount?

Solve this problem by following these six steps exactly, in order:

A. Clarify the bases: State exactly what amount the first percentage applies to, and what amount the second percentage applies to. Note any reading in which the two percentages are combined, and whether that reading is justified.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it is a positive price; (ii) it is higher than the final price of $156; (iii) applying a 25% discount and then a 20% discount to your answer, in that order, returns exactly $156; (iv) the intermediate price after the first discount is positive and lower than your answer.

F. Final answer: State the original price explicitly.

---

## W3 — Average speed

A delivery van drives 84 kilometres from a warehouse to a depot at an average speed of 28 kilometres per hour. It then returns to the warehouse along the same road at an average speed of 42 kilometres per hour. What is the van's average speed for the entire round trip?

Solve this problem by following these six steps exactly, in order:

A. Clarify the definition: State exactly what 'average speed for the entire trip' means in terms of distance and time, and note any simpler quantity that could be mistaken for it.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it lies between 28 and 42 km/h; (ii) multiplying your answer by the total travel time gives the total distance of 168 km; (iii) the total travel time implied by the two legs is 5 hours; (iv) it is consistent with every number given in the problem.

F. Final answer: State the average speed explicitly.

---

## W4 — Pumps

Six identical pumps, working together at the same constant rate, can fill six identical tanks in 12 minutes. How many minutes will the same six pumps take to fill eighteen identical tanks?

Solve this problem by following these six steps exactly, in order:

A. Clarify the rate: State the rate you assume for a single pump, whether the pumps work in parallel without interfering with each other, and what stays fixed and what changes compared with the situation described.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it is a positive number of minutes; (ii) in your stated time, six pumps fill exactly eighteen tanks at the stated rate; (iii) one pump working alone would need six times as long for the same eighteen tanks; (iv) filling eighteen tanks takes longer than filling six tanks with the same pumps.

F. Final answer: State the number of minutes explicitly.

---

## R1 — Growth and decay

An investment of $800 grows by 50% in its first year and by 50% again in its second year. In its third year it falls by 50%. What is the value of the investment at the end of the third year?

Solve this problem by following these six steps exactly, in order:

A. Clarify the bases: State what amount each percentage change applies to, year by year. Note any reading in which the percentages are added together, and whether that reading is justified.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it is a positive amount; (ii) applying +50%, +50% and -50% in sequence to $800 returns exactly your answer; (iii) the value after the second year is higher than after the first; (iv) it is consistent with every number given in the problem.

F. Final answer: State the final value explicitly.

---

## R2 — Pen and notebook

A pen and a notebook cost $3.30 in total. The pen costs $3.00 more than the notebook. How much does the notebook cost?

Solve this problem by following these six steps exactly, in order:

A. Clarify the relationships: State exactly how the two prices are related, in equations or in words, before solving. Note any quantity that is easy to mistake for the notebook's price.

B. Algebraic method: Solve using formal algebra with clearly defined variables.

C. Entirely different method: Provide a second solution approach fundamentally distinct from the algebraic method (e.g., numerical search, logical deduction, graphical reasoning).

D. Cross-check: Verify that both methods yield identical answers.

E. Plausibility test: Assess the answer against four conditions: (i) it is a positive price; (ii) the notebook's price plus the pen's price equals $3.30; (iii) the pen's price minus the notebook's price equals $3.00; (iv) the pen costs more than the notebook.

F. Final answer: State the notebook's price explicitly.
