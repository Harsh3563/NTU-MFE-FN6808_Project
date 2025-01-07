**Course Code/Name:** FN6808 - Derivative Securities


**Project Tasks:**
_Question 1: Modeling Volatility_
Find data for historical prices for any publicly traded equity. To ensure the length of data, use daily data
for at least 3 years. Fit the historical data to
1. Geometric Brownian motion
2. Any non-constant volatility model
Find market data for option prices for this stock. Use option prices to
3. Show volatility smile
4. Construct term structure of volatility
5. Plot the volatility surface, as a function of time to maturity and moneyness.
   
_Question 2: Vanilla European option pricing_
Use the non-constant volatility model obtained in Question 1(2). Calculate the price of a European call
option (whose today’s price can be observed in market) using
1. Monte Carlo
Use the Geometric Brownian motion obtained in Question 1(1). Calculate the price of the same
European call option using
2. Numerical PDE
3. Binomial Model
4. Black-Scholes formula
For each part of 1 to 3, show how accuracy can be improved by increasing computational time. Lastly,
5. Compare the four calculated prices with the “true price” observed in market. Comment on these
methods based on their efficiency and accuracy. Explain any source of error and make
suggestions on possible ways to reduce the error.

_Question 3: Variance reduction in Monte Carlo_
Use the Geometric Brownian motion obtained in Question 1(1). Calculate the price of any pathdependent option using
1. Crude Monte Carlo
2. Monte Carlo with two different (one for each time) variance reduction techniques, and show
how much efficiency is gained. _(Note: We used Antithetic Variates and Control Variates techniques)_


**Final Python (Jupyter Notebook - 'ipynb') Code:** 6808-Project.ipynb


**Final Stock Dataset:** MSFT_stock_data.csv
_- Publicly Traded Equity:_ Microsoft Corp. (MSFT)
_- Data Source:_ Yahoo Finance
_- Timeline:_ 3 Year + (till Present Day) Historical Prices (01/04/2021 - 09/27/2024)
_- Frequency:_ Daily
_- Columns:_ date(Date), symbol(General/Text), open(Numeric), high(Numeric), low(Numeric), close(Numeric), volume(Numeric), adj_close(Numeric)
_- All prices (open, high, low, close, adj_close) in USD_
_- Display Order:_ By date (Ascending / Oldest-First)


**Final (Call) Option Chain Dataset:** call_option.csv
_- Publicly Traded Underlying Equity:_ Microsoft Corp. (MSFT)
_- Data Source:_ Yahoo Finance
_- Expiration Dates:_ 18 October 2024 onwards
_- Strike Prices:_ All strike prices
_- Moneyness:_ In the money
_- Columns:_ {strike, bid, ask, last, impliedVolatility, volume} (Numeric), symbol (General), expiration (Date)
_- All prices (strike, bid, ask, last, impliedVolatility) in USD_
_- Display Order:_ By expiration (Ascending / Oldest-First)
