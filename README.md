# 📉 Short-Term Reversal Trading Strategy: A Market Timing Analysis

## 🧠 Project Overview

This project investigates the **short-term reversal (STR)** phenomenon in equity markets—an anomaly where stocks that have underperformed in the past month tend to outperform in the following month, and vice versa. Using decile-based portfolio analysis across multiple decades, market regimes (recessions vs. expansions), and weighting schemes (equal-weighted vs. value-weighted), we empirically explore the performance and viability of this contrarian investment strategy.

## 🎯 Objectives

- Validate the existence and consistency of short-term reversal patterns.
- Examine STR performance across different time periods and economic regimes.
- Compare portfolio construction approaches: **equal-weighted vs. value-weighted**.
- Investigate how **liquidity, volatility, and market cycles** impact STR returns.
- Analyze the **January Effect** as a seasonal amplifier of STR performance.

## 🧪 Methodology

- Constructed **decile portfolios** based on past 1-month returns.
- Measured the **spread portfolio** (Decile 10 - Decile 1) to evaluate reversal effects.
- Separated analysis across:
  - **Recessions vs. Expansions**
  - **Decade-by-decade trends**
  - **Equal vs. Value weighting**
  - **January vs. other months**

## 📊 Key Findings

### 🔄 Short-Term Reversal Exists
- **Decile 1 (past losers)** consistently outperformed **Decile 10 (past winners)** in subsequent months, particularly in **equal-weighted portfolios**.

### 🟠 Equal-Weighted Portfolios
- Amplify STR due to higher sensitivity to small-cap and illiquid stocks.
- Showed a **68.5% frequency** of negative spread returns.
- **STR strongest during recessions**, e.g., 1973–75 and 2020, suggesting use as a hedge during market stress.

### 🟢 Value-Weighted Portfolios
- STR effects are muted due to dominance of large-cap stocks.
- Showed **55.9% frequency** of negative spread returns.
- More stable across business cycles but lower alpha potential from STR.

### 📉 January Effect
- **Decile 1 stocks** posted much higher returns in January (**+3.03%**) vs. other months (**+0.86%**).
- Likely driven by tax-loss selling, window dressing, and seasonal rebalancing.
- **Spread portfolio (Dec 10 - Dec 1)** was **most negative (-2.65%)** in January.

### 📉 Recession vs. Expansion
- STR strategies **perform best in recessions** due to increased volatility and overreaction.
- During expansions, mispricings decline, and momentum factors dominate.

## ⚖️ Risk Factors & Limitations

- **High transaction costs** from frequent rebalancing, especially with illiquid small-cap stocks.
- **Volatility and liquidity exposure** are higher in equal-weighted portfolios.
- Performance varies **cyclically**, requiring adaptive strategy implementation.

## 🛠️ Tools & Data Sources

- **Data**: CRSP or equivalent time-series returns (inferred from structure)
- **Tools**: Python (Pandas, NumPy, Matplotlib), Excel (assumed for calculations and graphs)
- **References**: Peer-reviewed literature on STR, liquidity, and behavioral finance

## 📚 Key References

- Da, Liu & Schaumburg (2014) — _Management Science_
- Jegadeesh & Titman (1995) — _Review of Financial Studies_
- Cheng et al. (2014) — _SSRN: Liquidity Provision & STR_
- Kaul & Nimalendran (1990) — _Journal of Financial Economics_
- Simpson et al. (2011) — _STR & Industry Momentum_

## 📌 Conclusion

Short-term reversal strategies remain a **viable source of alpha**, especially in small-cap and illiquid segments of the market. While effective during periods of distress and in January, these strategies face challenges from **transaction costs, volatility, and dynamic market behavior**. Practitioners must weigh these factors when constructing STR-based portfolios.

---

> _“Markets are efficient most of the time, but not all of the time—and STR strategies exploit that inefficiency in short bursts.”_

