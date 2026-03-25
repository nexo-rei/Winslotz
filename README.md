# 🎰 WinSlotz Telegram Bot

A feature-rich Telegram bot for earning coins, playing games (Ludo / Slots), and withdrawing rewards through referrals and tasks.

---

## 🚀 Features

- 🎮 Ludo / Slot game system
- 💰 Coin-based economy
- 🔗 Referral earning system
- 📊 User balance tracking
- 💳 Withdrawal system (UPI / Payment Gateway)
- 🛠 Admin controls
- 🔐 Secure environment configuration

---

## 📁 Project Structure

```
winslotz-bot/
│── src/
│   ├── bot/            # Telegram bot handlers
│   ├── services/       # Game & business logic
│   ├── database/       # DB connection & models
│   ├── utils/          # Helper functions
│
│── .env.example        # Environment variables template
│── package.json
│── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/winslotz-bot.git
cd winslotz-bot
```

### 2. Install dependencies
```bash
npm install
```

### 3. Setup environment variables
```bash
cp .env.example .env
```

Edit `.env` and add your credentials:
- Telegram Bot Token
- Database details
- Payment API keys

---

## ▶️ Run the Bot

```bash
npm start
```

For development:
```bash
npm run dev
```

---

## 🔐 Environment Variables

All sensitive configs are stored in `.env`.

Example:
```
BOT_TOKEN=your_token
DB_HOST=localhost
JWT_SECRET=your_secret
```

⚠️ Never commit `.env` to GitHub.

---

## 🎮 How It Works

### 💰 Earn Coins
- Referral system
- Task completion
- Game winnings

### 🎲 Play Games
- Ludo (multiplayer / bot)
- Slot machine

### 💳 Withdraw
- Minimum withdrawal limit applies
- Admin approval (optional)

---

## 👨‍💻 Admin Features

- View users
- Approve withdrawals
- Adjust balances
- Enable / disable maintenance mode

---

## 🔗 Referral System

- Each user gets a unique referral link
- Earn bonus coins per successful signup
- Configurable limits and rewards

---

## 🛡 Security

- JWT authentication
- Encrypted sensitive data
- Rate limiting (recommended)

---

## 📦 Tech Stack

- Node.js
- Telegram Bot API
- PostgreSQL / MongoDB
- Express.js (optional backend)

---

## 📌 TODO / Future Updates

- [ ] Web dashboard
- [ ] Leaderboard system
- [ ] Daily rewards
- [ ] Anti-cheat system
- [ ] Multi-game expansion

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## 📄 License

MIT License

---

## 📞 Support

Contact: @your_support_username

---

## ⭐ Don't forget to star the repo!
