# Product Decisions

This project began as a customer segmentation exercise.

While exploring the data, the bigger issue became clear - different teams would interpret the same customer data differently. Marketing, support, and product could all reach different conclusions from the same dataset.

So the goal shifted from creating segments to creating a shared understanding of customer behaviour.

---

## What problem does this actually solve?

The original question:
> How should customers be segmented?

The practical problem:
> Teams don’t have a consistent way to describe customer behaviour.

Without a shared view, decisions become inconsistent:
- marketing targets the wrong users
- product optimises for the wrong features
- support prioritises the wrong accounts

The tool therefore focuses on making behaviour visible rather than defining fixed labels.

---

## Who would use this?

Anyone making decisions about customers:
- marketing
- product
- support

Their workflow is exploratory:
1. Look at customer patterns
2. Compare groups
3. form a hypothesis
4. decide what to test

The system supports reasoning, not automation.

---

## Why not cluster customers automatically?

Automatic clustering produces precise groups but unclear meaning.  
Teams tend to distrust segments they cannot explain.

Instead, simple behavioural dimensions were chosen:
- frequency
- value
- recency

These allow users to reach their own conclusions.

---

## Why make it interactive?

Static reports answer predefined questions.  
Teams rarely have predefined questions.

An interactive view lets users investigate:
- who buys often but recently stopped
- who spends a lot but rarely visits
- which customers are consistently engaged

The goal is discovery, not reporting.

---

## What would ship first?

The first version only provides visibility:
- behaviour map
- filters
- clear definitions

No recommendations yet.

---

## What would come later?

Later versions could:
- highlight unusual patterns
- suggest experiments
- integrate alerts

But only after teams build intuition using the data.

---

## Guiding idea

Before acting on customers, teams need to agree on what they are observing, and this tool builds that shared understanding.
