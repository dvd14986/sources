# Telegram Tag All Group Members Bot

This Telegram bot, built with Telethon, enables you to retrieve the list of all usernames in a Telegram group chat. When the `/all` command is issued, the bot responds with messages listing the usernames of all members in the group. If the list exceeds the maximum message length allowed by Telegram, it's split into multiple messages.

## Features

- Responds to `/all` command in group chats.
- Lists all member usernames in the group chat.
- Handles Telegram's message length limitation by splitting long lists into multiple messages.

## Setup

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Environment Variables**
   Create a `.env` file in the root directory with the following contents:
   ```plaintext
   API_ID=your_api_id_here
   API_HASH=your_api_hash_here
   TELEGRAM_BOT_TOKEN=your_bot_token_here
   ```
   Replace `your_api_id_here`, `your_api_hash_here`, and `your_bot_token_here` with your actual API ID, API Hash, and Telegram Bot Token.

## Running the Bot

After setting up, you can run the bot using:

```bash
python minnabot.py
```

This will start the bot, and it will listen for the `/all` command in group chats where it is a member.


## Disclaimer

This bot must be used in compliance with Telegram's Terms of Service and Privacy Policies. Ensure you have the necessary permissions in any groups where you deploy this bot.

## Acknowledgments

Thanks GPT for assistance in generating code and documentation for this project.