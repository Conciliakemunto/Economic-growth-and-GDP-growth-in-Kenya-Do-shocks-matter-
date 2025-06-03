
Economic Growth and Foreign Aid in Kenya: Do Shocks Matter?
What This Project Is About
This project dives into how Kenya’s economy has grown over the last 60 years and whether foreign aid has helped or hurt that growth—especially during tough times marked by economic shocks. Using data from the World Bank, I explore if foreign aid really supports Kenya’s development or if its impact changes when the country faces crises.

Data Source
•	Data from the World Bank Development Indicators
•	Covers the years 1963 through 2023
•	Key factors studied:
How fast the economy grows each year (GDP Growth Rate)
Amount of foreign aid Kenya received (in US dollars)
Investment levels in the economy (% of GDP)
Inflation rates (% increase in consumer prices)
Specific years flagged as “shock” years, marking economic or political crises

Cleaning and Getting the Data Ready
Before analysis, I cleaned the data carefully:
•	Standardized year information so everything lines up correctly
•	Renamed columns to make them easy to understand
•	Converted all numbers into the right formats and filled in missing values thoughtfully
•	Created a new column to flag years with shocks
•	Built an interaction term to see how foreign aid behaves during shock years

The Model and What It Shows
I ran two main regression models to analyze the relationships between economic growth and the other variables:
Ordinary Least Squares (OLS) Regression
•	This model examines how GDP growth depends on Foreign Aid, Investment, Inflation, and the interaction between Foreign Aid and Shocks.
•	Key findings:
Investment positively impacts economic growth — meaning more investment tends to boost the economy.
Inflation has a negative effect, confirming that higher inflation tends to slow down growth.
Foreign Aid and its interaction with shocks were not statistically significant in this model, suggesting their effect is less clear or more complex.
•	The OLS model explained about 21% of the variation in GDP growth, which indicates there are other factors influencing growth beyond what’s in this model.
Generalized Least Squares (GLS) Regression
•	GLS accounts for potential issues like changing error variance and autocorrelation in the data, providing a more reliable estimate.
•	Results showed a much stronger model fit, explaining about 83% of the variation in GDP growth.
•	Investment remained a strong positive predictor, and inflation consistently had a negative effect.
•	Interestingly, foreign aid showed a significant negative coefficient here, which raises important questions about its impact and suggests further investigation is needed.
•	The interaction between foreign aid and shocks was again not significant, but its inclusion helps understand how shocks might modify aid’s effect.

What I Learned
•	Investment is a key driver of Kenya’s economic growth over time.
•	Inflation tends to slow down growth, which aligns with economic theory.
•	Foreign aid’s role is complex and may not always be positive—especially during economic shocks.
•	Further research is needed to unpack the nuanced relationship between aid and growth, considering governance and policy contexts.

Visualizing the Story
•	Time series plots illustrate how GDP growth evolved over decades with clear trendlines.
•	Heatmaps and correlation matrices reveal relationships between variables.
•	Diagnostic plots confirm model assumptions and highlight areas for further improvement.
