# Trading-Bot
Automates stock and cryptocurrency trading using RSI and EMA indicators with support for both live and simulated modes.

## Features
- Executes RSI/EMA-based entry/exit signals with configurable periods/thresholds
- Live trading via exchange APIs and paper/simulated trading for safe testing
- Real-time notifications: email + SMS (via carrier email-to-SMS gateways)
- Order flow: submits/cancels orders and logs fills; writes trade logs/PnL to CSV
- Ticker watchlist, rate-limited polling, and optional WebSocket price streaming

## Tech Stack
- **Language:** Python 3.13.4
- **APIs:** REST/WebSocket — Alpaca (stocks), Binance (crypto)
- **Libraries:** requests, websockets, python-dotenv, smtplib
- **Tools:** SMTP (alerts), scheduler/cron, Git/GitHub
