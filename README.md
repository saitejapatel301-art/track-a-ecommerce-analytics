# Track A: E-Commerce Delivery & Revenue Analysis

**Business question:** Which product categories and states are dragging down
on-time delivery, and what revenue is at risk because of it?

**Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
(Kaggle), 112,650 order items, 2016 to Aug 2018. Revenue is in Brazilian reais (R$).

**Current version:** v1.0, static Excel analysis

## Version history

| Version | What it is | Link |
|---|---|---|
| v1.0 | Static Excel analysis: pivot tables + findings memo | [/v1-excel](./v1-excel) |
| v2.0 | Interactive Power BI dashboard | Coming next |
| v3.0 | AI Q&A app grounded in the metrics | Planned |

## Key findings (v1)

- Revenue is concentrated: health_beauty (R$1,258,681), watches_gifts (R$1,205,006) and bed_bath_table (R$1,036,989) lead. The top 10 categories total R$8.48M.
- Late deliveries cluster in a few states: AL (20.8% of orders late), MA (18.0%) and SE (16.3%), versus 4.4% in SP and MG.
- Average delay hides the problem: every state averages an early delivery, so late rate is the better measure.
- **Recommendation:** prioritize a logistics review for AL, MA and SE. Revenue at risk: R$51,226 in late-delivered order value across these three states.

Full details: [v1-excel/finding.md](./v1-excel/finding.md)

## Tech stack

Excel, Power Query, Pivot Tables, Git