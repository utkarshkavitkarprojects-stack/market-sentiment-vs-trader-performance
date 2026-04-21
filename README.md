# 📊  Market Sentiment vs Trader Performance
🧠 Overview

This project explores how market sentiment influences trader performance in the crypto market.

The goal is to move beyond surface-level analysis and understand:

How traders behave under different market conditions (Fear, Greed, Neutral)
Whether sentiment-driven behavior impacts profitability
What patterns can be used to improve trading decisions
🎯 Objective

The objective of this analysis is to understand the relationship between market sentiment and trader performance, uncover hidden behavioral patterns, and derive insights that can support smarter trading strategies.

📂 Dataset

Due to size constraints, the dataset is hosted externally.

🔗 Dataset Link:
https://drive.google.com/file/d/1gcNLnlbLGcVHzmEwkoCjgN0m7oGvNZFQ/view?usp=sharing](https://drive.google.com/drive/folders/1wopsO7l39s_5OmF2qazioTnt_PRXx13f?usp=drive_link

🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Google Colab

🔍 Approach

Before starting the analysis, key questions were framed around:

Impact of market sentiment on profitability
Role of trade size in gains/losses
Distribution of winning vs losing trades
Performance of Long vs Short positions
Combined effect of sentiment, position, and capital

The analysis was then carried out through:

Data Cleaning & Preprocessing
Feature Engineering (pnl_ratio, pnl_flag, position_type)
Exploratory Data Analysis (EDA)
Visualization & Insight Extraction

📈 Key Insights

Fear-driven markets are the most profitable, both in terms of total PnL and efficiency
Greed phases lead to poor performance, with lower returns and even negative efficiency
Long positions consistently outperform Short positions, indicating a strong directional bias
Short trades are highly sentiment-dependent, failing significantly during bullish conditions
Traders exhibit reactive behavior, often following sentiment instead of predicting it
Higher capital allocation during Fear suggests a buy-the-dip strategy

⚖️ Trading Insights & Strategy Implications

Focus on trading during Fear phases where opportunities are strongest
Avoid or limit exposure during Greed phases
Prefer Long positions for consistent performance
Use Short positions selectively, aligned with sentiment
Prioritize risk management over win rate

📁 Project Structure
.
├── notebooks/
│   └── Market_Sentiment_&_Trading_Performance.ipynb
├── README.md

🚀 How to Run

Open the notebook in Google Colab
Ensure dataset access (Drive link provided above)
Run all cells
💡 Conclusion

This project demonstrates that trader performance is strongly influenced by market sentiment and behavioral biases.

By incorporating sentiment-aware strategies and disciplined decision-making, traders can significantly improve performance and reduce risk.
