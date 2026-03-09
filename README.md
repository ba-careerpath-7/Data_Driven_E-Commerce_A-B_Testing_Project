# Data Driven E-Commerce A/B Testing Project
Customer Transaction A/B Testing Project from the resume.



---

## Project well-received by Kaggle Grandmaster and Expert contributors

**Last verified: 12/16/25**

Kaggle Link:
https://www.kaggle.com/code/brettean7/data-driven-e-commerce-a-b-testing-project

This project was acknowledged by top Kaggle contributors for clarity and methodological rigor.

---


### 📊 Marketing Analytics & Hypothesis Testing: Multi-National Consumer Insights

* Project Overview:

This project applies rigorous statistical inference and A/B testing to a multi-national consumer dataset. The goal was to move beyond surface-level metrics to determine which demographic and geographic factors significantly impact revenue and customer retention.

---
### Core Methodologies

Inferential Statistics: A/B Testing, One-Way ANOVA, and Proportion Testing.

NLP Integration: Sentiment Analysis of customer feedback to quantify emotional engagement.

Computational Stats: Bootstrap Resampling to validate parametric test assumptions.

Bias Mitigation: Identifying and documenting sampling bias to prevent flawed business logic.

---

## 📊 Marketing Analytics & Hypothesis Testing Results

| Test # | Statistical Test | Finding | Evidence ($p$-value or CI) | Marketing Suggestion |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Single Mean Test (Income) | Rejected Null | $p \approx 0$ | **Caution:** Potential sampling bias identified; $p$-value may not be reliable. |
| **2** | Difference in Means (Gender) | Failed to Reject | $p = 0.35$ | **Gender-Neutral:** Not enough evidence that gender drives income variance. Avoid gender-specific targeting. |
| **3** | Difference in Proportions (Churn) | Failed to Reject | $p = 0.80$ | **Global Consistency:** Churn rates are stable across USA/International markets. |
| **4** | Difference in Means (Age/NLP) | **Rejected Null** | $p = 0.043$ | **Target Older Demographics:** Significant increase in emotional sentiment scores for older users. |
| **5** | One Way ANOVA (Geography) | **Rejected Null** | $p \approx 0$ | **Tiered Expansion:** Prioritize high-performance markets: USA, UK, and Germany. |
| **6** | Bootstrap Resampling (Gender) | Failed to Reject (Confirmed Test 2) | CI contains 0 | **Validation:** Resampling confirms gender is not a statistically significant factor for income. |






