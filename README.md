# Python Telegram Bot

This is a simple Telegram bot built with Python using the **python-telegram-bot** library.
The bot can respond to basic commands and messages and works in both private chats and groups.

## Features

* `/start` command greeting
* `/help` command
* Custom command support
* Message response system
* Works in group chats when mentioned
* Basic text processing

## How It Works

The bot listens for messages and commands, processes the text, and sends a reply based on predefined conditions.

Example responses:

* "hello" → Bot replies with a greeting
* "how are you" → Bot replies with a status message
* Unknown text → Bot replies that it doesn't understand

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Install dependencies

```bash
pip install python-telegram-bot
```

3. Run the bot

```bash
python bot.py
```

## Project Structure

```
bot.py        # Main bot code
README.md     # Project documentation
```

## Commands

* `/start` — Start the bot
* `/help` — Get help information
* `/custom` — Placeholder command for future updates

## Notes

You should store your bot token securely (for example using environment variables) instead of keeping it directly inside the code.

## Future Improvements

* Add more commands
* Add database support
* Improve message understanding
* Deploy the bot to a cloud server

## Author

Created as a beginner Python project to learn how Telegram bots work.
