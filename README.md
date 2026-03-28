# Case Study For Time Series Forecasting 
Leading economic indicators, such as the stock market or the housing market, often change prior to large economic adjustments. For example, arise in stock prices often means that investors are more confident of future growth in the economy. Or a fall in building permits is likely a signal that the housing market is weakening—which is often a sign that other sectors of the economy are on the downturn. 
Consider what happened prior to the 2008 recession. As early as October 2006, building permits for new homes were down 28% from October 2005. Analysts use economic indicators to predict future trends and gauge where the economy is heading. The information provided by economic indicators helps firms implement or alter business strategies.

<img width="649" height="479" alt="image" src="https://github.com/user-attachments/assets/94e29981-a6de-4558-a61d-836d7d168d9a" />

Pooja Nanda is an analyst for a large investment firm in Chicago. She covers the construction industry and has been given the challenging task of forecasting housing starts for June 2019. She has access to seasonally adjusted monthly housing starts in the United States from January 2016 to May 2019. A portion of the data is shown in Table 1.

**TABLE 1. Monthly Housing Starts (in 1,000s)**

<img width="210" height="224" alt="image" src="https://github.com/user-attachments/assets/94f7f09e-1886-425f-aff8-7666efe6ceed" />


Pooja would like to use the sample information to identify the best-fitting model to forecast housing starts for June 2019.

## Sample Report - Forecasting Monthly Housing Starts
Leading economic indicators are often used to gauge where the economy is heading. The housing market is one of the most important indicators because it is a significant component of the economy. When this sector weakens, just about everyone and everything feels it—from homeowners and construction workers to government municipalities that rely on property taxes to operate. Given the importance of the housing market, this report will employ simple time series models to project historical data on housing starts.
A scatterplot of housing starts from January 2016 to May 2019 is shown in Figure 1. A casual observation of the scatterplot suggests quite a bit of random variation and possibly a slight upward trend. There is no concern for seasonality as the housing starts data represent seasonally adjusted annual rates.

**FIGURE 1. Scatterplot of housing starts (in 1,000s)**
![Screenshot 2026-03-27 145733](https://github.com/user-attachments/assets/2ab65131-fa5a-4aa2-9082-8fe21fae6d12)

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
<img width="654" height="144" alt="image" src="https://github.com/user-attachments/assets/8cff8276-3253-48a4-8f1c-935ebd1bf024" />

The linear trend model provides the best sample fit, as it has the lowest values for MSE, MAD, and MAPE. 
Therefore, the estimated linear trend model is used to derive the forecast for June 2019 as:

<img width="459" height="37" alt="image" src="https://github.com/user-attachments/assets/e9bac734-a98c-438e-9a40-afa4c81ab749" />

Housing starts play a key role in determining the health of the economy and are, therefore, always under scrutiny. The U.S. housing market seems to be on solid ground even though there has been a slowdown from its peak in early 2018.
