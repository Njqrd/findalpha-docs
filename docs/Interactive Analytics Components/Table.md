---
sidebar_position: 6
title: Table
---

# Table


import useBaseUrl from '@docusaurus/useBaseUrl';

## Fund & ETF Performance Table

<img
  src={useBaseUrl('/img/fund-table-screenshot.png')}
  alt="Fund and ETF Performance Table Screenshot"
  width="100%"
/>

This interactive table component displays fund and ETF performance data, fully **unified to the selected time period and currency**. It supports advanced metrics, inline sorting, tooltips with formulas, and interactive row behavior for comparison.

---

### Table Columns & Hover Tooltips

Hover over any column header to reveal:
- A **short description** of the metric.
- The **mathematical formula** used to compute the value.

| Column               | Tooltip Content (on Hover)                           |
|----------------------|------------------------------------------------------|
| **Return**           | Sparkline preview of historical price movements     |
| **Currency**         | Selected currency (e.g., EUR, USD, GBP, CHF)        |
| **Rate of Return**   | Total percentage return over selected period        |
| **R/R Ratio**        | Risk/Return Ratio (reward per unit of risk)         |
| **Sharpe**           | Sharpe Ratio (risk-adjusted return)                 |
| **Sortino**          | Downside-adjusted return metric                     |
| **Alpha**            | Excess return over benchmark                        |
| **Volatility**       | Annualized standard deviation                       |
| **Beta**             | Correlation with benchmark                          |
| **Drawdown**         | Maximum observed peak-to-trough drop                |
| **Symbol**           | Ticker symbol of the fund/ETF                       |

---

### Interactive Features

#### Hover-to-Explain
Hovering over a **column header** displays:
- A **tooltip** with explanation of the metric
- The **formula** used to derive the value

#### Column Sorting
Clicking any column header sorts the table by that metric. The direction is indicated by an arrow:
- 🔼 Ascending
- 🔽 Descending

#### Row Hover Previews
Hovering over a **row** displays a **mini performance chart** for that specific fund or ETF.

#### Pin Rows for Comparison
Clicking a row **pins** that fund/ETF:
- Pinned funds are persistently highlighted
- Compared against the **benchmark** and the **currently hovered row**
- Ideal for quick visual comparisons

---

### Customization Context

The table always reflects the **user’s selected time period and currency**. All metrics and chart data adapt dynamically to those settings.

---

### Example Workflow

1. **Set** your preferred time frame (e.g., 3Y) and currency (e.g., EUR).
2. **Hover** over the **Sharpe** header to learn what it means and how it's calculated.
3. **Click** the **Alpha** column to sort funds by their excess returns.
4. **Hover** the row for `iShares Gold Trust` to see its sparkline.
5. **Click** to **pin** it for direct comparison with your benchmark and any other hovered fund.

---

### 🛠 Accessibility & UX

- All interactive elements are accessible via keyboard.
- Tooltips are screen-reader friendly.
- Sort icons and pinned rows are clearly styled for accessibility.

---

### Image Asset

Make sure to place your image at:

