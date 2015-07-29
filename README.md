## AutoCoin - A MustWin LLC Hack Week Project
----
Automated Bitcoin Wallet Management backed by Trading Algorithms via Coinbase Wallet and Exchange API

####Features
- Realtime Data Streaming of Bitcoin Transactions for your wallets and other wallets in the block chain
- Realtime Market Data from Coinbase Exchange
- View orders being executed by the system. Interviene and stop future orders at any moment
- Choose between various algorithms on Risk/Reward Scaling

###To Do:
-----

- Collect Bitcoin Market Data and create some baseline charts
- Build a simple moving average algorithm (rather than my shitty reversal threshold algo) that actually uses technical analysis
- Possibly Implement a Support Vector Machine (via PyBrain? sitting on a rest API), that makes decisons for us rather than regular mathematical functions
  - I've heard it being used in various algorithmic trading applications, but moar research is needed :p
  - Implement a failsafe protocol that automagically cancels all open orders + option to liquify all bitcoins in case of error or market crash to user choice of currency 
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
- Some Legal Stuff
  - Basic stuff like "Hey you're giving us control of your wallet to do buying and selling of bitcoins, just so you know"
  - 
 
###Some Notes
------

- Stack
  - Node.JS + Express + _AngularJS?_ (or maybe just scratch it and go full Mean.io)
  - easy use of the CoinBase Exchange API + Sockets.IO
- Integrations
  - CoinBase Wallet API + Oauth
  - Coinbase Exchange API
  - ChangeTip Oauth (only really be able to use the bitcoin wallet address)
- Marketing
  - Could probably gain traction from press: "CODE2040 Alumni & MustWin Employee creates Automated Bitcoin Wallet Management"
  - all this talk about "FUND MORE BLACK/LATINO ENTREPRENEURS"....well MW LLC did it :p
  - Also CODE2040 is super cuddly with Andreeseen Horowitz, Google Ventures, and other investors (potential there? maybe, idk, don't think we need their capital atm)
  - Have some undergrad friends doing AI development back at my home institution (we could give them internships/grant to help develop the algorithm with us)
    - Also two of my old AI Proffessors (Marie desJardins and Tim Oates) would be super down to help me out.
    - that way we can focus on development and intergration, they can build a backend service, we REST-ify it (or embedded it), and boom-pow-skadoosh
- Legal
  - whatever that is :p
- Sales
  - we take 2% of all successful transactions