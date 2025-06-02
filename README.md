# 🤖 Slack Bot with Flask, Slack Events API & Bolt

Welcome to the **Slack Bot Project** — a Python-based bot integrated with Slack that can welcome users, schedule messages, respond to bad words, and track message activity.

> Built using: `Flask`, `slack_sdk`, `slackeventsapi`, and `python-dotenv`

---

## ✨ Features

✅ Responds to messages & reactions  
✅ Sends welcome messages on keyword trigger (`start`)  
✅ Detects and warns on bad language  
✅ Tracks user message counts  
✅ Schedules and deletes future messages  
✅ Uses Slack Events API via Flask for real-time interaction

## 🗂️ Project Structure
Slack-Bot/
├── bot.py # Main application file
├── .env # Environment variables (not committed)
└── README.md # Project documentation


## ⚙️ Setup Guide

```bash
git clone https://github.com/KartikeyaDookia/slack-bot.git
cd slack-bot
python -m venv venv
venv\Scripts\activate          # Windows
# OR
source venv/bin/activate       # macOS/Linux
pip install -r requirements.txt



