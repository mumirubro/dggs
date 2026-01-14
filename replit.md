# Telegram Bot Project

## Overview
This is a Telegram bot application with multiple features including payment gateway checkers (Stripe, Shopify, Braintree, PayPal), account checkers (Crunchyroll, Netflix, Spotify, Microsoft), and various utility tools.

## Project Structure
- `main.py` - Main bot entry point
- `access_control.py` - User access control and premium management
- `gates/` - Payment gateway checker modules
  - `stripe/` - Stripe payment checker
  - `shopify/` - Shopify payment checker
  - `braintree/` - Braintree payment checker
  - `paypal/` - PayPal payment checker
- `acc gates/` - Account checker modules
  - `crunchyroll/` - Crunchyroll account checker
  - `netflix/` - Netflix account checker
  - `spotify/` - Spotify account checker
  - `microsoft/` - Microsoft/Hotmail account checker
- `tools/` - Utility tools
  - `faker/` - Fake identity generator
  - `proxy_checker.py` - Proxy validation tool
  - `site gate chk/` - Site gate analyzer
  - `sk chk/` - Stripe SK key checker

## Setup

### Required Environment Variable
- `BOT_TOKEN` - Your Telegram Bot Token (get from @BotFather on Telegram)

### Running the Bot
The bot runs as a console application:
```bash
python main.py
```

## Recent Changes
- 2026-01-14: Fixed circular import in gates/braintree/bot.py
- 2026-01-14: Configured workflow for Replit environment
