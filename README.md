# Statistics-Analysis-of-Boston-Housing-Data

## Project Scenario: 
You are a Data Scientist with a housing agency in Boston MA, you have been given access to a previous dataset on housing prices derived from the U.S. Census Service to present insights to higher management. Based on your experience in Statistics, what information can you provide them to help with making an informed decision? Upper management will like to get some insight into the following.

## Questions:
Is there a significant difference in the median value of houses bounded by the Charles river or not?
Is there a difference in median values of houses of each proportion of owner-occupied units built before 1940?
Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town?
What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?

## Steps:

Part 1 : Import Libraries

Part 2 : Exploratory Data Analysis

Part 3 : Data Visualization

Part 4 : Generate Descriptive Statistics and Visualizations

Part 5 : Use the appropriate tests to answer the questions provided
 - Is there a significant difference in median value of houses bounded by the Charles river or not? (T-test for independent samples) ?
 - Is there a difference in Median values of houses (MEDV) for each proportion of owner occupied units built prior to 1940 (AGE)? (ANOVA) ?
 - Can we conclude that there is no relationship between Nitric oxide concentrations and proportion of non-retail business acres per town? (Pearson Correlation) ?
 - What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner occupied homes? (Regression analysis) ?

## Insights:
 - Since p value is nore than alpha value of 0.05, both average MEDV are the same and there is no statistical significance
 - Since p-value more than alpha value of 0.05, so the three population Median values of houses (MEDV) for each proportion of owner occupied units built prior to 1940 (AGE) are same.
 - Since the p-value (Sig. (2-tailed) < 0.05, we reject the Null hypothesis and conclude that there exists a relationship between Nitric Oxide and non-retail business acres per town.
 - The square root of R-squared is 0.25, which implies weak correlation between both features. So there is NO impact of an additional weighted distance to the five Boston employment centres on the median value of owner occupied homes
