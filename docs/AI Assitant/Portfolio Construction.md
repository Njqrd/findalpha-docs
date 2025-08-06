---
id: portfolio-builder-overview
title: Portfolio Builder Agent Overview
sidebar_label: Portfolio Builder Overview
sidebar_position: 3
description: High-level summary of the Portfolio Construction AI Agent and its strategic output.
---

# Portfolio Builder Agent Overview

The **Portfolio Builder Agent** constructs strategic, high-conviction portfolios tailored to a user’s investment objective — whether that’s growth, income, defensiveness, or thematic exposure.

Unlike traditional static recommendations, this agent delivers **dynamic, structured portfolios** built entirely from verified ETFs and mutual funds, sourced from a pre-approved symbol list.

---

## What Does It Do?

This agent transforms natural language prompts (e.g., _"Build an aggressive portfolio with technology, small-cap, and emerging market exposure"_) into a **professionally structured investment portfolio**.

Each portfolio includes:

- **Strategic context** — what kind of investor this is for
- **Expected risk/return profile** — defined in ranges
- **Clear investment thesis** — summarized in under 200 words
- **Structured portfolio layout** — using Core, Growth, Satellite, and Defensive roles
- **Interactive breakdown** — users click through to view each fund’s rationale and performance

---

## Example Output (Aggressive Growth Portfolio)

> A high-conviction, growth-oriented portfolio that targets long-term capital appreciation by combining technology, small-cap, and emerging markets. Expected returns range from 12–18% with volatility between 18–25% and a max drawdown target of -30%. Allocations are tactically positioned with quarterly rebalancing to maintain momentum.

| Allocation Role | Fund Example | Strategy |
|------------------|--------------|----------|
| Core Growth | XLK | Broad tech sector exposure with strong historical returns |
| Satellite Growth | SMH | Semiconductor innovation and agility |
| Small-Cap Growth | VIOV | Deep small-cap value exposure for long-term upside |

All fund-specific metrics (e.g., Sharpe Ratio, Drawdown, Alpha) are shown within the **interactive portfolio UI**, not in text. Allocation weights range from **15–35%** per position.

---

## What Makes It Different?

| Feature | Description |
|--------|-------------|
| **Symbol-locked** | Only uses verified and available fund symbols — no guesses or hallucinations |
| **Metric referencing** | Refers to live metrics via placeholders like `[XLK](Sharpe_Ratio)` rather than hardcoding values |
| **Role-based structure** | Every fund is assigned a portfolio role: Core, Satellite, Growth, Defensive, etc. |
| **Minimalist, strategic messaging** | Delivers ultra-concise summaries and leaves all details to the frontend interface |
| **Behaviorally aware** | Balances expected returns with emotional risk tolerance (e.g., avoiding high-vol funds for cautious profiles) |

---

## Who Should Use It?

This agent is ideal for:

- Investors seeking **ready-to-use portfolio templates**
- Platforms needing **clickable, interactive portfolio layers**
- Financial apps offering **automated portfolio intelligence**
- Advisors designing **sample portfolios** for various client profiles

---

## Summary

The **Portfolio Builder Agent** offers clear, actionable portfolio strategies with a focus on transparency, simplicity, and data-backed rigor — all while keeping the heavy lifting in the interface, not the text.

## Example 
<iframe
  src="/pdfs/PortBuilder.pdf"
  width="100%"
  height="1000px"

>
  <p>Your browser does not support iframes. <a href="/pdfs/PortBuilder.pdf" target="_blank">Click here to view the PDF</a></p>
</iframe>