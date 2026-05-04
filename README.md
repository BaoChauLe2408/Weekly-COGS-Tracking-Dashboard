# 📊 F&B Strategic COGS & Inventory Control Dashboard1

## 📝 Project Overview
This project features a comprehensive management reporting system designed for the F&B industry to monitor **Cost of Goods Sold (COGS)** and inventory dynamics. The primary goal is to provide stakeholders with actionable insights into gross margins, operational waste, and inventory efficiency to protect profitability.

## 🚀 Key Analytical Components
The dashboard is structured to provide a multi-dimensional view of cost performance:
*   **Executive Cost Monitoring**: High-level tracking of Revenue vs. Actual COGS to monitor the overall Gross Margin percentage.
*   **Category-Specific Drill-down**: Granular analysis of performance across various business lines, including Buffet (Food/Beverage), Retail, and Internal Stock Transfers.
*   **Inventory Variance & Wastage**: Detailed tracking of "Xuất hủy" (Wastage) to identify cost leakage points and improve operational discipline.
*   **Time-Series Variance Analysis**: Weekly monitoring of COGS fluctuations to detect price anomalies or sudden shifts in consumption patterns.

## 💡 Methodology: Periodic Inventory System
Rather than relying solely on theoretical POS data, this project implements the **Periodic Inventory Method** for higher financial accuracy:
1.  **Reconciliation**: Calculating **Actual COGS** via the formula: Actual COGS = Beginning + Purchases - Ending.
2.  **Shrinkage Identification**: Comparing Actual COGS against Theoretical (POS-based) COGS to quantify inventory shrinkage.
3.  **Consumption Logic**: Analyzing "Average usage per guest" to optimize recipe portioning and procurement planning.

## 🛠 Tech Stack
*   **Visualization**: Looker Studio.
*   **Data Pipeline**: Google Sheets integrated with Python for automated data cleaning and inventory logic processing.
*   **Data Sources**: POS Sales records, Physical Stocktake logs, and Supplier Invoices.

## 🔍 Project View
Below are the key modules of the dashboard:

### 1. Executive Summary & Weekly Trends
![Executive Summary](/presentation/Executive_Summary.pdf)

### 2. Deep-dive Analysis (Buffet & Beverage)
![Buffet Analysis](/presentation/Buffet_Analysis.pdf)
![Beverage Analysis](/presentation/Beverage_Analysis.pdf)

### 3. Retail & Wastage Control
![Retail Sales](/presentation/Retail_Sales.pdf)
![Wastage Tracking](/presentation/Wastage_Tracking.pdf)

### 4. Internal Stock Movements
![Internal Transfers](/presentation/Internal_Transfers.pdf)
## 📈 Strategic Impact
*   **Enhanced Transparency**: Shifted from "gut-feeling" management to data-driven cost control.
*   **Loss Prevention**: Successfully highlighted high-waste categories, enabling management to intervene and reduce cost leakage.
*   **Audit Readiness**: Provided a clear audit trail for inventory movements and price adjustments.

---
*Note: All data displayed in screenshots has been anonymized or modified to protect business confidentiality.*
