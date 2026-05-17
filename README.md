# Crypto Price Tracker

Real-time cryptocurrency price monitoring tool with customizable alerts and data export.

## Features

- Real-time price tracking for BTC, ETH, and 50+ altcoins
- Support for Binance and Bitkub exchanges
- Price alerts via Discord and Telegram notifications
- Historical data export to CSV and JSON
- Built-in technical indicators (RSI, MACD, Bollinger Bands)
- Low-latency WebSocket connections for live data

## Tech Stack

- **Language:** Python 3.11+
- **APIs:** Binance API, Bitkub API
- **Data:** Pandas, NumPy
- **Notifications:** Discord Webhooks, Telegram Bot API
- **Storage:** SQLite / CSV export

## Installation

```bash
git clone https://github.com/kphrphsphs1-stack/crypto-price-tracker.git
cd crypto-price-tracker
pip install -r requirements.txt
cp .env.example .env
python main.py
```

## License

MIT License
