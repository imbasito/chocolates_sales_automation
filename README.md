# 🍫 Chocolate Sales Automation – Batch Processing Project

This project simulates real-world automation of daily sales data for a fictional brand, **Awesome Chocolates**. It processes multiple raw sales CSVs, groups by product, filters top-selling items, and exports clean Excel reports with timestamps.

## 🔧 Tools Used
- Python (pandas, os, datetime)
- Excel export (.xlsx)
- Realistic retail workflow simulation

## 🧠 What It Does
- Combines multiple `.csv` files from `raw_data/`
- Groups by Product, sums Amount and Boxes
- Filters top products (Amount > 350,000)
- Exports summary as Excel in `/exports/`
- Logs exported filenames

## 📁 Project Structure

chocolate-sales-automation/
├── raw_data/ # Incoming daily CSVs
├── exports/ # Auto-generated Excel summaries
├── scripts/ # Python scripts (processor, combiner)
├── powerbi_dashboard/ # (Optional) Power BI dashboard file
├── README.md # Project overview
└── project_summary.pdf # (Optional) Final presentation/report

## ✅ How to Run
1. Add `.csv` sales files into `raw_data/`
2. Run the processor script:
```bash
python scripts/batch_sales_processor.py

Check the exports/ folder for results!

💼 Why This Project?
This project simulates what retail and e-commerce analysts do daily — automating repeatable data flows, building clean summaries, and preparing data for dashboards and business insights.
