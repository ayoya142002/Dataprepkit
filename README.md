# Dataprepkit
# 🧹 Data Cleaning & Preprocessing Tool
### 👩‍💻 Developed by [Aya Gamal](https://linkedin.com/in/aya-gamal-senara)

This is a Python project for **automating data cleaning and preprocessing**.  
It helps analysts and beginners quickly handle missing values, encode categorical data, and view statistical summaries for any dataset.

---

## 🚀 Features
- 📂 Read files in multiple formats: **CSV**, **Excel**, **JSON**
- 🧮 Generate detailed **data summary** (mean, median, std, min, max, skewness)
- ⚙️ Handle **missing values** using:
  - Row removal  
  - Mean or Median imputation  
  - Custom value filling  
- 🔠 Encode **categorical data** automatically
- 💬 Interactive terminal interface for user input

---

## 🧩 Example Usage
```python
from data_cleaning_tool import DataHandler

handler = DataHandler()
handler.main()
