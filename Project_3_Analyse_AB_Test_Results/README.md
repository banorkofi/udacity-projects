# Analyse A/B Test Results

## Introduction
For this project I was working on understanding the results of an A/B test run by an e-commerce website. 

An e-commerce site is trying to increase the number of users who eventually pay for the company’s product. They have developed a new web page to help them increase users who pay. My aim is to help them discover if this new web page creates more conversions than their old web page. This will help them identify if they should implement the new page, keep the old one or perhaps run the experiment longer.

## About the project
There are 3 main parts:

Part I – Probability
- I acquainted myself with the dataset and calculated simple probabilities such as how many users converted etc.

Part II - A/B Test
- I created a statistical model to test the dataset with.

Part III – Regression
- I created three logistic regressions and interpreted them.

I found that:
- None of the variables were statistically significant. Therefore, there is weak evidence against the null hypothesis and we fail to reject it.
- If the user was based in Canada, they were approximately 0.98x more likely to convert than if they were based in UK or US, holding all other variables constant.
- If the page was new and the user was in UK they are 1.08x more likely to convert than if it was a Canadian seeing a new page.
- If the page was new and the user was in US they are 1.05x more likely to convert than if it was a Canadian seeing a new page.
- This pattern above suggests that UK users were more receptive to change.

