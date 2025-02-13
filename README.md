# popular_crypto_trading_strategies_and_backtesting_methods
In this project, we demonstrate several popular crypto trading strategies and backtesting methods.

Basically, we:

•	Developed a cryptocurrency trading strategy using Python and the CoinGecko API to backtest its effectiveness against historical Ethereum price data over a one-year period.

•	Utilized technical indicators such as Simple Moving Average (SMA), Bollinger Bands, and RSI to identify trading opportunities.

•	Implemented a trend-following strategy based on SMA crossovers, generating buy and sell signals.

•	Evaluated the trading strategy's performance by calculating key metrics like Sharpe Ratio, Max Drawdown, and Win Rate.

•	Visualized the strategy's equity curve using Matplotlib to understand its cumulative returns and risk profile.

•	Extracted, cleaned, and manipulated historical price data from the CoinGecko API using Pandas.

•	Demonstrated proficiency in data analysis, visualization, and financial modeling using Python libraries such as NumPy, Pandas, and Matplotlib.

•	Developed and backtested a trading strategy using concepts in Technical Analysis.

Installing Dependencies from requirements.txt

Follow these steps to install the required Python dependencies on your system.

✅ Prerequisites:

•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version

📌 Installation Instructions

🖥️ Windows:

1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt

🍏 macOS & 🐧 Linux:

1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt

🔍 Additional Tips:

•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit

# Windows (CMD)

venv\Scripts\activate

# Windows (PowerShell)

venv\Scripts\Activate.ps1

# macOS/Linux

source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt

•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt

🛠️ Verifying Installation:

Run:
sh
CopyEdit
pip list
to check if all packages are installed.
