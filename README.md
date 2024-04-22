<div align="center">
    <h1>🏮 KANA SNIPER 🏮</h1>



</div>

---

<p align="center">
    <img src="https://img.shields.io/github/stars/0xtaodev/jupiter-python-cli">
    <img src="https://img.shields.io/github/forks/0xtaodev/jupiter-python-cli">
    <br>
    <img src="https://img.shields.io/github/issues/0xtaodev/jupiter-python-cli">
    <img src="https://img.shields.io/github/issues-closed/0xtaodev/jupiter-python-cli">
    <br>
    <img src="https://img.shields.io/github/languages/top/0xtaodev/jupiter-python-cli">
    <img src="https://img.shields.io/github/last-commit/0xtaodev/jupiter-python-cli">
    <br>
</p>

# 📖 Introduction
**Kana** is a Sniper bot that sniper all the tokens on  **[Solana]() features** including a **Fast** sniper.<br>


# ✨ Quickstart

This project has been made for Python 3.11

## 🛠️ Installation

💾 **Clone this repository**
```sh
Download this repository
```
💻 **Install the required libs**
```sh
pip install -r requirements.txt
```
▶️ **Start**
```sh
python main.py
```

# 🤖 Sniper Bot
**In top of most of the Kana features that you can use, you are also able to snipe token.**<br>
❗**Please note that Sniper Bot is experimental and subject to change as there might be issues that I didn't see.**

### ⚙️ How it works
Every second, the bot will send a GET request to [Solana].<br>
If there is a route available for this token, it will then execute it.<br>
Please note that only tokens with sufficient liquidity and on-chain metadata are listed in Jupiter API: min. 250$ liquidty and buy/sell price impact are below 30%.<br>
When these criteria are met, it will take a few minutes to automatically add the token.<br>

### 🆕 Add a token to snipe
- Token/Project name
- Token Address
- Amount ($) to buy
- Take Profit ($)
- Stop Loss ($)
- Slippage (%)

If token has a launch date:
- Month
- Day
- Hours
- Minutes

### 🔭 Watch token
You can watch your trading position by selecting the token.<br>
<img src="https://github.com/KanaDevv/Solana-sniper-bot/blob/main/logo.PNG" width="50%" height="50%">

### ✍🏻 Edit tokens
You can modify token info as follow:
- Name
- Address
- Selected Wallet
- Buy Amount
- Take Profit
- Stop Loss
- Slippage
- Launch date
- Delete

# 🗨️ Q&A
### Where are my private keys?
*Your private keys are stored in `wallets.json`.*
### Is there any fees when swapping using Kana?
*There are no additional fees when performing swaps via the CLI; the costs should be the same as using the Jupiter UI.*
### Does sniper bot remains running if I close the Kana?
*If you close the Kana, the sniper bot will stop running.*
### Is it possible to swap any tokens?
*You can only swap tokens that are listed on Jupiter based on their criterias.*


# 📝 TO-DO
- [ ] Clean up code ⚡
- [ ] Add docstrings 📑
- [ ] Display tokens owned 🪙
- [ ] Favorite tokens displayed in first tokens for swap/limit orders/dca... ⭐
- [ ] Wallet Duplication detection
- [ ] Display message when swap failed (slippage error...)
- [ ] Disable swap / limits orders / etc, if not enough $SOL to cover the tx fees
- [ ] Give possibility to exit current choice (swap, limit order, dca, donation...) 🏃🚪
- [ ] Adjust Wallets ID when one is deleted
- [ ] Bridge 🌉
- [ ] Perpetual 💸

