# 🎮 Polish Gamedev Stocks Data Analysis

This project analyzes Polish gaming companies listed on the Warsaw Stock Exchange (GPW), with a focus on correlations, portfolio optimization, and the impact of game releases on stock prices.

## 📊 **Project goals**
- Measure correlations between CD Projekt Red and other gamedev stocks.
- Build optimized portfolios that either:
  - minimize volatility, or
  - maximize the Sharpe ratio.
- Compare the results with the WIG-Games index.

## 🛠 **Methodology**
- Data preprocessing and cleaning (closing prices, dates).
- Correlation matrix and rolling correlation analysis.
- Portfolio optimization using mean-variance approach:
  - Minimum volatility portfolio.
  - Maximum Sharpe ratio portfolio.
- Cumulative return comparison vs. WIG-Games index (starting from 2022).

## 📈 **Key findings**
- Many gamedev stocks on GPW show moderate to high positive correlations.
- Optimized portfolios achieved similar or better risk-adjusted returns compared to WIG-Games.
- Correlations fluctuate over time, which partially limits diversification inside the sector.

## 🔮 **Possible extensions**
 Exploratory analysis of event impact.
- Event study: measuring the impact of game premieres on stock prices.
- Sentiment analysis: checking how news and reviews affect prices.
- Comparing trading volumes around key dates.
- Testing event-driven trading strategies.


## ✅ **Technologies**
- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Jupyter Notebook
- Optimization & financial statistics

---

## 📌 **Disclaimer**
This project is for educational purposes only. It does not constitute investment advice.
