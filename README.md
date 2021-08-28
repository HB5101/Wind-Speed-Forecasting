# Wind-Speed-Forecasting
Statistical Analysis and Forecasting of Wind Energy (Intra-State)

This projects aims to analyse wind energy for five study regions of the same state and forecast wind energy for next week or even for next month.

## Data
2000-2014 hourly wind speed data of five locations in the state of Rajasthan

## Methodology
![image](https://user-images.githubusercontent.com/55729258/131213500-bb28fcb1-7575-46c9-9dd6-82840753754b.png)

## Results
[Red Curve - Prediction, Blue Curve - Actual Dataset]

- *Auto Regression (AR) model*

  ![image](https://user-images.githubusercontent.com/55729258/131213659-f21f5cdf-aefb-4423-a68c-9c2e79933f89.png)
  
  MAE Score = 0.427
  
- *Moving Average(MA) model*

  ![image](https://user-images.githubusercontent.com/55729258/131214139-de90f83b-c602-4d60-b9a0-f263911a9f16.png)

  MAE Score = 0.424
  
-  *Autoregressive Moving Average (ARMA) model*

   ![image](https://user-images.githubusercontent.com/55729258/131214190-6fb89f67-3446-4213-9aa1-38be5bb7e1fa.png)

   MAE Score = 0.396
   
-  *ML Technique - LSTM*

   ![image](https://user-images.githubusercontent.com/55729258/131214242-fe5c6b07-68ef-4137-a050-ce6dd86b9688.png)

   MAE Score = 0.01
