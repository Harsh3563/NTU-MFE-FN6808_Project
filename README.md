Course Code/Name: FN6808 - Derivative Securities

Final Python (Jupyter Notebook - 'ipynb') Code: 6808-Project.ipynb

Final Stock Dataset: MSFT_stock_data.csv
- Publicly Traded Equity: Microsoft Corp. (MSFT)
- Data Source: Yahoo Finance
- Timeline: 3 Year + (till Present Day) Historical Prices (01/04/2021 - 09/27/2024)
- Frequency: Daily
- Columns: date(Date), symbol(General/Text), open(Numeric), high(Numeric), low(Numeric), close(Numeric), volume(Numeric), adj_close(Numeric)
- All prices (open, high, low, close, adj_close) in USD
- Display Order: By date (Ascending / Oldest-First)

Final (Call) Option Chain Dataset: call_option.csv
- Publicly Traded Underlying Equity: Microsoft Corp. (MSFT)
- Data Source: Yahoo Finance
- Expiration Dates: 18 October 2024 onwards
- Strike Prices: All strike prices
- Moneyness: In the money
- Columns: {strike, bid, ask, last, impliedVolatility, volume} (Numeric), symbol (General), expiration (Date)
- All prices (strike, bid, ask, last, impliedVolatility) in USD
- Display Order: By expiration (Ascending / Oldest-First)
