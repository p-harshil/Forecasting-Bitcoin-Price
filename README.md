# Time-Series-Analysis-of-Bitcoin-Price
### Overview:
Bitcoin price is a time series data over specific time downloaded from yahoo finance data. The main aim of this project is to catch the bitcoin price volatility and predict the future price using ARIMA model.

### Libraries Required:
- pandas
- numpy
- yfinance
- datetime
- seaborn
- matplotlib
- statsmodel
- sklearn

### Data Sources:
https://finance.yahoo.com/

### About the Dataset:
For bitcoin, the data shows 'Open', 'High', 'Low', 'Close', 'Adj Close' and 'Volume' columns. Here, 'Close' values are used to compute returns and the value predicted is same too.
We have used isolation forest algorithm to detect the anomalies in the daily closing price for the selected time span. This gives us an idea about the destribution of the dataset and how can we treat them. If the ratio of these anomalies are higher, we must treat them with proper method and avoid simply ignoring them.


### Future Work: 
To forecast the price with better accuracy, more macroeconomics variables must be used as well. Here we have not taken 'T-bill' rate into the account. 
