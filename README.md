# Mutual-Fund-Analysis
Project Overview -
Nifty 50 Portfolio Analyzer: Analyze 50 Indian stocks, build sample portfolios, calculate Sharpe/Sortino ratios, and run Monte Carlo simulations to optimize risk-adjusted returns for investors.

📊 Key Features & Results
✅ 348 days of Nifty 50 data (50 stocks)
✅ Portfolio: 8.62% annual return, 15.17% volatility
✅ Sharpe Ratio: 0.44 | Sortino Ratio: 0.45
✅ Risk-return scatter plots + Monte Carlo sims

🚀 Quick Start
1. pip install pandas numpy matplotlib seaborn
2. Place nifty50closingprices.csv in data/
3. jupyter notebook Mutual_Fund_analysis.ipynb
4. Run all cells → Get portfolio insights!

📈 What It Does
Loads & Cleans: Nifty 50 daily prices (no missing data)
Calculates: Daily returns → Annualized metrics
Visualizes: Price trends, risk-return scatter
Portfolio: 5-stock equal-weight (20% each)
Risk Metrics: Sharpe (0.44), Sortino (0.45)
Future: Monte Carlo simulations ready

💡 Key Insights for Investors
Conservative: Add stable stocks (HDFCBANK, TCS)
Aggressive: Tilt toward high-return stocks (BAJAJ-AUTO)
Portfolio beats risk-free rate (2%) on Sharpe basis

🎯 Perfect For
Students: Portfolio theory + Python implementation
Retail Investors: Data-driven allocation decisions
Analysts: Risk-return framework template
