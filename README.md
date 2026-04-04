# 🚀 Data Cleaning & Analytics Pipeline

**Developer:** Vansh Raj  
**Environment:** Pydroid 3 (Mobile Development)

---

## 📌 Project Overview
This project is a professional-grade Python automation tool designed to transform **dirty raw data** into structured, actionable sales reports.

---

## 🛠 Key Features
- 📥 Data Ingestion (CSV & Excel using Pandas)
- 🧹 Automated Cleaning (duplicates, whitespace removal)
- 🔄 Data Type Correction
- 📊 Advanced Analytics (Revenue, AOV, Top Product)
- 📁 Export to CSV & Excel

---

## ⚙️ Installation
pip install pandas numpy openpyxl

---

## ▶️ How to Run
python main.py

---

## 🧪 Example Input (Dirty Data)

---

## 🔧 Core Cleaning Logic
df.drop_duplicates(inplace=True)
df['Product'] = df['Product'].str.strip()
df['Price'] = pd.to_numeric(df['Price'], errors='coerce')

df['Quantity'] = df['Quantity'].fillna(1)
df['Price'] = df['Price'].fillna(df['Price'].mean())

---

## 📊 Sample Output
==============================
      SALES REPORT      
==============================
Total Revenue: 3983.33
Average Order Value: 569.05
==============================

---

## 📁 Output Files
clean_sales_report.csv  
sales_report.xlsx  

---

## 💡 Use Cases
- Business sales analysis  
- Student data projects  
- Freelancing data cleaning  

---

## ⭐ Support
If you like this project, please star the repo and watch for updates!
