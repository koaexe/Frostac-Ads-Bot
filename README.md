<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0,061220,45,0b2d55,80,0f3d78,100,061220&text=Frostac&fontSize=58&fontColor=a8d8f0&animation=fadeIn&fontAlignY=41&desc=Your%20shortcut%20to%20effortless%20advertising.&descSize=14&descColor=6ab4d4&descAlignY=63" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&style=italic&weight=300&size=17&duration=3000&pause=1500&color=A8D8F0&background=00000000&center=true&vCenter=true&width=560&height=30&lines=One+message.+An+entire+network.;Crypto+payments+without+a+processor.;Your+ad.+Your+wallet.+Your+platform." alt="" />

<br/><br/>

[![](https://img.shields.io/badge/-@frostac-0a1628?style=flat-square&logo=telegram&logoColor=a8d8f0&labelColor=0a1628)](https://t.me/frostac)&nbsp;[![](https://img.shields.io/badge/-frostacs.vercel.app-0a1628?style=flat-square&logo=vercel&logoColor=a8d8f0&labelColor=0a1628)](https://frostacs.vercel.app)

<br/>

![](https://img.shields.io/badge/Status-Under%20Development-0a1628?style=flat-square&logo=githubactions&logoColor=f0a808&labelColor=0a1628)

</div>

<br/>

---

<br/>

## ✦ What is Frostac

Frostac is a modern Telegram advertising platform that automates the process of promoting businesses, communities, products, and services across a network of Telegram groups and channels.

With a native Telegram Mini App, automated campaign management, a self-custodial crypto payment gateway, wallet-based billing, and powerful management tools, Frostac makes Telegram advertising simple, efficient, and scalable.

<br/>

<div align="center">

`11 Cryptocurrencies` &nbsp;·&nbsp; `5 Service Plans` &nbsp;·&nbsp; `3 Billing Cycles` &nbsp;·&nbsp; `Self-Custodial Wallets` &nbsp;·&nbsp; `Referral Commission` &nbsp;·&nbsp; `Coupon System`

</div>

<br/>

---

<br/>

## ✦ Languages & Technologies

<br/>

<div align="center">

![](https://img.shields.io/badge/Python-0a1628?style=flat-square&logo=python&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/JavaScript-0a1628?style=flat-square&logo=javascript&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/HTML5-0a1628?style=flat-square&logo=html5&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/CSS3-0a1628?style=flat-square&logo=css3&logoColor=a8d8f0&labelColor=0a1628)

![](https://img.shields.io/badge/python--telegram--bot-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/Pyrogram-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/asyncpg-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/bip--utils-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/Flask-0a1628?style=flat-square&logo=flask&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/Node.js-0a1628?style=flat-square&logo=nodedotjs&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/PostgreSQL-0a1628?style=flat-square&logo=postgresql&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/Vercel-0a1628?style=flat-square&logo=vercel&logoColor=a8d8f0&labelColor=0a1628)

</div>

<br/>

---

<br/>

## ✦ Architecture

<br/>

```
Frostac/
│
├── bot/          Telegram Bot  (Python 3.11 · python-telegram-bot · Pyrogram)
│   ├── app/      Core logic — database, wallet, userbot, UI layer
│   └── assets/   Banners and brand assets
│
└── web/          Telegram Mini App + Webhook Layer  (HTML · CSS · JS · Node.js)
    ├── [frontend] Mini App UI — Flask in dev, Vercel in prod
    └── api/       Serverless payment confirmation handlers  (Vercel)
```

<br/>

---

<br/>

## ✦ Features

<br/>

### Telegram Mini App &nbsp; ![](https://img.shields.io/badge/In%20Progress-0a1628?style=flat-square&logo=githubactions&logoColor=f0a808&labelColor=0a1628)

A native Telegram Mini App — opens directly inside the bot, no external browser needed. Designed with an iOS liquid glass aesthetic, smooth animations, bottom navigation, haptic feedback, and full Telegram WebApp SDK integration. Currently under active development.

<br/>

### Crypto Payment Gateway — fully self-custodial

A single BIP-39 mnemonic seed generates a unique on-chain deposit address per invoice via HD wallet derivation. No payment processor, no custody risk.

- Invoices carry a **30-minute expiry** with automatic status updates
- **Themed QR codes** generated server-side — gradient background, Frostac logo overlay
- Real-time confirmations via **8 Vercel serverless webhook endpoints**, one per coin
- User is notified inside Telegram the moment payment is confirmed

<br/>

<div align="center">

![](https://img.shields.io/badge/BTC-0a1628?style=flat-square&logo=bitcoin&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/ETH-0a1628?style=flat-square&logo=ethereum&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/BNB-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/SOL-0a1628?style=flat-square&logo=solana&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/LTC-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/MATIC-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/TRX-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/TON-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)

![](https://img.shields.io/badge/USDT%20·%20TRC20%20/%20ERC20%20/%20TON-0a1628?style=flat-square&logo=tether&logoColor=a8d8f0&labelColor=0a1628)&nbsp;![](https://img.shields.io/badge/USDC-0a1628?style=flat-square&logoColor=a8d8f0&labelColor=0a1628)

![](https://img.shields.io/badge/⭐%20Telegram%20Stars-0a1628?style=flat-square&logo=telegram&logoColor=f0c040&labelColor=0a1628)

</div>

<br/>

### Service Plans — tiered advertising packages

| Plan | Positioning |
|---|---|
| **Starter** | Entry-level — ideal for small promos |
| **Growth** | Scaling reach across mid-size networks |
| **Pro** | High-volume campaigns with priority delivery |
| **Elite** | Power operators running multiple campaigns |
| **Enterprise** | Full platform access, custom arrangements |

Every plan is available in **1 Week · 1 Month · 3 Months** billing cycles. Clients pay directly from their in-bot wallet balance or via a fresh crypto invoice.

<br/>

### Ads Bot — Pyrogram userbot delivery engine

Ad delivery runs through a real Telegram user session via Pyrogram — not a bot account. Ads are forwarded natively across the entire registered group network on demand, with full group management (add, list, remove, inspect) handled from inside the bot.

- **Telegram Forum support** — automatically detects forum-type groups and forwards to the correct topic thread
- **Flood control** — built-in FloodWait handling keeps the session safe under heavy delivery loads
- **Delivery tracking** — forward success and failure rates logged per run

<br/>

### Wallet & Billing

Each user holds an internal USD wallet balance — topped up via crypto invoice or Telegram Stars, deducted at checkout with no external payment flow. Full transaction history is stored in Postgres.

- **Crypto top-up** — generates a fresh on-chain invoice; balance is credited automatically on confirmation
- **Telegram Stars** — native Telegram payment method; users pay directly inside the chat using Stars, which are converted and credited to their wallet balance instantly

<br/>

### Referral System

An automated referral program with deep-link tracking. Referrers earn **5% commission** on every top-up made by users they bring in — credited to their wallet instantly with no manual approval.

<br/>

### Coupon System

Owner-created discount codes with a custom balance value and total usage cap. Single-claim enforcement per user — redeemed balance lands directly in the wallet.

<br/>

### Stats &nbsp; ![](https://img.shields.io/badge/Expanding-0a1628?style=flat-square&logo=githubactions&logoColor=f0a808&labelColor=0a1628)

Platform-level delivery stats are already tracked — total groups reached, forums vs standard groups, and per-run forward success rates.

User-facing campaign analytics are planned: clients will be able to view a full breakdown of their ad campaigns directly inside the bot — reach, delivery rate, active duration, and historical performance per campaign.

<br/>

---

<br/>

## ✦ Availability

Frostac is a **private, closed-source project** — the source code is not publicly available and is not open for contributions, forks, or redistribution.

This repository exists as a portfolio reference only. The codebase, infrastructure, and all associated assets remain the exclusive property of the author.

If you're interested in using Frostac's advertising services, reach out via the links below.

<br/>

---

<br/>

<div align="center">

[![](https://img.shields.io/badge/-@sulfamic-0a1628?style=flat-square&logo=telegram&logoColor=a8d8f0&labelColor=0a1628)](tg://user?id=6239650886)&nbsp;[![](https://img.shields.io/badge/-@7nii-0a1628?style=flat-square&logo=discord&logoColor=a8d8f0&labelColor=0a1628)](https://discord.com/users/716195447525474305)&nbsp;[![](https://img.shields.io/badge/-koasync@gmail.com-0a1628?style=flat-square&logo=gmail&logoColor=a8d8f0&labelColor=0a1628)](mailto:koasync@gmail.com)&nbsp;[![](https://img.shields.io/badge/-koaexe-0a1628?style=flat-square&logo=github&logoColor=a8d8f0&labelColor=0a1628)](https://github.com/koaexe)&nbsp;[![](https://img.shields.io/badge/-@koaisdev-0a1628?style=flat-square&logo=x&logoColor=a8d8f0&labelColor=0a1628)](https://x.com/koaisdev)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0,2a6fa8,45,1a4d7a,80,0a2840,100,061220&section=footer" width="100%" />
