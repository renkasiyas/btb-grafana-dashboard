# btb-grafana-dashboard

![btb-grafana-dashboard screenshot](screencapture.png)

Grafana dashboard for [Binance Trade Bot](https://github.com/MasaiasuOse/binance-trade-bot).

## Installation

**Prerequisites**: Docker and docker-compose.

In `docker-compose.yml`:
- In the first part of line 11, replace `./example_database.db` for the relative path of your BTB database. Example: `../binance-trade-bot/data/crypto_trading.db:/app/crypto_trading.db`.
- In line 17 and 18 change credentials.

Run `docker-compose up -d` and go to [127.0.0.1:42069](127.0.0.1:42069) in your browser.