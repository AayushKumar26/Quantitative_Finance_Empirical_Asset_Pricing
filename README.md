# Quantitative Finance & Empirical Asset Pricing

**ECO764: Financial Econometrics** — Course Project, IIT Kanpur
Aayush Kumar (230027)

Empirical financial-econometrics work in **Python** spanning stylized facts of asset
returns, volatility modeling, factor investing, futures price discovery, arbitrage, and
event-driven options strategies — applied to Indian equity, index, and derivatives data.

---

## Repository Structure

```
├── Assignment 1/   Stylized facts of daily equity returns
├── Assignment 2/   7-part empirical study (volatility, factors, futures, arbitrage)
│   └── Code files/ Q1–Q7 Jupyter notebooks
└── Assignment 3/   Event study — parliamentary election & capital markets
```

---

## Assignment 1 — Stylized Facts of Asset Returns

Statistical analysis of **daily BSE Sensex returns (2000–2025)**, documenting the classic
empirical properties of financial return series:

- **Small average returns** — mean daily return negligible relative to volatility
- **Serial correlation** — near-zero autocorrelation in returns (weak-form efficiency)
- **Volatility clustering** — strong, persistent autocorrelation in *squared* returns
- **Non-normality** — negative skewness and high excess kurtosis (fat tails)
- **Leverage effect** — negative returns followed by higher future volatility

Includes Python code for data download, return computation, and all diagnostic plots
(ACF, return distribution vs. normal density).

---

## Assignment 2 — Empirical Study (7 Parts)

A multi-part quantitative study across volatility, cross-sectional pricing, and futures
markets:

1. **Volatility modeling** — GARCH(1,1) fit to index returns; volatility clustering & fat tails
2. **Factor investing** — Value / Size / Momentum / Market portfolios; Sharpe ratios,
   drawdowns, and Fama-French 3-factor / IVOL–CAPM analysis
3. **Continuous futures** — series construction via FX conversion & Panama back-adjustment
4. **Price discovery & hedging** — cointegration & VECM; optimal hedge ratios and
   variance-reduction comparison (OLS vs. VECM)
5. **Arbitrage** — cost-of-carry model; identification of mispricing / arbitrage windows
6. **Climate & freight derivatives** — temperature-based derivative pricing
7. **Futures & spot volatility** — test of the destabilisation hypothesis

Code for each part is in `Assignment 2/Code files/` as `Q1.ipynb` … `Q7.ipynb`.

---

## Assignment 3 — Event Study: Elections & Capital Markets

Case study on the impact of the **2009 Indian parliamentary election** on capital markets,
using real options and equity data:

- **Options strategies** — long call, bull call spread, long straddle & long strangle;
  payoff formulas and diagrams
- **Performance evaluation** — realized returns across strategies post-result
- **Hedging effectiveness** — protective-put analysis across strikes (ICICI Bank, Reliance)
- **Return dispersion** — Nifty 50 stock returns and sector-rotation patterns
- **Downside scenarios** — bearish / high-volatility strategies referencing the 2008 crash

---
