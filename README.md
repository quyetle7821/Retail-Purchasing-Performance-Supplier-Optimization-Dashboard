# 📊 Procurement Spend & Supplier Performance Analysis | Retail Import/Distribution | Power BI (Power Query + DAX)
- Business questions :
  +  How does purchasing spend change over time, and what drives it by supplier/SKU?
  +  Where are the price gaps vs best price, and how much potential savings can we capture?
  +  Which suppliers deliver the best balance of cost vs delivery performance (received/on-time rate)?
- Domain : Procurement / Purchasing Analytics for a retail import & distribution company (Wide World Importers – WWI), focusing on spend control, supplier evaluation, and delivery reliability.
📌 Goal : Build a Power BI dashboard to monitor purchasing cost, ordering trends, supplier effectiveness, and provide actionable insights & recommendations to optimize procurement operations.

Author: Lê Trường Quyết
Date: 2025-09-07
Tools Used: Power BI (Power Query, DAX)

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
3. [🧠 Design Thinking Process](#-design-thinking-process)
4. [📊 Key Insights & Visualizations](#-key-insights--visualizations)
5. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? 

- This project analyzes purchasing data from Wide World Importers (WWI) in Power BI to help the business understand where money is spent, what items drive cost, and which suppliers perform best :
  
    ✔️ Analyze WWI purchasing data in Power BI to understand spend trends and the main drivers by supplier and SKU.
  
    ✔️ Identify price gaps vs best price and estimate potential savings to support negotiation and cost control.
  
    ✔️ Evaluate supplier performance (cost + delivery/received rate) and turn insights into actionable procurement recommendations.

  👤 Who is this project for?

    ✔️ Procurement / Purchasing managers
    ✔️ Supply chain & warehouse teams
    ✔️ Finance / management stakeholders
  
## 📂 Dataset Description & Data Structure 

### 📌 Data Source
   
  - Source: Wide World Importers (WWI) – a sample data warehouse dataset 
  - Size : 
    + Tables (sheets): 13 tables
    + Total rows: ~915,249 rows across all tables 
    + Columns: varies by table (6 → 21 columns)
  - Format : .xlsx
### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used:  
  The dataset consists of 6 main tables used to build the WWI Purchasingdashboard:
  - 🧾 Fact_Transaction – Transaction-level purchasing spend (Total Incl/Excl Tax, PO ID…).
  - 📦 Fact_Movement – Order/receipt movements to calculate Ordered/Received Qty & Received Rate.
  - 🏭 Dim_Supplier – Supplier master data (supplier name, category, payment terms…).
  - 🏷️ Dim_StockItem – SKU master data (unit price, lead time days, quantity per outer…).
  - 📅 Dim_Date – Calendar table for month/quarter/year analysis & time intelligence.
  - 🔁 Dim_TransactionType – Classifies movement/transaction types (used for ordered vs received logic).
#### 2️⃣  Data Relationships:  
  <img width="948" height="762" alt="image" src="https://github.com/user-attachments/assets/95e706a0-df95-48a1-9507-1ef0857f13a6" />



















