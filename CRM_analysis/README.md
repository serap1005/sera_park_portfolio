# **Customer Segmentation & CLTV Prediction for CRM Strategy (FLO E-commerce)**

**Author**: Sera Park  
**Contact**: sera.park.2026@anderson.ucla.edu  
**Dataset**: [Kaggle - flo-data-20k](https://www.kaggle.com/datasets/emrebilir/flo-data-20k-csv)

---

## **📌 Project Overview**

This project analyzes customer transaction data from FLO, a Turkish e-commerce platform, to extract insights for targeted CRM strategies.  
The focus is on customer segmentation and predicting **Customer Lifetime Value (CLTV)** for more efficient retention and marketing.

- **Goal**: Segment customers based on behavioral metrics and estimate future value.
- **Dataset**: 19,945 customers with online/offline orders, spending, and channel/category details.
- **Tools**: Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib), Jupyter Notebook

---

## **⚙️ Project Workflow**

### **1. Data Preparation & Feature Engineering**
- Combined online/offline metrics for total order count, value, and duration.
- Engineered categorical features (e.g., channel, category).
- Derived **RFM metrics** (Recency, Frequency, Monetary) for segmentation.

### **2. Exploratory Data Analysis (EDA)**
- Compared customer behavior across **channels, categories, and platforms**.
- Analyzed top purchasing trends, price ranges, and frequency patterns.

### **3. RFM Segmentation & Visualization**
- Created histograms to segment users by monetary value, recency, and frequency.
- Used `KMeans` clustering to define clear CRM customer groups.

### **4. CLTV Estimation**
- Computed expected CLTV using historical data and probabilistic models.
- Visualized and validated CLTV predictions to support retention strategies.

---

## **📊 Key Visualizations**

### **🧾 Order & Price Statistics**
<img src="images/order_num_sum_mean.png" width="45%"> <img src="images/total_price_sum_mean.png" width="45%">
<img src="images/offline_vs_online_last_order_dates.png" width="45%"> <img src="images/weekly_order_trends_by_channel.png" width="45%">

---

### **📦 Channel & Category Analysis**
<img src="images/heatmap_channel_vs_categories.png" width="45%"> <img src="images/top5_categories_by_channel.png" width="45%">
<img src="images/category_counts_top15.png" width="45%">

---

### **💳 Spending Distribution**
<img src="images/boxplot_total_order_number.png" width="45%"> <img src="images/boxplot_total_customer_value.png" width="45%">
<img src="images/histplot_total_customer_value.png" width="45%"> <img src="images/scatter_order_vs_value.png" width="45%">
<img src="images/boxplot_value_by_order_period_category.png" width="45%"> <img src="images/scatter_order_period_vs_value.png" width="45%">

---

### **📈 Target Group Comparison**
<img src="images/barplot_channel_distribution_top_vs_target.png" width="45%">
<img src="images/barplot_category_distribution_top_vs_target.png" width="45%">
<img src="images/barplot_order_num_online_offline_distribution.png" width="45%">

---

### **📐 RFM & User Distribution**
<img src="images/rfm_distribution_hist.png" width="45%">
<img src="images/rf_heatmap_user_count.png" width="45%"> <img src="images/rf_heatmap_avg_monetary.png" width="45%">

---

### **🔍 CLTV Modeling**
<img src="images/cltv_distribution.png" width="45%"> <img src="images/cltv_hist_segmented.png" width="45%">
<img src="images/kmeans_pv_cl_scatter.png" width="45%"> <img src="images/histplot_cltv_pred_segmented.png" width="45%">

---

### **🏆 Top Customer Profiles**
<img src="images/barplot_top10_pf.png" width="30%"> 
<img src="images/barplot_top10_cv.png" width="30%"> 
<img src="images/barplot_top10_cl.png" width="30%"> 
<img src="images/barplot_top10_cltv.png" width="30%"> 

---

## **💡 Strategic Takeaways**

- **Online vs Offline Behavior**: Online channels dominate in recency and volume, suggesting stronger customer engagement.
- **Top Categories & Channels**: Segmentation by top-ordered categories shows clear channel preferences, guiding channel-specific promotions.
- **RFM Segmentation**: High-value customers are distinguishable by recency and monetary value—ideal for loyalty campaigns.
- **CLTV Prediction**: Top 10 CLTV customers identified—opportunity for VIP treatment, targeted marketing, and predictive retention strategies.

