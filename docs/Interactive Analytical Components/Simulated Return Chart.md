---
id: return-chart
title: Simulated Return Chart with Drawdowns
description: Time-series visualization of portfolio growth and drawdown analysis.
sidebar_label: Simulated Returns Chart
sidebar_position: 3
---

import useBaseUrl from '@docusaurus/useBaseUrl';

## Simulated Return Chart with Drawdowns

<img
  src={useBaseUrl('/img/returnchart/returnchart.png')}
  alt="Simulated return chart with drawdown visualization"
  width="100%"
/>

This component visualizes the **simulated monthly return** of the selected fund, its peer (hovered), and the benchmark. It models portfolio growth starting from a fixed amount (e.g., **€10,000**) over the selected time frame.

---

### Chart Lines

- **Green line**: Selected fund (e.g., IAU)
- **Dashed white line**: Hovered peer (e.g., FBTC)
- **Purple line**: Benchmark

Each line shows the simulated growth trajectory based on **compounded monthly returns**.

---

### Drawdown Overlay

- **Drawdown duration** (in months) and **severity** (in %) are annotated visually.
- Each drawdown is shown as a highlighted box over the return line.

> In the example above:
> - FBTC shows a **22.2% drawdown** lasting **5 months**
> - Benchmark shows an **8.9% drawdown** over **4 months**

---

### Toggle Visibility

Click the **eye icon** in the top-right corner to toggle drawdown visibility on/off.

---

### Interactions

- Hover over the chart to view **tooltip values** by date.
- Zoom or pan depending on the implementation (if enabled).

---

### Use Cases

- Understand fund resilience and **drawdown behavior** over time.
- Compare actual return **trajectories** vs total returns.
- Detect **recovery times** and **volatility patterns** across funds.

---

### Notes

- Return data respects the **selected currency and timeframe**.
- Drawdown metrics are calculated dynamically based on monthly closing values.

---
