# Time Series Experiments

### SMA.ipynb
This notebook visualizes the stock returns of different companies such as Google, Apple, IBM, etc. It includes visualizations of moving averages and stock returns.

### ESMA_and_Holt_Winters.ipynb
This notebook utilizes Exponential Simple Moving Averages (ESMA) and the Holt-Winters model from statsmodels for time series data of airline passengers.

### Perrin_Champane.ipynb
This notebook uses champagne data to perform forecasting using the ExponentialSmoothing model from Holt-Winters.

### Stock_Prediction.ipynb
This notebook applies the Exponential Smoothing model to stock data from Google for forecasting.

### ARIMA(with_stock_prices).ipynb
This notebook uses the S&P 500 dataset to predict Google's stock prices. The analysis includes stationarity tests and various plots, leading to the application of the ARIMA model, achieving an 85% root mean square error (RMSE).

### ARIMA.ipynb
This notebook uses airline passenger data to forecast future values. Given the presence of trend and seasonality in the data, the ARIMA model accurately identifies these patterns and provides a high level of accuracy in the predictions.


### Stationary.ipynb
This notebook explores the concept of stationarity, which is crucial for time series analysis. It includes performing the Augmented Dickey-Fuller (ADF) test to check the null hypothesis. If the data is non-stationary, the notebook demonstrates how to differentiate the time series to achieve stationarity.

### Auto_ARIMA.ipynb
In previous notebooks, the values of (p, d, q) were determined manually using ACF and PACF plots. This notebook utilizes the `auto_arima` function from the pmdarima package to automatically determine these values.

### ACF_and_PACF.ipynb
This notebook explores the ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) plots, which are essential for understanding and determining the values of p and q in time series models.

### ARIMA(Champange).ipynb
This notebook uses the champagne dataset to forecast future values using the ARIMA model.

### VARMA.ipynb
This notebook explores the VARMA model, a variant of ARIMA that works with two or more features. Unlike previous notebooks that focused on single-feature time series, this one extends the analysis to multiple features.

### ARIMA (Econometrics).ipynb
This notebook uses an econometrics dataset to perform forecasting with the ARIMA model.

### StockPrices (ML).ipynb\
This notebook utilizes Machine Learning methods to forecast future stock prices, specifically employing:
- Support Vector Regressor (SVR)
- Random Forest Regressor (RFR)
- Gaussian Process Regressor (GPR)

### Airline (ML) -No Differencing.ipynb
This notebook uses airline data to forecast future values, trends, and seasonality. Unlike previous statistical methods that involved differencing the data to achieve stationarity, this notebook employs non-stationary data and applies machine learning methods to evaluate their performance against traditional methods without differencing:
- Forecasts future values, trends, and seasonality in airline data.
- Uses non-stationary data without differencing.
- Evaluates machine learning methods against traditional methods.

### ML (Stock Prices Stationary).ipynb
This notebook uses the stock data and applies the same machine learning methods, but with stationary data. The results show improvement compared to the non-differenced data:
- Applies machine learning methods to stationary airline passenger data.
- Compares results with non-stationary data, showing improved accuracy.

### ML (Stock Prices Stationary).ipynb
This notebook uses the same airline passenger data and applies the same machine learning methods, but with stationary data. The results show improvement compared to the non-differenced data:
- Applies machine learning methods to stationary airline passenger data.
- Compares results with non-stationary data, showing improved accuracy.

### ML (Sales Data Champange).ipynb
This notebook uses the Champagne dataset to forecast trends, seasonality, and future values. It utilizes machine learning methods for forecasting, including SVR, Linear Regressor, and RFR. The notebook covers:
- One-step forecast.
- Multi-step forecast.
- Multi-step multi-output forecast.

### ANN_for_airline_data.ipynb
This notebook uses airline passenger data and applies an Artificial Neural Network (ANN) with a simple Dense layer for forecasting.

### CNN_Airline.ipynb
This notebook uses the same airline data but applies a Convolutional Neural Network (CNN) for forecasting. It includes:
- 1-step forecast.
- Multi-step forecast.
- Multi-step multi-output forecast.

  ### ANN_Human_Activity_Recognition.ipynb
This notebook focuses on human activity recognition using Artificial Neural Networks (ANN). It includes:
- Utilizing simple ANN Dense layers to model and predict human activities based on sensor data.
- Performing forecasting from both raw time series data and engineered features provided by experts.
- Achieving an initial accuracy of 93% and comparing the results with traditional machine learning techniques like Linear Regression, Support Vector Classifier (SVC), and Random Forest.
- Combining both time series and featured data into an extensive ANN model, which improves the prediction accuracy to 96%.
- Demonstrating the effectiveness of integrating multiple data sources and neural network architectures to enhance model performance.

### GRU_and_LSTM_(for time series).ipynb
This notebook applies GRU (Gated Recurrent Units) and LSTM (Long Short-Term Memory) models to the airline passengers dataset for time series forecasting. It includes:
- 1-step forecast, multi-step forecast, and multi-step multi-output forecast.
- Effectively identifies trends within the dataset.
- Delivers strong forecasting accuracy for predicting future values.

### Human_Activity_Recognition_LSTM.ipynb
This notebook utilizes the Human Activity Recognition dataset to forecast human activities using the LSTM (Long Short-Term Memory) method. It includes:
- Achieved 93% accuracy on raw time series data.
- Achieved 95% accuracy on derived feature data.
- Demonstrates the effectiveness of LSTM in capturing temporal dependencies for improved activity recognition.

### GARCH.ipynb
This notebook focuses on forecasting stock prices using the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) technique. Stock prices often follow a random walk, making prediction challenging, but GARCH helps in modeling and forecasting volatility for better predictions.

