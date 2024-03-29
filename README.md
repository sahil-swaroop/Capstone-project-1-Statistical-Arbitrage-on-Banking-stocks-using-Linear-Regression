# Statistical-Arbitrage-on-Banking-stocks-using-Linear-Regression-

In financial markets and in the real world there are time series which are cointegrated. In general terms if  two time series are ‘cointegrated’ then it means, that the two time-series move together and if  at all there is a deviation from this movement, it is either temporary or can be attributed to a  stray event, and one can expect the two time-series to revert to its regular orbit i.e. converge  and move together again. This type of time series is exactly what we want to find in financial  markets. 

So, in this project I will try and find those cointegrated relationships in banking stocks

So, to try to find a cointegrated time series we use linear regression. So, what linear regression  does in basic terms comes with the relationship between Independent variable X and dependent  variable Y. That relationship is described in terms of slope. so, slope captures how much Y  would change with change in X. 

Once we get a relationship then we can use that relationship to predict the value of Y from X.  But more often linear regression has a hard time predicting dependent variables properly. so,  we are not going to use linear regression predictions to directly make trades. 

Instead of focusing on predictions from the linear regression model we are going to focus on  errors made by the model also known as residuals. so, we will check whether the residuals of a  model are stationary or not meaning the residuals mean and variance is in tight range and  autocorrelation of residual is close to 0. This means a residual time series is stationary. 

Stationarity of residuals confirms that two stocks are cointegrated. they move closely together  and if at all some deviation happens that's temporary, they will converge back. That’s what a  cointegrated series is.
