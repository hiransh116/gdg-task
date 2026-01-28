TASK1:

This project implements and compares LSTM, ARIMA, and SARIMAX models for short-term stock price forecasting using Apple (AAPL) daily closing price data obtained from Yahoo Finance over the last eight years. The dataset is split into training and testing sets (80:20) and normalized using MinMax scaling, with a 50-day sliding window used to prepare sequential inputs for the LSTM model. A stacked LSTM network is trained to learn temporal dependencies, while ARIMA and SARIMAX models are used as statistical baselines, with SARIMAX incorporating weekly seasonality. All models generate 7-day forecasts, which are compared against actual prices using Root Mean Squared Error (RMSE) and visual analysis.



TASK 2:



This project demonstrates a news-based financial analysis system that combines real-time data retrieval with a Large Language Model (LLM) to assist in investment-related decision making. The code first uses NewsAPI to fetch the latest news articles related to a stock ticker (Microsoft – MSFT), safely extracts the top three article titles and descriptions, and formats them into a concise textual context. This news context is then passed to a LLaMA 3.1 model hosted on Groq using LangChain, where the model is prompted to act as a financial advisor and analyze the news to provide an investment-oriented response. 
