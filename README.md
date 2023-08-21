# My Python Trading Bot for Cryptocurrencies


## Introduction

Welcome to my Python trading bot for cryptocurrencies! As a crypto enthusiast, I've always been fascinated by the potential of
high-frequency trading in the dynamic and volatile world of cryptocurrency markets. This trading bot leverages the power of Python 
and some popular libraries to implement trading strategies based on Bollinger Bands and Double Bottom patterns.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Trading Techniques](#trading-techniques)
- [Disclaimer](#disclaimer)
- [Contact](#contact)

## Prerequisites

Before you can use this trading bot, make sure you have the following prerequisites:

1. **Binance Account**: You'll need a Binance account to access the Binance API. If you don't have an account, you can sign up at [Binance](https://www.binance.com/).

2. **API Keys**: Generate an API key and secret key from your Binance account. Keep these keys safe and secure. Dont code it directly, for safety keep it in a seperate file 
and read it into the file you are programming in.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-trading-bot.git
   ```

2. Install the required libraries using `pip`:

   ```bash
   pip install pandas
   pip install python-binance
   pip install plotly
   ```

## Usage

1. Replace the placeholders in `binance_keys.py` with your actual API key and secret key.

2. Run the trading bot script:

   ```bash
   python trading_bot.py
   ```

## Trading Techniques

### Bollinger Bands Strategy

The Bollinger Bands strategy involves using the standard deviation of price to create an envelope around a moving average. The goal is to identify potential buy or sell signals based on price movement within the bands.

### Double Bottom Pattern

The Double Bottom pattern is a bullish reversal pattern that signals a potential upward price movement. It occurs when a downtrend is followed by two consecutive troughs at roughly the same price level.

## Disclaimer

Please note that cryptocurrency trading involves a significant level of risk, and past performance is not indicative of future results. This trading bot and the strategies mentioned are for educational and informational purposes only. Use the bot at your own risk, and make informed decisions based on thorough research.

## Contact

If you have any questions, suggestions, or just want to discuss cryptocurrency trading and technology, feel free to reach out.

Happy trading and may the markets be ever in your favor!

---

*Disclaimer: This trading bot and strategies are not financial advice. Use at your own risk. Always do your own research and consult with professionals before making investment decisions.*
