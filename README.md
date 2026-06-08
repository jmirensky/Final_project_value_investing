#  📈 Value Investing Engine


## 🎯 Overview

This Python project combines company fundamentals and market data to evaluate investment opportunities.

The model analyzes selected S&P 500 companies, calculates key financial metrics, builds a four-factor scoring system, ranks companies annually, and exports the results to Tableau for visualization.



## 🧮 Methodology

### 1. Financial Analysis

Financial statements are extracted from Yahoo Finance and transformed into key investment metrics:

- ROE
- ROIC
- Operating Margin
- Current Ratio
- Debt-to-Equity
- FCF Yield
- EV/EBITDA
- P/E Ratio
- FCF Margin
- Revenue Growth
- EPS Growth

### 📊 2. Four-Factor Model

Companies are scored across four dimensions:

- Quality
- Financial Health
- Valuation
- Cash Generation & Growth

### 🏆 3. Ranking

Percentile-based scores are combined into an overall Investment Score and annual ranking.

Investment signals:

- BUY ['investment_score' >= 0.65 ]
- HOLD  ['investment_score'] between range [ 0.55 - 0.65 ) ]
- AVOID  ['investment_score'  < 0.55 ]

### 📈 4. Market Comparison

Prices are compared with market behavior using:

- Daily Prices
- 200-Day Moving Average (MA200)
- Relative Performance vs S&P 500

### 5. Visualization

Final datasets are exported to Tableau for dashboard creation.



## 🛠️ Tools

- Python
- Pandas
- NumPy
- yFinance
- Matplotlib
- Tableau



## ⚠️ Disclaimer

This project is intended for educational and portfolio purposes only and should not be considered investment advice.


## ✍️ Author

Julieta Mirensky

LinkedIn: https://www.linkedin.com/in/jmirensky/

GitHub: https://github.com/jmirensky

