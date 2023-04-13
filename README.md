
# OKX multiwallet withdrawal

This script allows you to withdraw from OKX MAIN balance to multiple wallets. Can be useful for participating in retrodrops and other types of abuse. This scriipt able to send random amounts to avoid linking wallets and send with random delay.

## Before Start
*This script DON'T has checks for invalid input and other errors. However, use at your own risk. The author is not responsible for any loss of funds.*

**Withdrawal is made ONLY to the address from the address book!**

## Get OKX API key, secret Key and passphrase


1) https://www.okx.com/ru/account/my-api -> Create API.
2) Сheck the box next to the <b>Enable Withdrawals</b>.
3) Copy API key, secret Key and passphrase to `config.js` file.

## Setup bot

1) Download ZIP and extract it to a folder or clone the repo.
2) Install node.js: `https://nodejs.org/en/` (LTS)
3) Setup your settings in `config.js` (set correct fee for necessary network!!)
4) Paste your wallets to `wallets.json` file, each wallet on a new line
5) Open folder with the bot in `cmd`
```bash
cd <path to folder with script>
```
6) Install dependencies
```bash
npm install
```
7) Start
```bash
node okxWithdraw.js
```


## Author

- [@p38iO](https://t.me/p38iO) you can say THX by USDT TRC-20: TUzywR3QV2oyy3NVdsLruAdS5vWd5Tv7c7
