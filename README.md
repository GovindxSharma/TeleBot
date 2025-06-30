
## 🤖 TeleBot – A Simple Telegram Bot with Inline Menu

> A minimal yet functional Telegram bot built using `node-telegram-bot-api`. The bot responds to messages with a persistent inline keyboard and handles user interactions such as `Menu`, `Start`, and `Exit` using Telegram's `callback_query` system.

---

### 🚀 Features

* ✅ Listens for incoming messages and replies with a welcome message
* ✅ Displays a **persistent inline menu** with action buttons
* ✅ Handles `menu`, `start`, and `exit` selections using `callback_query` events
* ✅ Easily extendable with more menu options and actions
* 🔐 Securely loads the bot token via `.env` file

---

### 🧠 Tech Stack

* [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) — Telegram Bot SDK
* **Node.js** — Backend runtime
* **dotenv** — For managing environment variables
* **Nodemon** — For local development with hot-reload
* *(Optional)* `telegraf` — Also installed if you want to migrate to a more modern Telegram bot framework

---

### 📁 Folder Structure

```
TeleBot/
├── index.js           # Main bot logic
├── .env               # Stores BOT_TOKEN
├── package.json
└── node_modules/
```

---

### 🛠️ Getting Started

#### 1. Clone the repo

```bash
git clone https://github.com/GovindxSharma/TeleBot.git
cd TeleBot
```

#### 2. Install dependencies

```bash
npm install
```

#### 3. Add your `.env` file

```env
BOT_TOKEN=your_telegram_bot_token_here
```

#### 4. Start the bot

```bash
npm start
```

> 🛎 Make sure the bot is registered via [BotFather](https://t.me/BotFather), and you've enabled privacy settings appropriately.

---

### 🔧 Customization Ideas

* Add more buttons in the inline menu
* Integrate with a database to store user inputs or preferences
* Send media (photos, audio, documents)
* Use `telegraf` for advanced middleware-based architecture

---



