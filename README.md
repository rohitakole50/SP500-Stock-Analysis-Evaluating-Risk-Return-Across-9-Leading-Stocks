# 📈 S&P 500 Sector-Based Stock Selection & Risk Analysis

This project explores risk-optimized stock selection from the S&P 500 by identifying top-performing stocks across diverse sectors. The analysis emphasizes consistent return potential, inter-sector diversification, and volatility management using Python and financial data from Yahoo Finance.

---

## 🔍 Project Overview

The goal was to simulate a long-term, diversified investment strategy by:

- Analyzing S&P 500 stock performance over time.
- Identifying stable stocks across different sectors.
- Visualizing and evaluating average returns and volatility.
- Selecting 9 stocks from 3 distinct sectors for portfolio consideration.

---

## 🏗️ Key Components

### 1. Data Extraction

- Pulled daily historical stock data using `yfinance`.
- Filtered stocks from the S&P 500 across multiple sectors.
- Used adjusted closing prices for return calculations.

### 2. Performance Metrics

- Computed daily percentage change for each stock.
- Aggregated to find **mean daily return**.
- Selected top 3 stocks from each of the 3 best-performing sectors.

### 3. Chosen Sectors & Stocks

| Sector       | Selected Tickers         |
|--------------|--------------------------|
| Utilities    | NRG, AES, NEE            |
| Health Care  | DXCM, PODD, MOH          |
| Real Estate  | CSGP, CBRE, SBAC         |

These stocks were chosen based on their consistently positive mean percentage change over the observation period.

### 4. Visualization

- Created sector-wise bar plots to compare performance.
- Displayed stock selection metrics using formatted data tables.
- Provided clarity on diversification logic.

---

## 📊 Tools Used

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`, `webscraping`, `API`
- **Jupyter Notebook** for development and exploratory analysis

---

## 💡 Key Takeaways

- Diversifying across sectors improves long-term risk mitigation.
- Utilities and Health Care sectors showed the most stable returns.
- Stocks with high mean daily return and low variance offer attractive options for conservative investors.

---

## 📁 Repository Contents

- `Investing_in_Stocks_(Fall_2024).ipynb`: Full Jupyter notebook
- `README.md`: Project documentation
- Sector & ticker selection plots and analysis

---

## 🔗 Future Enhancements

- Incorporate volatility and Sharpe Ratio for improved selection.
- Add sector correlation heatmap to visualize interdependencies.
- Extend to include macroeconomic indicators for smarter forecasting.

---

## 🧠 Author

**Rohit Akole**  
MSBAPM Student – University of Connecticut  
[Portfolio Website](http://rohitakole50.github.io)
