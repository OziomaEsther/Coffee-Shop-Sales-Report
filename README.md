#  Coffee Shop Sales Dashboard  

##  Project Overview  
Imagine you’re running a busy coffee shop chain. You want to know:  
- Which products sell the most?  
- Which days and hours are busiest?  
- How sales are growing (or declining) month by month?  

This project analyzes coffee shop sales data from **January to June 2023** using **Power BI**.  
The goal was to turn raw transaction data into a clear, interactive dashboard that reveals **business performance trends** at a glance.  
 
 *This dashboard was inspired by a tutorial video on building a Coffee Shop Sales Dashboard in Power BI By "Data Tutorials". I replicated it as part of my learning journey, but expanded on the documentation, storytelling, and insight generation to strengthen my understanding of dashboard design and DAX.*  

By combining **KPIs, Month-over-Month (MoM) growth, tooltips, and heatmaps**, the dashboard not only tracks sales but also tells a story of customer behavior and shop performance over time.  

---

## Objective  
The main objective was to **design an interactive dashboard** that helps decision-makers:  
1. Track **Total Sales, Total Orders, and Total Quantity Sold**.  
2. Monitor **growth trends month-over-month (MoM)**.  
3. Discover **peak business hours and days** through a sales heatmap.  
4. Break down performance by **product categories, product types, and locations**.  

---
## Key Dashboard Features  

### **1. KPI Cards**  
- Show **Total Sales, Total Orders, and Total Quantity Sold**.  
- Built using **DAX measures** for accurate aggregation.  

### **2. Month-over-Month Growth Analysis**  
- DAX formulas calculate changes between months.  
- Indicators:  
  - ▲ Positive growth  
  - ▼ Negative growth  
  - “No Previous Month” (for January baseline).  

 **Insight**: February saw a decline in all KPIs, but sales rebounded from March onward.  

### **3. Interactive Tooltips**  
- **Calendar View Tooltip** → Hovering on a day highlights its sales contribution.  
- **Sales by Day & Hour Tooltip** → Quickly reveals peak hours without switching charts.  
- This keeps the main dashboard clean while allowing deeper exploration.  

### **4. Sales Heatmap**  
- Visualizes sales intensity by **day of the week** and **hour of the day**.  
- Helps identify peak customer traffic (e.g., morning rush or weekend spikes).  

### **5. Breakdown Filters**  
- **Product Category** → Coffee, Tea, Bakery, etc.  
- **Product Type** → Subcategories within each product line.  
- **Location** → Compare sales across different stores.  

---

##  Key Insights  

- **February 2023**: Decline in MoM growth across all KPIs → a potential business challenge.  
- **March to June 2023**: Steady recovery and consistent upward momentum.  
- **June 2023**: Peak performance month with the highest **sales, orders, and quantity sold**.  

This pattern highlights the importance of **seasonality** and tracking **early warning signals** (like February’s dip).  

---

##  Technical Learnings  

Building this dashboard helped me strengthen several Power BI skills:  

- **DAX Measures**  
  - Created calculations for KPIs and MoM growth differences.  
  - Applied conditional logic for ▲ / ▼ indicators.  

- **Tooltip Pages**  
  - Linked visuals to hidden pages for cleaner interactivity.  
  - Delivered contextual insights without overwhelming the main dashboard.  

- **Heatmap Design**  
  - Used matrix visuals with conditional formatting to reveal patterns.  

- **Dashboard Storytelling**  
  - Structured visuals in a logical flow: KPIs → Trends → Details → Deep Dive.  
  - Focused on making it intuitive for both beginners and business decision-makers.  

---

##  Why This Project Matters  

This project is more than just a dashboard. It shows how **data storytelling** can transform raw numbers into business decisions:  
- Spotting **early warning signs** of decline (February).  
- Identifying **peak performance** months (June).  
- Understanding **customer behavior** (heatmap insights).  

It’s a demonstration of combining **analytics + design + storytelling** to make data **accessible, actionable, and insightful**.  

---

 
