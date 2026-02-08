# Global Equity Dynamics: The Growth-Decoupling Divergence (2024–2026) 🌍

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![yfinance](https://img.shields.io/badge/yfinance-API-green)](https://pypi.org/project/yfinance/)
[![Stats](https://img.shields.io/badge/Stats-Scipy.stats-orange)](https://scipy.org/)

## 📈 Project Thesis
Does revenue growth still predict stock returns? This project identifies a **Geographic Regime Divergence**. While the US market has decoupled from fundamentals in 2026, the Asian market maintains a robust, linear relationship between growth and price action.

---

## 🔬 The "Geographic Bias" Stress Test
I expanded the initial US-only study to include **50 major Asian constituents** across the TWSE, HKEX, TSE, and KRX to verify if "Growth Exhaustion" was a global phenomenon.

| Market | Sample Size | Correlation ($r$) | P-Value | Regime Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **US (NASDAQ)** | $N=20$ | $-0.04$ | $0.840$ | **Strategic/Narrative Pivot** |
| **Asia (Combined)** | $N=50$ | **$+0.61$** | **$< 0.0001$** | **Fundamental Growth** |

### 🛠 Technical Implementation
- **Cross-Border Pipeline:** Python scripts capable of parsing diverse Yahoo Finance suffixes (`.T`, `.HK`, `.TW`, `.KS`).
- **Statistical Rigor:** Pearson correlation and Significance testing ($P$-value) to eliminate "random noise" theories.
- **Reporting:** Formal analysis synthesized using **LaTeX** for institutional-grade documentation.

---

## 🌏 Key Insight: Narrative vs. Execution
The divergence suggests two distinct market behaviors in 2026:

1. **The US "Narrative" Market:** Returns are driven by "strategic turnarounds" (e.g., **INTC**) rather than revenue. Investors are pricing in long-term structural shifts, leading to a breakdown in growth correlation.
2. **The Asian "Execution" Market:** Returns are tightly tethered to physical output and hardware sales. High-growth semiconductor leaders like **SK Hynix (000660.KS)** saw returns of **+316%** mirroring their **+66%** revenue surge.



---

## ✅ Conclusions
- **Alpha is Geographic:** A "Growth" factor strategy would fail in New York but outperform in Seoul or Taipei in the current cycle.
- **Factor Decay:** US Mega-cap Tech has entered a "Factor Decay" phase where traditional growth metrics are lagging indicators.

---

## ⚙️ How to Reproduce
1. Clone the repo: `git clone https://github.com/Mariyyyaaella/Global-Equity-Dynamics`
2. Install: `pip install yfinance scipy pandas`
3. Run the Global Test: `python global_test.py`



