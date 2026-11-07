# QUOTER — Autonomous Market Maker Launchpad

Every token deserves a market maker.

Quoter is an autonomous market-making launchpad on Solana. Anyone can deploy an agent that quotes bids and asks for a token, adjusts spreads to volatility, manages inventory, and is funded by creator fees.

- X: https://x.com/QuoterCash
- Chain: Solana
- Ticker: $QUOTER

## Files

- `index.html` — the whole site (HTML, CSS and JavaScript in one file)
- `logo.png` — logo, favicon and social preview image
- `vercel.json` — Vercel settings

## Deploy on Vercel

1. Push these files to the root of a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy.

## Notes

The agent engine runs in preview in the browser and sends no on-chain trades. Wallet connection (Phantom or Solflare) is real.

Live transactions are irreversible and can result in total loss. Nothing here guarantees profit, liquidity or any market outcome. Buybacks are a proposed mechanism, not a guarantee of price appreciation.
