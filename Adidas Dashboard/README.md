# 🏃‍♂️ **Adidas Sales Performance Dashboard (Power BI)**

A comprehensive analytics project built in **Power BI** to analyze Adidas’ product performance, sales trends, retailer contribution, and customer behavior.
The dashboard delivers actionable insights across product categories, gender segments, regions, retailers, sales methods, and time-based performance.

---

## 🧠 **Project Inspiration**

This dashboard was inspired by modern retail BI dashboards and was developed to demonstrate strong skills in:

* Data modeling
* Business performance analysis
* Visual storytelling
* KPI design & time-intelligence in Power BI

---

## 📁 **Project Overview**

This Power BI project explores Adidas sales data across **three perspectives**:

1️⃣ **Product Analysis**
2️⃣ **Sales Analysis**
3️⃣ **Retailer Analysis**

The goal is to uncover insights around:

* Product category performance
* Unit sales by gender
* Regional contributions
* Year-over-year sales trends
* Retailer share & channel performance
* Forecasting & anomaly detection

---

## 🗂️ **Dataset Overview**

The dataset includes transactional sales data from Adidas retail channels.
Key fields include:

| Category          | Fields                                                         |
| ----------------- | -------------------------------------------------------------- |
| **Date**          | Transaction Date, Year, Quarter, Month                         |
| **Product**       | Product Category (Apparel, Athletic Footwear, Street Footwear) |
| **Customer**      | Gender Type (Men, Women), Region, State, City                  |
| **Retail**        | Retailer, Retailer ID, Sales Method (In-store, Online, Outlet) |
| **Sales Metrics** | Units Sold, Total Sales, Operating Profit, Operating Margin    |
| **Pricing**       | Price per Unit                                                 |

A dedicated **Date table** was created for accurate time-intelligence.

---

## 🧩 **Data Model**

The model centers on a fact table:

* `AdidasSalesdata` (sales transactions)

with relationships to:

* `Date` table
* Implicit dimensions (Retailer, Product Category, Region, etc.)

### 🔗 Key Relationship

`AdidasSalesdata[Transaction Date]` → `Date[Date]` (one-to-many)

This supports:

* YoY comparisons
* Forecasting
* Seasonal trend analysis
* Hierarchical drilldowns

---

# 📊 **Dashboard Pages**

Below are the visual summaries **with your linked PNG snapshots**.

---

## 1️⃣ **Product Analysis**

<img width="1024" height="592" alt="Product Analysis" src="https://github.com/user-attachments/assets/56d6418e-3c4a-4982-963e-922c2c961412" />

### 🎯 Key Insights

* Street Footwear leads in total units sold.
* Apparel and Athletic Footwear show balanced performance.
* Strong gender segmentation insights: some categories perform better among specific gender groups.
* Root Cause Analysis reveals geographical drivers (e.g., Southeast region performance).

### 📈 Visuals

* Units Sold by Product Category
* Units Sold by Category & Gender
* Decomposition Tree (Root Cause Analysis)
* Regional contribution breakdown

---

## 2️⃣ **Sales Analysis**

<img width="1024" height="592" alt="Sales Analysis" src="https://github.com/user-attachments/assets/77448645-c7eb-4ff7-8a00-3c3fab9d5c74" />

### 🎯 Key Insights

* Total Sales in 2021 reached **€177M+** with stable profit margins.
* Women contributed slightly more to total sales than men.
* Sales Method mix shows strong performance from In-store and Online channels.
* A 2022 sales forecast projects continued growth with visible seasonality.
* Anomaly detection highlights unusual sales spikes or dips.

### 📈 Visuals

* KPIs: Total Sales, Units Sold, Profit, Avg Margin, Avg Price per Unit
* Total Sales (2020 & 2021) + 2022 Forecast
* Sales by Gender
* Sales by Sales Method
* Trend line with forecast + confidence interval

---

## 3️⃣ **Retailer Analysis**

<img width="1024" height="592" alt="Retailer Analysis" src="https://github.com/user-attachments/assets/4b797a0c-c9c5-41f6-9ae1-29083647c458" />

### 🎯 Key Insights

* Retailer Sales Share quantifies each retailer’s contribution to overall sales.
* Sales YoY (%) highlights top-growing retailer partners.
* Retailer performance varies notably across product categories.
* Sales Method for each retailer uncovers their preferred selling channels.
* Sales Trend visualization reveals seasonal patterns for each retailer.

### 📈 Visuals

* Retailer Sales Share %
* YoY Sales Performance
* Total Sales by Retailer & Category
* Total Sales by Sales Method
* Month-by-month Retailer Sales Trend

---

# 💡 **Insights Highlights**

✔ **Product Performance:**
Street Footwear is the highest-selling category by units.

✔ **Gender Contribution:**
Women slightly lead in sales contribution across categories.

✔ **Channel Effectiveness:**
In-store and Online together dominate total sales.

✔ **Retailer Strength:**
Key partners like Foot Locker show strong category-level performance.

✔ **Forecasting:**
Sales forecasting suggests continued upward trend with predictable seasonality.

✔ **Regional Drivers:**
The Southeast region surfaced as a strong contributor during root-cause analysis.

---

# 🧠 **Skills Demonstrated**

| Skill                      | Description                                       |
| -------------------------- | ------------------------------------------------- |
| **Power BI Modeling**      | Data model, relationships, star-schema design     |
| **DAX**                    | Time intelligence, KPI measures, YoY, LY, ratios  |
| **Forecasting**            | Built-in Power BI forecasting & anomaly detection |
| **Data Visualization**     | Clean UI, Adidas-themed color palette, layout     |
| **Dashboard Storytelling** | Insight-driven narrative across pages             |
| **BI Best Practices**      | Slicers, tooltips, bookmarks, structured pages    |

---

# 🛠️ **Tools & Technologies**

| Tool                 | Purpose                                |
| -------------------- | -------------------------------------- |
| **Power BI Desktop** | Data modeling, DAX, dashboard creation |
| **Excel**            | Source data                            |
| **Power Query**      | Data cleaning & transformation         |
| **GitHub**           | Version control & portfolio hosting    |


---

# 👨‍💻 **Author**

**Vishal Venkateshan**

📧 [Email](mailto:vishal95.venkateshan@gmail.com)

🌐 [LinkedIn](https://www.linkedin.com/in/vishal-venkateshan/)

⭐ If you found this project helpful, please consider starring the repository!


