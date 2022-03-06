# A Yen for the Future
## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

Test the many time-series tools in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.

  # Time Series Forecasting

    1.Forecasting Returns using an ARMA Model
   
   ![Arma](https://raw.githubusercontent.com/Springe09/Time-Series-/main/ARMA_MODEL.PNG)
   
    2.Forecasting Returns using an ARIMA Model
      
   ![Arima](https://raw.githubusercontent.com/Springe09/Time-Series-/main/ARIMA_MODEL.PNG)
   
    3.Forecasting Returns using an GARCH Model
    
   ![GARCH](https://raw.githubusercontent.com/Springe09/Time-Series-/main/GARCH_MODEL.jpg)


   -Based on the results of the time series analysis yen is not a good buy right now.

   -The risk of the yen is expected to increase.

   -Both the ARMA an ARIMA Models show P-values > .05. If the p-value is greater than the significance level, you cannot conclude that the coefficient is statistically             significant. 
    We may want to refit the model without the term.



   # Linear Regression Modeling

   SKLearn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns.
   
   
   ![InvsOut](https://user-images.githubusercontent.com/95596179/156908895-d1b56829-bce5-481a-8a44-a2b806c6e1f6.PNG)


   Out-of-Sample Root Mean Squared Error (RMSE): 0.41547588962821286
   In-sample Root Mean Squared Error (RMSE): 0.5972597350419817
   -The RMSE is a measure of model accuracy. The higher the RMSE, the lower the accuracy (since a higher RMSE means higher prediction error).
   The in-sample (training sample) RMSE, at .60, is higher than the out-of-sample (testing sample) at 0.42. Typically, out-of-sample errors are higher than in-sample errors.
