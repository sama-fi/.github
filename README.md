<div align="center">

<img width="125" height="125" alt="7842492d-55ed-4957-bb3e-13f39c15fcd5-Photoroom" src="https://github.com/user-attachments/assets/24768fd2-f507-4399-a44b-12360015280d" />


### Find the other side of your rebalance.

**Wallet-to-wallet matching for tokenized stocks on BNB Chain.**

[Website](https://samafi.xyz) &nbsp;·&nbsp; [App](https://app.samafi.xyz) &nbsp;·&nbsp; [Docs](https://docs.samafi.xyz) &nbsp;·&nbsp; [On-chain proof](https://samafi.xyz/proof)

[![BNB Chain](https://img.shields.io/badge/BNB%20Chain-mainnet-F0B90B?logo=binance&logoColor=white)](https://bscscan.com/address/0x7811a30D29d6c2Ca95Aeb4EE9D896cE44Cb72AC8)
[![Contract](https://img.shields.io/badge/contract-source%20verified-2EA44F)](https://repo.sourcify.dev/56/0x7811a30D29d6c2Ca95Aeb4EE9D896cE44Cb72AC8)
![Solidity](https://img.shields.io/badge/Solidity-0.8.33-363636?logo=solidity&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?logo=nextdotjs&logoColor=white)

</div>
</div>

---

## What is SAMA?

When you rebalance your portfolio, you usually trade against a liquidity pool and pay its fees. But often someone else wants to make the exact opposite trade.

**SAMA finds that person.** It matches your rebalance with others who are heading the other way, even across three or more wallets, and swaps directly between you. What matches skips the pool entirely.

*"SAMA" means "the same" and "together" in Indonesian.*

## Why it matters

Tokenized US stocks (Binance **bStocks**) now trade on BNB Chain, but most of them trade in thin pools, and every wallet that rebalances pays the pool on its own.

- Only **18 of the 88** bStocks have a PancakeSwap pool holding $100K or more of USDT.
- Swapping $10K costs about **0.3%** in the deepest pool and **several percent** in the thinnest. *(PancakeSwap V3 quotes, October 2026.)*
- Even when two people want opposite trades, they never find each other, so both pay the pool.


## See it in action
<img width="1448" height="1086" alt="Group 60" src="https://github.com/user-attachments/assets/4c0ba21c-cd15-49bb-8c6e-cd75167d00dc" />
<img width="1448" height="1086" alt="Group 59" src="https://github.com/user-attachments/assets/03ee96d7-247f-4d24-98f2-ff2314669409" />

<img width="1448" height="1086" alt="Group 59" src="https://github.com/user-attachments/assets/ed6d589f-dc8d-4e96-b46d-4d6e9c7d5e3d" />


## How it works

1. **Sign in** with your email (you get an embedded wallet) or with your own wallet.
2. **Set your target mix.** Pick a preset, choose your own percentages, or just write it in plain words.
3. **Join a Circle.** A Circle is a group that rebalances the same tokens on a schedule, such as a community, a Telegram group or friends. Rounds happen inside Circles, which brings together people who need opposite trades.
4. **Sign up for the round.** One free signature adds your rebalance to the open round. Nothing moves yet.
5. **Review and approve.** When the round closes, SAMA shows exactly what you send and what you receive. You approve those exact amounts.
6. **Settle.** Every matched transfer goes through in **one transaction**: either all of them happen or none do. You get a receipt that was checked independently on-chain.
7. **Decide what's left.** Anything that didn't find a match can roll into the next round, be cancelled, or be swapped on PancakeSwap if the cost stays within the limit you set.

**A simple example.** Rina wants to swap TSLAB for NVDAB, Dimas wants NVDAB for GOOGLB, and Sari wants GOOGLB for TSLAB. No two of them fit, but together they form a loop. SAMA settles all three trades directly between them, and nobody pays the pool.

## What you can do in SAMA

- **See your portfolio live.** Balances are read straight from BNB Chain, with the gap to your target shown in dollars.
- **Set a target your way.** Presets, per-token percentages, or a sentence like "cut NVDAB to 20% and keep 10% in USDT".
- **Join or start a Circle.** Circles can be public, invite-only or private. Organizers share single-use invite links.
- **Ask the AI assistant.** It answers questions about your wallet, prices and Circles and can propose a target. It only reads and suggests, you confirm every change, and it can never move your funds.
- **Explore every token.** Each listed token has its own page with price chart, market cap, 24-hour volume, liquidity and the latest trades.
- **Keep your receipts.** Every settled round is re-checked independently and comes with a receipt linked to BscScan.
- **Track your history.** A monthly calendar shows how your wallet value changed.
- **Convert BNB to WBNB in one tap**, so BNB can be part of your rebalance.
- **Use it your way.** Mobile-first, light and dark mode, in English and Bahasa Indonesia.
- **Try the demo first.** It replays a real round with sample data and moves nothing.

## Supported assets

**88 bStocks**, which are tokenized US stocks and ETFs on BNB Chain (75 stocks and 13 ETFs), such as NVDAB, TSLAB, AAPLB, SPYB, QQQB, GOOGLB, MSFTB and NFLXB. Plus **WBNB** and **USDT** as cash. Each bStock is backed 1:1 by the underlying share held in regulated custody. Leveraged ETFs show a warning before you add them.

## Getting started

You need:
- An email address, or a wallet such as MetaMask, Trust Wallet, Binance Wallet or OKX Wallet.
- Some bStocks, BNB or USDT on BNB Chain. You can finish setup without them and add assets later.
- A little BNB for network gas, until gas sponsorship goes live.

**[Open the app →](https://app.samafi.xyz)**

## Safety and trust

- **Non-custodial.** SAMA never holds your tokens and never sees your keys. Tokens move straight from wallet to wallet.
- **Exact approvals.** You sign for the precise plan and the precise amounts. Nothing open-ended.
- **All or nothing.** A plan settles completely or not at all.
- **Verified on-chain.** The settlement contract is public and its source is verified: [`0x7811…2AC8`](https://bscscan.com/address/0x7811a30D29d6c2Ca95Aeb4EE9D896cE44Cb72AC8) on BNB Chain mainnet.
- **Independently checked.** After each settlement, a separate verifier reads it back from the chain and issues the receipt.
- **Human in control.** The AI assistant only proposes. You press the button.

## Questions

<details>
<summary><b>What if nobody matches my trade?</b></summary>
Nothing moves, and that's a valid result. You can carry your trade into the next round, cancel it, or swap it on PancakeSwap if the cost is within your limit.
</details>

<details>
<summary><b>Do I pay fees?</b></summary>
The matched part pays no pool fee, spread or price impact, and the SAMA contract takes no fee. You pay normal network gas in BNB. If you choose to swap a leftover on PancakeSwap, that swap pays PancakeSwap's pool fee and gas.
</details>

<details>
<summary><b>Can SAMA move my money?</b></summary>
No. You sign a free intent first, then approve the exact amounts of the final plan. Without your approval nothing is sent.
</details>

<details>
<summary><b>How often do rounds happen?</b></summary>
Each Circle sets its own schedule (started manually, daily or weekly) and how long each round collects signatures.
</details>

<details>
<summary><b>Who can see my trades?</b></summary>
Transfers on the blockchain are public, as on any chain. Inside SAMA, other members appear under pseudonyms, and receipts are open only to the members of that Circle.
</details>

<details>
<summary><b>Is SAMA audited?</b></summary>
Not yet. The contract is covered by unit, fuzz and mainnet-fork tests, but it has not been externally audited, so each plan is capped at **$500** for now.
</details>

<details>
<summary><b>Is this investment advice?</b></summary>
No. SAMA coordinates the trades you choose. It gives no investment advice and does not decide whether you may trade an asset.
</details>

## Status

SAMA is early-stage. The settlement contract is live on BNB Chain mainnet, plans are capped at $500 until an external audit, and gas sponsorship is planned but not live yet.

## Links

| | |
|---|---|
| **Website** | [samafi.xyz](https://samafi.xyz) |
| **App** | [app.samafi.xyz](https://app.samafi.xyz) |
| **Guide** | [docs.samafi.xyz](https://docs.samafi.xyz) |
| **On-chain proof** | [samafi.xyz/proof](https://samafi.xyz/proof) |
| **Code** | [sama-frontend](https://github.com/sama-fi/sama-frontend) · [sama-backend](https://github.com/sama-fi/sama-backend) |

---

<div align="center">

Built by **NGDKLabs**

</div>
