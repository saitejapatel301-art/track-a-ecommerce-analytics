# v1 Findings: Olist Delivery & Revenue

**Business question:** Which product categories and states are dragging down
on-time delivery, and what revenue is at risk because of it?

**Data:** 112,650 order items (2016 to Aug 2018). Revenue is in Brazilian reais (R$).

## Insights

1. **Revenue is concentrated in a few categories.** health_beauty (R$1,258,681),
   watches_gifts (R$1,205,006) and bed_bath_table (R$1,036,989) lead. The top 10
   categories total R$8.48M.
2. **Late deliveries cluster in a few states.** AL (20.8% of orders late),
   MA (18.0%) and SE (16.3%) are worst, versus 4.4% in SP and MG.
3. **Average delay hides the problem.** Every state averages an early delivery
   (AL is best at -8.0 days), so the late rate is the better measure.
4. **Volume grew about 4x year on year.** Q1 2017 had 5,906 items ordered,
   versus 24,097 in Q1 2018.

## Recommendation

Prioritize a logistics review for AL, MA and SE, the three states with
the highest late-delivery rates. Revenue at risk: R$51,226 in late-delivered order value across AL, MA and SE

## Data notes

- Undelivered orders are kept in the data, with no delay calculated.
- R$185,050 of revenue has no product category (blank in the source).
- Q3 2018 is a partial quarter (data ends August 2018), so the volume drop is not real.
- Volumes count order items (one row per item), not unique orders.
