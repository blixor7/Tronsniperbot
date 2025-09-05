#  TRON Sniper Bot

TRON Sniper is a **fast, automated trading assistant** built for the **TRON blockchain**.
It helps you **snipe tokens at launch, manage trades effortlessly, and stay in control**—all from Telegram.

---

##  What It Can Do

*  **Token Sniping Made Easy**
  Detect liquidity pairs on **SunSwap** the moment they appear and auto-execute trades.

*  **Hands-Free Trading**
  Automate buys and sells on TRON with precision timing.

*  **Telegram Integration**
  Manage your wallets, positions, and snipes directly from Telegram.

*  **Secure Data Management**
  MongoDB ensures your data stays private, safe, and reliable,

---

## 🚀 Getting Started

### Requirements

Before running the bot, make sure you have:

* [Node.js](https://nodejs.org/) (v16 or newer)
* npm or yarn
* [MongoDB Community Server](https://www.mongodb.com/docs/manual/administration/install-community/)

### Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/impredmet/tron-sniper.git
   cd tron-sniper
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run MongoDB**

   ```bash
   mongod
   ```

4. **Configure the bot**
   Open `.env` in the project root and fill in your settings.

5. **Start the bot**

   ```bash
   npm start
   # or
   yarn start
   ```

---

##  Telegram Commands

* `/start` → Initialize and get a welcome message
* `/wallets` → View linked wallets
* `/positions` → See active token positions
* `/pendingsnipes` → List all pending snipes

---

##  License

Released under the **MIT License** – see [LICENSE](LICENSE).

---

##  Contributing

Contributions are welcome!
If you’ve got ideas, fixes, or new features, fork the repo and submit a PR.
