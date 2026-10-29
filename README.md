# 🚀 Kite AI Automation-Bot CDY

**Kite AI Auto-Bot** is a next-gen JavaScript automation tool for interacting with the **KiteAI testnet** ecosystem and its forks (like GoKite, Pharos, Interlink). Perform XP farming, daily rewards, and AI agent chats using multiple wallets — all on autopilot 💼🤖

---

## ✨ Features

* 🧠 **Agent Interactions** 
  Auto-chat with Professor, Crypto Buddy, and Sherlock using customizable prompts.

* 💧 **Daily Faucet Claim**
  Automatically solve CAPTCHA and claim daily KITE tokens.

* 📈 **Staking Automation**
  Automatically stake KITE, claim rewards, and track returns.

* 👛 **Multi-Wallet Support**
  Easily manage and rotate between multiple wallets.

* 🧮 **Smart Analytics**
  Monitor XP points, token balances, and staking data in real-time.

* 🕒 **Scheduled Execution**
  Re-runs itself every 24h with built-in countdown logic.

* 🌐 **Proxy Support** *(Optional)*
  Supports rotating proxies via `proxy.txt` or `config.json`.

---

## 📋 Prerequisites

Make sure you have:

* [Node.js v16+](https://nodejs.org/)
* At least one Ethereum-compatible private key
* [2Captcha API key](https://2captcha.com/) *(if using faucet auto-claim)*
* Access to KiteAI testnet: [testnet.gokite.ai](https://testnet.gokite.ai/?referralCode=ODMG4EWE)

---

## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/DalleDai/Kite-Ai-Automation-Bot.git
```
```bash
cd Kite-Ai-Automation-Bot
```

2. **Install dependencies**

```bash
npm install
```

3. **Create environment file**

```bash
cp .env.example .env
```

4. **Edit `nano .env`** with your private key(s):

```env
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=optional_private_key
```

---

## 🚀 Usage

To start the bot:

```bash
node index.js
```

What it does:

1. Logs into each wallet
2. Claims faucet rewards
3. Stakes tokens & claims rewards
4. Chats with AI agents
5. Waits and schedules the next run in 24h

---

## 💰 Wallet Setup

1. Get ETH from a testnet faucet
2. Visit [KiteAI Testnet](https://testnet.gokite.ai/?referralCode=ODMG4EWE)
3. Claim initial KITE
4. Stake at least 1 KITE to start earning XP and rewards

---

## 🧠 Troubleshooting

* **Invalid private key** – Ensure key starts with `0x`
* **Captcha not solving** – Check 2Captcha balance/API key
* **Staking failed** – Make sure you have KITE & testnet ETH

---

## 🔒 Security Notes

* Private keys are stored securely in `.env` (never commit this!)
* Proxy and network handling are sandboxed
* All interactions are with official Kite endpoints
* Code is open-source for review and auditing

---

## Happy Farming! 🚀🌾

*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

---

## ☕ Buy Me a Coffee

* **EVM:** `0x49bb35693e9631760d2f3519e7db1dd618580a6a`
* **TON:** `UQDDYNRWZI12zMfXYBoy300ydECC5uouMUFLd_yZa6ZO4Jsm`
* **SOL:** `2PhLDFnyX8whHDMBbfGSFoLnVEsei6TYxyiqpDzPGyT1`
* **SUI:** `0xf3b008f8aac4b92195176aad27a892c565c216fd5c07bc99c70edb8394e23b59`

---

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes (where applicable)
* 💡 Contribute ideas and code

---
