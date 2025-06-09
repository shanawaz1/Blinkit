# Blinkit Sales Analytics Dashboard

## Project Overview

This Power BI project delivers a comprehensive sales analytics dashboard for **Blinkit**, India’s last-minute app. The dashboard is designed to provide actionable insights into sales performance, item distribution, outlet characteristics, and customer ratings across outlet types and locations. It enables business stakeholders to make data-driven decisions by visualizing key performance indicators (KPIs), trends, and breakdowns with interactive filters and a modern, user-friendly design.

---

## Key Features

### 1. Interactive Filters (Slicers)
- **Outlet Location Type:** Filter by Tier 1, Tier 2, or Tier 3 outlets.
- **Outlet Size:** Analyze performance by Small, Medium, or High-sized outlets.
- **Item Type:** Drill down into specific product categories.
- **Clear All Slicers:** Instantly reset all filters for a holistic view.

### 2. High-Level KPIs
- **Total Sales:** $1.20M
- **Average Sales:** $141
- **Number of Items:** 8,523
- **Average Rating:** 3.9  
These KPIs provide a snapshot of overall business health and performance.

### 3. Sales Trend Analysis
- **Outlet Establishment Year:**  
  - Line and area charts visualize annual sales from 2011 to 2022.
  - Highlights key milestones and sales peaks (e.g., $205K in 2017).
  - Identifies growth patterns and seasonal trends.

### 4. Product & Item Analysis
- **Fat Content Breakdown:**  
  - Donut chart splits total sales between Low Fat ($425K) and Regular ($776K) items.
- **Top Item Types:**  
  - Horizontal bar chart ranks categories by total sales (e.g., Fruits & Vegetables, Snack Foods, Household, Dairy).
- **Fat by Outlet:**  
  - Bar chart shows sales distribution by fat content across outlet location types.

### 5. Outlet Segmentation
- **Outlet Size Distribution:**  
  - Donut chart visualizes sales by outlet size: Medium ($249K), Small ($445K), High ($508K).
- **Outlet Location Type:**  
  - 100% stacked bar chart compares sales across Tier 1 ($336.40K), Tier 2 ($393.15K), and Tier 3 ($472.13K) locations.

### 6. Outlet Type Performance Table
- **Detailed Table:**  
  - Displays Outlet Type, Total Sales, Number of Items, Average Sales, Average Rating, and Item Visibility.
  - Conditional formatting highlights key metrics for quick comparison.

---

## Technical Details

- **Data Preparation:**  
  - Data cleaned and transformed using Power Query (M language).
  - Relationships established between sales, items, and outlet tables.

- **Data Modeling:**  
  - Star schema with fact and dimension tables.
  - Calculated columns and measures created using DAX for KPIs, sales aggregations, and ratings.

- **DAX Highlights:**  
  - Measures for total sales, average sales, item counts, and ratings.
  - Use of functions like `COUNTROWS`, `SUM`, `AVERAGE`, `CALCULATE` for dynamic insights.

- **Visualization:**  
  - Combination of cards, donut charts, bar charts, line/area charts, and tables.
  - Slicers for interactivity and dynamic filtering.
  - Conditional formatting for visual emphasis.

- **User Experience:**  
  - Clean, modern UI with a consistent yellow theme reflecting Blinkit branding.
  - Responsive layout for easy navigation and data exploration.

---

## Business Insights

- Sales are highest in Tier 3 locations and high-sized outlets.
- Regular fat items outperform low-fat items in total sales.
- Fruits & Vegetables and Snack Foods are top-selling categories.
- Sales peaked in 2017, indicating a significant business milestone.
- Average sales per item and customer ratings are consistent across outlet types.

---

## How to Use

1. Open the Power BI report (`.pbix` file) in Power BI Desktop.
2. Use the filter panel on the left to explore sales performance by outlet type, size, and item category.
3. Interact with visualizations for deeper insights into trends, product performance, and outlet segmentation.
4. You can also interact with charts and filter them based on your selection.

---

## Potential Enhancements

- Integrate time intelligence (YoY, MoM growth).
- Add drill-through pages for detailed outlet or item analysis.
- Incorporate predictive analytics for sales forecasting.
- Enable export of filtered data for business users.

---

## Repository Structure

---

## License

This project is licensed under the apache 2.0  License.

---

*For questions or contributions, please open an issue or submit a pull request.*

