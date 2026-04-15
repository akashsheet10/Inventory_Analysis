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

```
Coffee-Shop-Sales/
│
├── Copy_of_Coffee_Shop_Sales.xlsx   # Main Excel workbook
│   ├── Transactions                 # Raw transactional data (149,116 rows)
│   ├── KPI by AKASH                 # Pivot tables & KPI calculations
│   ├── Dashboard 2.0                # Main interactive dashboard
│   └── Dashboard 2.0 (2)           # Alternate dashboard view
│
├── dashboard.png                    # Dashboard screenshot
└── README.md                        # Project documentation
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
| `unit_price` | Price per unit ($) |
| `product_category` | High-level product group |
| `product_type` | Specific product type |
| `product_detail` | Full product name/description |
| `revenu` | Revenue generated from the transaction |
| `transaction date text` | Date in readable text format |
| `days of week` | Day number (1–7) |
| `hour` | Hour of transaction (24-hr format) |

---

## 🏪 Store Performance

| Store Location | Transactions | Revenue |
|---|---|---|
| Hell's Kitchen | 50,735 | $236,511.17 |
| Astoria | 50,599 | $232,243.91 |
| Lower Manhattan | 47,782 | $230,057.25 |
| **Total** | **149,116** | **$698,812.33** |

> All three stores show remarkably balanced performance, reflecting consistent brand standards across locations.

---

## 📈 Monthly Revenue Trend

| Month | Revenue |
|---|---|
| January | $81,677.74 |
| February | $76,145.19 |
| March | $98,834.68 |
| April | $118,941.08 |
| May | $156,727.76 |
| June | $166,485.88 |

> 📈 Revenue grew **~104%** from January to June, indicating strong seasonal demand and business growth.

---

## 🛍️ Product Category Breakdown

| Category | Transactions | Revenue |
|---|---|---|
| Coffee | 58,416 | $269,952.45 |
| Tea | 45,449 | $196,405.95 |
| Bakery | 22,796 | $82,315.64 |
| Drinking Chocolate | 11,468 | $72,416.00 |
| Coffee Beans | 1,753 | $40,085.25 |
| Loose Tea | 1,210 | $11,213.60 |
| Flavours | 6,790 | $8,408.80 |
| Packaged Chocolate | 487 | $4,407.64 |
| Branded | 747 | $13,607.00 |

> ☕ **Coffee** alone accounts for nearly **39%** of all revenue, followed by **Tea** at ~28%.

---

## ⏰ Hourly Sales Distribution

Peak hours for customer footfall and revenue:

| Hour | Revenue Share |
|---|---|
| 10 AM | ~12.7% |
| 9 AM | ~12.2% |
| 8 AM | ~11.8% |
| 11 AM | ~9.1% |
| 7 AM | ~9.1% |

> 🕙 **Morning hours (8 AM – 10 AM)** drive the highest volume — the classic morning coffee rush.

---

## 🔑 Key KPIs

- 💰 **Total Revenue:** $698,812.33
- 🧾 **Total Transactions:** 149,116
- 💵 **Average Transaction Value:** ~$4.69
- 🏆 **Top Product Type:** Brewed Chai Tea (17,183 transactions)
- 📅 **Best Month:** June ($166,485.88)
- 🏪 **Top Store:** Hell's Kitchen ($236,511.17)

---

## 🛠️ Tools & Techniques Used

- **Microsoft Excel** – Data analysis, pivot tables, KPI calculations
- **Power Query / Excel Formulas** – Data transformation and feature engineering
- **Pivot Charts** – Visual representation of trends
- **Slicers & Filters** – Interactive dashboard controls
- **Conditional Formatting** – Highlighting key metrics

---

## 🚀 How to Use

1. **Clone or download** this repository
2. Open `Copy_of_Coffee_Shop_Sales.xlsx` in **Microsoft Excel 2016 or later**
3. Navigate to the **Dashboard 2.0** sheet to explore the interactive dashboard
4. Use **slicers** to filter by store, month, product category, or day of week
5. Explore the **KPI by AKASH** sheet for detailed pivot analysis

---

## 💡 Key Insights

- 📈 Revenue nearly **doubled** from January to June, suggesting strong growth momentum
- ☕ **Coffee and Tea combined** account for **~67%** of total revenue
- 🕗 The **morning rush (7–10 AM)** is the most critical window for all three stores
- 🏪 All stores perform **nearly equally**, suggesting effective operations management
- 🥐 **Bakery** is the 3rd highest revenue category — strong upsell opportunity alongside beverages

---

## 👨‍💻 Author

**Akash**
- 📊 Data Analyst | Excel Dashboard Developer
- 🔗 [GitHub Profile](https://github.com/your-username)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

⭐ *If you found this project helpful, please give it a star!*
