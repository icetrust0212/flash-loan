# Flashloan Bot

Flashloan bot on polygon network

## Quickstart

### 1. Setup Environment Variables

You'll need an RPC_URL environment variable. You can get one from [Alchemy website](https://alchemy.com/?r=33851811-6ecf-40c3-a36d-d0452dda8634) for free.

Then, you can create a .env file with the following.

```
RPC_URL='<your-own-alchemy-polygon-mainnet-rpc-url>'
```

If you want to execute flashloan on the polygon mainnet, you need to add your PRIVATE_KEY environment variable as well, [with a private key from your wallet](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key).

```
PRIVATE_KEY='your-PRIVATE_KEY'
```

\*Note: If using metamask, you'll have to add a `0x` to the start of your private key)

### 2. Install Dependencies

Run the following command.

```bash
yarn install
```

### 3.Build

```bash
yarn build
```

### 4. Run Bot

```bash
yarn start
```

- [Flashloan Arbitrage Trades are Still Profitable](https://medium.com/coinmonks/flashloan-arbitrage-trades-are-still-profitable-28db937f1a43)
- [Reasons why my flashloan bot didn't work](https://youtu.be/JYKuNp4D2Ig)
