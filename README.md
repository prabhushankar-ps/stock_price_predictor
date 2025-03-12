
# Stock Price Predictor App

This repository contains a Streamlit-based web application for predicting stock prices using a pre-trained machine learning model.

## Features

- **Stock Data Retrieval**: Fetch historical stock data using [yFinance](https://pypi.org/project/yfinance/).
- **Pre-Trained Model Integration**: Uses a Keras model (`Latest_stock_price_model.keras`) for stock price prediction.
- **Interactive Visualization**: Displays stock data and predictions interactively.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/stock-price-predictor.git
   ```

2. Navigate to the project directory:
   ```bash
   cd stock-price-predictor
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   Ensure you have the following Python libraries installed:
   - Streamlit
   - Pandas
   - Numpy
   - Keras
   - yFinance
   - Matplotlib

4. Download the pre-trained model file (`Latest_stock_price_model.keras`) and place it in the project directory.

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run web_stock_price_predictor.py
   ```

2. Enter a stock ticker symbol (e.g., `GOOG` for Google) in the input box.

3. View the historical stock data and predicted stock prices.

## File Overview

- **web_stock_price_predictor.py**: Main script for the Streamlit app.
- **requirements.txt**: File containing the list of dependencies.

## Requirements

- Python 3.8 or later
- Internet connection (to fetch stock data via yFinance)

## Contributing

Contributions are welcome! Feel free to submit a pull request or raise an issue for improvements.



---

*Happy predicting!* 🎉
