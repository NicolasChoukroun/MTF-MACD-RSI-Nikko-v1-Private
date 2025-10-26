# MTF-MACD-RSI-Nikko-v1-Private
MTF MACD + RSI (Nikko) v1 Private

# 🧠 MTF MACD + RSI (Nikko) v1

A professional **2-in-1 Pine Script indicator** that merges two powerful systems:
- **MTF MACD (Multi-Timeframe MACD)** — Momentum and trend analyzer  
- **RSI Divergence (Nikko)** — Reversal and divergence detector  

Easily switch between them with a simple toggle in the indicator settings.

---

## ⚙️ Overview

This script provides **two distinct analysis modes** inside a single indicator:
1. **MTF MACD Mode** → Focuses on multi-timeframe trend confirmation and momentum strength.  
2. **RSI Divergence Mode** → Focuses on reversal detection using RSI and price divergence.  

A color-coded label in the indicator pane shows which mode is active:
- 🔴 **MACD Mode**
- 🟢 **RSI Mode**

---

## 🧩 Features

### 🔄 Dual-Mode System
| Mode | Description | Color |
|------|--------------|-------|
| **MACD** | Multi-timeframe momentum analysis using EMA-based MACD calculations (15m / 1H / 1D / 1W) | 🔴 |
| **RSI** | Divergence detection between RSI and price, plus trend regression | 🟢 |

Switch easily in the settings with:
```pine
Show MACD (Uncheck for RSI)
