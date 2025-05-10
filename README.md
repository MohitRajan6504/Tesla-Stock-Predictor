# 📈 Stock Price Prediction using Generative AI

This project demonstrates how deep learning and Generative AI techniques can be applied to predict future stock prices using historical stock market data. The model uses LSTM (Long Short-Term Memory) neural networks to forecast future stock trends and provides a user-friendly web interface built with Streamlit.

## 🚀 Project Overview

- **Goal**: Predict future stock prices based on historical data using LSTM neural networks.
- **Technologies**: Python, TensorFlow, yFinance, Streamlit
- **Interface**: Streamlit web app where users can input stock tickers and view predictions.

---

## 🧠 Features

- Download historical stock data from Yahoo Finance
- Preprocess and normalize time series data
- Build and train an LSTM model for stock prediction
- Visualize actual vs. predicted stock prices
- Simple and intuitive web UI for predictions

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- TensorFlow / Keras
- Streamlit
- yFinance

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   
2. Install dependencies:
pip install -r requirements.txt

3. Run the Streamlit app:
streamlit run app.py

🧪 How It Works

Data Loading: Fetches stock data using yfinance.

Preprocessing: Normalizes the data and prepares sequences for time series prediction.

Model Building: Uses LSTM layers to learn temporal patterns.

Prediction: Predicts future stock values based on learned patterns.

Visualization: Plots actual vs. predicted prices in the Streamlit UI.



🧪 Testing

Tested with major stock tickers (AAPL, TSLA, MSFT, etc.)

Validated predictions using RMSE and trend accuracy

Edge cases (e.g., invalid ticker symbols) are handled gracefully

🔮 Future Work

Use Transformer models for improved forecasting

Integrate real-time news sentiment analysis

Add multi-stock comparison and export features

Deploy on cloud (Heroku, AWS, etc.)

