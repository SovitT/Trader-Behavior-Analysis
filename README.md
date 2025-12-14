# Trader-Behavior-Analysis

Trader Behavior Analysis Under Market Sentiment (Fear vs Greed)
📌 Project Overview

This project explores how market sentiment (Fear vs Greed) influences trader behavior in the cryptocurrency market.
Using historical trader data and the Bitcoin Fear & Greed Index, the analysis focuses on identifying behavioral patterns and hidden signals that can support smarter trading strategies.

The work is primarily EDA-driven, with insights derived through visual analysis rather than predictive modeling.

📂 Dataset Description
1. Bitcoin Market Sentiment Dataset

Source: Fear & Greed Index

Key Columns:

date: Calendar date

classification: Market sentiment (Fear, Greed, Extreme Fear, Extreme Greed)

2. Historical Trader Data (Hyperliquid)

Key Columns (subset used):

account

symbol

side (buy / sell)

size (trade size)

time / timestamp-related column

Note: The dataset does not contain explicit realized PnL or leverage fields.

🎯 Objective

Analyze how trader behavior—activity level, position sizing, and trade direction—aligns or diverges from overall market sentiment (Fear vs Greed), and identify hidden behavioral signals that could influence smarter trading strategies.

🧠 Key Analysis Performed

Market sentiment distribution (Fear vs Greed)

Trading activity trends over time

Trade size distribution under different sentiment regimes

Buy vs Sell behavior during Fear and Greed periods

Behavioral signal summarization

All analysis is supported using visualizations (EDA).

📊 Key Insights

Trading activity increases significantly during greed phases.

Traders take larger and more aggressive positions when sentiment is positive.

Fear periods show reduced activity and higher selling pressure.

Market sentiment reliably reflects collective trader psychology.

Even without profitability or leverage data, sentiment provides actionable behavioral signals.

📁 Project Structure
ds_sovit/
├── notebook_1.ipynb        # Complete EDA and analysis (Google Colab)
├── csv_files/
│   └── behavioral_signals_summary.csv
├── outputs/
│   ├── sentiment_distribution.png
│   ├── trade_size_boxplot.png
│   ├── trading_activity_over_time.png
│   ├── buy_sell_by_sentiment.png
├── ds_report.pdf           # Final summarized insights
└── README.md               # Project documentation

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

▶️ How to Run

Open notebook_1.ipynb in Google Colab

Upload the provided CSV datasets

Run cells sequentially from top to bottom

Generated charts will be saved automatically in the outputs/ folder

📝 Notes

Profitability and leverage analysis were skipped due to missing fields in the dataset.

All conclusions are data-driven and visualization-based.

The project strictly follows the submission structure guidelines.

✅ Conclusion

This analysis demonstrates that market sentiment is a strong behavioral indicator.
Fear and Greed phases influence trader participation, position sizing, and trade direction, making sentiment-aware analysis valuable for improving trading decision frameworks.
