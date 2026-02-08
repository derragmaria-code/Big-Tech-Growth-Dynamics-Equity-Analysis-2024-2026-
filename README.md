# Big Tech Growth Dynamics Equity Analysis (2024–2026) 🚀

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![yfinance](https://img.shields.io/badge/yfinance-API-green)](https://pypi.org/project/yfinance/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)

This project investigates the **shifting relationship between fundamental health and market performance** for mega-cap technology firms. While initially hypothesized as a **"Growth-Dominant Regime,"** stress-testing revealed a transition into a **Strategic Value Regime** in early 2026.

---

## Project Overview

This pipeline automates the extraction and statistical validation of financial metrics to identify **market drivers**.  

**Core Question:**  
> Does top-line revenue growth still dictate investor returns in a post-AI-hype market?

**Key Result:**  
Quantitative evidence confirms a **regime shift**, where **strategic positioning** (e.g., Foundry expansion, monopoly power) now outweighs simple revenue velocity.

---

## 🛠 Data Pipeline

- **Extraction:** Automated retrieval of NASDAQ-20 ticker data via the `yfinance` API.  
- **Statistical Validation:** Pearson correlation coefficients (\(r\)) and P-values calculated using `scipy.stats`.  
- **Reporting:** Findings typeset in LaTeX for **institutional-grade documentation**.

---

## 📊 Key Findings: From Hypothesis to Reality

| Phase | Hypothesis | Statistical Result | Market Verdict |
|-------|------------|------------------|----------------|
| Pilot (N=3) | Growth-Dominant | \( r = +0.98 \) | High correlation; growth rewarded |
| Stress Test (N=20) | Growth-Dominant | \( r = -0.04 \), \( p = 0.84 \) | Hypothesis invalidated; Strategic Value Pivot |

---

### The Strategic Value Pivot

- **The Anomaly of 2026:** Negative-growth firms (e.g., INTC) **outperformed** high-growth firms (e.g., PLTR) due to **strategic turnaround premiums**.  
- **The Monopoly Moat:** Infrastructure monopolies (e.g., ASML) maintained **high returns** despite low growth, proving **market criticality** is the new alpha.  




---

## ✅ Takeaways

1. **Growth alone no longer drives returns** in mega-cap tech.  
2. **Strategic execution and market dominance** are the primary drivers in 2026.  
3. Future analyses should emphasize **Free Cash Flow Yield, strategic initiatives, and critical market positioning**.

---

---

## 🔗 References

- [yfinance API](https://pypi.org/project/yfinance/)  
- [scipy.stats documentation](https://docs.scipy.org/doc/scipy/reference/stats.html)

---



