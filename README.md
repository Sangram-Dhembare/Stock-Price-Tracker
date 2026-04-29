📈 Stock Price Tracker
A Python-based data visualization tool that fetches real-time market data and generates interactive price trend charts. Built to demonstrate API integration, data handling with Pandas, and visualization with Matplotlib.

🚀 Features
Real-time Data: Fetches the latest stock prices using the Yahoo Finance API.

Interactive Charts: Generates clean, readable line graphs of price history.

Customizable: Supports any stock ticker (AAPL, TSLA, NVDA) and even cryptocurrencies (BTC-USD).

Colab Ready: Optimized to run in Google Colab or local environments.

🛠️ Tech Stack
Python 3.x

yfinance: For financial data extraction.

Matplotlib: For data visualization.

Pandas: For data structuring and analysis.

📦 Installation & Usage
Option 1: Running in Google Colab (Recommended)
Open Google Colab.

Upload the Stock_Price_Tracker.ipynb file.

Run the first cell to install dependencies:

Bash
!pip install yfinance matplotlib
Run the main code cell and enter a ticker symbol when prompted.

Option 2: Local Setup
Clone this repository:

Bash
git clone https://github.com/YOUR_USERNAME/Stock-Tracker.git
Install dependencies:

Bash
pip install yfinance matplotlib pandas
Run the script:

Bash
python stock_tracker.py
📊 Sample Output
When you run the script and enter AAPL, the program generates a visualization similar to this:

Note: The graph displays the Date on the X-axis and the Adjusted Closing Price on the Y-axis.

📝 Future Improvements
[ ] Add a feature to compare two stocks side-by-side.

[ ] Implement a technical indicator like the Moving Average (SMA).

[ ] Export the final graph as a PNG or PDF automatically.
