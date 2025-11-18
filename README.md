# Epicure VPN

Epicure VPN-Telegram-boot for managing the VPN subscriptions via Marzban API. Supports the payment of Yoomoney, maintains user database in PostgreSQL and operates on Aiogram.

<img src="images/example-image.png" alt="Example Image" width="300">

## Features

- User registration  
- Subscription status check  
- Yoomoney payment handling  
- Xray client link generation via Marzban API  
- Localization support

## Installation and Run

```bash
git clone https://github.com/mordvn/epicure-vpn.git
cd epicure-vpn
```

Create`.env` file (see `.env.example`) 

## Deployment using UV

```bash
uv sync
uv run python3 app/main.py
```

## Deployment using Docker

```bash
docker build -t epicure-vpn .
docker run --env-file .env epicure-vpn
```

## License

MIT License
