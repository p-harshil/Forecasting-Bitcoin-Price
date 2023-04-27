# Time Series Analysis of Bitcoin Price
### Overview:
The aim of this project is to analyze the Bitcoin price time series data and predict future prices using time series forecasting models. The data is downloaded from Yahoo Finance and contains daily information on Bitcoin's open, high, low, close, adjusted close, and volume columns.

#### Screenshot of the Bitcoin Historical Data:

![image](https://user-images.githubusercontent.com/68314057/234961026-71cd181a-23a2-494c-9852-6eef40ac70b3.png)

### Dependecies:
- pandas
- numpy
- yfinance
- datetime
- seaborn
- matplotlib
- statsmodel
- sklearn

### Packages used:

- **Machine Learning**: sklearn, statsmodel
- **Data Manipulation**: pandas, numpy, datetime
- **Data Visualization**: matplotlib, seaborn
- **Data Import**: yfinance

### Data Sources:
The data used in this project is sourced from Yahoo Finance. It is important to note that the Close column is used to compute returns and the value predicted is also the Close value.
https://finance.yahoo.com/

### About the Dataset:
- The dataset has no null values.
- Isolation forest used to detect the anomalies in the dataset for given date range.</br>
**Note**: Anomaly Detection gives an idea about the destribution of the dataset and how can we treat them. If the ratio of these anomalies are higher, we must treat them with proper method and avoid simply ignoring them.
- Log Transformation and First Difference is applied to reduce the variance in the dataset.

### Forecasts:
ARIMA and Double Exponential Smoothing (DES) models are used for predicting and forecasting the price. The results are analysed using MAE, MSE and RMSE performance metrics.

### Future Work: 
Create prompt for user input to select the start and end date of the historical data.
To forecast the price with better accuracy, more macroeconomic variables must be used as well. In this project, T-bill rate is not taken into account. 

### Instructions:
To run this project, the required libraries must be installed. The data is already included in the project via yfinance, but if you want to use more recent data, you must change the date to download it from Yahoo Finance.
