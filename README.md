
# 📊 Automated Workforce Analytics
Python-based data analytics project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightblue?logo=numpy)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 🚀 Project Overview

**Automated Workforce Analytics** is a Python-based data analytics project designed to automate workforce-related financial tracking and project cost computation across multiple structured datasets.

The project demonstrates strong fundamentals in **data manipulation**, **business rule implementation**, and **analytical problem-solving** using real-world workforce and project data.

*“Built a Python-based solution to automate financial tracking and compute project costs across distinct data frames.”*

---

## 🛠️ Technologies Used

- 🐍 **Python**
- 🧮 **NumPy** – numerical operations
- 🐼 **Pandas** – data manipulation & analysis
- 📓 **Jupyter Notebook**

---

## 📂 Dataset Structure

The project works with three primary datasets:

| Dataset | Description |
|------|------------|
| **Employee Data** | Employee personal and location details |
| **Seniority Level Data** | Designation level hierarchy |
| **Project Data** | Project cost, status, and ownership |

All datasets are stored and processed as **CSV files**.

---

## 📌 Key Features & Tasks

✔ Created multiple DataFrames and persisted them as CSV files  
✔ Handled missing project cost values using **running average logic**  
✔ Split full names into first and last names  
✔ Merged multiple datasets into a unified analytical DataFrame  
✔ Applied **business rules** for:
- Employee **bonus calculation**
- **Designation demotion** for failed projects
- **Promotion logic** based on age
  
✔ Removed ineligible employees based on designation threshold  
✔ Aggregated total project cost per employee  
✔ Implemented conditional filtering and string-based searches  

---

## 🔍 Business Logic Highlight

### Designation Demotion Rule
- Designation hierarchy: `1 (Highest) → 4 (Lowest)`
- Failed projects result in **demotion (+1 level)**
- Employees exceeding level 4 are removed automatically

✔ Correctly implemented hierarchy-aware demotion logic.

---

## 📈 Output Highlights

- Clean, unified **Final DataFrame**
- Bonus-calculated workforce metrics
- Aggregated project cost per employee
- Business-rule compliant analytics output

---



---

## 🎯 Learning Outcomes

- Practical use of **Pandas & NumPy**
- Real-world data cleaning techniques
- Business rule translation into code
- Analytical thinking & debugging
- Structured data pipeline design

---

## 👤 Author

**Arundas P R**  
📌 Python | Data Analytics | Workforce Analytics  

---

⭐ *If you find this project useful, feel free to star the repository!*





