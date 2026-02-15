# 🧠 Customer Behaviour Case Study
### Turning raw transactional data into a usable decision tool

A product-thinking case study based on the KPMG Data Analytics simulation.

---

## The Core Question

Most data projects try to answer:

> *Who are our best customers?*

This project instead asks:

> **Can we even reliably recognise a customer before trying to target them?**

Because if customer measurement is inconsistent, any targeting system — no matter how advanced — becomes unreliable.

---

## Context

The dataset represents a retail business trying to identify high-value customers for marketing campaigns.

At first glance, this looks like a segmentation or modelling task.

But before deciding *who to target*, a more fundamental issue appears:

- inconsistent demographic values  
- missing attributes  
- duplicate transactions  
- fragmented records  

So the real problem becomes:

> **Not a marketing problem — a measurement problem**

---

## Approach

### 1. Validate the data before analysing it
Instead of immediately searching for trends, I treated the dataset like production telemetry.

Goal: determine whether decisions made from this data would be trustworthy.

---

### 2. Use interpretable segmentation (RFM)

Rather than predictive modelling, I applied a transparent behavioural framework:

| Metric | Meaning |
|------|------|
| Recency | How recently a customer purchased |
| Frequency | How often they purchase |
| Monetary | Value contributed |

This produces understandable customer groups instead of opaque scores.

The objective was reliability, not sophistication.

---

### 3. Build a usable internal tool

Instead of static results, I created an interactive Power BI dashboard that acts as a lightweight product.

The dashboard allows teams to explore:

- repeat customers
- recent engagement
- spending contribution
- behavioural differences between groups

The `.pbix` file in this repository represents a **prototype customer intelligence interface**, not just a chart export.

---

## What this shows

Many analytics exercises end at insight.

This project focuses on **decision readiness**.

Key learning:

> Targeting systems usually fail because inputs are unreliable, not because models are weak.

Before automation, a team needs behavioural clarity.

---

## If this became a real product

**Step 1 — Measurement**
Standardise and validate customer data collection

**Step 2 — Understanding**
Provide a live behavioural dashboard *(current prototype)*

**Step 3 — Action**
Introduce targeting and automation only after trust exists

---

## How to explore

1. Review the prepared dataset / analysis
2. Open the Power BI file
3. Interact with filters and segments
4. Observe how simple behavioural grouping already enables decisions

---

## Repository Structure

