# Power BI Sales Analysis Dashboard - Awesome Chocolate

## 📌 Project Overview
This Power BI project analyzes sales data for the fictional chocolate company, **Awesome Chocolate**. The dashboard provides insights into sales, shipments, costs, and profits across various time frames, enabling better decision-making.

## 📊 Data Model
The project employs a **star schema** with:
- **Fact Table:** `shipments`
- **Dimension Tables:** `salesperson`, `product`, `geography`, `calendar`

## 📈 Key Measures & KPIs
- **Total Sales**
- **Total Boxes Sold**
- **Total Shipments**
- **Total Costs** *(derived from shipments & product data)*
- **Total Profit = Sales - Costs**
- **Profit Percentage = (Profit / Sales) * 100**
- **Low Box Shipments** *(shipments with <50 boxes)*

## 🔍 Power BI Features Used
- **DAX Measures** *(indicated by calculator symbol)*
- **Calculation Groups** for Month-on-Month (MoM) & Year-on-Year (YoY) analysis
- **Power Query / SQL** for efficient large dataset handling
- **New Card Visuals** for key metrics with reference labels
- **Slicers** for product category and geography filters
- **Bookmarks** to toggle between detailed views
- **Tooltips** displaying contextual sales breakdowns

## 🚀 Report Features & Visualizations
### **1️⃣ Sales & Profit Analysis**
- **Multi-Row Cards:** Total Profit & Profit Percentage visualization
- **Profit Breakdown:** Profit by product category

### **2️⃣ Shipment Analysis**
- **Filtered Shipments:** Analyzing low-box shipments and their impact
- **Histogram:** Shipment distribution by box count
- **Gauge Chart:** Visualizing low-box shipments

### **3️⃣ Time Intelligence**
- **Calendar Table:** Supports MoM and YoY comparisons
- **Line Chart:** Trend analysis for sales, shipments, and profit using field parameters
- **MoM Analysis:** Displays absolute and percentage changes in sales

### **4️⃣ Report Layout & Interactivity**
- **Structured Wireframe:** Summary metrics at the top, details below
- **Bookmarks:** Toggle between `People Details` and `Product Details` while preserving filters
- **Custom Tooltips:** Contextual breakdowns when hovering over data points
- **Conditional Formatting:** Enhances readability with icons, colors, and data bars

## 🎨 Design Principles
✔ **Consistency:** Uniform color schemes & formatting styles  
✔ **Clarity:** Clear labeling & intuitive navigation  
✔ **Efficiency:** Optimized performance for large datasets  
✔ **User-Friendly:** Interactive filtering and navigation tools  

![image alt](https://github.com/GauravLayak/PowerBI_Sales_DashBoard/blob/822215aec74b1e0455c42dac191fcebf31da04af/Sales%20Analytics%20Dashboard.png)

---

## 📢 Conclusion
This Power BI dashboard provides comprehensive insights into **Awesome Chocolate's** sales performance, enabling data-driven business decisions. The interactive elements enhance user engagement, making data exploration seamless and insightful.

🚀 **Next Steps:**
- Incorporate real-time data updates
- Expand analysis with customer segmentation insights
- Optimize DAX queries for further performance enhancements



