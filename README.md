Analysis of a DataFrame of Argentine real estate data from 2003 to predict the Price (USD) / m ^ 2 of the property.

In the first part, regular expressions are used to fill in missing values ​​and then outliers are removed.

In the second part, Scikit-Learn linear regression models with and without regularization are used: (LassoCV, RidgeCV, ElasticNet, LinearRegression) to predict the Price (USD) / m ^ 2 of the property.

Statistical information is plotted using Seaborn, Matplotlib, and YellowBrick.
