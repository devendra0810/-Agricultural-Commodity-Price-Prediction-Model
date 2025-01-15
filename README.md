# Agricultural-Commodity-Price-Prediction-Model
This project aims to develop a predictive model to forecast the prices of agricultural commodities, specifically focusing on seasonal price variations. It helps farmers, traders, and policymakers gain valuable insights into price trends, facilitating informed decision-making.

**Features:**

1.Predicts agricultural commodity prices based on historical data and seasonal trends.

2.Utilizes LSTM (Long Short-Term Memory) networks for accurate time-series predictions.

3.Seasonal data points are visualized to show price trends throughout the year.

**Tools & Technologies:**

1.Pandas: For data manipulation and analysis.

2.NumPy: For numerical operations.

3.Matplotlib: For data visualization.

4.TensorFlow & Keras: For building and training the LSTM model.

5.Scikit-Learn: For preprocessing and model evaluation.

6.MinMaxScaler: For scaling the price data between 0 and 1.

**Methodology:**

1.Data Preprocessing: The dataset was cleaned and transformed into a format suitable for time-series analysis. The date column was converted to a datetime format, and prices were scaled using the MinMaxScaler.

2.Model Building: An LSTM-based model was constructed to predict future commodity prices using historical data.

3.Evaluation: The model's performance was evaluated using RMSE and MAPE metrics to assess prediction accuracy.

This project enhances predictions and provides valuable insights into agricultural commodity pricing, offering practical benefits to farmers and stakeholders in the agricultural sector. It also plays a key role in achieving cyclicity in market trends.
