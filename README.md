Customer Behaviour Case Study — From Raw Data to a Decision Tool

A product-thinking case study based on the KPMG Data Analytics simulation.

This project is not about building the most complex model.
It is about answering a simpler and more important question:

If a team had this data, what could they safely do with it?

Why this project exists

The dataset represents a retail company that wants to identify high-value customers for marketing campaigns.

At first, this looks like a segmentation task.

But before deciding who to target, a more basic concern appears:

Can the business consistently recognise the same customer over time?

If the answer is uncertain, any targeting system — no matter how advanced — becomes unreliable.

So instead of jumping to prediction, this project focuses on something more fundamental:

Turning raw data into something a team can actually trust and use.

What I did
1) Checked whether the data is usable

Rather than immediately analysing trends, I first treated the dataset like a real product telemetry source.

I looked for issues that would break a real system:

unrealistic ages and invalid birth dates

inconsistent category labels

incomplete records

duplicate or fragmented transactions

missing customer attributes

The goal here was simple:
before building intelligence, verify measurement.

2) Created a reliable behavioural view (RFM segmentation)

Instead of predictive modelling, I used a transparent segmentation method:

Metric	What it tells us
Recency	Who came back recently
Frequency	Who returns often
Monetary	Who contributes meaningful value

This produces understandable behavioural groups rather than abstract scores.

The intention was not to be fancy — it was to be dependable.

3) Built a usable internal tool (Power BI dashboard)

Rather than presenting static results, I built an interactive dashboard that acts like a lightweight product.

The dashboard allows someone in marketing or operations to explore:

repeat customers

recent activity

spending contribution

differences between customer groups

The Power BI file in this repo is meant to be used, not just viewed.

It represents the first usable version of a “customer intelligence system”.

What this project shows

Many data projects answer:

What happened?

This project tries to answer:

What can a team confidently act on?

The main learning:

Targeting systems fail less often because of bad models and more often because of unreliable inputs.

Before automation, a business needs behavioural clarity.

If this were developed further

A realistic product direction would be:

Step 1 — Measurement
Make customer data consistent at entry

Step 2 — Understanding
Give teams a live behavioural dashboard

Step 3 — Action
Only then introduce targeting and automation

The dashboard in this repo represents step 2.

How to explore the project

Review the cleaned dataset / notebooks to understand preparation

Open the Power BI file

Interact with filters to see how customer groups change

Observe how simple segmentation already enables decisions

Repository contents

dataset — simulated retail customer & transaction data

analysis — preparation and segmentation logic

dashboard.pbix — interactive behavioural dashboard

README — case study explanation
