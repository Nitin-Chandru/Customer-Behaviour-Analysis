# Customer Behaviour Explorer
### Turning raw transactions into something a team can actually use

🔗 Try the live explorer: https://public.tableau.com/views/CustomerBehaviourExplorer-NitinC/Dashboard1  
An interactive tool to identify valuable, inactive, and loyal customers in seconds.

---

## Why this project exists

Many data projects try to answer who our best customers are.

But that only works if behaviour is measured clearly.

Before targeting users, a team first needs to understand:

**How does each customer actually behave?**

If that is unclear, any marketing or automation built on top becomes unreliable.

This project focuses on making behaviour understandable before making predictions.

---

## The dataset problem

Retail transaction data records purchases, not behaviour.

Each customer appears across multiple rows, making it difficult to directly answer questions like:

- Who is loyal?
- Who is valuable but inactive?
- Who buys frequently but spends little?

So the goal was to transform raw transactions into stable behavioural signals.

---

## Approach

### 1. Convert transactions into behaviour

Three interpretable metrics were created:

| Behaviour | Meaning |
|--------|------|
| Frequency | How often a customer purchases |
| Value | Total contribution generated |
| Recency | How recently they were active |

This creates a dependable representation of engagement.

---

### 2. Create understandable segments

Instead of predictive scoring, customers are grouped into intuitive categories:

- Loyal & high value
- Frequent buyers
- Big spenders
- Low engagement

The goal is immediate human understanding, not statistical complexity.

---

### 3. Build a decision interface

The Tableau dashboard allows anyone to:

- spot valuable customers instantly
- find inactive high-value users
- compare behaviour patterns
- explore retention opportunities

Rather than a one-time analysis, it acts as a lightweight internal tool.

---

## What this demonstrates

Most analytics projects explain the past.

This project focuses on enabling decisions.

---

## If this evolved into a real product

1. **Measurement** — standardise behaviour tracking  
2. **Understanding** — provide live behavioural exploration *(current stage)*  
3. **Action** — introduce targeting and automation

---

## How to explore

Open the dashboard and try answering:

- Which valuable customers stopped purchasing recently?
- Who buys frequently but contributes little value?
- Which users should retention focus on?

Hover over customers and use filters to explore behaviour.

---

## Repository contents

- dataset — transaction and customer data
- calculations — behavioural metric definitions
- dashboard — interactive behaviour explorer
- README — product case study explanation

---
