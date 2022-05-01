# A Yen for the Future

<img src="https://github.com/ChantalAG/Time-Series-Forecasting/blob/main/Images/CADJPY.jpg" width="500" height="300">

## Background

Financial departments of large companies have to make foreign currency transactions while doing international business. Hedge funds are interested in anything that will provide an edge in predicting currency movements. Both are eager to gain a better understanding of the future direction and risk of various currencies. 

In this project, Time-Series Forecasting and Linear Regression Modelling are used to predict future movements in the value of the Canadian dollar verses the Japanese yen. Forecasting models used include, Autoregressive Moving Average (ARMA), Autoregressive Integrated Moving Average (ARIMA), and Generalized Autoregressive Conditional Heteroskedasticity (GARCH). Linear regression model is evaluated with In-Sample and Out-of-Sample performance metrics. 

## Resources
[CAD-JPY Exchange Rate Data](https://github.com/ChantalAG/Time-Series-Forecasting/blob/main/cad_jpy.csv)

    
## Time-Series Forcasting
    
![image](https://user-images.githubusercontent.com/99493522/166161901-28c74e39-4dbe-4a8e-acda-7e75a232eee7.png)


### Decomposition Using a Hodrick-Prescott Filter

![image](https://user-images.githubusercontent.com/99493522/166161975-487950ad-a202-4ec6-92a9-47813dde850a.png)


### Forecasting Returns using an ARMA Model

![image](https://user-images.githubusercontent.com/99493522/166162044-99ee6cc3-0b61-4e3d-88f6-6f1dfa0f5951.png)

### Forecasting the Exchange Rate Price using an ARIMA Model

![image](https://user-images.githubusercontent.com/99493522/166162066-2af93518-8871-4a98-8074-770fcc7afa00.png)

### Volatility Forecasting with GARCH

![image](https://user-images.githubusercontent.com/99493522/166162087-d70814bb-df9a-4a22-8fcb-92e71959ef9f.png)


### Time-Series Forcasting Conclusions

It would not be recommended to buy the yen at this time. The initial time-series plot shows a decrease in price over time, the ARIMA model forecasted that the yen will have a steady decline over the next 5 days, and the GARCH model forecasted an increase in volatility over the next 5 days. Based on this analysis, the risk of the yen can be expected to increase.

## Linear Regression Modelling Conclusions

The lower the Root Mean Squared Error (RMSE), the better the model performs. Therefore, this model performs better on the Out-of-Sample data. Since the RMSE for Out-of-Sample data is lower, 0.64 then the RMSE for In-sample data, 0.84.


## Contributors

Chantal Garnett

