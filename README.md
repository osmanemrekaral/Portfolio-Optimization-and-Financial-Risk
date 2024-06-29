# Portfolio-Optimization-and-Financial-Risk

//

In first Jupyter Notebook "portfolio construction in python with random forest" file I download various stocks' price data from yahoo finance.

and then I calculate the returns and to predict future returns, I fit a random forest model on the data

then I select the top 5 stocks with the most returns, and optimize their weights in my portfolio by maximizing their sharpe ratio

then to compare the results with the ML focused first method, I optimize sharpe ratios using only historical data.

it turns out that sharpe ratio is slightly higher in this case

//

In second file named  "var and es calculation using mc methods" again I make a portfolio using data from yahoo finance.

then we simulate (using t distribution with df = 3 ) portfolio returns, according to the historial mean and variance of the existing portfolio return.

and then we calculate Expected shortfall (ES) and Value at Risk (VaR) which are popular measures for financial risk.

then we plot them accordingly with a histogram of simulated returns

//

In third file named,  "VaR calculation using parametric methods"  we calculate VaR using parametric methods

first of all, we calculate returns from daily prices and then mean and variance of the returns of the Apple stock.

and then following the parametric method's formula, we find the VaRs' for confidence level %95 for both t dist. and normal dist.

Finally, we find plot the histogram of returns and specify the two calculated VaRs on it.
