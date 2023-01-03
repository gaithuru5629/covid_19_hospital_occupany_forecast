# covid_19_hospital_occupany_forecast
Forecast of COVID-19 Related Hospital Occupancy


Problem:
Shortage on medical supplies and health care workers
Delay on scheduled non-COVID surgeries and other specialized treatment

Project Objective:
Predict the supply of PPE and medical staff required for Saskatchewan city hospitals based on daily hospital admission rate of confirmed COVID-19 cases in different Saskatchewan regions

Benefits:
Encourage more college students to pursue the medical field of study
Provide an overview on the COVID cases in Saskatchewan
Encourage government or local authority to take necessary actions

Modelling and Tools Used:
* Python programming languages and relevant libraries
* Pandas to create data frame, read data from csv file and perform other data analysis
* NumPy to work with arrays and perform certain mathematical calculation
* Matplotlib and Seaborn to do visualization

Models used for analysis and the prediction for time series forecasting:

Statistical models in statsmodels:
* Simple exponential smoothing
  * Holt's method of smoothing
  * Holt's exponential trend 
  * Holt's additive damped trend
* Recursive autoregressive forecasting in scikitlearn.
* AutoRegressive Integrated Moving Average (ARIMA)

