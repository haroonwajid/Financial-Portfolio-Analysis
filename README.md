# Financial-Portfolio-Analysis

## Overview
This Jupyter Notebook provides a comprehensive analysis of a stock portfolio using historical stock data. The analysis includes data retrieval, portfolio optimization, and performance evaluation metrics such as annualized return, Value at Risk (VaR), and Expected Shortfall (ES).

## Contents
1. **Data Import and Preparation**
   - Import necessary libraries (e.g., `pandas`, `numpy`, `yfinance`, `matplotlib`).
   - Load stock data from a JSON file.

2. **Stock Data Retrieval**
   - Fetch historical stock prices using the `yfinance` library.
   - Handle exceptions for any tickers that fail to retrieve data.

3. **Portfolio Optimization**
   - Calculate the Global Minimum Variance (GMV) portfolio weights.
   - Calculate the Maximum Sharpe Ratio portfolio weights.

4. **Performance Evaluation**
   - Calculate annualized returns for the portfolios.
   - Compute Value at Risk (VaR) and Expected Shortfall (ES) for risk assessment.

5. **Visualization**
   - Plot the portfolio weights over time for both GMV and Maximum Sharpe portfolios.
   - Display a summary table of average weights and standard deviations for both portfolios.

6. **Cumulative Returns Comparison**
   - Compare cumulative returns of the GMV portfolio against actual returns over specified periods.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries:
  - `pandas`
  - `numpy`
  - `yfinance`
  - `matplotlib`
  - `scipy`

## Usage
1. Clone the repository or download the notebook.
2. Ensure all required libraries are installed in your Python environment.
3. Open the notebook in Jupyter and run the cells sequentially to perform the analysis.

## Notes
- The notebook assumes that the stock data is available in a JSON format at the specified path.
- Adjust the date ranges and tickers as necessary for your analysis.
- Ensure you have an active internet connection for fetching stock data using `yfinance`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
