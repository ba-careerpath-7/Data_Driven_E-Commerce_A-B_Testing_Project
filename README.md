# Customer_Transaction_A-B_Testing_Project
Customer Transaction A/B Testing Project from the resume.


#⭐ SECTION A: Introduction

Hello guys!

Welcome to the A/B Testing Project!


Many people who are into experiments such as marketing data may have already heard the phrase "A/B Testing". This may sound like a complex topic, but I am here to tell you that is NOT a complex topic!

If you are familiar with statistics, A/B Testing is just a two sample statistical test in disguise, such as a two sample t-test. That's it!

So this project will go over the basics of statistical inference, A/B testing, and even applications on how to implement Natural Language Processing (NLP) and bootstrapping. We will even extend A/B testing to A/B/C/D/E testing using Analysis of Variance (ANOVA).



---






### Motivation for doing statistical tests such as A/B tests!

Lets say that we conduct a A/B test on the weights of NBA centers vs NBA point guards. We find that we have evidence that the weights of centers and point guards are different.

We can use that decision to make basketball strategies where a center who tends to be heavier should prioritize being in the paint, while a point guard should do plays that require fast movement since point guards tend to weigh less.

Statistical tests like t-tests, A/B tests, and ANOVA are a powerful tools for data-driven decision making. This project shows some reasons why they are widely used in data science today.

---


----

### What questions are we examining?

This project will use customer transaction data. This data contains 10,000 customers with variables such as age, gender, country, annual income, number of purchases, feedback ratings, and churn rates.

* Variables such as age, gender, and country will be our groups that we compare. Notice that these variables are discrete numbers or categorical types.

* Variables such as annual income, number of purchases, and churn rates are continuous numbers that can be decimals. We will measure how groups differ from each other using these continuous variables. (Notice that feedback ratings are words, not numbers. In SECTION F, we will go over how to use NLP to get numerical scores out of those sentences.)


**We will answer 6 questions in this project:**

1. Single Mean Test on annual income for USA customers:

Does this data set show a statistically different average from the USA average annual income?

2. Difference in Means A/B Test on annual income for Males and Females:

Do we have evidence that males and females have different average annual incomes?


3. Difference in Proportions A/B Test on churned customers for USA and other countries:

Do we have evidence that the proportion of USA churned customers is different from the proportion of churned customers from other countries?

(Churned definition: To stop using a product or service.)


4. Difference in Means A/B Test on feedback text for young and elder people (Using NLP):

Can we find evidence that young and elder people have different average emotional scores when leaving feedback for the products they buy?

5. One Way ANOVA Test on the average number of purchases made for each of the 5 countries:

Is there evidence that at LEAST one country has a different average number of purchases when analyzing 5 different countries?

6. Difference in Means A/B Test on annual income for Males and Females (Bootstrap Resampling to revisit Question 2):

Can we give additional evidence of Question 2's result? We will use a process called bootstrapping that mimics real data, even if our sample size is small.

Before answering these questions, lets jump into cleaning and exploring the data!!!

---
