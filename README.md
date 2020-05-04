# Stock-Prediction
An LSTM based Prediction Model for Stock Price Prediction.

## Description
The Model Predicts the Price of Stock on the basis of Previous 60 days data of that particular Stock.

Parameters - OPEN ,CLOSE ,HIGH ,LOW ,VOLUME.

After fetching the dataset of stock, the data is Scaled in range(0,1) with MinMaxScaler.

Scaled data is broken into train-test split as Follows -
  Train data - 60 days continuous price
  Test Data - 61st day Price (Prediction)

LSTM Sequential Model is trained on this data.

The Accuracy of Model is checked along with MEAN Squared Error.

Then, The Predictions are made and Validated,
