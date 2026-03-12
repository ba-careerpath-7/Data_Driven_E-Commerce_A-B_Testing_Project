# Data Driven E-Commerce A/B Testing Project
Customer Transaction A/B Testing Project from the resume.



---

## Project well-received by Kaggle Grandmaster and Expert contributors

**Last verified: 12/16/25**

Kaggle Link:
https://www.kaggle.com/code/brettean7/data-driven-e-commerce-a-b-testing-project

This project was acknowledged by top Kaggle contributors for clarity and methodological rigor.

---

## 1. ⭐ What is this _____ Project about?


---

## 2. 💵 The Business Problem: ______________


---
## 3. 💡 Key Insights and Final Conclusions



### 📊 Marketing Analytics & Hypothesis Testing Results (for this specific anonymous company data set):

| Test # | Statistical Test | Finding | Evidence ($p$-value or CI) | Marketing Suggestion |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Single Mean Test (Income) | Rejected Null | $p \approx 0$ | **Caution:** Potential sampling bias identified; $p$-value may not be reliable. |
| **2** | Difference in Means (Gender) | Failed to Reject | $p = 0.35$ | **Gender-Neutral:** Not enough evidence that male and female genders have significant income differences. Avoid gender-specific targeting. |
| **3** | Difference in Proportions (Churn) | Failed to Reject | $p = 0.80$ | **Global Consistency:** Churn rates are stable across USA/International markets. |
| **4** | Difference in Means (Age/NLP) | **Rejected Null** | $p = 0.043$ | **Target Older Demographics:** Significant increase in emotional sentiment scores for older users. |
| **5** | One Way ANOVA (Geography) | **Rejected Null** | $p \approx 0$ | **Tiered Expansion:** Prioritize high-performance markets: USA, UK, and Germany. |
| **6** | Bootstrap Resampling (Gender) | Failed to Reject (Confirmed Test 2) | CI contains 0 | **Validation:** Resampling confirms gender is not a statistically significant factor for income. |


### 📈 Interesting plots for some of the Statistical Tests above:

[i will post some pie charts, box plots, and so on]

### 💡 Business Value Delivered
* **Budget Optimization:** Prevented wasteful gender-based ad spend since there was not enough evidence that genders show significant  income differences. 
* **Strategic Growth:** Identified the "Older Demographic" as the highest-value emotional segment for targeted loyalty programs.
* **Risk Mitigation:** Flagged possible unreliable sampling for this data set (The population USA income mean is still reliable), preventing flawed financial forecasting.



---
## 4. 📔 The Methodology of what I did: 

### Firstly, I did exploratory data analysis.

Plots of predictor variables against response variables were made.
Additionally, predictor variables against other predictor variables were made.

### Secondly, ________________________________ were created.
  
* **Stack:** Python (NumPy, pandas, matplotlib, seaborn, scikit-learn, XGBoost, plotly, SciPy)

### Thirdly, I tried to gather insights about _____________________.

For a refresher, check them out at [point 3!](#3--key-insights-and-final-conclusions) 

---

## 5. 💻 Technical Log 

### Core Methodologies

Inferential Statistics: A/B Testing, One-Way ANOVA, and Proportion Testing.

NLP Integration: Sentiment Analysis of customer feedback to quantify emotional engagement.

Computational Stats: Bootstrap Resampling to validate parametric test assumptions.

Bias Mitigation: Identifying and documenting sampling bias to prevent flawed business logic.

---




