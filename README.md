# Reliance-Stock-Prediction
Upon successively failing to forecast the Reliance stock prices since the Covid-19 pandemic, I decided to work on this project that uses data and maths (no guts unlike me) to forecast the same for me. <br><br>

In this model, Facebook's prophet (earlier fbprophet) library is used for time series analysis or to be more precise time series forecasting.
<li> The data is collected from yahoo finance. (The dataset is named RELIANCE.NS.csv)
<li>The data is collected from 01/01/2014(Almost 2 years before Jio launch) to 17/08/2022(present).
<li>The dataset is preprocessed to drop all the columns except for data and the closing value for that day.
<li>2/3rd of the data serves as training data and the remaining as test data.
<li>Weekly, Monthly and Yearly trends are also shown.
