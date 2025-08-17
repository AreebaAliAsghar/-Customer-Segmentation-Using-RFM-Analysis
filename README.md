# 👥 Customer Segmentation Using RFM Analysis  

## 🔍 Project Overview  
This project was completed **remotely at Elevvo Pathways** as part of my Data Analytics internship.  

It applies **RFM (Recency, Frequency, Monetary) analysis** to the **Online Retail Dataset (UCI)** to segment customers based on their purchasing behavior.  
The segmentation provides insights into **loyal customers, at-risk customers, and dormant customers**, enabling targeted marketing strategies.  

---

## ⚙️ Workflow & Methodology  

### 1. Data Preparation  
- Loaded the **Online Retail Dataset (UCI)**  
- Removed missing values and duplicate entries  
- Filtered for valid transactions (excluding canceled orders)  
- Feature engineering for **Recency, Frequency, and Monetary** values  

### 2. RFM Calculation  
- **Recency (R):** Days since last purchase  
- **Frequency (F):** Number of transactions per customer  
- **Monetary (M):** Total spend per customer  

### 3. Segmentation Logic  
- Assigned **scores (1–5)** to each RFM metric  
- Created **RFM segments** by combining scores  
- Grouped customers into meaningful categories such as:  
  - **Champions (High R, High F, High M)**  
  - **Loyal Customers (High F, Moderate R, Moderate M)**  
  - **At Risk (Low R, Moderate F, High M)**  
  - **Hibernating (Low R, Low F, Low M)**  

### 4. Marketing Recommendations  
- **Champions:** Exclusive discounts, early product launches  
- **Loyal Customers:** Loyalty programs, membership perks  
- **At Risk:** Win-back campaigns, re-engagement emails  
- **Hibernating:** Reminder campaigns, first-time offers  

---

## 📊 Tools & Libraries  
- **Python:** pandas, numpy  
- **Visualization:** seaborn, matplotlib  
- **Excel (optional):** pivot tables & heatmaps  

---

## 📌 Key Insights  
✔️ A small percentage of **champion customers** drive a large portion of revenue  
✔️ Many **one-time buyers** represent a re-engagement opportunity  
✔️ **Seasonal shopping peaks** suggest targeted campaigns during holidays  
✔️ **Dormant customers** require different messaging compared to loyal buyers  

