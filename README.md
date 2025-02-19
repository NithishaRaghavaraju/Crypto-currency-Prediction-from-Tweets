# Crypto-currency-Prediction-from-Tweets

ryptocurrency Prediction from Tweets
This project focuses on predicting cryptocurrency price movements based on tweets from influential figures in the crypto space using an LSTM-based model.

## 📂 Dataset
The dataset includes cleaned tweets from various sources, such as:

Elon Musk (Ethereum, ETH, BTC, Bitcoin)
CZ Binance (Ethereum, Bitcoin, BTC, ETH)
Binance (BTC, Bitcoin, Ethereum, ETH)
SBF FTX (Ethereum, Bitcoin)
## 🔹Data Processing
load_data(): Loads and preprocesses tweet data.
clean_text(): Performs text cleaning and tokenization.
generate_sequences(): Creates input sequences for model training.

## 🧠 Model Architecture
The model consists of an LSTM-based neural network with the following methods:

build_model(): Defines the LSTM network structure.
train_model(): Trains the model using historical tweet data.
evaluate_model(): Calculates performance metrics such as RMSE and MAE.

## 📊 Model Performance
The trained model is evaluated using:

calculate_rmse(): Computes Root Mean Squared Error (RMSE).
calculate_mae(): Computes Mean Absolute Error (MAE).

