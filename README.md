# Google-Stock-Price-Prediction-using-LSTM
Performed Google’s stock price prediction using our Keras’ LSTMs model trained on past stocks data

Step 1 – Importing required libraries.

Step 2 – Reading our training data.

Step 3 – Getting our training data in shape.

Step 4 – Creating the Stock Price Prediction model.

Step 5 – Training the Stock Price Prediction model.

Step 6 – Reading the test data.

Step 7 -Getting the Stock Price Predictions on test data.

Step 8 – Plotting the predictions and real data.


🔍 Project Highlight: Google Stock Price Prediction using LSTM

I'm thrilled to share my recent project on predicting Google stock prices using Long Short-Term Memory (LSTM) networks! 📈 Here’s what I learned:

Data Preparation:

Collected and preprocessed historical stock data.
Scaled data between 0 and 1 to enhance model performance.
Structured data to create sequences for training, with the model learning to predict the stock price based on the last 60 days of data.
Model Building:

Constructed an LSTM model with four layers, each with 50 units, and incorporated dropout layers to prevent overfitting.
Used the Adam optimizer and mean squared error as the loss function, optimizing the model for better accuracy.
Training & Testing:

Trained the model over 100 epochs with a batch size of 32, refining the model’s ability to predict stock prices.
Validated the model on test data, ensuring it could generalize well to new, unseen data.
Results & Visualization:

Predicted stock prices and visualized them against actual prices.
While the model wasn’t perfect, it successfully captured significant trends and spikes, demonstrating the power of LSTM in time series prediction.
This project enhanced my understanding of deep learning, particularly in financial time series forecasting, and solidified my skills in data preprocessing, model building, and performance evaluation. 🚀



