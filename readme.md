# Comparing two approaches in modeling SunSpots Time Series. 

If Time Series has lots of data points it's more suitable using RNN, LSTM neural net layeres in ML models.
Problem arises when using pmdarima library with auto-arima method. 
Auto-arima can quckly fill up all RAM memory if time series has to much data points. It's imposible to infer p and q parameters based on
partial-autocorelated  and autocorelated graphs in this example.
