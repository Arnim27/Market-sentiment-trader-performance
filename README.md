Trader Behavior Insights: Market Sentiment & Performance:- This project explores how Bitcoin market sentiment (Fear & Greed Index) impacts trader performance using historical trade data from the Hyperliquid platform. The goal is to identify behavioral patterns and derive insights that can support sentiment-aware trading strategies.

Project Structure
├── assignment part 1 - Exploratory Data Analysis.ipynb
├── assignment part 2 - Model developement.ipynb
├── assignment part 3 - Trading Strategy and Impact.ipynb
└── README.md
Part 1 – EDA: Data cleaning, missing value analysis, and sentiment vs profitability exploration
Part 2 – Model Development: Predicting trade profitability using market sentiment and trade features
Part 3 – Strategy & Impact: Translating insights into sentiment-aware trading implications

Datasets Used:
Bitcoin Fear & Greed Index: Daily market sentiment classified as Fear or Greed
Hyperliquid Historical Trades: Trade-level data including size, direction, timestamps, and realized PnL

Approach:- Market sentiment was aligned with intraday trades using time-aware merging. Trades were labeled as profitable or unprofitable based on closed PnL. Categorical variables were encoded, and missing sentiment values were treated as neutral to preserve data coverage. A Random Forest model was used to capture non-linear relationships between sentiment, trade characteristics, and profitability.

Key Insights:-
Trades executed during Greed sentiment show a higher probability of profitability
Market sentiment acts as a meaningful contextual signal rather than a standalone predictor
Trade size and positioning interact with sentiment to influence outcomes

Trading Implications:- Sentiment can be used as a risk filter in trading systems. Conservative positioning during Fear regimes and selective participation during Greed regimes may improve overall performance without increasing model complexity.

