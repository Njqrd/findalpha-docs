

---
id: frequency-distribution
title: Frequency Distribution
sidebar_label: Frequency Distribution
sidebar_position: 4
description: Distribution of monthly returns showing volatility and consistency patterns.
---

import useBaseUrl from '@docusaurus/useBaseUrl';


<img
  src={useBaseUrl('/img/frequencyDist.png')}
  alt="Radar chart comparing fund metrics"
  width="100%"
/>
This chart shows the **distribution of monthly returns** for the selected fund(s) and the benchmark. It helps users understand the **volatility** and **consistency** of returns by visualizing how often returns fall within specific ranges. The selcted metric can be chnaged using the drop down menu on the top right of the component.

Useful for spotting:

- Skewness  
- Fat tails (risk of extreme events)  
- Outliers

If you click one of the buckets, it will highlight the investemet that exist with in that bucket on the scatter chart, and grey out the ones that do not exists in the table

## Example


<img
  src={useBaseUrl('/img/FrequencyDistributionTable.png')}
  alt="Radar chart comparing fund metrics"
  width="100%"
/>