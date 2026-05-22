# 🇮🇳 FII Flow Analysis — India (2008–2026)
### *"₹5.7 Lakh Crore Nikala FII Ne — Phir Bhi Nifty Kyun Khada Hai?"*

> A data-driven Power BI dashboard exploring 19 years of Foreign Institutional Investor (FII) flows into Indian equity markets, their correlation with global macro triggers, and the structural rise of Domestic Institutional Investors (DII) as India's financial immune system.

---

## 📁 Repository Structure

```
fii-india-analysis/
│
├── data/
│   ├── FII_Master_Annual.csv        ← 19 years annual data (2008–2026)
│   └── FII_Monthly_KeyEvents.csv    ← 11 key outflow months with event tags
│
├── powerbi/
│   └── FII_Dashboard.pbix           ← Power BI dashboard file
│
├── README.md
└── DAX_Measures.md                  ← All DAX formulas used in the dashboard
```

---

## 📊 Data Sources

| Data Point | Source |
|---|---|
| FII / FPI Net Equity Flows | [NSDL — fpi.nsdl.co.in](https://fpi.nsdl.co.in) |
| Nifty 50 Historical Closing | [NSE India](https://www.nseindia.com) |
| DII Net Flows | [NSE FII-DII Reports](https://www.nseindia.com/reports/fii-dii) |
| US 10Y Treasury Yield | [FRED — St. Louis Fed](https://fred.stlouisfed.org/series/DGS10) |
| USD/INR Exchange Rate | [RBI Reference Rates](https://www.rbi.org.in) |

> ⚠️ **Note:** 2021 FII data and 2026 partial-year data should be cross-verified at fpi.nsdl.co.in before citing in research.

---

## 🔑 Key Insights from the Dashboard

### Insight 1 — The DII Dam (Most Important)
From 2022 onward, every rupee FII sold was more than absorbed by DII. In 2024, DII bought ₹5,10,000 Cr while FII net flow was near zero. India's market is no longer FII-dependent.

### Insight 2 — The US 10Y Yield Magnet
Near-perfect inverse correlation: every time US 10Y yield crossed 3%, FII began exiting India. This is the carry trade mechanism — risk-free US returns pulling capital away from emerging markets.

### Insight 3 — Nifty Resilience Paradox
2022: FII sold ₹1,21,439 Cr → Nifty fell only 4.3%
2025: FII sold ₹1,66,286 Cr → Nifty fell only 0.6%
The structural DII floor has fundamentally changed how India reacts to FII exits.

### Insight 4 — The 2026 Iran War Shock
April 2026 single-month outflow of ₹1,22,540 Cr is on track to be the largest monthly outflow ever recorded, exceeding even October 2024's ₹94,017 Cr.

### Insight 5 — USD/INR as a Leading Indicator
When USD/INR rises sharply (2011, 2013, 2022, 2026), FII outflow follows. Rupee weakness = FII's dollar-denominated return shrinks = more selling pressure.

---

## 🛠️ How to Use This Dashboard

1. Download `FII_Dashboard.pbix`
2. Open in Power BI Desktop (free download from Microsoft)
3. If data doesn't refresh — go to `Home → Transform Data → Data Source Settings` and re-point to your local CSV path

---

## 📌 About This Project

Built as part of a YouTube channel focused on explaining Indian financial markets through 3D data visualization. Every number in this dashboard traces back to an official source — NSDL, NSE, FRED, or RBI.

**Subscribe for weekly market breakdowns:** [YouTube Channel Link]
**Connect on LinkedIn:** [LinkedIn Profile]

---

## 📜 License
Data sourced from public government and regulatory databases. Dashboard design and analysis is original work. Free to use with attribution.
