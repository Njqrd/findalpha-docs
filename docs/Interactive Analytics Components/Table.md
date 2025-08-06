---
id: table
title: Table
sidebar_label: Table
sidebar_position: 1
description: Interactive fund and ETF performance table with sorting and comparison features.
---

# Table


import useBaseUrl from '@docusaurus/useBaseUrl';

## Fund & ETF Performance Table

<img
  src={useBaseUrl('/img/table/fulltable.png')}
  alt="Fund and ETF Performance Table Screenshot"
  width="100%"
/>

This interactive table component displays fund and ETF performance data, fully **unified to the selected time period and currency**. It supports advanced metrics, inline sorting, tooltips with formulas, and interactive row behavior for comparison.

---


### Interactive Features

#### Hover-to-Explain
Hovering over a **column header** displays:
- A **tooltip** with explanation of the metric
- The **formula** used to derive the value

<video width="950" controls>
  <source src="/videos/Column%20Headers.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>

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

