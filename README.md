📊 Employee Data Cleaning Project

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-DataCleaning-yellow?logo=pandas&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green)
![GitHub Repo Size](https://img.shields.io/github/repo-size/yourusername/employee-data-cleaning)
![Last Commit](https://img.shields.io/github/last-commit/yourusername/employee-data-cleaning)

---

🧹 Objective

This project demonstrates the process of **cleaning and preparing a raw employee dataset** using **Python (Pandas)**. The raw data contained missing values, inconsistent formatting, and duplicate records, which were systematically cleaned to create a ready-to-analyze dataset.

---

📁 Dataset Overview

- **File Name:** `employee_raw_dataset.csv`
- **Records:** 1000+ (with intentional noise: duplicates, missing values, format issues)
- **Fields Included:**
  - Employee ID
  - Name
  - Age
  - Gender
  - Department
  - Salary
  - Joining Date
  - Country

---

🛠️ Tools Used

- Python 🐍
- Pandas 📊
- NumPy
- Jupyter Notebook / VS Code

---

🔍 Cleaning Process Highlights

1. **Missing Values**
   - Handled missing numerical fields using median imputation
   - Categorical blanks filled with `"Unknown"` or `"Not Specified"`
   - Blank or malformed dates set to a default or most frequent value

2. **Duplicates**
   - Removed duplicate records using `.drop_duplicates()`

3. **Inconsistent Text Formats**
   - Standardized values in `Gender`, `Country`, and `Department`

4. **Date Formatting**
   - Converted `Joining Date` to a consistent datetime format

5. **Column Cleanup**
   - Renamed columns to lowercase and snake_case (e.g., `joining_date`)
   - Checked and enforced appropriate data types

---

📁 Files Included

| File                          | Description                              |
|-------------------------------|------------------------------------------|
| `employee_raw_dataset.csv`    | Original uncleaned dataset               |
| `employee_cleaned_dataset.csv`| Final cleaned dataset                    |
| `employee_cleaning.ipynb`     | Jupyter notebook for all cleaning steps |
| `README.md`                   | Project documentation                    |

---

✅ Output

A **cleaned employee dataset** ready for analysis or visualization with consistent, validated, and structured data.

---

💡 Future Improvements

- Integrate with a dashboard (e.g., Power BI or Streamlit)
- Automate cleaning with functions and config files
- Add unit tests to validate each cleaning step

---

🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests to improve this project further.

---

## 📬 Contact

👩‍💻 Sumit Dawn  
📧 Email: sumitdawn05@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sumit-dawn-35909025a/)

---

