# BLDX TON Miner Telegram Bot

A Telegram bot for BLDX TON Mining platform.

## Deployment Instructions

### Local Development
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the bot:
   ```bash
   python bot.py
   ```

### Deploying to Render

1. Create a Render account at https://render.com

2. Fork or upload this repository to your GitHub account

3. In Render Dashboard:
   - Click "New +"
   - Select "Web Service"
   - Connect your GitHub repository
   - Choose the repository with your bot code

4. Configure the service:
   - Name: `bldx-ton-miner-bot` (or any name you prefer)
   - Environment: `Python`
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python bot.py`
   - Select the Free plan

5. Click "Create Web Service"

The bot will automatically deploy and start running. You can monitor the deployment and logs in the Render dashboard.

### Environment Variables
- `TELEGRAM_TOKEN`: Already configured in bot.py (7545746171:AAFsI8zRnrs0_INPxO6eFrCHKkukAs9FRmM)

## Features
- Welcome message with images
- Interactive buttons for mining and community
- Automatic response to /start command
# newbot
