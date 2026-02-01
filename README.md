# AI TradingVision GPX

**Professional MT5 Expert Advisor for GBPUSD — Multi-Timeframe Trend Strategy with Strict Risk Control**

---

## Overview

AI TradingVision GPX is a MetaTrader 5 Expert Advisor designed for **GBPUSD** on the **M1** timeframe. It uses a multi-timeframe trend approach (M1 + M5 + H4) with moving averages, session filters, and strong risk management to target consistent growth with controlled drawdown.

---

## Performance Highlights

| Metric | Typical Result |
|--------|----------------|
| **Test Period** | 2020.01.02 – 2020.12.11 (~11 months) |
| **Symbol / Timeframe** | GBPUSD, M1 |
| **Total Net Profit** | ~2,900+ |
| **Balance Drawdown** | ~4.3% |
| **Profit Factor** | ~3.67 |
| **Total Trades** | ~114 |
| **Expected Payoff** | ~25 per trade |

*Results from backtest (Every tick model); live/demo results may vary by broker, spread, and market conditions.*

---

## Key Features

- **Multi-timeframe filter** — M1, M5, and H4 alignment for higher-probability trend entries  
- **Session-based trading** — London AM (9–11) and NY (14–17) for liquid hours  
- **Trailing stop** — Locks in profit as the market moves in your favor  
- **Breakeven** — Moves SL to entry after small profit to protect capital  
- **Early exit for losers** — Cuts losing trades at a preset loss level to limit drawdown  
- **Drawdown limits** — Stops new entries when total or daily drawdown exceeds set %  
- **Margin-aware lot sizing** — Caps lots when deposit is small so trades open without margin errors  
- **Time-based close** — Closes all positions at a fixed time (e.g. 02:00) for clean daily reset  

---

## Requirements

- **Platform:** MetaTrader 5 (MT5 only)  
- **Symbol:** GBPUSD (optimised)  
- **Timeframe:** M1  
- **Model:** Every tick (for backtesting)  
- **Deposit:** 3000+ (1:100) recommended for full lot; EA auto-reduces lots on smaller accounts  

---

## Quick Start

1. Copy **AI_TradingVision_GPX_Clone.ex5** to `MQL5/Experts/`
2. Restart MT5 or refresh Navigator
3. Attach to a **GBPUSD M1** chart
4. Enable **AutoTrading** (green button in toolbar)

For detailed setup, parameters, and backtest tips, see **[Usage_Guide.md](Usage_Guide.md)**.

---

## Project Structure

```
├── Experts/
│   └── AI_TradingVision_GPX_Clone.mq5   # EA source
├── Usage_Guide.md                        # Full parameter & usage guide
└── README.md
```

---

## Disclaimer

Trading forex involves risk. Past backtest performance does not guarantee future results. Use on demo first and only risk capital you can afford to lose.

---

*AI TradingVision GPX — Built for disciplined, rule-based trend trading.*
