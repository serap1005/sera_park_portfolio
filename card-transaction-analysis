# **Card Transaction Analysis & Market Entry Fit**

Analyze large-scale credit card transactions to profile consumer behavior, identify high-value categories (“core stores”), and assess alignment with a new brand’s market profile for district entry decision-making.

---

## **Business Problem**
A retail brand is evaluating **District A** for new store entry, but lacks historical local performance data.  
Using **card spending data**, the goal is to determine:
- Does the district’s consumer spending pattern match the brand’s product and service profile?
- Which store categories drive the highest sales and visits?
- How do consumers behave across weekends, holidays, and payment options?

---

## **Data Overview**
- **Transactions:** 3.36M rows (2016–2018)
- **Columns:** store_id, date, time, card_id, amount, installments, days_of_week, holyday, weekend (engineered)
- **Period Coverage:** 3 years of daily transaction data
- **Key Features:** Refunds as negative amounts, sparse installment usage, explicit holiday/weekend flags

---

## **Methods**
1. **Exploratory Data Analysis (EDA)** – category/store ranking by **transaction count** and **sales amount**
2. **Core Store Definition** – top recurring categories with sustained share across years
3. **Behavioral Segmentation** – weekend vs. weekday, holiday impact, installment adoption
4. **Year-over-Year Share Tracking** – shifts in category dominance
5. **Strategic Fit Assessment** – alignment of local demand with brand profile

---

## **Key Findings**
- **Transaction Scale:** ~3.36M transactions, avg. ticket ~₩832; refunds up to –₩250K present
- **Weekend Mix (Core Stores):** ~30.9% weekend vs. 69.1% weekday transactions
- **Holiday Impact:** ~4.4% of transactions occur on holidays
- **Installment Usage:** Rare overall (~0.5% of all transactions) but potentially strategic for high-ticket items
- **Category Dominance Shift:**
  - **2017:** store 753 led with 44% share; store 1342 had 27.7%
  - **2018:** store 1342 rose to 37.2%, store 0 to 31.7%, while store 753 dropped to 13.9%
- **Implication:** The local market is dynamic—category leadership changes significantly year-over-year

---

## **Business Recommendations**
- **Entry Decision:** Match brand’s target category with the **current** leading store types; 2018 mix favors store 1342– and 0–type categories
- **Staffing Strategy:** Weekend transactions at ~31% justify higher Fri–Sun staffing; holiday spikes are modest but worth capturing
- **Promotional Targeting:** Installments should be targeted to high-ticket categories rather than mass campaigns
- **Refund Policy:** Negative transactions indicate the need for strict refund monitoring in top-volume stores

---

## **Key Visuals**
<img src="images/core_weekend_vs_weekday.png" width="400">  
<img src="images/core_holiday_vs_nonholiday.png" width="400">  
<img src="images/core_installments_count.png" width="400">  
<img src="images/yoy_sales_share_core.png" width="400">

---

## **Tech Stack**
**Python**: pandas, matplotlib, seaborn  
**Analytics**: share/ratio analysis, time-based segmentation, category share tracking  
**Focus**: Turning EDA into actionable **market-entry recommendations**
