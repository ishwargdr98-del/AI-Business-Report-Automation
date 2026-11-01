# AI Business Report Automation 📊

A Python and Pandas project that analyzes real-world retail transaction data to identify data quality issues and generate structured business reports.

## 🎯 Project Objective

The goal of this project is to automate data quality checks on retail transaction data and create a summary report that helps identify missing values and unusual records.

## 🛠️ Technologies Used

- Python
- Pandas
- Google Colab
- Jupyter Notebook
- CSV Data Processing
- GitHub

## 📂 Project Files

- `AI_Business_Report_Automation.ipynb` — Notebook containing data analysis and data quality checks.
- `data_quality_audit.csv` — Summary report generated from the analysis.

## 📊 Dataset

This project uses the **UCI Online Retail dataset**, which contains transaction records from a UK-based online retail business.

The dataset includes fields such as:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## 🔍 Data Quality Checks

The notebook checks for:

- Total number of records
- Missing CustomerID values
- Missing product descriptions
- Negative quantities
- Zero unit prices
- Negative unit prices

## 📈 Initial Findings

The initial analysis identified the following records requiring further investigation:

| Metric | Count |
|---|---:|
| Total Rows | 541,909 |
| Missing CustomerID | 135,080 |
| Missing Description | 1,454 |
| Negative Quantity | 10,624 |
| Zero UnitPrice | 2,515 |
| Negative UnitPrice | 2 |

**Important:** These are initial data-quality findings, not confirmed errors. Negative quantities may represent returns or credit transactions, and zero prices may have legitimate business explanations.

## 🚀 How to Run

1. Open `AI_Business_Report_Automation.ipynb` in Google Colab or Jupyter Notebook.
2. Load the UCI Online Retail dataset.
3. Run the notebook cells in order.
4. Review the data quality summary.
5. Export the results to `data_quality_audit.csv`.

## 💼 Business Value

This project demonstrates how Python and Pandas can help businesses:

- Automate repetitive data checks.
- Identify records requiring investigation.
- Generate structured CSV reports.
- Improve visibility into data quality.
- Reduce manual reporting effort.

## 🔮 Future Improvements

- Add automated data validation rules.
- Generate Excel reports.
- Create visualizations of data quality issues.
- Add reusable reporting functions.
- Build a repeatable reporting workflow.

## 👨‍💻 Author

**Ishwar Bhardwaj**

Python | Pandas | Data Analysis | Business Automation

---

*This project is part of my ongoing journey to build practical Python and AI business automation solutions.*
