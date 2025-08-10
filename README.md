# Trader Performance vs. Bitcoin Market Sentiment

## 📌 Overview
This project analyzes the relationship between **Hyperliquid trader performance** and the **Bitcoin Fear & Greed Index** to uncover patterns in PnL, win rate, and leverage usage under different market sentiment conditions.

The analysis aims to provide **data-driven insights** for smarter crypto trading strategies.

---

## 📂 Datasets
1. **Historical Trader Data (Hyperliquid)**
   - Includes account details, trading pairs, execution prices, sizes, sides, timestamps, leverage, closedPnL, etc.

2. **Bitcoin Fear & Greed Index**
   - Daily sentiment classification: `Extreme Fear`, `Fear`, `Neutral`, `Greed`, `Extreme Greed`.

---

## 📊 Analysis Performed
- Merged historical trading data with market sentiment labels.
- Calculated:
  - **PnL Mean, Median, Total, Std**
  - **Win Rate**
  - **Trade Volume**
  - **PnL Sharpe Ratio**
- Identified **top 5% trades** contributing most to PnL by sentiment.
- Created **visualizations** for PnL & win rate distribution.

---

## 📈 Key Findings
- Trader performance varies significantly across market sentiment phases.
- High leverage trades show different win rates in `Fear` vs. `Greed` conditions.
- Top 5% trades often account for a disproportionately large share of total profits.

---

## 📷 Visualizations
- **PnL & Win Rate by Sentiment × Leverage**
- **Top Trade Contribution by Sentiment**

---

## 📁 Project Structure
- ├── trader_sentiment_analysis.ipynb # Main analysis notebook
- ├── outputs/
- │ ├── pnl_summary.csv # Summary stats
- │ ├── top5_contrib.csv # Top trade contribution
- │ ├── charts/ # Generated plots
- ├── trader_sentiment_analysis_report.pdf # PDF report
- └── README.md

---

## 🚀 How to Run
1. Open the notebook in Google Colab:
   
   https://colab.research.google.com/github/<username>/<repo>/blob/main/trader_sentiment_analysis.ipynb
   
Install required dependencies:
- pip install pandas matplotlib
- Run all cells to reproduce results.

---
 
### 📬 Submission Details
This analysis was prepared for the "Junior Data Scientist – Trader Behavior Insights" hiring challenge.

### 🏷 Tags
crypto trading data-analysis bitcoin fear-greed-index hyperliquid pnl leverage visualization

### Google Derive - 
https://drive.google.com/drive/folders/1LLyQEcG8mBfWG8OMakWoRrguf42Hwqby?usp=drive_link

## Google Colab - Code file
https://colab.research.google.com/drive/1aAUVOdEmOQfE0O7dn7tbS5qZG6U7ext1?usp=drive_link
