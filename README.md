This project demonstrates how to perform data cleaning using SQL on a raw dataset (`layoffs.csv`) involving global tech layoffs. It includes identifying inconsistencies, handling missing data, and preparing the dataset for analysis.

---

##  Objective

To clean and transform raw layoff data into a structured and analysis-ready format using SQL queries.

---

## Dataset

- **File**: `layoffs.csv`
- **Source**: Public dataset containing information on company layoffs, including company name, industry, total laid off, percentage laid off, country, etc.

---

## 🛠 Tools & Technologies

- **SQL** (Structured Query Language)
- **MySQL Workbench** (or any SQL environment)
- **Git & GitHub** for version control

---

##🧼 Cleaning Steps Performed

1. **Removed duplicates**
2. **Handled NULL or missing values**
3. **Standardized company and industry names**
4. **Converted date formats**
5. **Extracted useful information (e.g. year, month)**
6. **Filtered unrealistic or outlier entries**
7. **Reorganized table structure for further analysis**

---

##  Script

- **File**: `cleaning_script.sql`  
Contains all SQL queries used during the cleaning process, well commented for clarity.

---

##  Output

A cleaned version of the original dataset, ready for:
- Descriptive analytics
- Visualization
- Further machine learning pipeline

---

##  Getting Started

1. Clone the repo:
   ```bash
2. git clone https://github.com/VAMPxLOVE/data-cleaning-sql.git
3. Open layoffs.csv in your SQL environment.

Run cleaning_script.sql step-by-step.
