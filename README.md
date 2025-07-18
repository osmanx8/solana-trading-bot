# 🔄 Solana Volume Bot for PumpSwap, Raydium & Meteora

A high-performance automated Solana trading bot that interacts with decentralized exchanges like PumpSwap, Raydium (CLMM & CPMM), and Meteora (DLMM & Dynamic AMM). This bot is built to simulate transaction volume by automating wallet creation, SOL distribution, and swap operations, while also handling token sales, fee collection, and closing of token accounts.

## 🔍 Transaction Examples
- **Pumpswap:** https://solscan.io/tx/ZkEdGvHeu1tR2Agy1RvqcX9XST5YDRFbCPaqTo1kCgPbae7XuKh3qjYmLBbZC7KMHP9GvBadJYzVceBvCZhbhFk

- **Meteora DLMM:** https://explorer.jito.wtf/bundle/558eb9f86665cd3362f0dde7a847452370d0a5c100d6cf1276bc7469ee9728b0

- **Meteora Dynmic AMM:** https://explorer.jito.wtf/bundle/44b1e24a0fb2d2038582deef52a6c5834e9118835f07cc30d76453070e7cfaee


## 📌 Features
🧩 Multi-Wallet Creation & Automated SOL Distribution

🤖 Automated Buy/Sell on PumpSwap, Raydium CPMM & CLMM, Meteora DLMM & Dynamic AMM

🔁 Automatic Sweep of Old Wallets — Sell tokens, withdraw SOL, and close associated token accounts

📊 Real-Time Logging — Tracks transactions, volume metrics, and token statistics

🛠️ Customizable Parameters — Set buy/sell ranges, delays, RPC endpoints, and more

📦 Up-to-Date SDK Support — Uses latest PumpSwap SDK for accurate pool info and swap calculations
## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/osmanx8/Burn-ATA-Solana.git
cd Burn-ATA-Solana
```
### 2. ⚙️Clone the Repo
Fill out .env 
```env
MAIN_KEYPAIR_HEX=
TREASURY_WALLET=
MAIN_RPC_URL=
MAIN_WSS_URL=
DEV_RPC_URL=
DEV_WSS_URL=
``` 
### 3. ⚙️Figure out initial settings

- Example
```typescript
{
    isPumpToken: "y",
    basemint: new web3.PublicKey("Frno4J9Yqdf8uwQKziNyybSQz4bD73mTsmiHQWxhJwGM"),
    minAndMaxBuy: "0.00001 0.00001",
    minAndMaxSell: "0.00001 0.00001",
    delay: "2 3",
    jitoTipAmt: "0.01",
    cycles: 3,
    marketID: "Frno4J9Yqdf8uwQKziNyybSQz4bD73mTsmiHQWxhJwGM"
}
```
### 4.⚙️ Run with command

Install node modules and run bot with command
```bash
yarn
yarn dev
```

```package.json
"start": "node dist/index.js",
"dev": "ts-node-dev src/index.ts",
"build": "tsc",
```

## 🎫 Contact

[Telegram](https://t.me/pup5ol)

### Please don't forget give ✨Star✨ and 🎞Fork🎞. 😊
