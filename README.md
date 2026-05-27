# Samsung Supply Chain Analytics Dashboard

## Project Overview

This project is a Supply Chain Analytics Dashboard created for Samsung company data. The dashboard helps analyze the complete supply chain process including procurement, inventory, production, shipment, and sales.

The main goal of this project is to identify supply chain issues such as stock shortages, supplier delays, high procurement cost, production defects, shipment delays, and low-profit products.

## Business Problem

Samsung wants to improve its supply chain efficiency by reducing delays, avoiding stockouts, controlling procurement and shipping costs, improving production quality, and increasing overall profitability.

This dashboard helps supply chain analysts make data-driven decisions by providing clear insights into supplier performance, inventory status, production efficiency, shipment performance, and sales profitability.

## Dataset Description

The project uses multiple CSV files:

### Dimension Tables
- `dim_date.csv` - Contains date-related information
- `dim_customer.csv` - Contains customer details
- `dim_facility.csv` - Contains warehouse/factory/facility details
- `dim_product.csv` - Contains product details
- `dim_supplier.csv` - Contains supplier details

### Fact Tables
- `fact_inventory.csv` - Contains inventory and stock details
- `fact_procurement.csv` - Contains procurement and supplier order details
- `fact_production.csv` - Contains production quantity and defect details
- `fact_sales.csv` - Contains sales, revenue, and profit details
- `fact_shipment.csv` - Contains shipment, delivery, and logistics details

## Dashboard Objectives

- Analyze overall supply chain performance
- Track inventory levels and identify stockout risks
- Evaluate supplier performance based on cost, quality, and lead time
- Monitor production quantity and defect rate
- Analyze shipment delays and shipping cost
- Identify profitable products and customers
- Support better decision-making for supply chain operations

## Key Performance Indicators

The dashboard includes the following KPIs:

- Total Sales Revenue
- Total Profit
- Profit Margin %
- Total Procurement Cost
- Total Shipping Cost
- Total Quantity Produced
- Total Quantity Sold
- Average Supplier Lead Time
- Defect Rate %
- On-Time Delivery %
- Stockout Risk Products

## Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of supply chain performance using important KPIs such as revenue, profit, procurement cost, shipping cost, production quantity, and delivery performance.

### 2. Inventory Analysis
Analyzes stock levels, reorder points, safety stock, and facility-wise inventory. It helps identify products that are at risk of stockout.

### 3. Procurement Analysis
Analyzes supplier performance based on procurement cost, lead time, order quantity, and quality score.

### 4. Production Analysis
Tracks production quantity, defective units, defect rate, and facility-wise production performance.

### 5. Shipment Analysis
Analyzes shipment status, delivery delays, shipping cost, carrier performance, and delay reasons.

### 6. Sales and Profit Analysis
Analyzes revenue, profit, product-wise sales, customer-wise sales, and profit margin.

## Tools Used

- Power BI / Tableau / Excel
- CSV Dataset
- Data Cleaning
- Data Modeling
- Data Visualization
- Supply Chain Analytics

## Data Model

The project follows a star schema model.

Dimension tables are connected with fact tables using common keys such as:

- Date ID
- Product ID
- Customer ID
- Supplier ID
- Facility ID

This model helps in creating relationships between sales, inventory, procurement, production, and shipment data.

## Insights Generated

Some of the key insights from the dashboard include:

- Products with low stock levels
- Suppliers with high lead time
- Suppliers with high procurement cost
- Facilities with high defect rates
- Carriers causing shipment delays
- Products generating highest revenue and profit
- Customers contributing most to sales
- Areas where supply chain cost can be reduced

## Final Outcome

This dashboard provides a complete view of Samsung's supply chain operations. It helps the business improve efficiency, reduce operational costs, avoid inventory shortages, improve supplier selection, reduce shipment delays, and increase profitability.

## Project Conclusion

The Samsung Supply Chain Analytics Dashboard is useful for supply chain analysts, business analysts, and operations teams. It converts raw supply chain data into meaningful insights and supports better business decision-making.
