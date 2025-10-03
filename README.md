
# Excel Sales Dashboard Project 📊
---

## 📁 Project Overview
This project showcases an **interactive Excel Sales Dashboard** built on a synthetic dataset of **1001 sales records**.  
It demonstrates **end-to-end Excel data analysis**, including cleaning, calculated columns, pivot tables, and dashboard visualizations.

---

## 📊 Dataset
Columns include:
| Column Name           | Description                               | Example Value        |
|-----------------------|-------------------------------------------|----------------------|
| Product_ID            | Unique product identifier                 | P001                 |
| Sale_Date             | Date of sale                              | 2023-05-15           |
| Sales_Rep             | Sales representative name                 | John Doe             |
| Region                | Sales region                              | North                |
| Sales_Amount          | Total sales amount                        | 1250                 |
| Quantity_Sold         | Units sold                                | 10                   |
| Product_Category      | Category of product                       | Electronics          |
| Unit_Cost             | Cost per unit                             | 80                   |
| Unit_Price            | Selling price per unit                    | 120                  |
| Customer_Type         | Type of customer (New/Returning)          | Returning            |
| Discount              | Discount applied                          | 5%                   |
| Payment_Method        | Mode of payment                           | Credit Card          |
| Sales_Channel         | Channel (Online/Retail)                   | Online               |
| Region_and_Sales_Rep  | Combined region + rep field               | North - John Doe     |

---

## 📑 Calculated Columns (Markdown table)
| Column Name        | Formula / Logic                            | Example Value |
|--------------------|---------------------------------------------|---------------|
| Total_Cost         | Unit_Cost × Quantity_Sold                  | 800           |
| Total_Revenue      | Unit_Price × Quantity_Sold                 | 1200          |
| Profit             | Total_Revenue − Total_Cost                 | 400           |
| Profit_Margin_%    | (Profit ÷ Total_Revenue) × 100             | 33.3%         |
| Discounted_Price   | Unit_Price × (1 − Discount)                | 114           |
| Net_Sales          | (Discounted_Price × Quantity_Sold)         | 1140          |
| Year               | Extracted from Sale_Date                   | 2023          |
| Month              | Extracted from Sale_Date                   | May           |
| Quarter            | Extracted from Sale_Date (Q1–Q4)           | Q2            |

---

## 📈 Dashboard Features
- KPI Cards: Total Sales, Profit, Avg Profit Margin, Quantity Sold
- Visuals:
  - Net Sales by Region
  - Net Sales by Product Category
  - Monthly Sales Trend
  - Customer Type Split
  - Payment Method Share
  - Sales by Channel
- Auto-generated **Insights**

---

## 🔑 Key Insights
- Top Region by Net Sales  
- Best-selling Product Categories  
- Returning vs New Customer Contributions  
- Online vs Retail Channel Performance  
- Monthly/Quarterly Growth Trends  

---

## 🛠️ Skills & Functions Used
- Excel Functions: `SUMIF`, `IF`, `ROUND`, `TEXT`, `VLOOKUP`, `INDEX-MATCH`, `IFERROR`, etc.  
- Pivot Tables & Charts  
- Slicers for interactivity  
- Conditional Formatting  
- Dashboard Design Best Practices  

---

## 🚀 How to Use
1. Download the Excel file from this repository.
2. Open in Excel (Windows/Mac).
3. Navigate to the **Dashboard** sheet for the final view.

---

## 📌 About
This project is designed for:
- Data Analyst portfolio demonstration  
- Practice with **Excel-based BI dashboards**  
- GitHub + LinkedIn project sharing  

---
