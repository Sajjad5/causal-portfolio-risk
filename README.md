# Causal Attribution of Portfolio Risk
### From Correlated Factors to Interventions

This project analyzes which financial and macroeconomic risk factors 
cause changes in portfolio P&L and risk measures, and how these causal 
effects differ in normal vs stress regimes (including the Iran–USA conflict era).

## 🔍 Project Goals
- Identify causal relationships between risk factors and portfolio returns.
- Attribute portfolio P&L to interventional factor shocks.
- Compare causal effects during normal and stress periods.
- Incorporate US + German macro-financial data.
- Use ML-based causal discovery (PC algorithm) and DoWhy for causal inference.

## 📦 Data Sources
All data is **open-source**:
- US Markets: SP500, Treasury yields, credit spreads, VIX (Yahoo Finance)
- Germany: Bund yields, DAX, CPI, industrial production, ZEW sentiment (Yahoo + FRED)
- FX: EUR/USD
- Stress period: Iran–USA conflict (custom date windows)

## 🛠 Technologies
- Python
- Google Colab
- yfinance
- FRED API
- scikit-learn
- causal-learn
- DoWhy
- EconML
- pandas, numpy, matplotlib, seaborn

## 📘 Notebook
The main analysis is in:

