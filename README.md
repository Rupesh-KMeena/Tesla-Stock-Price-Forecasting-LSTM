# Tesla Stock Price Prediction

## Overview

This project involves predicting Tesla (TSLA) stock prices using historical data. The dataset includes daily stock price information from January 2015 to January 2024. The project utilizes machine learning techniques, particularly Long Short-Term Memory (LSTM) networks, to forecast stock prices based on historical data.

## Features

- Data preprocessing and exploratory analysis
- Visualization of historical stock prices
- Time series stationarity tests (ADF and KPSS)
- LSTM model implementation for stock price prediction
- Model evaluation with metrics such as MSE, MAE, and R² score

## Dataset

The dataset used in this project includes the following columns:

- `Date`: The date of the stock record
- `Open`: Opening price of the stock
- `High`: Highest price of the stock during the day
- `Low`: Lowest price of the stock during the day
- `Close`: Closing price of the stock
- `Volume`: Number of shares traded

**Source:**
- Tesla Stock Price Dataset: `/kaggle/input/tesla-stock-price/Tasla_Stock_Updated_V2.csv`

## Installation

Ensure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib plotly scikit-learn tensorflow statsmodels
```


## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/tesla-stock-price-prediction.git
    cd tesla-stock-price-prediction
    ```

2. **Run the Jupyter Notebook or Python script:**

    For Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

    For Python script:

    ```bash
    python tesla-stock-price-forecasting-lstm.py
    ```

3. **Explore the results:**

    - **Visualizations of stock prices:** Examine the charts and graphs showing historical and predicted stock prices.
    - **Model performance metrics:** Review the evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² score to assess model accuracy.
    - **Predicted stock prices:** Check the output of the model's predictions compared to actual stock prices.


## Results

The project includes various visualizations and metrics to evaluate the model's performance. Examples include:

- **Stock price trends over time:** Visualizations showing historical stock prices and predicted trends.
- **Model predictions vs. actual prices:** Comparison of the model's predictions with actual stock prices.
- **Performance metrics:** Evaluation metrics such as Mean Squared Error (MSE) and R² score to assess the accuracy of the model.

## Contributing

Feel free to contribute by submitting issues, pull requests, or suggestions. All contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [TensorFlow](https://www.tensorflow.org/) for the LSTM implementation
- [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/) for data manipulation
- [Matplotlib](https://matplotlib.org/) and [Plotly](https://plotly.com/) for visualization
- [Scikit-learn](https://scikit-learn.org/) for metrics and preprocessing
- [Statsmodels](https://www.statsmodels.org/) for statistical tests

