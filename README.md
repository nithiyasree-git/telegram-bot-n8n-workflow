# 🤖 Telegram Assistant Bot Workflow (n8n)
## 🎥 Demo

Watch the workflow in action: https://drive.google.com/file/d/1XBYWTcG_qPw-WCXhxoqnRkfFKYRsQp_G/view?usp=drivesdk
This n8n workflow connects to Telegram and acts like a smart assistant:
- Replies to text messages
- Transcribes voice messages using Deepgram
- Creates reminders from user input
- Reports current tasks

## 🔧 Setup Instructions

1. Open the HTTP Request nodes in n8n.
2. Replace:
   - `ENTER_YOUR_BOT_TOKEN_HERE` with your Telegram bot token
   - `ENTER_YOUR_DEEPGRAM_API_KEY_HERE` with your Deepgram API key
3. Deploy the workflow in n8n Cloud or locally.
4. Connect your Telegram bot using a webhook or polling.

## 📦 Requirements

- Telegram Bot with access to messages
- Deepgram API key (free tier available)
- n8n instance (Cloud or Desktop)

## 🎥 Demo

Watch the workflow in action: [Add your video link here]

## 📚 References

- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Deepgram API](https://developers.deepgram.com/)
- [n8n Docs](https://docs.n8n.io/)