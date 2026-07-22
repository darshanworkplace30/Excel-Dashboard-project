# FNP (Ferns & Petals) Sales Analysis Dashboard

## 📊 Project Overview
A comprehensive **Excel-based analytical dashboard** analyzing sales performance, customer behavior, and product trends for Ferns & Petals—a gift delivery service specializing in occasion-based gifting (Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries).

This project demonstrates end-to-end **data cleaning, transformation, and visualization** using modern Excel tools.

---

## 🎯 Key Metrics
- **Total Orders:** 1,000
- **Total Revenue:** ₹3,520,984
- **Average Delivery Time:** 5.53 dayS
- **Average Customer Spend:** ₹3,520.98

---

## 🛠️ Data Processing & Methodology

### 1. **Data Cleaning (Power Query)**
- **Merged datasets:** Combined Orders, Products, and Customers tables using relationship keys
- **Standardized text fields:** Cleaned occasion and category names for consistency
- **Created calculated columns:**
  - `Order_Time`: Extracted hour-of-day from order timestamp
  - `Delivery_Days`: Calculated days between order and delivery dates
  - `Customer_Segment`: Categorized by spending levels

### 2. **Data Modeling (Power Pivot)**
- Built **star schema** relationships:
  - Orders (Fact Table) → Products, Customers (Dimension Tables)
  - Created diagram view to visualize table relationships
  - Ensured referential integrity across all connections
- **Problem Solved:** Initial pivot tables showed duplicate values; resolved by establishing proper many-to-one relationships in Power Pivot

### 3. **Analysis & Visualization (Pivot Tables)**
Created 6 pivot tables based on key business questions:
1. **Revenue by Occasions** → Identify peak-performing occasions
2. **Revenue by Category** → Track product category performance
3. **Revenue by Hours** → Understand time-of-day ordering patterns
4. **Revenue by Months** → Seasonal trends analysis (2023 data)
5. **Top 5 Products by Revenue** → Best-performing SKUs
6. **Top 10 Cities by Orders** → Geographic demand hotspots

### 4. **Interactive Dashboard**
- **KPI Cards:** Four key metrics displayed prominently
- **6 Visualizations:** Mix of bar, line, and area charts
- **Dynamic Slicers:** Filter by Order Date, Delivery Date, and Occasion
- **Color Scheme:** Professional green palette matching brand guidelines

---

## 💡 Key Insights

### Revenue Drivers
- **Top Occasion:** Diwali and Raksha Bandhan generate highest revenue
- **Top Product:** Magnum Spl leads revenue followed by Qua Gift and Deluxe Gift
- **Top Category:** Cakes dominate revenue generation

### Customer Behavior
- **Peak Orders:** February and March show highest monthly sales
- **Geographic Concentration:** Kolkata, Bangalore, Delhi, and Pune are top-performing cities
- **Order Timing:** Evening hours (16:00-20:00) see peak ordering activity

### Delivery Performance
- **Average Turnaround:** 5.53 days from order to delivery
- **Consistency:** Delivery times stable across order quantities (no correlation spike)

---

## 📊 Dashboard Features

| Feature | Description |
|---------|-------------|
| **KPI Cards** | At-a-glance view of critical metrics |
| **Interactive Slicers** | Filter data by date ranges and occasions |
| **6 Chart Types** | Bar, line, and area charts for different perspectives |
| **Color-Coded Design** | Intuitive visual hierarchy with consistent branding |
| **Responsive Layout** | Organized grid for easy navigation |

---

## 🔧 Technical Stack
- **Microsoft Excel** (Data analysis & visualization)
- **Power Query** (ETL and data transformation)
- **Power Pivot** (Data modeling and relationships)
- **Pivot Tables** (Aggregation and summarization)
- **Excel Charts** (Dynamic visualizations)
- **Slicers** (Interactive filtering)

---

## 📈 Business Impact
This dashboard enables FNP to:
- ✅ Identify seasonal trends and adjust inventory accordingly
- ✅ Optimize marketing spend by occasion and geography
- ✅ Monitor delivery performance and customer satisfaction metrics
- ✅ Track product performance and recommend promotion
- ✅ Make data-driven decisions on expansion strategies

---
