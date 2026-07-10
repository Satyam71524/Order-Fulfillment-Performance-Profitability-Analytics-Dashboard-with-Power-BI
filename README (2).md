# Order Fulfillment Performance & Profitability Analytics Dashboard

## 📊 Project Overview

This Power BI dashboard analyzes order fulfillment efficiency and its impact on overall profitability. By leveraging detailed e-commerce and logistics data, this solution uncovers patterns in delivery performance, lead time, and customer behavior—enabling data-driven decision-making for supply chain optimization and revenue growth.

---

## 🔍 Key Insights

- **Lead Time Analysis**: Track average lead time and its fluctuations across shipping modes, customer regions, and product categories.
- **Late Delivery Risk Impact**: Quantify the impact of delivery delays on order profitability.
- **Customer Segment Performance**: Identify the most valuable customer segments by sales and profit contribution.
- **Shipping Mode Comparison**: Assess delivery reliability and risk by shipping mode.
- **Product Profitability**: Highlight high- and low-performing products using sales and profit metrics.

---

## 📁 Dataset Columns Used

- **Order & Shipping Info**: `order date`, `shipping date`, `Delivery Status`, `Late_delivery_risk`, `Shipping Mode`
- **Financial Metrics**: `Order Profit Per Order`, `Order Item Product Price`, `Order Item Discount`, `Sales`, `Benefit per order`
- **Customer Data**: `Customer Segment`, `Customer Country`, `Customer State`, `Customer Id`
- **Product Details**: `Product Name`, `Product Category`, `Category Name`, `Product Price`
- **Location Data**: `Latitude`, `Longitude`, `Order Region`, `Order City`

---

## 🧮 Key DAX Measures

- `Avg Lead Time = AVERAGEX(...)`
- `Late Delivery Count = CALCULATE(...)`
- `Profit Margin % = DIVIDE(...)`
- `Late Delivery Profit Loss = SUMX(...)`
- `On-Time Delivery Rate = DIVIDE(...)`

---

## 📈 Visualizations

- KPI Cards: Orders, Avg Lead Time, Late Deliveries %, Total Profit
- Line Chart: Lead Time Trend Over Time
- Line Chart - Total Sales and Profit By Month, Year
- Bar Chart: Profitability by Customer Segment
- Stacked Column Chart: Shipping Mode vs Late Delivery Risk
- Matrix: Late Delivery by Region and Delivery Status
- Matrix: Profit Margin Distribution
- Drillthrough Pages: Product and Customer Analytics

---

## 🎯 Business Impact

This dashboard enables stakeholders—including supply chain managers, product teams, and sales analysts—to:

- Reduce lead times by identifying bottlenecks
- Minimize late delivery losses
- Optimize shipping strategies
- Improve customer satisfaction
- Focus on high-performing segments and products

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Interactive Visualizations**

---

## 📎 File Name

`Order Fulfillment Performance & Profitability Analysis.pbix`

---

## 🙌 Author

**Satyam**  
Graduate Student | Business Analytics & Finance  
University at Buffalo, School of Management

---

