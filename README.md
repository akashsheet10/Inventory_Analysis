 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index bfe5709221eb49d081a392f1bf729d814dfce396..4dae4c59fa50ef18257c58b4f735551f6db8ae11 100644
--- a/README.md
+++ b/README.md
@@ -1,54 +1,59 @@
 # Inventory_Analysis
 # ☕ Coffee Shop Sales Analysis Dashboard
 
 An end-to-end **Excel-based Sales Analytics Dashboard** built on real transactional data from a New York City coffee shop chain. This project covers data cleaning, KPI engineering, pivot analysis, and an interactive visual dashboard — all within Microsoft Excel.
 
 ---
 
 ## 📊 Dashboard Preview
 
 ![Coffee Shop Sales Dashboard](https://github.com/akashsheet10/Inventory_Analysis/blob/main/Screenshot%202026-04-10%20220520.png?raw=true)
 ![Coffee Shop Sales Dashboard](https://github.com/akashsheet10/Inventory_Analysis/blob/main/Screenshot%202026-04-10%20220454.png?raw=true)
 
 > *Interactive Excel dashboard showing monthly revenue trends, hourly footfall, product category breakdown, and store-wise performance.*
 
 ---
 
 ## 📁 Project Structure
 
+```text
+Inventory_Analysis/
+├── README.md
+├── Copy of Coffee Shop Sales (wecompress.com).xlsx
+├── Screenshot 2026-04-10 220520.png
+└── Screenshot 2026-04-10 220454.png
 ```
-Coffee-Shop-Sales/
-│
-├── Copy_of_Coffee_Shop_Sales.xlsx   # Main Excel workbook
-│   ├── Transactions                 # Raw transactional data (149,116 rows)
-│   ├── KPI by AKASH                 # Pivot tables & KPI calculations
-│   ├── Dashboard 2.0                # Main interactive dashboard
-│   └── Dashboard 2.0 (2)           # Alternate dashboard view
-│
-├── dashboard.png                    # Dashboard screenshot
-└── README.md                        # Project documentation
+
+### Workbook Sheet Structure
+
+```text
+Copy of Coffee Shop Sales (wecompress.com).xlsx
+├── Transactions
+├── KPI by AKASH
+├── Dashboard 2.0
+└── Dashboard 2.0 (2)
 ```
 
 ---
 
 ## 📌 Dataset Overview
 
 | Field | Details |
 |---|---|
 | **Source** | Coffee Shop Chain – New York City |
 | **Time Period** | January 2023 – June 2023 (6 months) |
 | **Total Transactions** | 149,116 |
 | **Total Revenue** | $698,812.33 |
 | **Stores Covered** | 3 (Astoria, Hell's Kitchen, Lower Manhattan) |
 
 ### 🗂️ Raw Data Columns
 
 | Column | Description |
 |---|---|
 | `transaction_id` | Unique identifier for each transaction |
 | `transaction_date` | Date of the transaction |
 | `transaction_time` | Time of the transaction |
 | `transaction_qty` | Number of items purchased |
 | `store_id` | Numeric store identifier |
 | `store_location` | Store name/location |
 | `product_id` | Unique product identifier |
 
EOF
)
