# SINGULARITY TESTNET BOT
Singularity Testnet Bot

## Table Of Contents
- [SINGULARITY TESTNET BOT](#singularity-testnet-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Join My Telegram Channel](#join-my-telegram-channel)
  - [Singularity Finance Testnet](#singularity-finance-testnet)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)](#important-note-read-it-this-is-not-decoration)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS (v22)

     



## Singularity Finance |Incentives Testnet
New Testnet: Singularity Finance

➡️ Claim Faucet :  https://faucet-testnet.singularityfinance.ai/

➡️ Connect New Wallet : https://singularityfinance.ai/testnet

➡️ Complete Zeally : https://zealy.io/cw/singularityfinance/invite/4SnpNMfR9J4a6gLPxD0cL

- Get Test SFI Tokens
- Swap SFI > wSFI or Other
- Stake 50%
- Claim Reward
- Bridge SFI
- Complete Daily Onchain Task & Social Media Task 
- Done

**LFG**

## BOT FEATURE
- Multi Account 
- Proxy Support
- Support PK & SEED
- Daily Bridge (Disabled)
- Daily Wrap & Unwrap (Disable)
- Daily Stake & Unstake
- Daily Claim Staking Reward
- Daily Swap
- Daily Add Liquidity
- Daily Travel Rule (Later)


## Setup & Configure BOT

### Setuo
1. Clone project repo
   ```
   git clone https://github.com/Widiskel/singularity-testnet-bot.git && cd singularity-testnet-bot
   ```
2. Run
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Configure the bot config
    ```
   nano config/config.js
    ```
5. To run Auto TX
   ```
   npm run start
   ```
   


## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
3. start the bot
4. if any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

If any error regarding SQL, try to delete `database.db` first

Any eror during tx will be retried until it success, so ignore it

Singularity Dashboard is have a huge delay, also for the rpc and contract so don't worry just run and forget it.

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0x1f0ea6e0b3590e1ab6c12ea0a24d3d0d9bf7707d`
SOLANA : `3tE3Hs7P2wuRyVxyMD7JSf8JTAmEekdNsQWqAnayE1CN`
