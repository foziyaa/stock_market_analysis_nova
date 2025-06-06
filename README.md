📈 Predicting Price Moves with News Sentiment 📰
Nova Financial Solutions – B5W1 Challenge

🌟 Overview
This project explores the relationship between financial news sentiment and stock price movements. Conducted as part of Nova Financial Solutions’ B5W1 challenge, the analysis combines Natural Language Processing (NLP), technical stock indicators, and statistical methods to determine whether sentiment can serve as a predictive signal.

Core Achievements:

Performed Exploratory Data Analysis (EDA) on financial news headlines.

Conducted quantitative stock analysis (CAGR, Sharpe Ratio, Beta).

Applied sentiment analysis to news headlines using TextBlob.

Ran correlation studies between sentiment and stock returns.

Developed insights and recommendations for potential strategy integration.

🎯 Business Objective
Nova aims to improve financial forecasting accuracy using data-driven insights. This project focused on:

Sentiment Analysis: Classify headline tone and assign scores.

Correlation Study: Explore relationships between sentiment and stock price changes.

Recommendations: Propose strategy ideas based on findings.

📁 Project Structure
bash
Copy
Edit
.
├── data/                   # News & stock data
├── notebooks/              # Jupyter analysis notebooks
├── reports/                # Interim and final reports
├── scripts/, src/, tests/  # (Optional) Code, modules, and unit tests
├── .gitignore, LICENSE, README.md, requirements.txt
🛠️ Tech Stack
Language: Python 3.11

Libraries: Pandas, NumPy, Matplotlib, Seaborn, TextBlob, NLTK, yfinance, TA-Lib

Tools: JupyterLab, VS Code, GitHub Actions

⚙️ Setup Instructions
bash
Copy
Edit
# 1. Clone the repo
git clone https://github.com/foziyaa/stock_market_analysis_nova.git
cd stock_market_analysis_nova

# 2. Create & activate a virtual environment
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt
🛠 TA-Lib Installation
TA-Lib requires system-level libraries:

Windows: Download wheel from Gohlke’s site

macOS: brew install ta-lib

Linux: sudo apt-get install libta-lib-dev

NLTK Setup (if needed)
python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('vader_lexicon')
