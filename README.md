# 📊 Allwyn International AG — Financial Analysis 2025

A full financial analysis of Allwyn International AG based on their 2025 Annual Report.
Built as a portfolio project to demonstrate real-world financial data analysis using Python.

---

## 🎯 The Business Questions

1. How has Allwyn grown over the last 6 years (2019–2025)?
2. Which business segments drive the most revenue and profit?
3. Which products and channels are growing fastest?
4. How healthy is the balance sheet and cash flow?
5. What strategic events shaped 2025 performance?

---

## 💡 Key Findings

- **Net Revenue grew 4% to €4.1bn in 2025** — a 19% CAGR from 2019 to 2025
- **Continental Europe generates 83% of group EBITDA** at a 44.4% margin
- **Online NGR grew 11%** vs only ~1.5% for physical — digital is the key growth engine
- **iGaming is the fastest growing product** at +11% — double digit growth across all markets
- **Net leverage rose to 2.7x** due to €904m of strategic M&A — still within the industry comfort zone of 2.5–3.5x
- **Free cash flow increased to €1.33bn** — 84% of Adjusted EBITDA converted to cash
- **The UK margin of 3.5% is temporary** — Allwyn is in Year 2 of a 10-year licence with heavy tech investment now complete

---

## 📈 Charts Produced

| Chart | Type | Key Insight |
|---|---|---|
| Revenue & EBITDA Growth 2019–2025 | Line chart | 19% Net Revenue CAGR |
| Net Revenue by Segment | Grouped bar | Continental Europe = 72% of group |
| EBITDA Margin by Segment | Grouped bar | UK 3.5% vs CE 44.4% |
| EBITDA Contribution by Segment | Bar + Pie | CE generates 83% of group EBITDA |
| NGR by Product | Grouped bar + growth % | iGaming fastest growing at +11% |
| Online vs Physical Channel | Stacked bar | Online share up to 37% (+2pp) |
| Profitability and Margin Analysis | Grouped bar | All margins slightly compressed |
| Cash Flow and Leverage | Bar + leverage chart | FCF €1.33bn; leverage 2.7x |
| M&A and Strategic Spend | Horizontal bar | €904m deployed across 5 initiatives |
| KPI Summary Dashboard | 8-card grid | Full 2024 vs 2025 at a glance |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python 3.11 | Programming language |
| Pandas | Data loading, cleaning, aggregation |
| Matplotlib | All chart creation |
| Jupyter Notebook | Interactive analysis environment |

---

## 📁 Project Structure
First_Allwyn_Analysys/

│

├── README.md

├── analysis.ipynb

│

├── csv/

│   ├── 01_financial_performance_by_segment.csv

│   ├── 02_revenue_by_product_and_channel.csv

│   └── 03_historical_track_record_2019_2025.csv

│

└── charts/

├── chart_revenue_trend.png

├── chart_segment_comparison.png

├── chart_ebitda_margins.png

├── chart_ebitda_contribution.png

├── chart_product_mix.png

├── chart_online_vs_physical.png

├── chart_margins.png

├── chart_cashflow_leverage.png

├── chart_ma_spend.png

└── chart_kpi_summary.png
---

## ▶️ How to Run

```bash
# 1. Clone this repository
git clone https://github.com/Chrisstichios/First_Allwyn_Analysys.git
cd First_Allwyn_Analysys

# 2. Install required libraries
pip install pandas matplotlib

# 3. Open the notebook
jupyter notebook analysis.ipynb
```

All 10 charts will render inside the notebook automatically.

---

## 📊 About the Data

All data is extracted from the **Allwyn International AG Annual Report and Accounts 2025**
(published April 2026), structured into 3 CSV files for analysis.

- **01_financial_performance_by_segment.csv** — 35 rows covering revenue, EBITDA,
  margins and CAPEX for each segment in 2024 and 2025
- **02_revenue_by_product_and_channel.csv** — NGR breakdown by product
  (Lottery, Sports Betting, iGaming, VLTs) and online vs physical channel
- **03_historical_track_record_2019_2025.csv** — 7 years of Net Revenue,
  EBITDA, leverage and cash flow data

*This analysis is prepared for portfolio demonstration purposes only
and does not constitute financial advice.*

---

## 👤 About

Christos Stoicheios — Junior Data Analyst
📍 Athens, Greece
🔗 [GitHub](https://github.com/Chrisstichios) | 📧 chrisstichios@gmail.com

*Part of my data analyst portfolio — built using real corporate annual report data.*
