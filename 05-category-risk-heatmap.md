# The Category Risk Heatmap

> *A repeatable format for visualizing supplier and macro risk in a single page.*

## Why a heatmap?

Risk discussions in procurement tend to drown in qualitative narrative. Stakeholders skim. A single-page heatmap forces you to score each risk dimension explicitly, then displays the result in a format that an executive can absorb in thirty seconds.

## The five risk dimensions

Score each dimension from 1 (low risk) to 5 (high risk) for the category as a whole, and separately for each material supplier in the category.

### 1. Concentration risk

What share of the category sits with the top three suppliers? Score 1 if the top three hold less than 30%; score 5 if they hold more than 80%.

### 2. Geographic risk

How concentrated is the supply base in a single country or region? Single-country dependence in a politically volatile geography scores 5. Distributed multi-country supply scores 1.

### 3. Financial health risk

What is the financial stability of the primary suppliers? Use credit ratings, recent earnings trajectory, and any public news of distress. Investment-grade with stable outlook scores 1; sub-investment-grade with negative outlook scores 5.

### 4. Operational risk

How resilient is the supply chain to disruption? Score based on the existence of qualified backup suppliers, inventory buffers, and the time required to switch. Switchable in under 30 days scores 1; switchable only over 12+ months scores 5.

### 5. Regulatory and compliance risk

What is the exposure to changes in regulation, sanctions, ESG requirements, or trade policy? Score based on current exposure and the velocity of regulatory change in the category.

## The visualization

Build the heatmap as a 5-row table (one row per dimension) and N+1 columns (one column for the category overall, plus one column per material supplier). Color each cell using a green-amber-red gradient based on the score.

| Risk Dimension | Category | Supplier A | Supplier B | Supplier C |
| :--- | :---: | :---: | :---: | :---: |
| Concentration | 4 | 5 | 3 | 2 |
| Geographic | 5 | 5 | 4 | 1 |
| Financial Health | 2 | 2 | 1 | 4 |
| Operational | 3 | 3 | 2 | 5 |
| Regulatory | 4 | 4 | 4 | 3 |

## The narrative summary

Below the heatmap, write three sentences. The first identifies the single highest-risk cell in the table. The second identifies the most attractive risk profile across the supplier set. The third recommends the next sourcing action. That is the entire executive summary.

## Update cadence

The heatmap is a living document. Refresh it quarterly at minimum, and immediately after any material event (supplier earnings, regulatory change, geopolitical disruption). A six-month-old risk heatmap is not a risk heatmap; it is a relic.

---

*Part of the [Market Intelligence Frameworks](../README.md) repository, curated by [Tathastu Naranje](https://tathastunaranje.github.io).*
