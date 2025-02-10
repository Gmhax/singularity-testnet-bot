# SINGULARITY TESTNET BOT
Singularity Testnet Bot


## Prerequisite
- Git
- Node JS (v22)

     



## Singularity Finance |Incentives Testnet
New Testnet: Singularity Finance


➡️ Use burner wallet!

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
   git clone https://github.com/Gmhax/singularity-testnet-bot.git && 
   cd singularity-testnet-bot
   ```
2. Run
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
   Format: export const privateKey = ["your-private-key",];
   
5. Configure the bot config
    ```
   nano config/config.js
    ```
6. Create session
   ```
   screen -S singurality
   ```

7. To run Auto TX
   ```
   npm run start
   ```
   
##DETACH SESSION:

Ctrl + A, then Click D


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



