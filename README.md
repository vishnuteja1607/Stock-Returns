# Stock-Returns Analysis
Look at the distribution of S&amp;P 500 returns over the last 10 years

First we take a look at the normal distribution of a sequence of values, specifically the values for the kurtosis(measure of **tailedness**) and skewness(measure of **asymmetry**). These values will serve as reference for the S&P 500 returns.

We look at the histogram, boxpllot and density plot the daily returns which seem to suggest that these values may follow normal distribution. 

After fitting the normal distribution to these returns, we can draw out the kurtosis and skewness of these values. These values vary, buy a huge margin, from the reference values above, suggesting that fitting a normal curve to the daily returns of stocks is incorrect. 

Finally we close the deal by drawing out the Q-Q plot, which supports the previous conclusion!
