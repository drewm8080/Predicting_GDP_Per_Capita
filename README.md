# Project Title: Predicting GDP Per Capita Using NASDAQ Economic and Stock Market Data

## Abstract
In this final project, I utilized NASDAQ economic data and stock market data as predictors to forecast GDP per capita. Employing a Random Forest Regression model, I identified six predictors that enabled the model to predict GDP per capita with an accuracy of 94.17%. Additionally, I explored the reasons why these predictors might influence GDP per capita. Furthermore, I normalized the data to compare GDP per capita and the stock market data, revealing that the stock market may not have as significant an influence on GDP per capita as commonly believed.

## Background
The project utilized three primary data sources: NASDAQ API for economic data, web-scraped GDP per capita data, and Yahoo Finance stock data. The stock data encompassed the NASDAQ composite, S&P 500, and Dow Jones Industrial Average indexes. The NASDAQ API provided four distinct datasets on the US economy, including the unemployment rate, real GDP, Personal Consumption Expenditures, and exports and imports of the US.

## Modeling
To identify the most influential predictors of GDP per capita, a Random Forest Regression model was employed due to its robustness against overfitting. The model was trained using 70% of the data and tested on the remaining 30%. The results indicated that the model with seven trees and a maximum of five features produced the best outcomes.

## Analysis and Results
The analysis revealed that the US GDP per capita has exhibited steady growth over time. The model achieved an accuracy of 94.17% in predicting GDP per capita. Feature importance analysis identified six distinct features that significantly influenced GDP per capita, including market-based price index, services price index, exports of durable goods, real GDP, imports of nondurable goods, and non-durable goods price index.

## Conclusion
The project successfully identified six predictors of GDP per capita and challenged the common belief that stocks significantly impact GDP per capita. The technical challenges encountered during model selection were overcome, and the Random Forest Regression model proved to be the most effective for prediction.

**Accuracy**: 94.17%
