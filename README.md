# Bank-Marketing-Analysis-Dashboard
# 🏦 Bank Marketing Analysis Dashboard (Power BI)

An interactive Power BI dashboard built to analyze a bank's direct marketing campaign data — exploring customer demographics, financial behavior, and loan patterns to support better, data-driven decision-making.

---

## 📌 Overview

This project transforms a raw **Bank Marketing dataset** into a clean, interactive Power BI report. The dashboard focuses on understanding *who* the bank's customers are (job, education, age) and *how* that relates to their financial profile (balance, housing loans, personal loans) — key context for evaluating and targeting marketing campaigns.

## 🎯 Objective

Present bank customer and campaign data in a simple, interactive dashboard that supports better decisions around **loan risk, customer segmentation, and campaign targeting**.

## 📊 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Average Balance | 1,362.27 |
| Average Age | 40.94 |
| Average Duration (call) | 258.16 |

## 📈 Visuals Included

- **Column Chart** — Customer count by Job Role, broken down by Loan status and Education
- **Donut Chart** — Loan status by Education level
- **Pie Chart** — Housing loan distribution by Loan status
- **Interactive Slicers** — Job, Loan, Education, and Housing, for on-the-fly filtering across all visuals
- **KPI Callouts** — Average Balance, Average Age, and Average Duration

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — report building & data visualization
- **Power Query** — data cleaning & transformation
- **Data Modeling** — structuring the dataset for analysis
- **DAX** — measures and calculations (averages, counts)
- **Interactive Dashboard Design** — slicers, cross-filtering, layout & storytelling

## 📂 Repository Contents

```
├── Bank_Dashboard_Final.pbix   # Power BI report file
└── README.md                   # Project documentation
```

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Bank_Dashboard_Final.pbix` in **Power BI Desktop** (recommended: 2021 version or later).
3. Use the slicers (Job, Loan, Education, Housing) to filter the report and explore the data interactively.

> ⚠️ If the file was connected to an external data source, you may be prompted to update the data source path or refresh the data on first open.

## 📁 About the Dataset

The dashboard is built on a **bank marketing dataset**, containing customer-level records typically used to analyze direct marketing (phone-based) campaigns for term deposit products. Core fields used in this report include:

- **Demographics:** Job, Education, Age
- **Financial profile:** Balance, Housing Loan, Personal Loan
- **Campaign data:** Call Duration

## 💡 Key Insights

- The average customer balance sits around **1,362**, with an average age of **~41 years**.
- Job role is a strong lens for segmenting customers by both loan status and education level.
- Housing loan status varies meaningfully by loan status, useful for risk/targeting analysis.

## 👤 Author

Feel free to connect or reach out with feedback and suggestions!

## 📄 License

This project is open for learning and portfolio purposes. Feel free to fork and adapt it.
