#  Adidas Sales Analysis Dashboard (Power BI)

An interactive **Microsoft Power BI** dashboard that analyses Adidas sales performance across time, regions, states, product categories, and retail partners — turning raw sales data into clear, decision-ready insights.



---

##  Business Problem

Sales and management teams need a single view to answer questions such as:

- How are sales trending month over month?
- Which regions and states generate the most revenue?
- Which product categories and retailers drive performance?
- How profitable is the business overall?

This dashboard translates these business needs into KPIs and visuals that can be filtered by region and time period.

---

##  Key Metrics (KPIs)

| KPI | Value |
|---|---|
| Total Sales | **$859M** |
| Operating Profit | **$317M** |
| Units Sold | **2M** |
| Price per Unit | **$45** |
| Operating Margin | **42%** |

*Values are rounded as displayed in the dashboard.*

---

##  Dashboard Features

- **Monthly Sales Trend** – area/line chart highlighting peak and low months
- **Sales by Region** – donut chart comparing West, Northeast, Southeast, South, and Midwest
- **Geographical Sales Map** – sales by U.S. state
- **Sales by Product** – revenue comparison across product categories
- **Sales by Retailer** – contribution of each retail partner
- **Interactive Slicers** – filter the entire report by **Region** and **Invoice Date** range

---

##  Key Insights

- 🌎 **West** is the top region with ~**$270M** in sales (~30% of total).
- 👟 **Men's Street Footwear** is the best-selling category at ~**$199M**.
- 🏬 **West Gear** is the leading retailer at ~**$233M**.
- 📅 Sales **peak in July** (~$95M) and are **lowest in December** (~$51M).

> These are descriptive findings from the dashboard and highlight *where* differences occur, not *why*.

---

##  Tools & Skills

- **Microsoft Power BI Desktop** – data modelling, DAX measures, visual design
- **Power BI Service** – report published to a cloud workspace
- **Microsoft Excel** – source dataset
- **Skills demonstrated:** KPI design, data visualisation, interactive reporting, business-requirement translation, dashboard storytelling

---

##  Repository Structure

```
Adidas-Sales-Analysis-PowerBI/
├── Dataset/
│   └── Adidas_Sales.csv.xlsx
├── Dashboard/
│   └── Adidas_Sales_Analysis.pbix
├── Images/
│   └── dashboard_screenshot.png
└── README.md
```

---

## ▶ How to Explore

1. Clone or download this repository.
2. Open `Dashboard/Adidas_Sales_Analysis.pbix` in **Power BI Desktop** (Windows), or upload it to **app.powerbi.com → My workspace → Upload**.
3. Use the **Region** and **Invoice Date** slicers to filter the report.
4. Hover over visuals for tooltips and click chart elements to cross-filter.

---

##  Future Improvements

- Add YoY growth and profit-margin trend measures
- Add drill-through pages for state and retailer detail
- Implement row-level security (RLS) by region
- Connect to a SQL database for scheduled refresh

---

##  Author

**Laxmi Shetty** — [GitHub: Lax-shetty](https://github.com/Lax-shetty)

