# Stock Analysis with EMA and Trendline

This repository contains stock data analysis using the Exponential Moving Average (EMA) and Trendline methods. The dataset used is `all_stocks_5yr.csv`, which contains historical stock data from companies in the S&P 500 index for 5 years.

## Analysis Steps
1. **Data Preprocessing**:
- Read and clean the data.
- Filter data for specific stocks (example: AAL).

2. **Forecasting with EMA**:
- Calculate the Exponential Moving Average (EMA) for the closing price (`close`).
- Create a comparison plot of actual data vs. EMA predictions.

3. **Create Trendline**:
- Calculate the trendline using linear regression.
- Create a comparison plot of actual data vs. trendline.

## How to Run
1. Clone this repository.
2. Make sure the `all_stocks_5yr.csv` file is in the same directory.
3. Open Jupyter Notebook and run the `analysis.ipynb` file.

## Results
- **EMA Plot**: Shows the comparison of actual price to EMA prediction.
- **Trendline Plot**: Shows the general direction of stock price movement.

## Contributions
Please open an issue or pull request if you would like to contribute.

## License
This project is licensed under the [MIT License](LICENSE).