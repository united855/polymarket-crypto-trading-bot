# Trading bots

This directory contains **three** standalone Polymarket crypto **Up / Down** bots. Each has its own `README.md`, `requirements.txt`, and configuration (`.env` / `config.json` / `config.env`).

| Bot | Folder | Summary |
|-----|--------|---------|
| **PTB** (price-to-beat, diff, probability) | [`5min-15min-PTB-bot/`](5min-15min-PTB-bot/README.md) | BTC **5m/15m**; PTB vs spot rules, optional web dashboard (`polymarket_auto_trade.py`). |
| **BTC VWAP / momentum** | [`btc-binary-VWAP-Momentum-bot/`](btc-binary-VWAP-Momentum-bot/README.md) | BTC **5m/15m**; VWAP, deviation, momentum on the favorite; Rich terminal UI. |
| **Meridian** (multi-asset, late entry) | [`up-down-spread-bot/`](up-down-spread-bot/README.md) | BTC, ETH, SOL, XRP **5m/15m**; Late Entry V3, stop-loss / flip-stop; see also [`up-down-spread-bot/docs/README.md`](up-down-spread-bot/docs/README.md). |

**Suite overview, risk, and licensing:** [Repository README](../README.md)

Clone the repo, `cd` into one of the folders above, create a venv, `pip install -r requirements.txt`, then follow that bot’s README.
