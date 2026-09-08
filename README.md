# Step 20 — Interpret the Findings
[← Previous Step: Conduct Sensitivity Analysis](https://github.com/adnan-mayof/Sensitivity-Analysis/blob/main/README.md)

## Maya’s Evidence Synthesis Journey

### The Story

Maya has reached an important point in her evidence-synthesis journey.

She has:

* identified the research gap
* developed the research question
* created and tested the search strategy
* searched the databases
* developed the protocol
* screened the records
* assessed risk of bias
* extracted the data
* identified studies suitable for meta-analysis
* prepared the analysis data
* calculated effect sizes
* conducted the meta-analysis
* examined heterogeneity
* examined moderators
* conducted meta-regression
* conducted sensitivity analyses

Now Maya has many numbers in front of her.

She looks at her results table.

**Maya:** “I have all the results. Does that mean I’m finished?”

**Mentor:** “Not quite.”

**Maya:** “What else do I need to do?”

**Mentor:** “You need to interpret what the results mean.”

**Maya:** “Isn’t that just reporting the numbers?”

**Mentor:** “No. Reporting tells the reader **what you found**. Interpretation explains **what those findings mean in the context of your research question and evidence base**.”

Maya looks again at her results.

**Maya:** “So I need to connect the numbers back to the question?”

**Mentor:** “Exactly.”

---

# 1. What Does Interpretation Mean?

Interpretation is the process of explaining the meaning and implications of the evidence-synthesis findings.

Maya's primary meta-analysis produced:

> **Hedges' g = 0.64, 95% CI [0.52, 0.76]**

She should not stop at:

> “The pooled effect was 0.64.”

She needs to explain what that estimate means for her research question.

For example:

> The meta-analysis suggests that AI-powered learning technologies were associated with better learning outcomes than the comparison conditions across the studies included in the quantitative synthesis.

The interpretation connects the statistical finding to the substantive research question.

---

# 2. Start With the Research Question

Maya's research question is:

> **What is the effect of AI-powered learning technologies on student learning outcomes, and which characteristics of the intervention, learners, learning context, and study methodology explain variation in these effects?**

Her interpretation should therefore address both parts.

### Part 1 — Overall effect

> What did the evidence suggest about the effect of AI-powered learning technologies?

### Part 2 — Variation in effects

> What characteristics were associated with differences in effect sizes?

This prevents Maya from reporting statistical analyses without answering the original research question.

---

# 3. Separate Results From Interpretation

Maya creates two columns.

| Results                               | Interpretation                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Hedges' g = 0.64                      | AI-powered learning technologies were associated with better learning outcomes in the included quantitative studies |
| 95% CI [0.52, 0.76]                   | The estimated average effect is reasonably precise                                                                  |
| I² = 58%                              | Effects varied across studies beyond what would be expected from sampling variation alone                           |
| Duration β = 0.021                    | Longer interventions were associated with larger effect sizes at the study level                                    |
| Sensitivity analyses remained similar | The overall conclusion was reasonably stable under the examined analyses                                            |

**Mentor:** “See the difference?”

**Maya:** “Yes. The first column tells me what the analysis produced. The second explains what those results mean.”

---

# 4. Interpret the Direction of the Effect

Before interpreting the magnitude, Maya must know the direction of her effect size.

Her protocol defined:

> **Positive effect = better learning outcomes for the AI intervention group.**

Therefore:

> **g = 0.64**

indicates an effect favoring the AI intervention condition.

If the effect were negative, the interpretation would depend on how the effect-size calculation was coded.

This is why consistent effect-direction coding was important in Step 14.

---

# 5. Interpret the Magnitude Carefully

Maya might be tempted to say:

> “The intervention had a huge effect.”

Her mentor stops her.

**Mentor:** “Be careful.”

**Maya:** “Why?”

**Mentor:** “Effect-size benchmarks can be useful for orientation, but they should not replace substantive interpretation.”

The meaning of an effect size depends on:

* the outcome
* the population
* the intervention
* the comparison condition
* the measurement instruments
* the research context
* the quality and design of the evidence

A standardized effect of 0.64 can provide a useful summary, but Maya should avoid treating a numerical benchmark as a universal description of practical importance.

---

# 6. Statistical Significance Is Not the Same as Practical Importance

Maya sees that the confidence interval does not include zero.

She asks:

**Maya:** “So the result is statistically significant. Does that mean the intervention is important?”

**Mentor:** “Not necessarily.”

Statistical significance addresses whether the observed data provide evidence against a specified null hypothesis.

Practical importance asks a different question:

> **Is the magnitude of the effect meaningful in the real-world context?**

For example, a small effect could be meaningful if:

* the intervention is inexpensive
* it can reach many learners
* it requires little instructor time
* it produces benefits across many settings

Conversely, a statistically significant effect might have limited practical value if the improvement is very small or difficult to implement.

---

# 7. Interpret the Confidence Interval

Maya's result is:

> **g = 0.64, 95% CI [0.52, 0.76]**

The confidence interval communicates uncertainty around the estimated average effect.

Maya can say:

> “The estimated average effect was 0.64, with a 95% confidence interval from 0.52 to 0.76.”

She should avoid saying:

> “There is a 95% probability that the true effect is between 0.52 and 0.76.”

That wording does not represent the standard frequentist interpretation of a confidence interval.

---

# 8. Interpret Heterogeneity

Maya's heterogeneity analysis found:

> **I² = 58%**

She should not simply write:

> “There was 58% heterogeneity.”

Instead, she should explain that the observed variation in effect estimates included a substantial component attributed to between-study heterogeneity under the I² framework.

The important question becomes:

> **Why might the effects differ across studies?**

That leads directly to her moderator and meta-regression findings.

---

# 9. Connect Heterogeneity to Moderators

Maya found differences across AI functions.

Illustrative subgroup results:

| AI Function | Hedges' g |
| ----------- | --------: |
| Tutoring    |      0.78 |
| Feedback    |      0.61 |
| Assessment  |      0.48 |

The omnibus test was statistically significant.

Maya can say:

> “Effect sizes differed across AI-function categories in the included studies.”

But she should be careful.

She should **not** automatically conclude:

> “Tutoring causes greater learning gains than assessment.”

Why?

Because these are study-level comparisons.

The groups may differ in many other ways:

* learner populations
* intervention duration
* outcome measures
* implementation
* study design
* educational settings

Therefore, subgroup differences should generally be interpreted as **associations**, not automatically as causal effects.

---

# 10. Interpret Meta-Regression

Maya's meta-regression found:

> **Duration β = 0.021, 95% CI [0.004, 0.038], p = .018**

Maya might initially write:

> “Longer interventions cause greater learning gains.”

Her mentor shakes his head.

**Mentor:** “What did your analysis actually estimate?”

**Maya:** “The relationship between intervention duration and effect size across studies.”

**Mentor:** “Exactly.”

A more appropriate interpretation is:

> “Across the included studies, longer intervention duration was associated with larger effect sizes.”

The word **associated** is important.

Meta-regression based on study-level data does not automatically establish causation.

---

# 11. Avoid the Ecological Fallacy

Maya's data are primarily at the **study level**.

Suppose studies with longer interventions tend to report larger effects.

That does not necessarily mean:

> “Individual students who receive an intervention for longer will experience greater improvement.”

The study-level association may reflect other differences between studies.

This is an example of the importance of distinguishing:

> **study-level relationships**

from

> **individual-level relationships.**

---

# 12. Interpret Non-Significant Findings Carefully

Suppose Maya examines learner level.

Her meta-regression produces:

> **β = 0.08, 95% CI [-0.09, 0.25], p = .351**

Maya says:

**Maya:** “So learner level has no effect.”

**Mentor:** “That conclusion is too strong.”

A non-significant moderator analysis does not prove that a relationship does not exist.

A better interpretation is:

> “The analysis did not provide sufficient evidence of an association between learner level and effect size in this set of studies.”

Possible reasons include:

* genuinely little association
* limited statistical power
* few studies
* substantial variation within categories
* measurement differences
* residual heterogeneity

---

# 13. Interpret Sensitivity Analysis

Maya's primary analysis produced:

> **g = 0.64**

Her sensitivity analyses ranged approximately from:

> **g = 0.59 to 0.67**

Maya can therefore say:

> “The pooled estimate remained reasonably similar across the examined sensitivity analyses, suggesting that the overall conclusion was not highly dependent on the specific studies or analytical decisions examined.”

This is more informative than simply saying:

> “The results were robust.”

Maya should specify **what was tested**.

---

# 14. Bring Risk of Bias Into the Interpretation

Risk-of-bias findings are also part of interpretation.

Suppose the lower-risk sensitivity analysis produced:

> **g = 0.67**

while the primary analysis produced:

> **g = 0.64**

Maya might say:

> “The estimated effect remained similar when the analysis was restricted to studies with fewer risk-of-bias concerns.”

But she should not conclude:

> “Therefore, the evidence is completely free of bias.”

Risk-of-bias assessment identifies methodological concerns. It does not prove that the remaining evidence is unbiased.

---

# 15. Consider the Evidence Base, Not Just the Pooled Effect

Maya now remembers something important.

There were:

* **111 eligible studies** in the systematic review
* **22 studies** contributing to the primary meta-analysis
* **89 studies** contributing to the systematic/narrative synthesis but not the primary meta-analysis

Therefore, the pooled effect represents the **22 quantitatively synthesized studies**, not all 111 studies.

This distinction must remain clear.

Maya should not write:

> “Across all 111 studies, the pooled effect was 0.64.”

The pooled effect was calculated from the studies included in the quantitative synthesis.

---

# 16. Why Were 89 Studies Not in the Meta-Analysis?

Maya should also consider why some eligible studies did not contribute to the quantitative synthesis.

For example, some may not have provided suitable quantitative information for the planned analysis.

This affects interpretation.

The systematic review provides a broader evidence base than the meta-analysis.

Therefore:

```text id="w5h7rd"
111 eligible studies
        │
        ├───────────────┐
        ▼               ▼
  22 quantitative      89 systematic/
     synthesis         narrative synthesis
        │
        ▼
 Pooled effect = 0.64
```

The pooled estimate should be interpreted within the evidence available for quantitative synthesis.

---

# 17. Interpret Results in Context

Maya now asks:

**Maya:** “Should I compare my findings with previous reviews?”

**Mentor:** “Yes, but carefully.”

She can compare her findings with earlier evidence to determine whether:

* her overall finding is consistent
* her estimate is larger or smaller
* the populations differ
* the technologies differ
* the outcomes differ
* newer studies may explain differences
* methodological differences may explain different conclusions

A difference between reviews does not automatically mean that one review is correct and the other is not.

The reviews may have answered somewhat different questions.

---

# 18. Explain Possible Reasons for Variation

Maya's results suggest that effects vary across studies.

She can discuss plausible explanations supported by her evidence.

For example:

### Intervention characteristics

Different AI systems may provide different functions.

### Learner characteristics

Students may differ in prior knowledge, educational level, or learning needs.

### Learning context

An AI tool used in a structured classroom may operate differently from one used for independent learning.

### Outcome measurement

Achievement, knowledge, skill, and performance measures may capture different aspects of learning.

### Methodology

Randomized and quasi-experimental studies may produce different estimates because of differences in design.

These explanations should be connected to the actual evidence rather than presented as established causal mechanisms.

---

# 19. Distinguish Evidence From Speculation

Maya writes:

> “Longer interventions produce greater learning gains because students have more opportunities to practice.”

Her mentor asks:

**Mentor:** “Did your meta-regression test that mechanism?”

**Maya:** “No.”

**Mentor:** “Then be careful.”

A better interpretation is:

> “Longer intervention duration was associated with larger effect sizes. One possible explanation is that longer interventions may provide more opportunities for practice, although this mechanism was not directly tested in the meta-analysis.”

This distinction makes the interpretation more scientifically defensible.

---

# 20. Consider Generalizability

Maya also asks:

**Maya:** “Can I say these findings apply to all students?”

**Mentor:** “No. Look at the evidence base.”

Generalizability depends on characteristics such as:

* who participated
* where studies were conducted
* what technologies were used
* what outcomes were measured
* how long interventions lasted
* how studies were designed

If most studies were conducted with university students, Maya should be cautious about generalizing the findings to elementary school students.

If most studies examined short-term interventions, she should be cautious about making claims about long-term learning.

---

# 21. Interpret the Findings Without Overclaiming

Maya now creates three levels of statements.

| Evidence supports                                                | Be cautious with                                                      | Avoid claiming without evidence               |
| ---------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------- |
| AI interventions were associated with improved learning outcomes | AI may be useful across some educational contexts                     | AI works for every student                    |
| Longer intervention duration was associated with larger effects  | Duration may be an important factor                                   | Longer duration causes larger effects         |
| Effects differed across AI functions                             | AI function may contribute to variation                               | One AI function is universally superior       |
| Sensitivity results were similar                                 | Findings appear reasonably stable under tested alternatives           | Findings are universally robust               |
| 22 studies contributed to the meta-analysis                      | Quantitative evidence was available from a subset of eligible studies | All 111 studies supported the pooled estimate |

This is the difference between **evidence-based interpretation** and overgeneralization.

---

# 22. Maya Builds Her Interpretation

Maya now combines the findings.

Her interpretation might look like this:

> The quantitative synthesis suggests that AI-powered learning technologies were associated with improved student learning outcomes across the studies included in the meta-analysis. The pooled effect was positive, with a Hedges' g of 0.64 and a 95% confidence interval of 0.52 to 0.76. However, effect sizes varied across studies, as reflected by moderate heterogeneity. Moderator and meta-regression analyses suggested that characteristics such as AI function and intervention duration were associated with differences in effect sizes. These findings should be interpreted as study-level associations rather than causal effects. Sensitivity analyses produced broadly similar estimates, suggesting that the overall conclusion was reasonably stable under the examined analytical alternatives.

Maya reads it carefully.

**Maya:** “Now I'm not just listing numbers.”

**Mentor:** “Exactly. You're explaining the evidence.”

---

# 23. A Framework for Interpreting Meta-Analysis Findings

Maya creates a simple framework.

```text id="5j0vcz"
1. What did we find?
          ↓
2. How large and precise was the effect?
          ↓
3. How much did effects vary?
          ↓
4. What characteristics were associated
   with variation?
          ↓
5. Are the findings sensitive to
   particular studies or decisions?
          ↓
6. What does the evidence suggest
   for the research question?
          ↓
7. What should we NOT conclude?
          ↓
8. How broadly can the findings
   reasonably be generalized?
```

---

# 24. Interpretation Checklist

Before moving forward, Maya asks herself:

### Overall effect

* What was the pooled effect?
* What was the direction?
* How precise was the estimate?

### Heterogeneity

* How much did effects vary?
* Is there evidence of between-study variation?

### Moderators

* Which characteristics were associated with differences?
* Were these associations prespecified or exploratory?

### Meta-regression

* What predictors were examined?
* Are the relationships study-level associations?

### Sensitivity

* Did the findings remain similar?
* Which analyses were tested?

### Risk of bias

* What methodological concerns were present?
* How did they affect interpretation?

### Evidence base

* How many studies contributed to the meta-analysis?
* How many contributed only to the systematic/narrative synthesis?

### Generalizability

* To whom and to what settings can the findings reasonably apply?

### Causal language

* Does the evidence support an association or a causal conclusion?

---

# 25. Maya Is Ready for the Next Step

Maya closes her statistical output.

She has moved from:

> **Data → Effect sizes → Meta-analysis → Heterogeneity → Moderators → Meta-regression → Sensitivity**

to:

> **Evidence → Interpretation**

But one final question remains.

**Maya:** “Now that I understand the findings, how do I turn all of this into conclusions?”

Her mentor smiles.

**Mentor:** “That's the next step.”

Maya opens a new page.

She writes:

> **Step 21 — Develop Evidence-Based Conclusions**

---

# Key Takeaways

1. Interpretation explains what the findings mean in relation to the research question.
2. Reporting statistical results and interpreting those results are different activities.
3. The pooled effect should be interpreted in context rather than by numerical magnitude alone.
4. Statistical significance does not automatically mean practical importance.
5. Confidence intervals communicate uncertainty around the estimated effect.
6. Heterogeneity indicates variation among study effects but does not by itself explain why effects differ.
7. Moderator and meta-regression findings should generally be interpreted as associations when based on study-level data.
8. A non-significant moderator does not prove that no relationship exists.
9. Sensitivity analyses help evaluate the stability of conclusions.
10. Risk of bias should be considered when interpreting the strength and limitations of the evidence.
11. The pooled estimate applies to the studies included in the quantitative synthesis, not automatically to every eligible study.
12. Interpretation should avoid unsupported causal claims and overgeneralization.
13. Plausible explanations should be distinguished from mechanisms directly tested by the evidence.
14. Conclusions should be proportional to the evidence actually synthesized.

---

# Assessment

## Question 1

What is the main purpose of interpreting meta-analysis findings?

A. To change the statistical results
B. To explain what the findings mean in relation to the research question
C. To increase the number of included studies
D. To calculate new effect sizes

## Question 2

Maya finds Hedges' g = 0.64. What should she do next?

A. Automatically describe it as a very large practical effect
B. Interpret the effect in the context of the outcome, population, intervention, and evidence base
C. Delete studies with smaller effects
D. Treat the effect size as a p-value

## Question 3

What does a confidence interval primarily communicate?

A. The number of studies included
B. The probability that every individual student benefits
C. Uncertainty around the estimated effect
D. The risk-of-bias rating

## Question 4

Maya finds I² = 58%. What does this primarily indicate?

A. Exactly 58% of students benefited from the intervention
B. 58% of the studies were biased
C. A proportion of observed variability is attributed to between-study heterogeneity under the I² framework
D. The intervention caused 58% of the learning improvement

## Question 5

Maya finds that longer interventions are associated with larger effect sizes. Which interpretation is most appropriate?

A. Longer interventions definitely cause larger learning gains
B. Longer intervention duration was associated with larger effect sizes across the included studies
C. Every student benefits more from longer interventions
D. Intervention duration has no relationship with learning

## Question 6

Why should Maya be cautious about interpreting a study-level meta-regression as an individual-level relationship?

A. Study-level associations do not automatically describe relationships among individuals
B. Meta-regression cannot use continuous variables
C. Effect sizes cannot be interpreted
D. Heterogeneity prevents all interpretation

## Question 7

Maya finds a non-significant relationship between learner level and effect size. What should she conclude?

A. Learner level definitely has no influence
B. Learner level causes no difference
C. The analysis did not provide sufficient evidence of an association in the included studies
D. Learner level should be removed from the review

## Question 8

Why should statistical significance and practical importance be distinguished?

A. They address different questions about evidence and meaningfulness
B. Statistical significance is always more important
C. Practical importance is calculated from sample size only
D. They are identical concepts

## Question 9

There are 111 eligible studies, but only 22 contribute to the primary meta-analysis. Which statement is appropriate?

A. The pooled effect represents all 111 studies
B. The pooled effect represents the 22 studies included in the quantitative synthesis
C. The other 89 studies should be deleted
D. The systematic review contains only 22 studies

## Question 10

What is the best interpretation of similar sensitivity-analysis results?

A. The findings are universally true
B. The findings appear reasonably stable under the specific sensitivity analyses examined
C. The primary analysis should be discarded
D. Sensitivity analysis is unnecessary

## Question 11

Maya observes that tutoring has a larger subgroup effect than assessment. What should she avoid concluding automatically?

A. That the subgroup estimates differ
B. That the difference may be associated with AI function
C. That tutoring necessarily causes greater learning gains
D. That the subgroup findings should be interpreted in context

## Question 12

Why should Maya consider risk of bias when interpreting her findings?

A. Risk of bias can provide information about methodological concerns that affect confidence in the evidence
B. Risk of bias determines the publication year
C. Risk of bias automatically determines the effect size
D. Risk of bias replaces the meta-analysis

## Question 13

Which statement best distinguishes reporting from interpretation?

A. Reporting describes findings; interpretation explains their meaning and implications
B. Reporting and interpretation are exactly the same
C. Reporting is optional when interpretation is completed
D. Interpretation only involves calculating p-values

## Question 14

Maya proposes that longer interventions produce larger effects because students receive more opportunities to practice. If her analysis did not test this mechanism, how should she present it?

A. As a proven causal mechanism
B. As one possible explanation rather than an established finding
C. As a statistical result
D. As a confirmed moderator

## Question 15

Why should Maya consider generalizability?

A. Findings from a particular evidence base may not automatically apply to populations, settings, technologies, or durations that were not adequately represented
B. Generalizability determines the p-value
C. Generalizability replaces risk-of-bias assessment
D. Generalizability determines whether a study is a duplicate

---

# Answer Key

| Question | Answer |
| -------- | ------ |
| 1        | **B**  |
| 2        | **B**  |
| 3        | **C**  |
| 4        | **C**  |
| 5        | **B**  |
| 6        | **A**  |
| 7        | **C**  |
| 8        | **A**  |
| 9        | **B**  |
| 10       | **B**  |
| 11       | **C**  |
| 12       | **A**  |
| 13       | **A**  |
| 14       | **B**  |
| 15       | **A**  |


## 🚀 Maya's Journey Continues

Maya has now **completed the interpreting the Findings**.
The next challenge is to Develop Evidence-Based Conclusions

She is now ready to move to:

### Next Step

### **[Step 21 — Develop Evidence-Based Conclusions](https://github.com/adnan-mayof/Develop-Evidence-Based-Conclusions/blob/main/README.md)**
