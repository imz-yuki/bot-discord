# 🚀 Boost Server Bot

[![Discord Bots](https://img.shields.io/badge/Discord-Bot-blue)](https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&permissions=8&scope=bot)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> Một bot Discord đa năng với các tính năng quản trị, nuke server, kinh tế ảo, minigame, và AI tích hợp.

## ✨ Tính năng nổi bật

- 🛡️ **Auto-kick bot**: Tự động phát hiện và kick bot khác khỏi server.
- 🔥 **Nuke Server**: Công cụ nuke toàn diện (chỉ dùng trong test).
- 💰 **Kinh tế ảo**: Hệ thống tiền xu, câu cá, làm việc, mua sắm.
- 📊 **Level & XP**: Tự động tính điểm kinh nghiệm và cấp độ.
- 🎲 **Minigame**: Tài xỉu, bầu cua, rps, poll, giveaway.
- 🤖 **AI tích hợp**: Hỗ trợ nhiều provider AI (Gemini, Mistral, Claude, v.v.).
- 🛠️ **Quản trị**: Ban, kick, mute, clear, cảnh báo, log.

## 🚀 Hướng dẫn cài đặt

### Yêu cầu
- Python 3.10+ (hoặc Node.js 18+ tùy phiên bản)
- Discord Bot Token ([lấy tại đây](https://discord.com/developers/applications))

### Các bước
```bash
# 1. Clone repo
git clone https://github.com/your-username/bot-discord.git
cd bot-discord

# 2. Cài dependencies
pip install -r requirements.txt   # Python
# hoặc
npm install                        # Node.js

# 3. Tạo file .env và nhập token
cp .env.example .env
# Mở .env và điền BOT_TOKEN=...

# 4. Chạy bot
python src/main.py
# hoặc
npm start
