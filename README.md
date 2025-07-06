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

