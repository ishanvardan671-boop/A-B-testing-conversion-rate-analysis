# A/B Testing & Statistical Analysis – E-commerce Conversion Rate

## 1. Project Overview

This project is based on A/B Testing, a statistical method used to compare two versions of a webpage, product, or business strategy to find out which one performs better.

In this project, I studied an e-commerce business case where the company wants to improve its purchase conversion rate by changing the design of its checkout page.

The project explains how an A/B test is planned, how users are divided into two groups, how conversion rates are compared, and how statistical results are used to make business decisions.

**Project Domain:** Data Analytics & Business Intelligence  
**Project Type:** Statistical Analysis & Business Case Study  
**Focus Area:** A/B Testing, Hypothesis Testing, Conversion Rate Analysis

---

## 2. Business Problem

An e-commerce company wants to improve the number of customers who successfully complete their purchases.

The company has an existing checkout page and is considering introducing a new design.

Before making the new design available to all customers, the company wants to test whether it actually improves the purchase conversion rate.

**Main Business Question:**

Does the new checkout page increase the purchase conversion rate compared to the existing checkout page?

---

## 3. Understanding A/B Testing

A/B Testing is an experimental method in which two versions of something are compared to understand which version performs better.

In this project, two groups are created:

- **Group A – Control Group:** Users see the existing checkout page.
- **Group B – Treatment Group:** Users see the new checkout page.

Both groups are compared using the same business metric: Purchase Conversion Rate.

The purpose is to identify whether the observed improvement is meaningful or could have happened by chance.

---

## 4. Project Workflow – Step by Step

### Step 1: Define the Objective

The first step was to clearly define the purpose of the experiment.

**Objective:** To check whether the new checkout page can increase the purchase conversion rate.

The primary metric selected for the experiment was Purchase Conversion Rate.

**Purchase Conversion Rate Formula:**

Conversion Rate = (Number of Purchases / Total Users) × 100

### Step 2: Define the Hypotheses

Before starting the experiment, two hypotheses were defined.

- **Null Hypothesis (H0):** There is no difference in the purchase conversion rates of Group A and Group B.
- **Alternative Hypothesis (H1):** There is a difference in the purchase conversion rates of Group A and Group B.

Hypothesis testing helps determine whether the observed result is statistically significant.

### Step 3: Set Experiment Parameters

Some important parameters were defined before running the experiment.

| Parameter | Value |
|---|---:|
| Baseline Conversion Rate | 5% |
| Minimum Detectable Effect (MDE) | 1 percentage point |
| Target Conversion Rate | 6% |
| Significance Level (Alpha) | 5% |
| Statistical Power | 80% |
| Traffic Allocation | 50% – 50% |
| Planned Sample Size | 8,160 users per group |

**What do these terms mean?**

- **Baseline Conversion Rate:** The existing purchase conversion rate, which is 5%.
- **MDE:** The minimum improvement the experiment is designed to detect. Here, it is an increase from 5% to 6%.
- **Significance Level:** A 5% significance level is used to control the risk of a Type I error.
- **Statistical Power:** An 80% power means the experiment has an 80% chance of detecting the specified effect if that effect truly exists.
- **Sample Size:** The minimum number of users required in each group to conduct the experiment with the selected parameters.

### Step 4: Execute the Experiment

Users were divided equally into two groups.

- Group A received the existing checkout page.
- Group B received the new checkout page.

Both groups were observed under the same experimental conditions.

The planned minimum sample size was 8,160 users per group. The illustrative experiment results used in this analysis are based on 10,000 users per group.

### Step 5: Calculate Conversion Rates

After collecting the experiment results, the purchase conversion rate was calculated for both groups.

| Metric | Group A | Group B |
|---|---:|---:|
| Total Users | 10,000 | 10,000 |
| Purchases | 500 | 600 |
| Conversion Rate | 5% | 6% |

**Group A:**

(500 / 10,000) × 100 = 5%

**Group B:**

(600 / 10,000) × 100 = 6%

The new checkout page achieved a higher purchase conversion rate.

### Step 6: Calculate the Lift

Lift measures the improvement in performance between the two groups.

**Absolute Lift:**

6% − 5% = 1 percentage point

This means the new checkout page increased the conversion rate by 1 percentage point.

**Relative Lift:**

((6% − 5%) / 5%) × 100 = 20%

This means Group B achieved a 20% relative improvement compared to Group A.

### Step 7: Perform Statistical Testing

A Two-Proportion Z-Test was used to compare the conversion rates of the two groups.

This test helps determine whether the difference between the two conversion rates is statistically significant.

**Experiment Results:**

- Z-score: Approximately 3.1
- P-value: Approximately 0.002
- Significance Level: 0.05

**Interpretation:**

The p-value (0.002) is lower than the significance level (0.05).

Therefore, the result is statistically significant, and the null hypothesis is rejected.

This provides evidence that the difference in conversion rates is unlikely to be due to random chance alone.

### Step 8: Calculate the 95% Confidence Interval

A 95% confidence interval helps estimate a reasonable range for
