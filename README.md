# BlinkIT-Grocery-Sales-Analysis-PowerBI
Exploratory Data Analysis of BlinkIT grocery sales data using Power BI — covering outlet performance, item categories, fat content, location tiers, and an interactive dashboard.
# 🛒 BlinkIT Grocery Sales Analysis — Power BI Dashboard

## 📌 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)** on BlinkIT grocery sales data using **Power BI**. It covers data cleaning, DAX measures, and an interactive **Power BI Dashboard** to visualize key business insights across outlet types, item categories, fat content, location tiers, and sales performance.

---

## 📂 Repository Files

| File | Description |
|---|---|
| `BlinkIT_Grocery_Data.xlsx` | Raw dataset with 8,523 grocery records across BlinkIT outlets |
| `BLINKIT_DASHBOARD.pbix` | Interactive Power BI Dashboard with full analysis |

---

## 📊 Dataset Description

**File:** `BlinkIT_Grocery_Data.xlsx`  
**Sheet:** `BlinkIT Grocery Data`  
**Total Records:** 8,523 rows

| Column | Description |
|---|---|
| Item Fat Content | Fat category of the item (Low Fat / Regular) |
| Item Identifier | Unique code for each item |
| Item Type | Product category (e.g., Fruits, Snack Foods, Dairy, etc.) |
| Outlet Establishment Year | Year the outlet was established (2011–2022) |
| Outlet Identifier | Unique ID for each outlet (10 unique outlets) |
| Outlet Location Type | Tier classification — Tier 1, Tier 2, Tier 3 |
| Outlet Size | Size of the outlet — Small, Medium, High |
| Outlet Type | Type of store — Supermarket Type1/2/3 or Grocery Store |
| Item Visibility | Shelf visibility score of the item (0.0 to 0.33) |
| Item Weight | Weight of the item in kg (4.5 to 21.35) |
| Sales | Sales value in USD (31.29 to 266.88) |
| Rating | Customer rating of the item (1.0 to 5.0) |

---

## 🏪 Data Coverage

- **10 Unique Outlets** across India
- **16 Item Categories** including Fruits & Vegetables, Snack Foods, Dairy, Frozen Foods, and more
- **3 Location Tiers** — Tier 1, Tier 2, Tier 3
- **4 Outlet Types** — Supermarket Type1, Type2, Type3, Grocery Store
- **Outlet Establishment Years:** 2011 to 2022
- **Total Sales:** $12,01,681.49
- **Average Sales per Item:** $140.99
- **Average Customer Rating:** 3.97 / 5.0

---

## 🛠️ Tools & Technologies

- **Dashboard Tool:** Microsoft Power BI (`.pbix`)
- **Data Source:** Microsoft Excel (`.xlsx`)
- **Techniques Used:** Data Cleaning, DAX Measures, KPI Cards, Slicers, Drill-through, Conditional Formatting, Bar/Donut/Line Charts

---

## 🔍 Analysis Performed

### 📦 Item-Level Analysis
- Sales breakdown by Item Type (16 categories)
- Fat Content distribution — Low Fat vs Regular
- Item Visibility vs Sales correlation
- Top-selling and lowest-selling product categories

### 🏪 Outlet Performance Analysis
- Total and average sales by Outlet Type
- Outlet Size impact on sales (Small vs Medium vs High)
- Sales trend by Outlet Establishment Year (2011–2022)
- Outlet-wise rating comparison

### 🌍 Location Tier Analysis
- Revenue contribution by Tier 1, Tier 2, and Tier 3 cities
- Outlet count vs sales volume per tier
- Average rating by location type

### ⭐ Rating & Visibility Analysis
- Distribution of customer ratings across all items
- High-rated vs low-rated category breakdown
- Item Visibility and its effect on Sales

---

## 📈 Dashboard Highlights

The `BLINKIT_DASHBOARD.pbix` file contains an **interactive Power BI Dashboard** featuring:

- 💳 **KPI Cards** — Total Sales, Average Sales, Average Rating, Total Items
- 📊 **Bar Charts** — Sales by Item Type and Outlet Type
- 🥧 **Donut Charts** — Fat Content split and Outlet Size share
- 📉 **Line Chart** — Sales trend by Outlet Establishment Year
- 🗺️ **Matrix/Table** — Outlet-wise performance breakdown
- 🎛️ **Slicers** — Filter by Outlet Location Type, Outlet Size, and Item Type

---

## 🚀 How to Use

1. **Download both files** from this repository.
2. Open `BlinkIT_Grocery_Data.xlsx` to explore the raw data.
3. Open `BLINKIT_DASHBOARD.pbix` using **Microsoft Power BI Desktop** (free download from [powerbi.microsoft.com](https://powerbi.microsoft.com)).
4. If prompted, update the data source path to point to your local copy of `BlinkIT_Grocery_Data.xlsx`.
5. Use the **slicers and filters** on the dashboard to explore insights interactively.

> ⚠️ **Note:** Power BI Desktop is required to open `.pbix` files. The file cannot be previewed directly on GitHub — download and open locally.

---

## 💡 Key Insights (Summary)

- **Fruits and Vegetables** and **Snack Foods** are the top two categories by item count and sales volume.
- **Low Fat** items make up ~64% of all products, reflecting health-conscious stocking.
- **Supermarket Type1** outlets generate the highest total sales, while **Grocery Stores** lag significantly.
- **Tier 3** cities have the highest number of outlets and contribute the most to overall sales volume.
- Outlets established in **2018** showed the highest sales peak in the establishment year trend.
- **Medium-sized** outlets contribute the largest share of total sales.
- Average customer rating across all items is a healthy **3.97 / 5.0**.

---

## 📁 Repository Structure

```
BlinkIT-Grocery-Sales-Analysis-PowerBI/
│
├── BlinkIT_Grocery_Data.xlsx      # Raw grocery dataset
├── BLINKIT_DASHBOARD.pbix         # Power BI Dashboard
└── README.md                      # Project documentation
```

---

## 🙋‍♂️ Author

**[Aman Yadav]**  
Aspiring Data Analyst | Power BI | Excel | MySQL  
📧 [amanyadav11981@gmail.com]  
🔗 [[LinkedIn Profile URL](https://www.linkedin.com/in/aman-yadav-a1a5b8216)]

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
