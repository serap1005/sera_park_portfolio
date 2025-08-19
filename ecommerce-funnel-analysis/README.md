# Cosmetics E-Commerce Funnel Analysis

### **Goal**
#### Understand user drop-off behavior across **View → Cart → Purchase** stages on a cosmetics e-commerce platform.
#### Deliver **data-driven funnel insights** and actionable recommendations to improve conversion rates.
---

## **Data & Method**
- **Dataset**: Kaggle – E-commerce Events in Cosmetics Shop
- Period: October 2019
- Volume: ~8.4M records | 839,812 unique sessions

- **Funnel Metric Calculation**:
  - Computed unique session counts per event stage
  - Calculated stepwise conversion rates:
    - View → Cart: 16.4%
    - Cart → Purchase: 16.7%
    - View → Purchase: 2.7%

- **Tableau Dashboard Creation**:
  - Built interactive funnel charts:
    - Conversion summary KPIs
    - Cart value vs. purchase probability
    - Trend over time
    - Session path mapping (user journey)
---

## **Key Findings**
- Major drop-off occurs between view and cart (~84% of sessions never add to cart).
- Mid-range product price ($10–50) bins convert significantly better than low/high extremes.
- Users who reach cart stage are highly likely to purchase (conversion >16%).
- Session path analysis shows majority follow View → Cart → Purchase flow, validating funnel linearity.

---

## **Business Impact**
- Focus UX improvements on reducing view-to-cart abandonment.
- Target discounts/promotions to high-converting price ranges.
- Use findings as a baseline A/B test benchmark for funnel optimization.
- Provide product teams with evidence to prioritize cart usability and personalized offers.

---

## **Tools**
Python (Pandas, Matplotlib, Seaborn)
Tableau Public (interactive dashboard)
