# Fincept Terminal

<div align="center">

[![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-C06524)](LICENSE)
[![C++20](https://img.shields.io/badge/C%2B%2B-20-00599C?logo=cplusplus)](https://isocpp.org/)
[![Qt6](https://img.shields.io/badge/Qt-6-41CD52?logo=qt&logoColor=white)](https://www.qt.io/)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)

<a href="Fincept Terminal" target="_blank"><img src="https://trendshift.io/api/badge/repositories/17028" alt="Fincept-Corporation%2FFinceptTerminal | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

### **Your Thinking is the Only Limit. The Data Isn't.**

State-of-the-art financial intelligence platform with institutional-grade financial analytics, AI automation, and unlimited data connectivity.

[📥 Download](../../releases) · [⚖️ License](LICENSE) 

![Fincept Terminal](https://raw.githubusercontent.com/Fincept-Corporation/FinceptTerminal/main/images/FinceptBanner.png)

<table>
  <tr>
    <td align="center" width="25%"><a href="Fincept Terminal"><img src="https://raw.githubusercontent.com/Fincept-Corporation/FinceptTerminal/main/images/EquityResearch.png" width="100%"/></a><br/><sub><b>Equity Research</b></sub></td>
    <td align="center" width="25%"><a href="Fincept Terminal"><img src="https://raw.githubusercontent.com/Fincept-Corporation/FinceptTerminal/main/images/Portfolio.png" width="100%"/></a><br/><sub><b>Portfolio</b></sub></td>
    <td align="center" width="25%"><a href="Fincept Terminal"><img src="https://raw.githubusercontent.com/Fincept-Corporation/FinceptTerminal/main/images/News.png" width="100%"/></a><br/><sub><b>News</b></sub></td>
    <td align="center" width="25%"><a href="Fincept Terminal"><img src="https://raw.githubusercontent.com/Fincept-Corporation/FinceptTerminal/main/images/NodeEditor.png" width="100%"/></a><br/><sub><b>Node Editor</b></sub></td>
  </tr>
</table>

</div>

---

## About

**Fincept Terminal v4** is a pure native C++20 desktop application. It uses **Qt6** for UI and rendering, embedded **Python** for analytics, and delivers professional terminal-class performance in a single native binary.

---

## Features

| **Feature** | **Description** |
|-------------|-----------------|
| 📊 **Multi-Asset Analytics** | DCF models, portfolio optimization, risk metrics (VaR, Sharpe), derivatives pricing across equity, fixed income, derivatives, portfolio, and alternatives via embedded Python |
| 🤖 **AI Agents** | 37 agents across Trader/Investor (Buffett, Graham, Lynch, Munger, Klarman, Marks…), Economic, and Geopolitics frameworks; local LLM support; multi-provider (OpenAI, Anthropic, Gemini, Groq, DeepSeek, MiniMax, OpenRouter, Ollama) |
| 🌐 **100+ Data Connectors** | DBnomics, Polygon, Kraken, Yahoo Finance, FRED, IMF, World Bank, AkShare, government APIs, plus optional alternative-data overlays such as Adanos market sentiment for equity research |
| 📈 **Real-Time Trading** | Crypto (Kraken/HyperLiquid WebSocket), equity, algo trading, paper trading engine, 16 broker integrations (Zerodha, Angel One, Upstox, Fyers, Dhan, Groww, Kotak, IIFL, 5paisa, AliceBlue, Shoonya, Motilal, IBKR, Alpaca, Tradier, Saxo) |
| 🔬 **QuantLib Suite** | 18 quantitative analysis modules — pricing, risk, stochastic, volatility, fixed income |
| 🚢 **Global Intelligence** | Maritime tracking, geopolitical analysis, relationship mapping, satellite data |
| 🎨 **Visual Workflows** | Node editor for automation pipelines, MCP tool integration |
| 🧠 **AI Quant Lab** | ML models, factor discovery, HFT, reinforcement learning trading |

---

## Installation

### Option 1 — Download Installer (Recommended)

Latest release: **v4.0.3** — [View all releases](../../releases)

| Platform | Download | Run |
|----------|----------|-----|
| **Windows x64** | [FinceptTerminal-x64.7z](../../releases) | Run installer → launch `FinceptTerminal.exe` |
| **Linux x64** | [FinceptTerminal-Linux-x64.run](../../releases) | `chmod +x` → run installer |
| **macOS Apple Silicon** | [FinceptTerminal-macOS-arm64.dmg](../../releases) | Open DMG → drag to Applications |

---

## What Sets Us Apart

**Fincept Terminal** is an open-source financial platform built for those who refuse to be limited by traditional software. We compete on **analytics depth** and **data accessibility** — not on insider info or exclusive feeds.

Recent builds also support optional **Adanos Market Sentiment** connectivity in **Data Sources → Alternative Data**. When configured, Equity Research can surface cross-source retail sentiment snapshots across Reddit, X, finance news, and Polymarket. Without an active Adanos connection, the feature remains dormant and the rest of the app behaves exactly as before.

- **Native performance** — C++20 with Qt6, no Electron/web overhead
- **Single binary** — no Node.js, no browser runtime, no JavaScript bundler
- **Full buy-side analyst toolkit** — equity, portfolio, derivatives, fixed income, corporate finance, alternatives
- **100+ data connectors** — from Yahoo Finance to government databases
- **Free & Open Source** (AGPL-3.0) with commercial licenses available

---

## Roadmap

| Timeline | Milestone |
|----------|-----------|
| **Shipped** | Real-time streaming, 16 broker integrations, multi-account trading, PIN authentication, theme system |
| **Q2 2026** | Options strategy builder, multi-portfolio management, 50+ AI agents |
| **Q3 2026** | Programmatic API, ML training UI, institutional features |
| **Future** | Mobile companion, cloud sync, community marketplace |

---

## License

> ⚠️ **Cloning, forking, or modifying this repository does NOT grant commercial rights.**
> A paid Commercial License is required for **any** business or internal company use — including forks that remove or replace Fincept's APIs with your own data sources. See **[Commercial License](https://github.com/Fincept-Corporation/FinceptTerminal/blob/main/docs/COMMERCIAL_LICENSE.md)** for binding terms.

**Dual Licensed: AGPL-3.0 (Open Source) + Fincept Commercial License**

| | |
|---|---|
| ✅ **Free under AGPL-3.0** | Personal use · Individual learning · Academic research · Open-source contributions to this repository |
| ❌ **Commercial License required** | Any business use (paid or free) · Internal company use · Startups at any stage · Hedge funds, brokerages, banks, fintechs · SaaS / hosted offerings · White-label or reselling · Forks that strip or replace Fincept APIs · Consulting deliverables · Employee training or evaluation by for-profit entities |

The license attaches to the **codebase and any Derivative Work of it**, not to specific API integrations. Substituting Fincept APIs with your own — or with any third party's — does not sever or extinguish the licensing obligation. **These terms apply to every version, branch, tag, and commit of Fincept Terminal — past, present, and future** — and remain in force indefinitely until superseded by a subsequent published version.

**Trademarks.** "Fincept", "Fincept Terminal", and the Fincept logo are trademarks of Fincept Corporation. Use in any forked, derivative, rebranded, or commercial product requires prior written permission. Removal or rebranding of these marks in a fork does not extinguish the underlying licensing obligation.

**Enforcement & Penalties.** Fincept Corporation actively monitors public repositories, app stores, cloud marketplaces, and SaaS platforms for unlicensed Commercial Use, and pursues DMCA takedowns, cease-and-desist notices, and civil action under Indian and international law. Unauthorized commercial use is subject to **liquidated damages starting at USD 50,000 per organization per year**, with higher amounts for unauthorized SaaS distribution, fork-and-replace deployments, and trademark misuse — in addition to backdated license fees, disgorgement of profits, and recovery of legal costs. **Joint and several liability** applies: any company that engages a third-party developer, integrator, or consultancy to build, modify, or deploy the Software is fully liable alongside that developer for any unauthorized use. Governing law: India · Exclusive jurisdiction: Delhi, India.


© 2025–2026 Fincept Corporation. All rights reserved.

---

<div align="center">

### **Your Thinking is the Only Limit. The Data Isn't.**

⭐ **Star** · 🔄 **Share** · 🤝 **Contribute**

</div>
