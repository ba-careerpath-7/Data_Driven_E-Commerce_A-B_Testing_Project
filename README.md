# Data Driven E-Commerce A/B Testing Project
Customer Transaction A/B Testing Project from the resume.



---

## Project well-received by Kaggle Grandmaster and Expert contributors

**Last verified: 12/16/25**

Kaggle Link:
https://www.kaggle.com/code/brettean7/data-driven-e-commerce-a-b-testing-project

This project was acknowledged by top Kaggle contributors for clarity and methodological rigor.

---

## 1. ⭐ What is this E-Commerce A/B Testing Project about?

This project will use anonymous customer transaction data. This data contains 10,000 customers with variables such as age, gender, country, annual income, number of purchases, feedback ratings, and churn rates.

* Variables such as age, gender, and country will be our groups that we compare. Notice that these variables are discrete numbers or categorical types.

* Variables such as annual income, number of purchases, and churn rates are continuous numbers that can be decimals. We will measure how groups differ from each other using these continuous variables. Additionally, notice that feedback ratings are words, not numbers. In this project, I will go over how to use NLP to get numerical scores out of those sentences!








---

## 2. 💵 The Business Problem: 6 Questions of Demographic Characteristics

**We will answer 6 questions in this project:**

* Question 1. Single Mean Test on annual income for USA customers:

Does this data set show a statistically different average from the USA average annual income?

* Question 2. Difference in Means A/B Test on annual income for Males and Females:

Do we have evidence that males and females have different average annual incomes?


* Question 3. Difference in Proportions A/B Test on churned customers for USA and other countries:

Do we have evidence that the proportion of USA churned customers is different from the proportion of churned customers from other countries?

(Churned definition: To stop using a product or service.)


* Question 4. Difference in Means A/B Test on feedback text for young and elder people (Using NLP):

Can we find evidence that young and elder people have different average emotional scores when leaving feedback for the products they buy?

* Question 5. One Way ANOVA Test on the average number of purchases made for each of the 5 countries:

Is there evidence that at LEAST one country has a different average number of purchases when analyzing 5 different countries?

* Question 6. Difference in Means A/B Test on annual income for Males and Females (Bootstrap Resampling to revisit Question 2):

Can we give additional evidence of Question 2's result? We will use a process called bootstrapping that mimics real data, even if our sample size is small. 




---
## 3. 💡 Key Insights and Final Conclusions



### 📊 Marketing Analytics & Hypothesis Testing Results (for this specific anonymous company data set):

| Test # | Statistical Test | Finding | Evidence ($p$-value or CI) | Marketing Suggestion |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Single Mean Test (Income) | Rejected Null (But observations may not represent all of the U.S.) | $p \approx 0$ | **Caution:** Potential sampling bias identified; $p$-value may not be reliable. |
| **2** | Difference in Means (Gender) | Failed to Reject | $p = 0.35$ | **Gender-Neutral:** Not enough evidence that male and female genders have significant income differences. Avoid gender-specific targeting. |
| **3** | Difference in Proportions (Churn) | Failed to Reject | $p = 0.80$ | **Global Consistency:** Churn rates are stable across USA/International markets. |
| **4** | Difference in Means (Age/NLP) | **Rejected Null** | $p = 0.043$ | **Target Older Demographics:** Significant increase in emotional sentiment scores for older users. |
| **5** | One Way ANOVA (Geography) | **Rejected Null** | $p \approx 0$ | **Tiered Expansion:** Prioritize high-performance markets: USA, UK, and Germany. |
| **6** | Bootstrap Resampling (Gender) | Failed to Reject (Confirmed Test 2's findings) | CI contains 0 | **Validation:** Resampling confirms gender is not a statistically significant factor for income. |


### 📈 Interesting plots for some of the Statistical Tests above:




**Test 5: Box Plot of 5 Countries' Purchase Numbers**

<img width="999" height="710" alt="github_AB_1_EDITED" src="https://github.com/user-attachments/assets/7cc60b47-66f2-44b5-af8d-27ba549947c8" />

Remember, the middle lines in a box plot represent the median (the 50th percentile). It is not the mean (average)!

In this company data, the countries of Germany, UK, and the USA appear to have higher medians and overall distributions than India and Brazil.

**Test 6: Histogram of Bootstrap Statistics and Bootstrap Confidence Interval (CI)**

<img width="1247" height="729" alt="github_AB_2" src="https://github.com/user-attachments/assets/62908525-a39e-45a2-a39e-12cd4a14260b" />

This bootstrap CI is based on the hypothesis test of gender annual income means:

$$H_0: \mu_{Female} - \mu_{Male} = 0$$
$$H_a: \mu_{Female} - \mu_{Male} \ne 0$$

The value of 0 is inside this bootstrap CI!  Therefore, we fail to reject the null hypothesis. We do not have enough evidence that male and females genders have significantly different incomes. We need more data to conclude that different genders earn different amount of money.


### 💡 Business Value Delivered
* **Budget Optimization:** Prevented wasteful gender-based ad spend since there was not enough evidence that genders show significant  income differences. 
* **Strategic Growth:** Identified the "Older Demographic" as the highest-value emotional segment for targeted loyalty programs.
* **Risk Mitigation:** Flagged possible unreliable sampling for this data set (The population USA income mean is still reliable), preventing flawed financial forecasting.



---
## 4. 📔 The Methodology of what I did: 

### Firstly, I did exploratory data analysis.

Plots of predictor variables against response variables were made.
Additionally, predictor variables against other predictor variables were made.

### Secondly, Statistical Tests were created.

Here is a overview of the types of statistical tests used:

* Inferential Statistics: A/B Testing, One-Way ANOVA, and Proportion Testing.

* NLP Integration: Sentiment Analysis of customer feedback to quantify emotional engagement.

* Computational Stats: Bootstrap Resampling to validate parametric test assumptions.

* **Stack:** Python (NumPy, pandas, matplotlib, seaborn, scikit-learn, XGBoost, plotly, SciPy)

### Thirdly, I tried to gather insights about what marketing strategies to implement.

For a refresher, check out the table and some points at [point 3!](#3--key-insights-and-final-conclusions) 

---





