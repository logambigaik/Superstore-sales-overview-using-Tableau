# Superstore Sales Analytics - Tableau Dashboard

## Dashboard Overview
Interactive Tableau dashboard analyzing Superstore performance across key business dimensions. The visualization provides actionable insights into regional sales, shipping efficiency, profitability, and order prioritization.

<img width="695" alt="image" src="https://github.com/user-attachments/assets/d483ed8f-2e04-421b-b126-f8dfd0c6374a" />

---

## Dashboard Components

### 1. Sales by Region Analysis
**Map Visualization**:
- Choropleth map color-coded by total sales volume
- Drill-down capability from country → region → state
- Dynamic tooltips showing:
  - % of total sales
  - YoY growth comparison
  - Top-selling product category per region

**Supporting Charts**:
- Bar chart: Top 5 performing regions with sales/profit duality
- Donut chart: Market share distribution across regions


<img width="281" alt="image" src="https://github.com/user-attachments/assets/c2428199-8102-459f-adb6-e006621b9fae" />

---

### 2. Shipping Cost Analysis
**Primary Metrics**:
- Shipping cost as % of sales by ship mode (Standard/Express/etc.)
- Cost per unit shipped comparison chart

**Matrix Visualization**:
- Heatmap of shipping costs vs. delivery speed
- Annotated with on-time delivery rates
- Filterable by product category weight class

**Trend Analysis**:
- Line chart tracking shipping cost fluctuations quarterly
- Reference line showing industry benchmarks


<img width="271" alt="image" src="https://github.com/user-attachments/assets/f7a1e544-2586-489f-b409-0c57c01f7163" />

---

### 3. Profit Margin by Category
**Sunburst Chart**:
- Hierarchical view: Category → Sub-Category → Product
- Color gradient: Red (loss) to Green (high profit)
- Interactive click-to-zoom functionality

**Comparative Analysis**:
- Side-by-side bars comparing:
  - Profit margin %
  - Absolute profit $
  - Return rates

**Outlier Detection**:
- Scatter plot of sales volume vs. profit margin
- Highlighted points for negative margin products

<img width="295" alt="image" src="https://github.com/user-attachments/assets/061abe8b-f8a4-4a97-9d68-598dd704c4a5" />

---

### 4. Order Priority Breakdown
**Priority Dashboard**:
- Gauge charts showing fulfillment rates for:
  - Critical (red)
  - High (orange)
  - Medium (yellow)
  - Low (green) priorities

**Time Analysis**:
- Waterfall chart: Processing time by priority level
- Reference line showing SLA targets

**Impact Assessment**:
- Stacked bar chart showing:
  - Revenue contribution by priority
  - Associated shipping costs

<img width="221" alt="image" src="https://github.com/user-attachments/assets/67384e9a-7b7f-4f99-81fc-8ca41ad06310" />

---

## Interactive Features
- **Dynamic Filtering**:
  - Time slider for date range selection
  - Region/category quick-select buttons
- **Highlight Actions**:
  - Hover over any chart to cross-filter others
  - Click any data point to isolate in all views
- **View Customization**:
  - Toggle between absolute values and percentages
  - Switch view modes (trend/compare/heatmap)

---

## Technical Implementation
- **Data Preparation**:
  - Calculated fields for margin % and shipping ratios
  - Conditional formatting for priority alerts
- **Performance**:
  - Data extracts optimized for mobile viewing
  - Context filters to accelerate load times

[Explore the Interactive Dashboard](https://public.tableau.com/app/profile/logambigai.kuppusamy/viz/Superstoresalesoverview_17466269298260/SuperstoreSalesOverview)

---

## Future Roadmap
- Add supplier performance metrics
- Implement inventory-to-sales ratio
- Create customer satisfaction correlation analysis
