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

Install the required dependencies:

pip install yfinance pandas numpy matplotlib seaborn


If you are running the exported Python script, simply execute it from your terminal. If you are using Jupyter, run all cells in the notebook.


💻 Usage
If you are running the exported Python script, simply execute it from your terminal. If you are using Jupyter, run all cells in the notebook.

python stock_analyzer.py


Example Terminal Interaction:

Plaintext

======== complete stock analyzer ===
Enter the stock symbol (or Q to Quit): NVDA

 ==============
 Company :NVIDIA Corporation
 Current Price: 210.96

==================

The program will then display a pop-up line chart showing the closing price along with the 7-day and 30-day moving averages.

🔮 Future Improvements
Refactor the hardcoded date ranges to allow dynamic, user-defined timeframes (e.g., "last 6 months" or "YTD").

Add additional technical indicators like RSI (Relative Strength Index) or MACD.

Convert the command-line interface into an interactive web dashboard using Streamlit.


```markdown
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

```

2. **Install the required dependencies:**
```bash
pip install yfinance pandas numpy matplotlib seaborn

```



## 💻 Usage

If you are running the exported Python script, simply execute it from your terminal. If you are using Jupyter, run all cells in the notebook.

```bash
python stock_analyzer.py

```

**Example Terminal Interaction:**

```text
======== complete stock analyzer ===
Enter the stock symbol (or Q to Quit): NVDA

 ==============
 Company :NVIDIA Corporation
 Current Price: 210.96

==================

```

*The program will then display a pop-up line chart showing the closing price along with the 7-day and 30-day moving averages.*

## 🔮 Future Improvements

* Refactor the hardcoded date ranges to allow dynamic, user-defined timeframes (e.g., "last 6 months" or "YTD").
* Add additional technical indicators like RSI (Relative Strength Index) or MACD.
* Convert the command-line interface into an interactive web dashboard using **Streamlit**.

```

<FollowUp label="Want to refactor the code before uploading?" query="Can you help me rewrite this script to fix the hardcoded dates and organize it into clean functions before I put it on GitHub?"/>

```








