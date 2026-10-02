# 📈 Python Stock Analyzer

A lightweight, interactive Python tool that fetches real-time financial data and historical stock prices to visualize market trends and moving averages. 

## 🚀 Key Features
* **Real-Time Data Extraction:** Instantly retrieves the current stock price and company name for any valid ticker symbol.
* **Historical Trend Analysis:** Downloads daily historical market data directly from Yahoo Finance.
* **Technical Indicators:** Automatically calculates and overlays 7-day and 30-day Moving Averages (MA) to help identify price momentum.
* **Interactive Visualization:** Generates clean, easy-to-read line charts comparing daily closing prices against moving averages.
* **Continuous CLI Loop:** Allows users to query multiple stocks in a single terminal session without restarting the program.

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **[yfinance](https://pypi.org/project/yfinance/):** Core library for querying the Yahoo Finance API.
* **[Pandas](https://pandas.pydata.org/) & [NumPy](https://numpy.org/):** Data manipulation and rolling window calculations.
* **[Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/):** Data visualization and plotting.

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/stock-analyzer.git](https://github.com/yourusername/stock-analyzer.git)
   cd stock-analyzer
