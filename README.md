# 📊 Amazon Sales Analysis & Visualization

## 🔍 Project Overview
This project analyzes Amazon sales data by following a complete data pipeline from raw data to final dashboard.

---

## 🔄 Project Workflow (Step-by-Step)

1. 📥 Raw Data (Excel)
   - Initial dataset in Excel format (`amazon.xlsx`)

2. 🧹 Data Cleaning (Jupyter Notebook)
   - Loaded raw data into Python
   - Cleaned and transformed data using Pandas
   - Handled missing values
   - Removed symbols like ₹ and %
   - Converted columns into numeric format
   - Created new feature: `discount_amount`

3. 📤 Cleaned Data Export
   - Saved cleaned dataset as `cleaned_amazon.csv`

4. 📊 Data Visualization (Power BI)
   - Imported cleaned data into Power BI
   - Created interactive dashboard
   - Added filters, charts, and KPI cards

5. 📄 Dashboard Export
   - Exported final dashboard as PDF (`dashboard.pdf`)

---

## 🛠️ Tools & Technologies Used
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Power BI
- Excel

---

## 📂 Project Files

| File Name | Description |
|----------|------------|
| amazon.xlsx | Raw dataset (original data) |
| project.ipynb | Data cleaning using Python |
| cleaned_amazon.csv | Cleaned dataset |
| dashboard.pbix | Power BI dashboard |
| dashboard.pdf | Final dashboard (exported) |

---

## 🧹 Data Cleaning Steps
- Removed currency symbols (₹)
- Removed percentage symbols (%)
- Converted columns to numeric values
- Handled missing values
- Created new column: `discount_amount`

---

## 📊 Key Insights

- 💰 Total Sales: **4.43M**
- ⭐ Average Rating: **3.97**
- 🎯 Average Discount: **47.60%**
- 🛒 Total Reviews: **26.57M**

### Insights:
- Electronics category has highest share
- Discount and rating do not have strong direct relation
- Most categories maintain rating close to 4

---

## 📈 Dashboard Features
- Category filter
- Discount vs Rating analysis
- Category share visualization
- Average discount by category
- KPI cards (Sales, Rating, Discount, Reviews)

---

## 🎯 Conclusion
This project demonstrates a complete data analysis of Sales 
