# Stock-Price-Analysis-and-Visualization-with-Pandas-TA-Lib-and-Plotly

## Overview

This repository contains a Python script for analyzing stock price data and performing technical analysis using various indicators. The script fetches historical stock price data from CSV files, combines them, and then adds technical indicators such as RSI (Relative Strength Index), Stochastic Oscillator, CCI (Commodity Channel Index), MACD (Moving Average Convergence Divergence), and more.

## Usage

1. **Requirements**
   - Python 3.10
   - Required Python libraries: pandas, ta, plotly, matplotlib, mplfinance, seaborn, random

2. **Installation**
   ```bash
   pip install pandas TA-Lib plotly matplotlib mplfinance seaborn

3. **Data Preparation**
   - Place your CSV files containing historical stock price data in the `data till 2023-1/` directory.

4. **Generated Indicators**
   - The code generates various technical indicators and adds them to the dataset.

5. **Visualization**
   - The script includes visualization code using `mplfinance`, `plotly`, and `matplotlib`. Sample visualizations include candlestick charts, moving averages, RSI distribution, correlation heatmap, and more.
   
## File Structure

- `data till 2023-1/`: Directory to store historical stock price CSV files.
- `HISTORICAL.ipynb`: Main notebook for Stock Price Analysis and Visualization with Pandas TA-Lib and Plotly and technical analysis.

## Visualizations

1. **Candlestick Chart**
   - Candlestick charts with and without indicators.
   - Moving averages plotted on candlestick charts.

2. **Technical Indicators Over Time**
   - Line plots showcasing RSI, MACD, SMA, and more.

3. **Correlation Heatmap**
   - Heatmap illustrating the correlation between different features.

4. **Moving Averages Comparison**
   - Line plot comparing various moving averages.

5. **RSI Over Time with Thresholds**
   - RSI values plotted over time with overbought and oversold thresholds.
  
## Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.
