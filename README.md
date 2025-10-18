# 📊 Excel Sales Analysis

An interactive Excel Sales Dashboard project built to analyze 10,000+ sales transactions.
This project demonstrates data cleaning, transformation, KPI calculation, pivot tables, and dashboard visualization using Microsoft Excel.




## 📂 Project Structure
```

Excel_Sales_Dashboard/
│
├── data/
│ ├── raw_data/ # Original dataset
│ ├── cleaned/ # Cleaned data files
│ └── Analysis/ # Analytical data outputs
│
├── excel/ # Final Excel report and KPIs
├── image/ # Dashboard screenshots
└── README.md # Project documentation
```


## 🛠️ Steps Performed
🔹 Data Preparation (Power Query)
- Loaded raw dataset into Excel

- Applied transformations:

- Promoted headers

- Changed data types

- Removed errors, blanks & duplicates

- Added Sales_ID column (SLS-1, SLS-2, ...)

- Created calculated columns:

- Total Sales = Quantity × Price
  Earned Commission = Total Sales × Commission


## 🔹 KPI Calculations

| Sr.No | KPI                       | Formula / Logic                                | Use                    |
|-------|---------------------------|-----------------------------------------------|-----------------------|
| 1     | Total Sales               | SUM(Total Sales)                              | Overall revenue        |
| 2     | Total Quantity Sold       | SUM(Quantity)                                 | Volume of sales        |
| 3     | Total Commission Earned   | SUM(Earned Commission)                        | Total payout           |
| 4     | Average Sales per Transaction | AVERAGE(Total Sales)                        | Transaction efficiency |
| 5     | Average Commission %      | (SUM(Earned Commission) ÷ SUM(Total Sales)) × 100 | Profitability insight |
| 6     | Top Sales Rep (by Sales)  | Pivot (Sales Rep, Total Sales, Sort Desc)    | Best performer         |
| 7     | Top State (by Sales)      | Pivot (State, Total Sales, Sort Desc)        | Best market            |
| 8     | Most Selling Item         | Pivot (Item, Quantity, Sort Desc)            | Demand analysis        |
| 9     | Top vs Bottom Performers  | Pivot + Conditional Formatting               | Highlights extremes    |
| 10    | Commission Efficiency     | (Earned Commission ÷ Total Sales)            | Efficiency comparison  |


## 🔹 Pivot Table Analysis

| Analysis Type                  | Description                                |
|--------------------------------|--------------------------------------------|
| Sales by Item                  | Compare sales & quantity per item          |
| Sales by Sales Rep             | Performance by representative             |
| Sales by State                 | Regional sales distribution                |
| Sales Trend by Date            | Monthly/Yearly trend analysis              |
| Commission Analysis            | Who earns the most commission              |
| Quantity by Item & State       | Cross-analysis for demand                  |
| Top vs Bottom Performers       | Highlights best & worst                     |
| Commission Efficiency          | Efficiency % across sales reps             |



## 📈 Dashboard Features

- Clean & professional UI design with slicers and charts
- KPIs at a glance (cards for Total Sales, Avg Sales, etc.)
- Time-series trend chart for daily/monthly analysis
- Geographical map chart for state-wise performance
- Bar & Pie charts for Sales Rep, Item, and Commission
- Top vs Bottom analysis with conditional formatting
- Insights box with key findings

## 🖼️ Dashboard Preview
<img width="1036" height="563" alt="Screenshot 2025-10-18 224733" src="https://github.com/user-attachments/assets/4ea8a98c-e177-48cc-bf22-ca8afc7b549d" />

## 🚀 How to Use
Clone this repo:
```bash
git clone https://github.com/harshada4912/Excel_sales_dashboard.git
```
1. Open the Excel file in the 4_Visuals/ folder

2. Interact with slicers and charts to explore insights
   

## 🛠️ Tools Used

- Microsoft Excel → Power Query, Pivot Tables, Charts

- Conditional Formatting → Top/Bottom highlighting

- Map Chart → State-wise sales visualization
---



## 👤 Author

- **Name:** Harshada Pawar
- **Email:** harshadapawar4912@gmail.com
- **GitHub:** [Profile](https://github.com/harshada4912)





