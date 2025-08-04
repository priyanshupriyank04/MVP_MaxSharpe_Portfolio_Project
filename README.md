# **NIFTY 50 – Minimum Variance & Maximum Sharpe Portfolio Optimization**

This project applies **Modern Portfolio Theory (MPT)** to build and compare two optimized portfolio strategies using **NIFTY 50** historical stock data.

---

## **Minimum Variance Portfolio (MVP)**

**Objective:** Minimize overall portfolio volatility while staying fully invested.  
**Focus:** Risk reduction through diversification.

**Variants explored:**
- **Long-Only** – No short selling; all positions between 0–100%.  
- **Long-Short Market-Neutral** – Equal long & short exposure, net market exposure = 0.  
- **Long-Short Non-Neutral** – Allows directional bias while using both longs & shorts.  

---

## **Maximum Sharpe Portfolio (MSP)**

**Objective:** Maximize risk-adjusted returns (**Sharpe Ratio**).  
**Focus:** Best return for each unit of risk.

Implemented as a **Long-Only** portfolio with position size capped at **5% per stock**.

---

## **Data**
- **5 years** of daily closing price data for NIFTY 50 stocks.
- Processed to calculate:
  - Daily returns  
  - Annualized returns  
  - Annualized volatility  

---

## **Results Summary**
- **MVP Strategies** → Best suited for stability and lower drawdowns; perform well in sideways/choppy markets.  
- **MSP Strategy** → Stronger performance in bullish markets due to higher exposure to high-return stocks.  
- **Comparison against NIFTY 50 benchmark** shows trade-offs between return maximization and risk control.

---
