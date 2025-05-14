# Data Folder Description

This folder documents the datasets used in this assignment.


---

## Dataset 1: Bitcoin Market Sentiment (Fear & Greed Index)
- **Filename:** fear_greed_index.csv
- **Description:** Contains daily market sentiment for Bitcoin, reflecting emotional indicators like fear or greed.

- **Columns:**
  - `timestamp`: Unix timestamp of the sentiment reading.
  - `value`: Numeric score representing sentiment (0 = Extreme Fear, 100 = Extreme Greed).
  - `classification`: Categorical label of sentiment (e.g., Fear, Greed, Neutral, etc.).
  - `date`: Human-readable date (format: YYYY-MM-DD).

---

## Dataset 2: Historical Trader Data (from Hyperliquid Exchange)
- **Filename:** historical_data.csv
- **Description:** Detailed record of trades executed by multiple accounts, capturing trade activity, size, profit/loss, and timing.

- **Columns:**
  - `Account`: Anonymized unique ID of the trading account.
  - `Coin`: The cryptocurrency traded (e.g., BTC, ETH).
  - `Execution Price`: The price at which the trade was executed.
  - `Size Tokens`: Number of tokens involved in the trade.
  - `Size USD`: Total USD value of the trade.
  - `Side`: Buy or Sell.
  - `Timestamp IST`: Trade timestamp in Indian Standard Time.
  - `Start Position`: Trader's position size before this trade.
  - `Direction`: Indicates opening/closing of a trade.
  - `Closed PnL`: Realized profit or loss from the closed position.
  - `Transaction Hash`: Unique hash of the transaction.
  - `Order ID`: Unique order identifier.
  - `Crossed`: Whether the order was a maker or taker (true/false).
  - `Fee`: Fee paid for executing the trade.
  - `Trade ID`: Unique identifier for the trade.
  - `Timestamp`: UTC timestamp of the trade.

---



