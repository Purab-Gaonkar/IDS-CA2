# IDS-CA2

Stock price prediction plays a crucial role in financial markets, enabling investors to make informed decisions. Due to the volatile and complex nature of stock price movements, machine learning and deep learning models are widely employed for forecasting. This project aims to analyze historical stock prices and develop a predictive model to forecast future trends.
For this study, we used the Maruti Suzuki stock dataset. The dataset contains daily stock price data with attributes such as Open, High, Low, Close, and Volume, among others.
Various preprocessing techniques were applied to clean and prepare the data for analysis. These included handling missing values, removing duplicates, and scaling the data to ensure consistency.
To explore stock price trends, exploratory data analysis (EDA) was performed, including correlation analysis, statistical summaries, and visualizations to understand patterns and key insights.
Multiple models — including XGBoost, LSTM, Decision Tree, and Random Forest — were implemented to forecast stock prices. Their performances were evaluated using metrics such as Root Mean Square Error (RMSE) and R² score.
The results showed that the LSTM model provided the highest accuracy, effectively capturing long-term dependencies and complex patterns in the data, making it the most suitable model for stock price forecasting in this study.

Dataset Details
Dataset Name: Maruti Finance Stock Dataset
Source: NIFTY-50 Stock Market Data (2000 - 2021)
Attributes:
    Date – Trading date of the stock.
    Symbol – Stock ticker symbol (e.g., Maruti).
    Series – Type of stock series (e.g., EQ for equity, BE for trade-to-trade).
    Prev Close – Closing price of the stock on the previous trading day.
    Open – Stock price at the beginning of the trading session.
    High – Highest price reached during the trading session.
    Low – Lowest price recorded during the trading session.
    Last – Last traded price before market close.
    Close – Final stock price at the end of the trading session (chosen as the target variable for forecasting).
    VWAP (Volume Weighted Average Price) – Average price of the stock weighted by volume.
    Volume – Total number of shares traded on that day.
    Turnover – Total value of shares traded (calculated as Volume × Price).
    Trades – Total number of transactions executed.
    Deliverable Volume – Number of shares actually delivered to buyers.
   % Deliverable – Percentage of total volume that resulted in actual delivery of shares.
