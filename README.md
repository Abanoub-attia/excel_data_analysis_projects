# 📊 Excel Data Analysis Projects

A collection of Excel-based data analysis projects focused on the **data science job market**, exploring salary trends, in-demand skills, and regional compensation differences using real-world job posting data from 2023.

🔗 **Repository:** [github.com/Abanoub-attia/excel_data_analysis_projects](https://github.com/Abanoub-attia/excel_data_analysis_projects.git)

---

## 📁 Repository Structure

```
excel_data_analysis_projects/
│
├── Images/
│
├── Project_1-Dashboard/
│   ├── 1_Salary_Dashboard.xlsx
│   └── README.md
│
├── Project_2-Analysis/
│   ├── 1_Project_Analysis.xlsx
│    └── README.md
│
└──  README.md
```

---

## 🗂️ Projects Overview

### 📌 Project 1 — Salary Dashboard
📂 [`Project_1-Dashboard/`](./Project_1-Dashboard/)

An interactive Excel dashboard designed to help job seekers explore and compare salaries across different data-related roles, countries, and job schedule types.

**Key Features:**
- 📊 Horizontal bar chart ranking job titles by median salary
- 🗺️ Map chart visualizing median salaries by country
- 🧮 Dynamic `MEDIAN(IF(...))` array formulas for multi-criteria filtering
- ❎ Data validation dropdowns for Job Title, Country, and Schedule Type

**Excel Skills Used:**
| Skill | Purpose |
|---|---|
| Charts | Bar chart & map chart for visual salary comparison |
| Formulas & Functions | `MEDIAN`, `IF`, `FILTER`, `SEARCH` for dynamic calculations |
| Data Validation | Restrict inputs to valid, predefined options |

**💡 Key Insight:** Senior roles and Engineering positions consistently command higher salaries than Analyst roles across most regions.

---

### 📌 Project 2 — Data Jobs Market Analysis
📂 [`Project_2-Analysis/`](./Project_2-Analysis/)

A deep-dive analytical project investigating four key questions about the data science job market — from the relationship between skills and pay to identifying the most valuable technologies.

**Questions Explored:**
1. 💼 Do more skills get you better pay?
2. 🌍 What's the salary for data jobs in different regions?
3. 🛠️ What are the top skills of data professionals?
4. 💰 What's the pay for the top 10 skills?

**Excel Skills Used:**
| Skill | Purpose |
|---|---|
| Power Query | ETL — extract, clean, and load job & skills data |
| Power Pivot | Build a relational data model linking jobs and skills |
| DAX | Calculate median salaries with custom measures |
| Pivot Tables | Aggregate salary and skill frequency data |
| Pivot Charts | Combo charts (column + line) for dual-axis analysis |

**💡 Key Insights:**
- 📈 More skills correlate with higher salaries, especially for Senior Data Engineers and Data Scientists
- 🐍 SQL and Python are the most in-demand skills across data roles
- ☁️ Cloud skills (AWS, Azure) are rapidly growing in prevalence
- 💵 The US shows a notably higher salary premium for high-tech data roles compared to international markets

---

## 🧰 Tools & Technologies

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Microsoft Excel** — Charts, Formulas, Power Query, Power Pivot, DAX, Pivot Tables & Charts, Data Validation

---

## 📂 Dataset

Both projects use a real-world dataset of **data science job postings from 2023**, containing:
- 👨‍💼 Job titles
- 💰 Annual salary averages
- 📍 Locations / Countries
- 🛠️ Required skills
- ⏰ Job schedule types

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Abanoub-attia/excel_data_analysis_projects.git
   ```
2. Navigate to either project folder
3. Open the `.xlsx` file in **Microsoft Excel** (2016 or later recommended for full feature support)
4. Use the dropdowns and interact with the dashboard/pivot tables directly

> ⚠️ **Note:** Power Query and Power Pivot features require the **Windows** version of Excel. Some features may not be available in Excel for Mac or Excel Online.

---