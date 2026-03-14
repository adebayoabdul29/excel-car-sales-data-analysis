# 🚗 Bam Autos — Car Sales Data Cleaning & Visualization

> An end-to-end data analytics project covering data cleaning, exploratory analysis, and interactive dashboard visualization of a car dealership sales dataset.

---

## 📌 Project Overview

This project analyzes **23,906 car sales transactions** from Bam Autos dealerships across multiple regions in the United States. The goal is to uncover insights on revenue trends, customer demographics, dealer performance, and vehicle preferences through structured data cleaning and compelling visualizations.

---

## 📂 Repository Structure

```
bam-autos-analysis/
│
├── data/
│   └── bam_autos_raw.csv          # Raw dataset before cleaning
│
├── Bam_Autos.xlsx                 # Full workbook (raw + cleaned + dashboard)
│
└── README.md                      # Project documentation
```

---

## 📊 Dataset Overview

| Column | Description |
|---|---|
| `Car_id` | Unique identifier for each sale |
| `Date` | Date of purchase |
| `Customer Name` | Name of the buyer |
| `Gender` | Customer gender |
| `Annual Income` | Customer's annual income ($) |
| `Dealer_Name` | Name of the dealership |
| `Company` | Car manufacturer/brand |
| `Model` | Car model name |
| `Engine` | Engine type (Overhead Camshaft / Double Overhead Camshaft) |
| `Transmission` | Transmission type (Auto / Manual) |
| `Color` | Car color |
| `Price ($)` | Sale price in USD |
| `Dealer_No` | Dealer identification number |
| `Body Style` | Vehicle body type (SUV, Sedan, Hatchback, etc.) |
| `Phone` | Customer phone number |
| `Dealer_Region` | Geographic region of the dealer |
| `Qty` | Quantity sold |

---

## 🧹 Data Cleaning Steps

The following cleaning steps were applied to the raw dataset:

- ✅ Converted `Date` column from Excel serial number format to proper date format
- ✅ Standardized `Engine` column (removed encoding issues e.g. `DoubleÂ Overhead Camshaft` → `Double Overhead Camshaft`)
- ✅ Handled missing and inconsistent values across columns
- ✅ Added derived columns: `Revenue` (Price × Qty) and `Salary Group` (income segmentation)
- ✅ Verified data types for numeric and categorical fields

---

## 📈 Key Insights & Analysis

- **Total Revenue:** $99,892,343
- **Total Units Sold:** 3,728
- **Average Sale Price:** ~$26,795
- **Year-over-Year Growth Rate:** ~41.2%
- **Gender Split:** ~79% Male buyers | ~21% Female buyers
- **Top Performing Regions:** Austin, Scottsdale, Pasco
- **Most Popular Body Styles:** SUV, Passenger, Hatchback
- **Top Car Brands:** Ford, Toyota, Chevrolet, Dodge, Cadillac

---

## 🖥️ Dashboards

The Excel workbook contains two interactive dashboards built in Excel:

1. **Demography Dashboard** — Visualizes customer income groups, gender distribution, and buying patterns
2. **Sales Dashboard** — Tracks revenue, units sold, dealer performance, and regional breakdown

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, analysis, and dashboard creation |
| **Power Query** | Data transformation and shaping |
| **Pivot Tables** | Aggregation and summary statistics |
| **Excel Charts** | Data visualization |

---

## 👤 Author

**Abdulfattah**
Data Analyst | Accounting Graduate | Interior Decorator

> *"Turning raw numbers into meaningful stories."*

---

## 📬 Contact

Feel free to connect or reach out for collaboration:

- 🐙 GitHub: [@fattah-canvas](https://github.com/fattah-canvas)

---

## 📝 License

This project is for portfolio and educational purposes.
