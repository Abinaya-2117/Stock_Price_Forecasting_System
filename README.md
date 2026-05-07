# Tesla (TSLA) Stock Price Forecasting using LSTM

##  Project Overview
This project focuses on predicting the "Open" stock price of Tesla (TSLA) using Deep Learning. By utilizing Long Short-Term Memory (LSTM) networks, the model captures complex temporal dependencies in historical stock data to forecast future price movements.

##  Business Impact
* **Problem Statement:** Stock markets are highly volatile; traditional statistical models often fail to capture non-linear trends in high-growth stocks like Tesla, leading to high-risk exposure for traders.
* **Approach:** Built a multi-layer LSTM recurrent neural network. Implemented a sliding window technique (look-back period) to process historical technical indicators and normalized data using MinMaxScaler to improve convergence.
* **Solution:** Delivered a high-fidelity forecasting engine that achieves a **Root Mean Square Error (RMSE) of 1.86**. This allows for automated trend identification and significantly reduces manual technical analysis time.

##  Performance Metrics
* **RMSE:** 1.86 (indicates the model's predictions are, on average, within $1.86 of the actual price).
* **Accuracy:** The model successfully tracks significant market volatility and trend shifts as seen in the visualization below.

##  Visualizing Results
![Actual vs Predicted Graph](Actual%20VS%20Predictions%20Graph.png)

##  Tech Stack
* **Language:** Python
* **Deep Learning:** Keras/TensorFlow (LSTM Layers)
* **Data Processing:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib
