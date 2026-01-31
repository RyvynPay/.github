<div align="center">

<img src="https://raw.githubusercontent.com/RyvynPay/FE/main/public/logo.png" width="150" alt="Ryvyn Logo">

# RYVYN PAY

### _Your Money. Always Working. Always Yours._

<br/>

[![Frontend Repository](https://img.shields.io/badge/Frontend-Repository-black?style=for-the-badge&logo=github)](https://github.com/RyvynPay/FE)
&nbsp;
[![Smart Contracts Repository](https://img.shields.io/badge/Smart_Contracts-Repository-black?style=for-the-badge&logo=github)](https://github.com/RyvynPay/SC)

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Try_Now-ryvyn--pay.vercel.com-00D9FF?style=for-the-badge)](https://ryvyn-pay.vercel.com)

<br/>

[![Next.js](https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js)](https://nextjs.org/)
[![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity)](https://soliditylang.org/)
[![Base](https://img.shields.io/badge/Base_Network-0052FF?style=flat-square&logo=coinbase)](https://base.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

**`deposit`** → **`spend`** → **`earn`** → **`repeat`** ♻️

</div>

<br/>

## 💀 The DeFi Dilemma

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   💰 Want to EARN?      →   Lock your funds ⛓️          │
│   💸 Want to SPEND?     →   Forget about yield 📉      │
│                                                         │
│   Billions sit idle. Inflation eats value. Every day.   │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

**The old rule:** _Money works — OR — Money moves. Pick one._

<br/>

## ⚡ Ryvyn Breaks The Rules

We built **ryUSD** and **ryIDR** — stablecoins that **earn while you spend**.

```diff
+ ✅ Hold ryUSD    →  Earn rewards
+ ✅ Send ryUSD    →  Earn rewards
+ ✅ Receive ryUSD →  Earn rewards
- ❌ No lockups
- ❌ No farming
- ❌ No complexity
```

> **"Why choose between liquidity and yield when you can have both?"**

<br/>

## 🎯 Core Features

<table>
<tr>
<td width="50%">

### 💧 Liquid Yield

Your **ryUSD/ryIDR** earns continuously.  
No staking. No locking. Just hold & earn.

</td>
<td width="50%">

### 🎮 Prediction Boost

Stake **ryBOND** → Make predictions → Multiply your yield.  
DeFi meets gamification.

</td>
</tr>
<tr>
<td width="50%">

### � Dual Currency

Native support for both:

- **USDC** → ryUSD (Global)
- **IDRX** → ryIDR (Indonesia)

</td>
<td width="50%">

### ⚡ Stream Bonds

Rewards vest linearly.  
Claim every second. Your yield, your timing.

</td>
</tr>
</table>

<br/>

## 🏗️ Architecture

```
                    ┌──────────────┐
                    │     USER     │
                    └──────┬───────┘
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
         ┌────────┐   ┌────────┐   ┌────────┐
         │ Deposit│   │Transfer│   │  Claim │
         └───┬────┘   └───┬────┘   └───┬────┘
             │            │            │
             ▼            ▼            ▼
    ┌─────────────────────────────────────────┐
    │              RYVYN PROTOCOL             │
    │  ┌───────────────────────────────────┐  │
    │  │  ryUSD / ryIDR  ◄──► TreasuryMgr  │  │
    │  │         │                  │      │  │
    │  │         ▼                  ▼      │  │
    │  │     ryBOND ◄──────► YieldManager  │  │
    │  │         │                         │  │
    │  │         ▼                         │  │
    │  │   PredictionBoost                 │  │
    │  └───────────────────────────────────┘  │
    └─────────────────────────────────────────┘
```

<br/>

## 📦 Repositories

|     | Repository                               | Stack                            | Description          |
| :-: | :--------------------------------------- | :------------------------------- | :------------------- |
| 🎨  | **[FE](https://github.com/RyvynPay/FE)** | Next.js 15, TypeScript, Tailwind | Frontend Application |
| ⛓️  | **[SC](https://github.com/RyvynPay/SC)** | Solidity, Foundry                | Smart Contracts      |

<br/>

## 🧪 Deployed on Base Sepolia

<details>
<summary><b>📋 View Contract Addresses</b></summary>

<br/>

| Contract        | Explorer                                                                                                 |
| :-------------- | :------------------------------------------------------------------------------------------------------- |
| ryUSD           | [`0x9e94BC6b...C50E88`](https://sepolia.basescan.org/address/0x9e94BC6b8D81e94D5272d8e2F2BcCAC267C50E88) |
| ryIDR           | [`0x5403ff9c...48311`](https://sepolia.basescan.org/address/0x5403ff9c5c173eEe01255Eeb4d0925bD21748311)  |
| ryBOND          | [`0xB367b394...35a93`](https://sepolia.basescan.org/address/0xB367b39466BE0c5a94DbFCa22bF8A8B356A35a93)  |
| TreasuryManager | [`0xc6841f2d...16Eee`](https://sepolia.basescan.org/address/0xc6841f2d1900d239579B809b1fc8D1b5D0716Eee)  |
| YieldManager    | [`0xEF835c04...45b80`](https://sepolia.basescan.org/address/0xEF835c04113FC566028B537B18cA0B1E9d745b80)  |
| PredictionBoost | [`0xeAd4547a...A5Ea2`](https://sepolia.basescan.org/address/0xeAd4547a2b3d7c7D999b59e4966B1264c31A5Ea2)  |
| RyvynHandler    | [`0x983ae30F...6f93`](https://sepolia.basescan.org/address/0x983ae30F3530442D8889999f81E296CA7a336f93)   |

</details>

<br/>

## 🛤️ Roadmap 2026

```
Q1 ━━━━━━━━━━━━━━━━━ Q2 ━━━━━━━━━━━━━━━━━ Q3 ━━━━━━━━━━━━━━━━━ Q4
     │                    │                    │                    │
     ▼                    ▼                    ▼                    ▼
┌─────────┐         ┌─────────┐         ┌─────────┐         ┌─────────┐
│   MVP   │         │  EXPAND │         │ MARKET  │         │   DAO   │
│  LAUNCH │         │  ASSETS │         │  PLACE  │         │  LIVE   │
└─────────┘         └─────────┘         └─────────┘         └─────────┘
  Protocol           Multi-asset          ryBOND             Community
  on Base            + Premium UX         Utilities          Governance
```

<br/>

## 👥 The Builders

<table>
<tr>
<td align="center"><b>⛓️ Farhan</b><br/><sub>Smart Contracts</sub></td>
<td align="center"><b>⛓️ Ferdinand</b><br/><sub>Smart Contracts</sub></td>
<td align="center"><b>⚙️ Naufal</b><br/><sub>Backend</sub></td>
<td align="center"><b>🎨 Faisal</b><br/><sub>Frontend</sub></td>
<td align="center"><b>🎨 Arif</b><br/><sub>Frontend</sub></td>
</tr>
</table>

<br/>

---

<div align="center">

### 🚀 Quick Start

```bash
# Smart Contracts
git clone https://github.com/RyvynPay/SC && cd SC && forge build

# Frontend
git clone https://github.com/RyvynPay/FE && cd FE && pnpm dev
```

<br/>

**MIT License** • Built for **Base Indonesia Hackathon 2025**

<br/>

_"Making profitable payments for everyone."_

</div>
