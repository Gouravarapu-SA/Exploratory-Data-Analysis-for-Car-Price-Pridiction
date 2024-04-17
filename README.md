# Data Analysis on Car Sales

This document contains a data analysis on car sales, exploring the impact of various characteristics on car prices. The analysis aims to identify the most important variables for predicting car prices and provide recommendations based on the findings.

## Summary

The analysis begins by importing necessary libraries such as Pandas, NumPy, and Seaborn for data manipulation and visualization. The car dataset is then loaded into a Pandas dataframe, and data types are checked to determine appropriate visualization methods.

Scatterplots and regression lines are used to visualize the relationship between continuous numerical variables like engine size, highway miles per gallon (MPG), and price. Boxplots are employed for categorical variables like body style.

Statistical analysis is performed using methods like `describe()`, `value_counts()`, and `groupby()` to understand the distribution of values. Correlations are calculated between potential predictor variables (e.g., wheelbase, horsepower, length) and the target variable (price). Additionally, Analysis of Variance (ANOVA) is used to test if there are significant differences between the group means of the "drive-wheels" variable.

## Approach

The approach followed in the document involves the following steps:

1. Importing libraries and loading data into a Pandas dataframe.
2. Visualizing individual features using scatterplots, regression lines, and boxplots.
3. Performing statistical analysis, such as value counts, groupby, and aggregation, to understand the distributions of variables.
4. Finding correlations between potential predictor variables and the target variable (price) using Pearson correlation and p-values.
5. Utilizing ANOVA to test if the differences between group means of the "drive-wheels" variable are statistically significant.
6. Evaluating the results to determine which variables are most important for predicting car prices.

## Solution

Based on the visualizations, statistical analysis, correlations, and ANOVA tests, the variables most important for predicting car prices are:

### Continuous Numerical Variables:
- Length
- Width
- Curb-weight
- Engine-size
- Horsepower
- City-mpg
- Highway-mpg
- Wheelbase
- Bore
- Drive-wheels

The numerical variables like engine size, horsepower, and highway MPG showed strong correlations with the target variable (price). Additionally, the ANOVA results indicated significant differences between the mean prices of different "drive-wheels" categories.

### Categorical Variable:
- Drive-wheels

The variables related to engine performance, fuel efficiency, dimensions, and the drive-wheel configuration seem to have the most impact on car price prediction.

The recommended solution is to feed these important variables into machine learning models to achieve the best performance in predicting car prices.
