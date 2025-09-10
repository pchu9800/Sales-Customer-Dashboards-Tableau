# Sales & Customer Performance Dashboard (Tableau)

Interactive Tableau dashboards for sales and customer analytics with cross-filtering, year-over-year (YoY) comparisons, and parameter-driven filtering.

**Live Demo:** (https://public.tableau.com/app/profile/paulo.chu/vizzes)

---

## 🎯 Highlights

* **Dashboards:** Sales & Customers (with navigation buttons between them)
* **KPIs:** Total Sales, Total Profit, Total Quantity; Total Customers, Sales per Customer, Total Orders
* **Visuals:**

  * Sales & Profit by Sub-Category
  * Sales & Profit Trend over Time
  * Top 10 Customers by Profit 
  * Customer Distribution by # Orders
* **Interactivity:**

  * Click any mark to filter the current dashboard
  * **Filter button** reveals: Year (2021–2023 parameter), Category, Sub-Category, State, City, Region
  * Buttons to switch between **Sales** ↔ **Customers**
* **Comparisons:** Each KPI includes YoY variance vs previous year
* **Design:** Color-coded legends, averages/benchmarks displayed

---

## 📁 Repository Structure

```
.
├── README.md
├── tableau/
│   └── sales_customer_dashboard.twbx
```

---

## 🚀 Quickstart

1. **Clone** this repo
2. Open `tableau/sales_customer_dashboard.twbx` in **Tableau Public (Desktop)**
3. If data is local, update data source paths as needed
4. Publish to **Tableau Public** (File → Save to Tableau Public)
5. Add your published link to the **Live Demo** section above

---

## 🔧 Features in Detail

### Sales Dashboard

* **KPIs:** Total Sales, Total Profit, Total Quantity (with YoY deltas)
* **Charts:**

  * Sales & Profit by Sub-Category 
  * Sales & Profit Trend over Time 
* **Interactions:** Click bars/lines to filter; filter panel exposes Year (2021–2023), Category, Sub-Category, State, City, Region

### Customer Dashboard

* **KPIs:** Total Customers, Sales per Customer, Total Orders
* **Charts:**

  * Top 10 Customers by Profit
  * Customer Distribution by Number of Orders
* **Interactions:** Same filter panel + cross-filtering on click

### Navigation

* **Buttons** switch between Sales and Customer dashboards

---

## 📊 KPI Notes

* **Total Sales/Profit/Quantity:** Aggregate for selected filters/year
* **YoY Change:** Current year vs previous year for the same selection
* **Sales per Customer:** Total Sales ÷ Distinct Customers
* **Top 10 by Profit:** Sorted descending, ties resolved by Sales/Customer name

## 💡 Key Takeaways

* 📈 **Track sales trends and profit performance over time**  
* 🏆 **Identify top-performing products, categories, and customers**  
* 👥 **Understand customer purchase patterns and distribution**  
* ⚡ **Interactive dashboards for quick, data-driven decision making**

## 🗂 Data Source
- Sample or mock sales and customer data used for dashboard demonstration
- Includes multiple years (2021–2023), categories, sub-categories, and regional information
- Designed to showcase Tableau dashboard functionality and interactivity

## 🔮 Future Improvements
- Connect dashboards to **live data sources** (e.g., SQL or API)  
- Add **forecasting and predictive analytics** for sales trends  
- Enhance **visual storytelling** with dynamic tooltips and annotations  
- Include **geographical map visualizations** for regional insights

## 💼 Business Value
- Quickly identify top-performing products and customers  
- Spot sales trends and seasonal patterns  
- Make data-driven decisions on marketing, inventory, and customer engagement

