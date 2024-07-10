## Project Overview

This project aims to analyze the trends and correlations in the prices of natural gas, crude oil, gold, and Bitcoin over time. The analysis includes plotting price trends, calculating moving averages, normalizing prices for comparison, and computing correlation matrices for daily price changes.

## Features

- **Trend Analysis**: Visualize the price trends of various assets over time.
- **Moving Average Analysis**: Smooth out short-term fluctuations using a 30-day moving average.
- **Comparative Analysis**: Compare the performance of different assets by normalizing their starting prices.
- **Correlation Analysis**: Compute and display the correlation matrix of daily price changes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/onniep/stock-market-trend-analysis.git
    cd stock-market-trend-analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install pandas numpy matplotlib
    ```

3. Ensure you have the dataset (`Stock Market Dataset.csv`) in the root directory of the project.

## Usage

Run the script to perform the analysis:
```bash
python StockTrendAnalysis.ipynb