Commodity Price Forcesting

I have used the market price of Brazilian soybeans as an endogenous variable for prediction, and used 13 exogenous variables such as weather, exchange rate, soybean futures price, crude oil futures price, etc., to assist in the prediction. The price variables have already undergone stability analysis and other preprocessing operations, and ARIMA, LSTM models have been used for preliminary modeling.
To Do: 
1. Adjust data
2. Explore more possibilities of exogenous variables 
3. Try other models 
4. Find out why LSTM's performance decreases when using exogenous variables (only using which exogenous variable causes price lag, making the model remember historical prices rather than predict prices)

Personal Thoughts：
1. Adjust the data, as there are too many factors affecting market prices, I would like to switch to using futures prices as the prediction target instead of market prices if the effect is still not satisfactory after trying other models (there are already relevant literature on futures prices). 
2. The overall article is preparing to use the comparison of exogenous variables and multiple models as the main way of elaboration.
