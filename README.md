# 📊 ITC Financial Dashboard - Power BI Project

This project is a financial analysis of **ITC Limited**, focused on understanding trends in revenue, expenses, cash flows, and balance sheet components over the past decade. The dataset was sourced from Screener.in and transformed into an interactive Power BI dashboard.
This project focuses on cleaning and preparing ITC Ltd's multi-year financial data for analysis using Power BI. While the dashboard itself is under development, the core Power Query transformations and data modeling groundwork have been completed.

---

## 📁 Dataset Overview

The Excel file includes the following sheets:
- **Profit & Loss**
- **Balance Sheet**
- **Cash Flow**
- (Plus metadata: Quarters, Data Sheet, Customization)

Each sheet contains year-wise financial data from FY2015 to FY2024 (including projections for trailing/best/worst case).

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **Power Query (M Language)** for data cleaning
- **Excel** (source format)
- **Git** for version control and documentation

---

## 🚧 In Progress

- [x] Data import and cleanup
- [x] Unpivoting and normalization
- [ ] KPI design and layout
- [ ] Dashboard visuals (Revenue trends, Cash Flow, Balance Sheet overview)

---

## 🧹 Data Cleaning & Transformation

Performed using Power Query:

- Removed top rows and promoted headers
- Renamed and standardized column names
- Unpivoted year columns to enable time-series analysis
- Cleaned numeric formats and assigned appropriate data types
- Added contextual columns (e.g., source, year)

---

## 📊 Planned Dashboard Features

### Pages / Views:
- **Financial Overview**
  - KPIs: Revenue, Profit, Cash Flow
  - Trends over time (2015–2024)
- **P&L Breakdown**
  - Line chart of revenue, expenses, and profit
  - Year-over-year % changes
- **Cash Flow Analysis**
  - Stacked bar chart of operating, investing, and financing flows
- **Balance Sheet Trends**
  - Growth in equity, reserves, and borrowings

### Interactivity:
- Year slicers
- Tooltip-based insights
- Clean and minimal theme

---

## 📊 Current Dashboard Features

- **Revenue & Profit Trends**
  - Line charts showing revenue and profit over time (2015–2024)
- **Cash Flow Overview**
  - Visual breakdown of operational, investing, and financing cash flows
- **Clean, Year-wise Visuals**
  - Slicer/filter for year selection
  - All visuals laid out on a single page


## 📈 Key Insights

- Consistent revenue growth post-2017 with a notable jump in FY2023
- Stable operating profit margins
- Negative cash flows from financing due to dividends/share buybacks
- Strong reserves and low long-term borrowings

---

## 🚀 How to Use

1. Clone this repo  
   `git clone (https://github.com/Vishalkompalli/BI-Projects.git)`

2. Open Power BI Desktop  
   `File > Open` and select `ITC_Report.pbix`

3. Or start from scratch:
   - Load `ITC.xlsx` into Power BI
   - Use `Transform Data` to replicate cleaning steps
   - Build visuals using clean tables

---

## 🧠 What I Learned

- Cleaning multi-sheet financial Excel data in Power Query
- Importance of long vs wide format for BI
- Building time-series and comparative visuals
- Designing a readable, insight-rich dashboard

---

## 📬 Contact

Created by Vishal (vishal.kompalli@gmail.com) - Embedded Systems Engineer transitioning into Data Analytics.

If this helped or you're hiring, feel free to reach out!

