# Student Academic Performance Analysis

> A Power BI dashboard and data analysis project examining the factors that influence university student grades — including lifestyle, digital behaviour, academic environment, and student wellbeing — built as a Data Analytics Mini Project.

---

## Project Overview

This project analyzes factors affecting academic performance among university students. Using a dataset of 10,064 student records across 35 variables, the project covers end-to-end data analysis: raw data cleaning in Excel, written analysis in a report, and an interactive Power BI dashboard with filters for attendance, study hours, gender, and age.

---

## Dashboard Preview

![Student Academic Performance Dashboard](Dashboard.pdf)

> Open `Dashboard.pdf` for a full visual preview of the dashboard without downloading Power BI.

---

## Dataset

**Raw File:** `Factors__affecting__university_student_grades_dataset.csv`

| Property | Details |
|---|---|
| Records | 10,064 students |
| Features | 35 columns |
| Target Variable | Grades (A / B / C) |

### Key Variables

| Category | Variables |
|---|---|
| Demographics | Age, Gender, Family Income, Parental Education |
| Academic | Previous Grades, Attendance, Study Hours, Class Participation |
| Lifestyle | Sleep Patterns, Nutrition, Physical Activity, Stress Levels |
| Digital Behaviour | Screen Time, Educational Tech Use, Time Wasted on Social Media |
| Environment | School Environment, Professor Quality, Class Size, Study Space |
| Wellbeing | Self Esteem, Motivation, Bullying, Peer Group |
| Support | Tutoring, Mentoring, Parental Involvement, Extracurricular Activities |

### Grade Distribution

| Grade | Students |
|---|---|
| A | 443 |
| B | 484 |
| C | 464 |
| **Total** | **1,391** |

---

## Project Workflow

### 1. Data Cleaning — Excel
- Cleaned raw CSV data in Microsoft Excel
- Standardised column names and data formats
- Handled inconsistencies across categorical variables
- Produced a clean, analysis-ready dataset (`Cleaned_Dataset.xlsx`)

### 2. Analysis Report — Word
- Written interpretation of key findings
- Structured analysis of how each factor category relates to student grades
- Available in `Analysis_Report.doc`

### 3. Power BI Dashboard
Interactive dashboard with the following visualizations:

| Visual | Description |
|---|---|
| KPI Cards | Grade A, B, C student counts and Total Students |
| Bar Chart | Digital Behaviour vs Grades |
| Bar Chart | Academic Progression vs Grades |
| Stacked Bar | Healthy Lifestyle vs Grades |
| Stacked Bar | Academic Environment vs Grades |
| Bar Chart | Student Wellbeing vs Grades |
| Bar Chart | Learning Engagement vs Grades |

### Dashboard Filters
- Attendance (Average / Good / Excellent)
- Study Hours (High / Medium / Low)
- Gender (F / M)
- Age (18–22 slider)

---

## Key Findings

- High digital distraction is associated with lower grades across all categories
- Students with improved academic progression show higher Grade A representation
- Healthy lifestyle is associated with better grade distribution
- Strong academic environment correlates with higher performance
- Students at risk for wellbeing issues show higher Grade C rates
- High learning engagement is concentrated among Grade A and B students

---

## Files in This Repository

| File | Description |
|---|---|
| `Factors__affecting__university_student_grades_dataset.csv` | Raw dataset (10,064 records × 35 columns) |
| `Cleaned_Dataset.xlsx` | Cleaned and standardised dataset |
| `Analysis_Report.doc` | Written analysis report |
| `Student_Academic_Performance_Analysis.pbix` | Power BI dashboard file |
| `Dashboard.pdf` | Dashboard screenshot — visual preview |
| `README.md` | Project documentation |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and preprocessing |
| Microsoft Word | Analysis report writing |
| Microsoft Power BI Desktop | Dashboard and visualizations |
| Power Query | Data transformation |
| DAX | Calculated measures |

---

## How to Use

1. Clone or download this repository
```bash
git clone https://github.com/bibythayyil/student-academic-performance-analysis-excel-powerbi
```

2. For a quick preview — open `Dashboard.pdf`

3. For the full interactive dashboard — open `Student_Academic_Performance_Analysis.pbix` in **Microsoft Power BI Desktop**

4. If prompted to refresh data, point the source to `Cleaned_Dataset.xlsx` on your local machine

> **Note:** Power BI Desktop is free to download from [Microsoft](https://powerbi.microsoft.com/desktop/).

---

## Author

**Bibin T S**
---
