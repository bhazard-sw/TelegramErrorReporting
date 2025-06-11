# Telegram Error Reporter

A lightweight Python utility that sends real-time error notifications to a Telegram channel. Great for long-running scripts, cron jobs, or microservices needing instant error visibility.

---

## Features

- Real-time error alerts to Telegram
- Includes detailed traceback for debugging
- Markdown-formatted messages
- Minimal dependencies (`requests`, `python-dotenv`)
- Easy plug-and-play with any Python project

---

## Prerequisites

- Python 3.7+
- [Telegram Bot Token](https://t.me/BotFather) (create with @BotFather)
- Telegram Channel where the bot is added as an **admin**
- Telegram Channel ID:
  - For **public**: `@your_channel_username`
  - For **private**: use the numeric ID like `-1001234567890`

---

## Installation

```bash
pip install requests python-dotenv
