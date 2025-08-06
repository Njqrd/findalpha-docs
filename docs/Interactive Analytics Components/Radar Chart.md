---
id: radar-chart
title: Fund Metrics Radar Chart
description: Visual comparison of normalized fund metrics for selected fund, peer, and benchmark.
sidebar_label: Radar Chart
sidebar_position: 2
---

import useBaseUrl from '@docusaurus/useBaseUrl';

## Fund Metrics Radar Chart

<img
  src={useBaseUrl('/img/radarChart.png')}
  alt="Radar chart comparing fund metrics"
  width="100%"
/>

The radar chart displays a **normalized visual comparison** of key performance metrics across:

- The **selected fund**
- A **peer fund (hovered)**
- The **benchmark**

All metrics are **normalized across the full dataset**, allowing meaningful relative comparisons even when the original scales differ.

---

### How It Works

Each axis represents one performance metric:

- **Rate of Return**
- **R/R Ratio**
- **Sharpe**
- **Sortino**
- **Alpha**
- **Volatility**
- **Beta**
- **Drawdown**

> All metrics are scaled to a [0, 1] range internally to enable proper polygon comparisons. Higher values indicate "better" performance, except where contextually reversed (e.g., lower drawdown = better).

---

### Interactions

- The **selected fund** is shown in green.
- The **peer (hovered fund)** is displayed with a dashed white outline.
- The **benchmark** is shown in purple.
- Hover over each polygon to see tooltips with raw values.

---

### Use Cases

- Quickly assess **performance strengths and weaknesses** at a glance.
- Validate if a fund outperforms a benchmark **across multiple metrics**, not just return.
- Compare **risk-adjusted metrics** like Sharpe and Sortino vs volatility and drawdown.

---

### Notes

- Radar values are updated based on **selected time period and currency**.
- The chart automatically updates when the user changes the **hovered** or **pinned** fund.

---
