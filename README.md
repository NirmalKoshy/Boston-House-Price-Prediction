# Boston-House-Price-Prediction
The analysis in this Boston housing data notebook focused on understanding the relationships between various factors and the median value of homes (MEDV) in Boston, utilizing data and R-based tools. Here's what we did throughout the project:

**1) Data Loading and Cleaning:**

We loaded the dataset, cleaned it by removing some irrelevant columns, and checked for missing values, ensuring the data was ready for analysis. No missing values were found.

**2) Exploratory Data Analysis (EDA):**

We explored the data by calculating correlations between different variables. For example, we found that factors like crime rate (CRIM), number of rooms (RM), and percentage of lower-status population (LSTAT) had strong correlations with the median house price.

**3) Visualization:**

We created scatter plots to visualize relationships. For instance, a plot between the crime rate (CRIM) and the median value (MEDV) highlighted how increasing crime rates tend to lower property values.

**4) ANOVA Analysis:**

We conducted an ANOVA test to see how two factors, CHAS (proximity to the Charles River) and RAD (access to highways), impacted housing prices. We found that both had statistically significant effects on housing prices, with the highway access variable having a particularly strong influence.

**5) Model Preparation:**

We used the plotly library to generate interactive graphs, providing deeper insights into how variables like crime rate and house prices interacted visually.
