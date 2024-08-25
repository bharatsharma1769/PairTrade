The Pairs Trading strategy is a market-neutral strategy that focuses on two highly correlated assets, usually 
in the same industry. We try to model the relation between the ratio of the two stocks and whenever the prices 
deviate from the mean, we go long on one stock and short on the other speculating for the prices to converge due to
the mean reversion theory.

The choice of equity pairs is not trivial, since in addition to finding high correlation, we also conduct two
co-integration tests to ensure that both prices form a stationary time-series. Finally, we backtest our strategy
with historical data and create a Equity Curve for our account.

