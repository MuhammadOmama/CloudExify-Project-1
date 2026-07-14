# 📦 Project 1: Online Retail Sales Data Analysis

An end-to-end Exploratory Data Analysis (EDA) pipeline utilizing real-world transaction logs from a UK-based e-commerce retail store. This project satisfies the requirements of the **CloudExify Summer Internship 2026**.

---

## 🔗 Dataset Information
* **Dataset Name:** Online Retail II (UCI Machine Learning Repository)
* **Historical Window:** 2009 – 2011 
* **Database Format:** Excel Spreadsheet (`.xlsx`)
* **Download Links:** * [Kaggle Dataset Link](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
  * [UCI Machine Learning Repository Direct Link](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

---

## 🛠️ Project Requirements & Implementation Checklist

| Requirement | Description | Status |
| :--- | :--- | :--- |
| **Data Loading** | Programmatically read Excel sheet data into Pandas  |  Completed |
| **Missing Value Handling** | Isolate and drop records containing critical null keys like `Customer ID`  |  Completed |
| **De-duplication** | Drop duplicate log inputs representing duplicate system events  |  Completed |
| **Return Separation** | Isolate return invoices (prefixed with "C") and negative quantities from raw sales |  Completed |
| **Feature Engineering** | Derive custom time structures (`YearMonth`, `MonthName`, `DayOfWeek`, `Hour`)  |  Completed |
| **Statistical Baseline** | Calculate gross metrics (Total Revenue, Average Order Value, Medians)  |  Completed |
| **Visualization 1** | Plot top 10 products by gross sales  |  Completed |
| **Visualization 2** | Track chronological monthly sales velocity |  Completed |
| **Visualization 3** | Map distribution profiles across regional scales |  Completed |
| **Dynamic Reporting** | Export program summaries automatically to external text logs (`report.txt`) |  Completed |

---

