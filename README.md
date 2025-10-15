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
---


💬 You’ll be prompted to:

Enter your dataset path

Choose how to handle missing values

Automatically encode categorical columns

Get the final data summary and cleaned output
---
🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn (for ColumnTransformer & OneHotEncoder)
---
📊 Example Output
Data Summary:
Number of Rows: 1000
Number of Columns: 10
Average Values [Age]: 32.4
Most Frequent Value [Gender]: Male
Standard Deviation [Salary]: 4567.2
Skewness [Experience]: 0.42
...

📚 Future Improvements

Add export feature for cleaned data (to CSV)

Add outlier detection & handling

Add correlation matrix visualization

🔗 Connect

📧 ayagama662@gmail.com

🔗 LinkedIn
