# Data Driven E-Commerce A/B Testing Project
Customer Transaction A/B Testing Project from the resume.



---

## Project well-received by Kaggle Grandmaster and Expert contributors

**Last verified: 12/16/25**

Kaggle Link:
https://www.kaggle.com/code/brettean7/data-driven-e-commerce-a-b-testing-project

This project was acknowledged by top Kaggle contributors for clarity and methodological rigor.

---




**⭐Overview:**
Analyzed anonymous e-commerce user data to identify key predictors of income and churn. Conducted rigorous A/B testing on numerical and NLP features to determine their impact on user behavior.
Applied A/B testing, ANOVA, and bootstrap methods for robust evaluation.


**🎨Results:**

	Statistical Test	Results	Evidence	Marketing Suggestion
1	Single Mean Test on annual income for USA customers:	Rejected the null that the average income is 67080. BUT due to sampling bias, this conclusion is not reliable.	The p-value is approximately 0. But we can not fully trust this p-value due to possible sampling bias.	No suggestion. Sampling bias might be present, so any suggestion may not be reliable.
2	Difference in Means A/B Test on annual income for Males and Females:	Failed to reject the null. Concluded that we do not have enough evidence that Males and Females have different average annual incomes.	The p-value = 0.35. This is greater than alpha = 0.05, so we fail to reject the null.	A company should NOT focus on targeting a specific gender to maximize revenue.
3	Difference in Proportions A/B Test on churned customers for USA and other countries:	Failed to reject the null. Concluded that we do not have enough evidence that the churn proportions of the USA and other countries are different.	The p-value = 0.80. This is greater than alpha = 0.05, so we fail to reject the null.	USA companies should NOT focus on targeting a non-USA countries to avoid high churn rates.
4	Difference in Means A/B Test on feedback text for young and elder people (Used NLP):	Rejected the null. Concluded we DO have enough evidence that young and elder people have different average emotional scores.	The p-value = 0.043. This is LESS than alpha = 0.05, so we reject the null.	A company should consider focus on selling products to older age groups!
5	One Way ANOVA Test on the average number of purchases made for each of the 5 countries:	Rejected the null. Concluded that we DO have enough evidence that at LEAST 1 country has a different average number of purchases compared to other countries.	The p-value is approximately 0. This is LESS than alpha = 0.05, so we reject the null.	The Marketing Team COULD prioritize selling products on the USA, UK, and Germany.
6	Difference in Means A/B Test on annual income for Males and Females (Bootstrap Resampling to revisit Statistical Test 2):	Failed to reject the null. Even Bootstrapped data had the same conclusion as the original A/B Test on annual income for Males and Females.	The bootstrap Confidence Interval contains the null mean value of 0. Therefore, we fail to reject the null.	For statistical test 2, we have more insights that a company should NOT focus on targeting a specific gender to maximize revenue.


---

Technologies: Python, Pandas, NumPy, SciPy, Matplotlib, Seaborn




