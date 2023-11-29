# Exploratory-Data-Analysis-for-Car-Price-Pridiction
contains a data analysis on car sales, exploring the impact of various characteristics on car prices and recommending important variables for price prediction.
Data Analysis on Car Sales
Summary
The document analyzes a car dataset to determine which characteristics impact the car price. It first imports libraries like Pandas, Numpy and Seaborn for data manipulation and visualization. The data is loaded into a dataframe and analyzed
The data types are checked to find the right visualization methods. Scatterplots and regression lines are used to visualize continuous numerical variables like engine-size and highway-mpg versus price. Boxplots are used for categorical variables like body-style. Statistical analysis is done using describe(), value_counts() and groupby() to understand the distribution of values. Correlations are calculated between variables like wheel-base, horsepower, length and price. ANOVA is used to test if there are significant differences between group means of drive-wheels.
Approach
The approach followed in the document involves
Importing libraries and loading data into dataframe
Visualizing individual features using scatterplots, regression lines and boxplots.
Doing statistical analysis like value counts, groupby and aggregation to understand distributions.
Finding correlations between potential predictor variables and price using Pearson correlation and p-values.
Using ANOVA to test if differences between group means of drive-wheels are statistically significant.
Evaluating results to determine which variables are most important for predicting price
Solution
Based on the visualizations, statistical analysis, correlations and ANOVA tests, the variables most important for predicting car price are:
Continuous numerical variables:
Length, Width, Curb-weight, Engine-size, Horsepower, City-mpg, Highway-mpg, Wheel-base, Bore
Drive-wheels
The numerical variables like engine-size, horsepower, highway-mpg showed strong correlations with price. ANOVA results showed significant differences between the mean prices of different drive-wheel categories.
Categorical variable:
These variables relating to engine performance, fuel efficiency, dimensions and drive-wheel configuration seem to have the most impact on car price prediction. The solution is to feed these important variables into machine learning models to get the best performance in predicting car prices.
