slidenumbers: true
footer: ![inline 10%](images/ga.png) J. Pounders, DSI-EAST-1

# ![inline 30%](images/ga.png)  Hypothesis Testing

### Justin Pounders

---

# Objectives

- Define null and alternative hypotheses
- Define and calculate the t-statistic, p-value
- Describe how to apply a t-test

---

# Hypothesis Testing

**Example**: Say we are testing the efficacy of a new blood pressure drug.

- 50 people receive placebo (control group)
- 50 people receive treatment (experimental group)
- These 100 people are a *random sample* from the *population*

---

# Hypothesis Testing

**Example**: Say we are testing the efficacy of a new blood pressure drug.

- *Null hypothesis*: drug has no effect
- *Alternative hypothesis*: drug has an effect

---

# Hypothesis Testing

**Example**: Say we are testing the efficacy of a new blood pressure drug.

- *Null hypothesis*: drug has no effect
- *Alternative hypothesis*: drug has an effect

> **Question**: What should be considered a *significant* (non-random) effect?

---

# t-Test

*t-statistics*: a measure of the **degree by which our groups differ** (standardized by the variance of measurement)

*p-value*: a metric that indicates the probability that our measured difference **was due to random change** in the sampling of subjects

---

> A *p-value* is the probability of getting our sample data, given whatever measurement we actually observed, assuming the null hypothesis is true.

---

# Drug testing

**Data**: BPs of participants in two groups: $$x_i$$
**Statistic**: mean BP of each group: $$\bar{x}_E$$ and $$\bar{x}_C$$

- Null hypothesis, **H0**: $$\bar{x}_E - \bar{x}_C = 0$$
- Alternative hypothesis, **H1**: $$| \bar{x}_E - \bar{x}_C | > 0$$

$$p\text{-value} \leftarrow P(\text{data} \;\;\; | \;\;\; \bar{x}_E - \bar{x}_C = 0 )$$

---

# Why is this called a *t-test*?

In practice we use *t-distribution* rather than a **normal distribution**.

---

# [fit] Python Time

`go to notebook frequentist-hypothesis-test-ttests-pvalues.ipynb`

