# Gone with the Wind...Model🌪️💚📊
Year 2025

_Simulating and forecasting wind speeds in Ballarat, Victoria using R – with Weibull distribution modelling and SARIMA time series forecasting to assess wind turbine feasibility._



## Project Overview

This project investigates hourly wind speed patterns in Ballarat to assess the potential for wind turbine installation. Using observational data from the Ballarat Rowing Club, the project uses statistical simulation and time series forecasting to model and predict wind conditions relevant to renewable energy planning.

This project showcases both distribution modelling and time series techniques in R.  
Note: If reader does not have R studio - code and results can be viewed via .html file uploaded to this repo. 


## Key Technical Highlights

- **Weibull distribution modelling** with Maximum Likelihood Estimation (MLE)
- **SARIMA models** for time series forecasting
- Comparison of **annual vs seasonal modelling**
- Residual diagnostics using ACF, PACF, and Ljung-Box tests
- Exploratory ARIMAX models using seasonal dummy variables
- Interactive plots via `ggplotly`



## Features

### Feature 1  
**Statistical Simulation of Wind Speeds**  
- Applied Weibull distribution (annual and seasonal fits)  
- Compared log-likelihood and AIC to evaluate fit quality  
- Investigated model bias in upper-tail behaviour (extreme winds)

### Feature 2  
**Time Series Forecasting with SARIMA and ARIMAX**  
- Converted hourly data into regular time series  
- Identified seasonality via ACF plots and tested for stationarity  
- Manually tuned SARIMA configurations for better AIC and residuals  
- Forecasted next 48 hours of wind speeds with confidence intervals  
- Visualised forecast using interactive plots



## Outputs

- Weibull distribution plots (annual and seasonal)
- Q–Q plots showing goodness of fit
- SARIMA model diagnostics and forecast plots
- Interactive 48-hour wind forecast visualisation



## Dependencies

- R (≥ 4.0.0)
- `forecast`
- `fitdistrplus`
- `tseries`
- `ggplot2`
- `plotly`
- `lubridate`
- `dplyr`



## How to Run

Either: 
1. Open up in R Studio, uncomment the install.packages lines in the first code block and Run All. 
2. View code and output using .html that was knitted from R Studio. 

## Credits
Saf Flatters  
Data: City of Ballarat open data portal https://data.ballarat.vic.gov.au/explore/dataset/wind-observations/export/


## Connect with Me

📫 [LinkedIn](https://www.linkedin.com/in/safflatters/)


## License and Usage

![Personal Use Only](https://img.shields.io/badge/Personal%20Use-Only-blueviolet?style=for-the-badge)

  

This project is intended for personal, educational, and portfolio purposes only.

You are welcome to view and learn from this work, but you may not copy, modify, or submit it as your own for academic, commercial, or credit purposes.