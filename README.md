# Linear Regression with sklearn and seaborn

For this excersise I have chosen a dataset from [Kaggle](https://www.kaggle.com/) reflecting a timeseries of financial trading data on [Ethereum-Classic-ETC](https://www.kaggle.com/soham1024/ethereum-historical-data) crypto-currency. This dataset was updated Aug 2, 2020
at the time of this analysis and covers historical data at 1 day intervals for the period beginning Mar 2016 to Aug 02, 2020. 

The goal is to Identify:

```
    A) Does a correlation exist between one days' Close Price (shown as price in the dataset) and the previous days' volume. 
    B) If such a correlation exists, can it be used to create a predictive model of the next days' Price? High? Low? Spread?

```

For the purpose of this analysis, Volume will be considered as our constant variable. (should no direct correlations appear to exist with any other category, Volume as a ratio of one other column series will be considered as our next constant)

The Dependent Variable for this analysis will be set to Price(on the subsequent day of the constant)

### Table of Contents

[Linear Regression fit-lm PR](https://github.com/MasonChance/linear-regression/pull/1)
