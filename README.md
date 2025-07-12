# Video Downloader
A Python-based Telegram bot that downloads videos from YouTube, Instagram, and other platforms. Supports auto-compression (if size > 50MB), metadata logging, and Telegram video delivery — powered by yt-dlp, ffmpeg, and python-telegram-bot.

# 🎥 Telegram Video Downloader Bot

A Python Telegram bot that lets you download videos from platforms like YouTube, Instagram, Vimeo, etc., and sends them directly via Telegram. Built for personal use and self-hosting.

---

## ✨ Features

- 🔗 Accepts video links from YouTube, Instagram, and more
- 🎞 Compresses videos over 50MB using FFmpeg
- 📩 Sends downloaded videos directly to your Telegram chat
- 📁 Saves logs and file metadata locally
- 💻 Runs locally or deploy on Render/Railway (cloud hosting)

---

## ⚙️ Tech Stack

- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [FFmpeg](https://ffmpeg.org/)
- `nest_asyncio` for compatibility in hosted environments

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- FFmpeg installed
- Telegram Bot Token via [@BotFather](https://t.me/BotFather)

### Installation

```bash
git clone https://github.com/yourusername/telegram-video-downloader-bot.git
cd telegram-video-downloader-bot
pip install -r requirements.txt
python3 telegram_bot.py
