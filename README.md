
# BTSM(Beating The Stock Market)

Beating the stock market, using linear regression to outperform the market average. The monthly average returns of NASDAQ100 will be our dependent value and the monthly average returns of the S&P500 will be our independent value. The main idea is that when yhat is smaller than y(NASDAQ100 montly average return) we will trade y for x(S&P500). When yhat is bigger than y we will trade x for y. Since we are using linear regression for predictions its really important to split the data(train=0.8,test=0.2) and randomize = 42 so our model does not overfit.

After testing our model with an initial investment of 100.000$ it managed to outperform both the S&P500 and NASDAQ100.

Source of data: https://fred.stlouisfed.org/ 

Any feedback is welcome :)