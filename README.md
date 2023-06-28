<h1> Advanced-Stock-Prediction-with-Backtesting </h1>
<h2> Input Ticker Symbol and start date for model training when prompted </h2>
<h3>This model uses a Random Forest model to Predict whether the price of the stock given will increase or decrease tomorrow.</h3>
<h4><p>Understanding the final output: The predictions column predicts whether the model thinks the stock price will increase or decrease the next trading day. 
A value of 0.0 means that the model does not think the price will increase tomorrow, while a value of 1.0 means that the model is at least 60% confident that the price will rise tomorrow. The Target column is what actually happened that day: whether the price increased or decreased.</p></h4> 
<h5>Note: Each value of the table is shifted one day forward, so add one day to the dates shown in the table for it to match up with real-world dates.</h5>
<p>
My target for this model is to predict whether the stock will move up or down. Not trying to predict the absolute (close) price for the next day. Trying to predict the absolute price is a common pitfall and is not our main concern. As we want to know if we buy the stock right now will we turn a profit or a loss tomorrow?</p>
