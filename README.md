# International-FemHack---Groupal-Challenge 2022

# Hack The Markets - Predictive modelling
*Instrucciones del reto para el International FemHack*


### Resumen
To improve the European central bank's decision making, Christine Lagarde would need to have some certainty about future currency market dynamics, in particular, one of the ones she is most concerned about is the EUR/GBP pair. Therefore, they need your team to create a small predictive model for them to know if the value of the Euro will rise or fall against the British pound a month in advance.

### Dataset
Same dataset as in the individual challenge but with a new variable called ‘target’. The predictive variables of the dataset are:

‘Open’: Price of the pair at the beginning of the day.
‘High’: Maximum price that the pair reaches during the week.
‘Low’: Minimum price that the pair reaches during the week.
‘Close’: Price of the pair at the end of the week.
’rsi’: Relative Strength Index, is an indicator that is often used in technical analysis and shows the strength of the price.
’ema_fast’: Exponential Moving Average taking the average value of 14 weeks.
‘ema_slow’: Exponential Moving Average taking the average value of 42 weeks.
The moving averages are usually used to detect trends in the markets, when the fast moving average (ema_fast) exceeds the slow moving average (ema_slow) indicates the beginning of an uptrend.

‘volatility’: Volatility is a measure of the intensity of changes in the price of an asset. In this case the volatility has been obtained from the NATR (Normalized Average True Range).
Target:

‘target’: The target is defined by two values, 1 or 0.
If target is 1 means that in the next month, the closing price of the EURGDP pair will be higher than this week's closing price. If target is 0 means that in the next month, the closing price of the EURGDP pair will be lower than this week's closing price.


### User stories / Objetivos

✅ Task 1 → Modelling the predictive model

✅ Task 2 → Use the best model to predict the target of the dataset 'test_x'
