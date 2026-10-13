# 🛍️ Retail Analysis – Power BI Dashboard

An interactive **Power BI** dashboard analyzing the sales performance of a group of fashion and apparel stores (the **Fashions Direct** and **Lindseys** chains). It tracks sales, units sold, gross margin, and the performance of stores, districts, and buyers.

---

## 📌 Project Goals

- Track **sales and volumes** by store type (new stores vs. same stores), chain, district, and category.
- Compare **this year (TY) vs. last year (LY) sales** month by month.
- Identify the **top and bottom District Managers (DM)**, categories, and buyers.
- Measure **store productivity** (sales per square foot) and progress toward the new-store opening target.
- Simulate scenarios with a **What-If analysis**.

---

## 🗂️ Report Structure

The report has **4 pages**, accessible from the navigation menu on the left.

### 1. Overview
- **Filters**: store type (*New Store* / *Same Store*) and chain (*Fashions Direct* / *Lindseys*).
- **KPIs**: Total Sales, Total Units, and store count by store type and by chain.
- **Rankings**: Top 3 / Bottom 3 sales by District Manager and by category.
- **Average Unit Price**.
- **This year's sales trend** by fiscal month.
- **What-If analysis**: a slider to simulate a change (e.g., 50%) in sales.

### 2. District Analysis
- **Filters**: store type and District Manager.
- **TY vs. LY sales** by fiscal month (area chart).
- **Total sales by district** (FD-01 to FD-04, LI-01 to LI-05).
- **Sales variance (%)** by fiscal month.
- **Bubble chart**: sales variance %, average $/unit, this year's sales, and category.

### 3. Item Analysis
- **Sales by major category**: Men, Shoes, Juniors.
- **Overall KPIs**: Total Units, Total Sales, Gross Margin.
- **Top 10 by Buyer**: units, sales, and gross margin.
- **Chart type selector**: toggle between chart and table views.

### 4. Store Analysis
- **Year selector** (2005 → 2013).
- **Sales per square foot** by store.
- **Category sales**.
- **New stores vs. target** (donut chart).
- **Territory map** of total units sold.
- **Total sales by chain**.

---

## 📊 Screenshots

> Add your screenshots to an `images/` folder and adjust the paths below if needed.

| Overview | District Analysis |
|---|---|
| ![Overview](view1.JPG) | ![District Analysis](view2.JPG) |

| Item Analysis | Store Analysis |
|---|---|
| ![Item Analysis](view3.JPG) | ![Store Analysis](view4.JPG) |

---

## 🔑 Key Metrics (examples from the report)

| Metric | Value |
|---|---|
| Total Sales (Item Analysis) | $45.18M |
| Total Units | 8.48M |
| Gross Margin | $18.97M |
| Men / Shoes / Juniors Sales | $8.91M / $7.22M / $6.04M |
| Average Unit Price (new stores, Lindseys) | $6.66 |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX** for measures (TY/LY sales, variance %, average unit price, sales per sq ft, etc.)
- **Power Query** for data import and transformation
- **Star schema modeling** (fact and dimension tables: store, district, item/category, buyer, time)
- Power BI features: slicers, bookmarks, What-If parameters, tooltips, page navigation

---

## 📁 Repository Structure

```
├── Retail_Analysis.pbix     # Power BI file (rename to match yours)
├── images/                  # Report screenshots
│   ├── data1.JPG
│   ├── data2.JPG
│   ├── data3.JPG
│   └── data4.JPG
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repository>.git
   ```
2. Open the `.pbix` file with **Power BI Desktop** (Windows).
3. If needed, update the data source: *Home → Transform data → Data source settings*.
4. Navigate between pages using the left-hand menu and use the filters to explore the data.

---

## 💡 Key Insights (adapt to your own analysis)

- **Fashions Direct (FD)** districts generate significantly more sales than **Lindseys (LI)** districts.
- Sales fluctuate strongly across fiscal months, with a notable peak in March compared to last year.
- **Men**, **Shoes**, and **Juniors** are the top-contributing categories.
- A handful of buyers account for a large share of sales and gross margin.

---

## 👤 Author

**<Your Name>**
- LinkedIn: <link>
- GitHub: <link>

---

## 📄 License

This project was created for educational / portfolio purposes. Specify your preferred license here (e.g., MIT).
