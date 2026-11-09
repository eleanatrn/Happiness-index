# Happiness-index
Statistical analysis &amp; regression modelling of the World Happiness Report (2018–2019): drivers of national happiness, outlier diagnostics, OLS vs. robust regression, and 2019 ranking prediction.

# World Happiness Report – Regression analysis

Student project analysing the World Happiness Report (2018 and 2019). The goal was to see which factors explain a country's happiness score, and whether a model trained on 2018 can predict the 2019 ranking.

Data: [Happiness Index 2018–2019 on Kaggle](https://www.kaggle.com/datasets/sougatapramanick/happiness-index-2018-2019). The dataset covers about 156 countries per year. The variables are GDP per capita, social support, healthy life expectancy, freedom, generosity and perception of corruption.

## What's in the notebook

- Exploratory analysis: correlations, scatter plots, world map of the ranking
- Regression diagnostics: studentized residuals, QQ-plot, leverage, Cook's distance
- Variable selection with R², adjusted R², AIC and BIC
- Multiple linear regression (OLS) and robust regression (Huber) to handle outliers
- Prediction of 2019 scores with the 2018 model, evaluated with R², MSE and Kendall's tau on the ranking

## Results

On 2019 the model reaches an R² of XX and a Kendall's tau of XX. GDP matters a lot, but it does not explain the ranking alone: social support, life expectancy and freedom also play an important role.
