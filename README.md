# Raydium Volume Bot

This volume bot distribute SOL to multiple wallets and buy and sell with that distributed wallets permanently on the Raydium platform.

## Features

- **Automated Wallet Creation**: Create number of wallets automatically to buy and sell the token
- **Automated SOL Distribution**: Distributes SOL to those new wallets.
- **Endless Buy and Sell Swaps**: Buy and Sell with those wallets permanently.
- **Configurable Parameters**: Allows customization of buy amounts, intervals, distribution settings, and more.

## Usage
1. Clone the repository
```
git clone https://github.com/sourlodine/Solana-Raydium-Volume-Bot.git
cd Solana-Raydium-Volume-Bot
```
2. Install dependencies
```
npm install
```
3. Configure the environment variables

Rename the .env.example file to .env and set RPC and WSS, main wallet's secret key, and jito auth keypair.

4. Run the bot

```
npm run start
```



