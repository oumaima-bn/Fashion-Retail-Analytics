# 🛍️ Retail Analysis – Power BI Dashboard

An interactive **Power BI** dashboard analyzing the sales performance of a group of fashion stores. It tracks sales, units sold, gross margin, and the performance of stores, districts, and buyers.



## 📌 Project Goals

- Track **sales and volumes** by store type (new stores vs. same stores), chain, district, and category.
- Compare **this year (TY) vs. last year (LY) sales** month by month.
- Identify the **top and bottom District Managers (DM)**, categories, and buyers.
- Measure **store productivity** (sales per square foot) and progress toward the new-store opening target.
- Simulate scenarios with a **What-If analysis**.

---

## 🗂️ Report Structure

The report has **4 pages**, accessible from the navigation menu on the left.

| Page | What it shows |
|---|---|
| **Overview** | Filters by store type and chain, Total Sales / Units / Store Count, Top & Bottom 3 DMs and categories, Average Unit Price, monthly sales trend, What-If slider |
| **District Analysis** | TY vs. LY sales by fiscal month, sales by district (FD-01 to FD-04, LI-01 to LI-05), variance %, bubble chart by category |
| **Item Analysis** | Men / Shoes / Juniors sales, Total Units, Total Sales, Gross Margin, Top 10 buyers, chart/table toggle |
| **Store Analysis** | Year selector (2005–2013), sales per sq ft by store, category sales, new stores vs. target, territory map, sales by chain |

---

## 📊 Screenshots

### Overview
![Overview](View1.JPG)

### District Analysis
![District Analysis](View2.JPG)

### Item Analysis
![Item Analysis](View3.JPG)

### Store Analysis
![Store Analysis](View4.JPG)

---


## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX** for measures (TY/LY sales, variance %, average unit price, sales per sq ft, etc.)
- **Power Query** for data import and transformation
- **Star schema modeling** (fact and dimension tables: store, district, item/category, buyer, time)
- Power BI features: slicers, bookmarks, What-If parameters, tooltips, page navigation

---

