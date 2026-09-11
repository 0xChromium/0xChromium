<div align="center">

<img src="github/banner-hero.png" alt="REKT · Terminal 67 · the loss ledger of Robinhood Chain" width="100%">

<br>

[![X](https://img.shields.io/badge/𝕏-@rektreport-1B1F24?style=flat-square&labelColor=1B1F24&color=1B1F24)](https://x.com/rektreport)
![followers](https://img.shields.io/github/followers/NikOneZ1?style=flat-square&label=FOLLOWERS&labelColor=1B1F24&color=F5B400)
![stars](https://img.shields.io/github/stars/NikOneZ1/rekt?style=flat-square&label=REKT%20STARS&labelColor=1B1F24&color=F5B400)
![tests](https://img.shields.io/badge/TESTS-182%20passing-F5B400?style=flat-square&labelColor=1B1F24)
![views](https://komarev.com/ghpvc/?username=NikOneZ1&style=flat-square&label=PROFILE+VIEWS&color=F5B400)

</div>

## ▤ About

```ts
const rekt = {
  reads:   ["every pons launch", "every curve trade", "every pool swap after graduation"],
  folds:   "one position per wallet per token · average-cost realized PnL in dollars",
  prints:  ["a boarding pass", "a departures board", "a turbulence index", "the airline that cancelled you"],
  record:  { launches: 232_349, wallets: 749_179, lostByLosers: "$85.1M" },
  rules:   ["the trader, not the router", "cost basis or nothing", "the record says how deep it is"],
  wallet:  null,  // every page is a read. nothing connects, nothing signs.
};
```

## ▤ Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TYPESCRIPT-1B1F24?style=flat-square&logo=typescript&logoColor=F5B400)
![Node](https://img.shields.io/badge/NODE%2022-1B1F24?style=flat-square&logo=node.js&logoColor=F5B400)
![viem](https://img.shields.io/badge/VIEM-1B1F24?style=flat-square&logo=ethereum&logoColor=F5B400)
![SQLite](https://img.shields.io/badge/SQLITE-1B1F24?style=flat-square&logo=sqlite&logoColor=F5B400)
![Uniswap v4](https://img.shields.io/badge/UNISWAP%20V4-1B1F24?style=flat-square&logo=uniswap&logoColor=F5B400)
![SSE](https://img.shields.io/badge/SSE-1B1F24?style=flat-square&logoColor=F5B400)
![Caddy](https://img.shields.io/badge/CADDY-1B1F24?style=flat-square&logoColor=F5B400)
![No build](https://img.shields.io/badge/NO%20BUILD%20STEP-1B1F24?style=flat-square&logoColor=F5B400)

</div>

## ▤ Now boarding

<img src="github/banner-ship.png" alt="$REKT · 67% of Robinhood Chain traders lost money. Find out how much you contributed." width="100%">

<div align="center">

[![repo](https://img.shields.io/badge/REPO-NikOneZ1%2Frekt-F5B400?style=flat-square&labelColor=1B1F24&logo=github&logoColor=F4F4F2)](https://github.com/NikOneZ1/rekt)
[![board](https://img.shields.io/badge/DEPARTURES%20BOARD-rekt.report-F5B400?style=flat-square&labelColor=1B1F24)](https://rekt.report)
[![desk](https://img.shields.io/badge/COMPENSATION%20DESK-rekt.report%2Fdesk-F5B400?style=flat-square&labelColor=1B1F24)](https://rekt.report/desk)
[![x](https://img.shields.io/badge/𝕏-@rektreport-F5B400?style=flat-square&labelColor=1B1F24)](https://x.com/rektreport)

<br>

![launches](https://img.shields.io/badge/LAUNCHES%20READ-232%20349-F5B400?style=flat-square&labelColor=1B1F24)
![pool](https://img.shields.io/badge/REACHED%20A%20POOL-1.9%25-F5B400?style=flat-square&labelColor=1B1F24)
![wallets](https://img.shields.io/badge/WALLETS-749%20179-F5B400?style=flat-square&labelColor=1B1F24)
![losses](https://img.shields.io/badge/LOSSES%20RECORDED-1%20719%20097-F5B400?style=flat-square&labelColor=1B1F24)
![lost](https://img.shields.io/badge/LOST%20BY%20THE%20LOSERS-%2485.1M-E0322B?style=flat-square&labelColor=1B1F24)

<sub>measured from the folded record · Robinhood Chain · numbers move, the queries do not</sub>

<br><br>

![ca](https://img.shields.io/badge/%24REKT%20CONTRACT-boarding%20soon%20%C2%B7%20no%20CA%20yet%20%C2%B7%20anything%20claiming%20to%20be%20%24REKT%20is%20not%20ours-1B1F24?style=flat-square&labelColor=F5B400&color=1B1F24)

</div>

| What | How it works in practice |
|---|---|
| **Two streams** | curve trades and Uniswap v4 pool swaps. Pool swaps are 70% of trading; a site that indexes only the curve shows an empty page to anyone who trades the tokens that made it |
| **The trader, not the router** | 14% of swaps arrive through an ERC-4337 bundler, so the account behind the user operation is read out of the receipt |
| **Cost basis or nothing** | proceeds are scaled to the share of tokens we actually saw bought. A sold airdrop is worth zero here, in either direction |
| **Compensation desk** | half of every creator fee goes to stakers through an on-chain splitter behind a three-day timelock. The desk page reads the escrow so the promise is checkable before it is kept |

> Every page is a read. Nothing connects, nothing signs, and the machine serving this holds no key.

<img src="github/banner-foot.png" alt="Now boarding: everyone · Destination: zero · On time · rekt.report" width="100%">
