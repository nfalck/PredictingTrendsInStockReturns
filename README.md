# Predicting Trends in Stock Returns

In this project, I explore predicting trends in stock returns where machine learning is used to give a result of either "up" (1) or "down" (0) for every day that you predict. I have decided to use both LSTM and Random Forest to compare the both methods.

The purpose of this project was to get a taste of machine learning and learning to use pandas, numpy, TensorFlow, and scikitlearn to analyze data and start learning how to make models, combining my interest to learn machine learning and finance.

For the first attempt, the outcomes were not great, but I have learned a lot from it. For future improvements, I could test other models, change the parameters and incorporate different technical indicators to see how it affects the accuracy; as well as reduce the risk for overfitting/underfitting. Finally, feature importance and correlation can be done to see which features actually affect the results and which do not, or are redundant.

This project was done by first collecting data of the stock GOOG from Yahoo Finance, exploring it and converting them to logarithmic returns. Then it was feature engineering consisting of RSI, MACD, Bollinger Bands and SMA. After, the data was split into training and testing data. Lastly, the LSTM and RF models were created and compared in their accuracy.

If Github does not render the notebook: [Click here to view it on NB Viewer](https://nbviewer.org/github/nfalck/PredictingTrendsInStockReturns/blob/main/Exploration_of_Predicting_Trends_in_Stock_Returns.ipynb)
