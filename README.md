# Machine Learning Test

In the platform of your choice, solve the below problem and send us the link to the repository with the solution.

## Problem

The purpose is to predict the weekly sales (demand) in physical retail stores.

You'll be provided with a solution after you submit your solution.

## Data

This is the historical data that covers sales from 2010-02-05 to 2012-11-01, in the file [stores_sales.csv](stores_sales.csv). Within this file you will find the following fields:

- store: the store number
- date: the week of sales
- weekly_sales: The total sales for the given store
- holiday_flag: whether the week is a special holiday week (1 – Holiday week, 0 – Non-holiday week)
- temperature: Temperature on the day of sale in Fahrenheit
- fuel_price - Cost of fuel in the region
- cpi: Prevailing consumer price index
- unemployment: Prevailing unemployment rate

Holiday Events:

- Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
- Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
- Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
- Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

## Task

Build a model that predicts the `weekly_sales` for each store. A store is identified by the combination of `store` and `date`. The model should be able to predict the `weekly_sales` for a given store and date.

You can use any machine learning library you want.

## Evaluation

The evaluation metric is the [Root Mean Squared Error](https://en.wikipedia.org/wiki/Root-mean-square_deviation) (RMSE).

## Submission

Send us the link to the repository with the solution.

## Bonus

- Explain the model you built and why you chose it.
- Explain how you would deploy the model in production.
- Explain how you would monitor the model in production.
- Explain how you would retrain the model over time.
- Explain how you would evaluate the model over time.
- Explain how you would improve the model over time.

## Key Differentiators

- The code is well structured and easy to understand
- The notebook / repository is well documented
- Best practices in Python are followed
- Strong understanding of mathematical concepts in machine learning
