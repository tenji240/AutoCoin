## AutoCoin - A MustWin LLC Hack Week Project
----

- Automated Bitcoin Wallet Management backed by Trading Algorithms via Coinbase Wallet and Exchange API
- Realtime Data Streaming of Bitcoin Transactions for your wallets and other wallets in the block chain
- Realtime Market Data from Coinbase Exchange
- View orders being executed by the system. Interviene and stop future orders at any moment
- Choose between various algorithms on Risk/Reward Scaling

###To Do:
-----

- Collect Bitcoin Market Data and create some baseline charts
- Build a simple moving average algorithm (rather than my shitty reversal threshold algo) that actually uses technical analysis
- Possibly Implement a Support Vector Machine (via PyBrain? sitting on a rest API), that makes decisons for us rather than regular mathematical functions
- Enable CoinBase Wallet OAuth Authentication and Support
- Enable CoinBase Exchange API and WebSockets for data streaming (keep hearing Socket.io)
- Some REAL Market Data Research, Haven't heard too much in the field of hey, what's going on
- Build a simple dashbaord that shows: 
  - recent wallet transactions (including status of transaction and such)
  - Current Wallet Balance (total balance + multi-wallet breakdown
  - Chart of current Bitcoin Prices in the BTC-USD Index
  - _maybe_ add support for BTC-GBP or BTC-EU
- Build a user page that shows: 
  - user balance and balance breakdown 
  - projected algorithm results (based on instant trades) and actual results
  - other possible algorithm results?
- Look into the legal stuff of managing Bitcoin (seems pretty free at the moment, not much gov reg)
- It'd be cool if all we did was manage buying and selling, and let CoinBase handle the rest
 
