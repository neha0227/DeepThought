# DeepThought
Deep Thought
# DeepThought Assignment — Target Company Research


part A 
## Overview
This project identifies 25 companies in Pune across specialty manufacturing and industrial instrumentation that fit DeepThought’s "Federer Company" ICP.

## Contents
- companies.csv → Final list with scoring
- methodology.md → Research approach
- notes.md → Observations and learnings

## Approach
- Selected Pune as manufacturing hub
- Focused on specialty chemicals + instrumentation
- Applied 6-point Federer scoring model
- Verified each company manually

## Key Insight
Most companies initially identified failed due to:
- Revenue > ₹500Cr
- Being traders/service providers
- Lack of growth signals

Final list includes only verified companies with evidence-backed scoring.

## Disclaimer
All data is based on publicly available sources and manually verified to reduce AI hallucination.



part B : 
 Question 1: Sourcing Methods
1. DSIR-Recognized R&D Units
Why useful: Indicates companies investing in R&D → strong signal of differentiation (C3)
Limitation: Misses newer startups

2. Industry Expo Exhibitor Lists
Examples: CPHI India, IMTEX, ELECRAMA
Why useful: Companies spend money to exhibit → strong growth intent (C6)
Limitation: Skews toward companies with marketing budgets


3. BSE SME / NSE Emerge
Why useful: Public financials → easy revenue validation
Limitation: Only listed companies

4. Regulatory Databases
Examples: USFDA, EU-GMP
Why useful: Strong proof of manufacturing + export quality
Limitation: Pharma-heavy

5. MCA Database
Why useful: Large-scale company discovery using NIC codes
Limitation: Noisy, requires filtering



6. LinkedIn Sales Navigator
Why useful: Helps identify technical founders (C4)
Limitation: Self-reported data



💡 Insight:
A multi-source + deduplication approach is necessary to ensure quality and scale.

🚀 Question 2: 1000-Company Proposal
🎯 Goal
Build a list of 1000 ICP-qualified companies in 30 days.

🔄 Funnel Model
4000 companies (raw)↓2500 after filtering↓1400 AI-qualified↓1000 final verified

📅 Week-wise Plan
🗓️ Week 1 — Sourcing
Collect 3500–4000 companies from:


DSIR list
Expo lists
McA database
LinkedIn


Perform:
Deduplication
Website identification


 Week 2 — AI Scoring
Scrape company websites:
About, products, leadership

Use AI to:
Score C1–C6
Extract structured insights

 Week 3 — QA + Re-scoring
Identify:
False positives
Missing data
Re-score borderline companies

 Week 4 — Finalization
Manual verification of 300–400 companies
Finalize 1000 companies
Add personalization hooks






 HAND-DRAWN DIAGRAM (DRAW THIS)
Draw this on paper exactly like this:
         SOURCES(DSIR | Expo | MCA | LinkedIn)               ↓        4000 Companies               ↓        Filtering Stage   (Remove traders, large firms)               ↓        2500 Companies               ↓        AI Scoring (C1–C6)               ↓        1400 Shortlisted               ↓        Borderline Review               ↓        Human QA               ↓        FINAL 1000

