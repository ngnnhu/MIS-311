# Case Study For Time Series Forecasting 
Leading economic indicators, such as the stock market or the housing market, often change prior to large economic adjustments. For example, arise in stock prices often means that investors are more confident of future growth in the economy. Or a fall in building permits is likely a signal that the housing market is weakening—which is often a sign that other sectors of the economy are on the downturn. 
Consider what happened prior to the 2008 recession. As early as October 2006, building permits for new homes were down 28% from October 2005. Analysts use economic indicators to predict future trends and gauge where the economy is heading. The information provided by economic indicators helps firms implement or alter business strategies.

<img width="632" height="419" alt="image" src="https://github.com/user-attachments/assets/4ae858a3-0bb3-4b92-9c8c-90823f0b6b0a" />

Pooja Nanda is an analyst for a large investment firm in Chicago. She covers the construction industry and has been given the challenging task of forecasting housing starts for June 2019. She has access to seasonally adjusted monthly housing starts in the United States from January 2016 to May 2019. A portion of the data is shown in Table 1.

**TABLE 1. Monthly Housing Starts (in 1,000s)**

<img width="203" height="218" alt="image" src="https://github.com/user-attachments/assets/78744a33-9e1f-4c5e-a3d4-514820a2696c" />

Pooja would like to use the sample information to identify the best-fitting model to forecast housing starts for June 2019.

## Sample Report - Forecasting Monthly Housing Starts
Leading economic indicators are often used to gauge where the economy is heading. The housing market is one of the most important indicators because it is a significant component of the economy. When this sector weakens, just about everyone and everything feels it—from homeowners and construction workers to government municipalities that rely on property taxes to operate. Given the importance of the housing market, this report will employ simple time series models to project historical data on housing starts.
A scatterplot of housing starts from January 2016 to May 2019 is shown in Figure 1. A casual observation of the scatterplot suggests quite a bit of random variation and possibly a slight upward trend. There is no concern for seasonality as the housing starts data represent seasonally adjusted annual rates.

**FIGURE 1. Scatterplot of housing starts (in 1,000s)**
<img width="664" height="401" alt="image" src="https://github.com/user-attachments/assets/1db5d887-bf47-44aa-87bd-53ac4e6db0a4" />

**Given the findings from Figure 1, three models are estimated:**
1. The three-period moving average model.
2. The simple exponential smoothing model.
3. The simple linear trend model, yt = β0 + β1t + εt, where yt represents
housing starts.

**Three performance measures are used for model selection:**
1. Mean square error (MSE)
2. Mean absolute deviation (MAD)
3. Mean absolute percentage error (MAPE)

Ideally, the preferred model will have the lowest values for MSE, MAD, and MAPE. 
Table 2 shows the values of these three performance measures for the models.

**TABLE 2. Performance Measures of Competing Models** 
<img width="605" height="184" alt="image" src="https://github.com/user-attachments/assets/26e2498a-8846-4329-8dee-2d8b403d7fb7" />

The linear trend model provides the best sample fit, as it has the lowest values for MSE, MAD, and MAPE. 
Therefore, the estimated linear trend model is used to derive the forecast for June 2019 as:

<img width="346" height="31" alt="image" src="https://github.com/user-attachments/assets/148e74b0-d711-49c2-92e2-b81e928dd27c" />

Housing starts play a key role in determining the health of the economy and are, therefore, always under scrutiny. The U.S. housing market seems to be on solid ground even though there has been a slowdown from its peak in early 2018.
