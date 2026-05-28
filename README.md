# 📊 Finance Analyst Portfolio Project — Nusantara Digital Group (Indonesia)

End-to-end **Finance Analyst** case study for a fictional Indonesian **software & digital marketing company**. It covers profitability, cost, budgeting, and forecasting analysis built entirely in **Microsoft Excel**.

> All figures are in **IDR millions**. Data is **simulated** for portfolio purposes; client names are illustrative only.

---

## 🏢 Business Context

Nusantara Digital Group operates four service lines across the Indonesian market:

| Service Line | What it does
| Influencer Marketing | Creator/KOL campaign management
| Ads Management | Paid media buying & optimization
| E-commerce Enablement | Store setup, ops & marketplace growth
| SaaS Creator Platform | Subscription tools for creators |

---

## 🎯 Objectives

- Profitability analysis (overall + by service line)
- Revenue trend analysis with Indonesian seasonality (Lebaran, Harbolnas)
- Operational cost breakdown & cost-saving opportunities
- Budget vs Actual variance analysis
- 3-month revenue & profit forecast
- Executive KPI dashboard + business recommendations

---

## 🛠️ Tools & Techniques

- **Microsoft Excel** — modelling, formulas, formatting
- **Power Query** — data shaping / cleaning logic
- **PivotTables / SUMIF–AVERAGEIF** — aggregation
- **Charts & KPI cards** — dashboard visualization
- **TREND()** — linear-regression forecasting

---

## 📈 Key Results (FY2025)

| KPI | Value
| Total Revenue | IDR 59,187 mn
| Gross Profit | IDR 31,618 mn (53.4% margin)
| Net Profit | IDR 14,391 mn (24.3% margin)
| Operating Expense Ratio | 75.7%
| Revenue Growth (Jan→Dec) | +66.3%
| Blended ROAS | 4.18x
| Average CAC | IDR 3.80 mn
| Budget Utilization | 75.6% |

The **SaaS Creator Platform** has the highest gross margin (69.7%) and **Influencer Marketing** the highest net margin (30.8%), while **Ads Management** drives volume at the lowest margin. Operational cost (46.6% of revenue) is the #1 efficiency lever.

---

## 📊 Dashboard Components

- Executive KPI cards (Revenue, Net Profit, Margins, OpEx, Growth, ROAS, CAC)
- Monthly revenue trend chart
- Net profit trend chart
- Operating cost breakdown (pie)
- Profitability by service line (bar)
- Budget vs Actual (clustered column)
- Revenue forecast — next 3 months (line)

---

## 📁 Repository Structure

```
finance-analyst-portfolio/
├── data/
│   └── finance_raw_data.csv          # 192 rows, 12 months, 4 services
├── file/
│   └── Finance_Analysis.xlsx         # KPIs, pivots, charts, forecast
├── reports/
│   ├── Financial_Report.docx         # Full analysis + recommendations
│   └── Executive_Summary.md          # One-page summary
└── README.md
```

---

## 🔍 Analysis Workflow

1. **Ingest & clean** raw client-level data.
2. **Aggregate** to monthly and service-line summaries.
3. **Calculate KPIs** — margins, growth, OpEx ratio, CAC, ROAS.
4. **Variance** — Budget vs Actual with status flags.
5. **Forecast** — 3 months via `TREND()` linear regression.
6. **Visualize** — executive dashboard.
7. **Recommend** — cost-saving & revenue-optimization actions.

---

## 💡 Business Recommendations (summary)

- **Invest more in:** SaaS Creator Platform + Influencer Marketing (best margins).
- **Cut cost in:** Operational cost (esp. Ads Management) + SaaS licence rationalization.
- **Highest profitability:** SaaS (gross margin), Influencer Marketing (net margin).
- **Marketing efficiency:** Shift spend toward highest-ROAS / lowest-CAC services; track at service level monthly.

---

## 👤 About

Built as an **intermediate-level portfolio project** for a **Junior Finance Analyst** role, demonstrating practical financial analysis, Excel modelling, and business storytelling.

*Open the workbook in Excel for the live, formula-driven dashboard.*
