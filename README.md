# 📚 Ontario School Education System Analysis

This project explores Ontario’s public education system by analyzing multiple datasets sourced from the Government of Ontario and the City of Ottawa. Our goal is to uncover patterns and insights related to student performance, school demographics, educator statistics, suspension rates, and transitions to postsecondary education using structured data analysis with SQL.

---

## 📌 Project Objectives

- Integrate and clean multiple education datasets from different sources.
- Identify trends in student achievement across school boards and regions.
- Analyze transitions from secondary to postsecondary institutions.
- Examine educator demographics and school suspension rates.
- Provide actionable insights for improving educational equity and policy-making.

---

## 📂 Datasets Used

| Dataset Title | Source | Year |
|---------------|--------|------|
| [School Information and Student Demographics](https://data.ontario.ca/dataset/school-information-and-student-demographics) | Government of Ontario | 2024 |
| [School Board Achievements and Progress](https://data.ontario.ca/dataset/school-board-achievements-and-progress/resource/9d81dc27-32ef-4864-94b5-f09950d00c72) | Government of Ontario | 2024 |
| [School Board Achievements (Ottawa)](https://open.ottawa.ca/datasets/school-board-achievements-and-progress/explore) | City of Ottawa | 2020 |
| [Suspension Rates by School Board](https://data.ontario.ca/dataset/suspension-rates-by-school-board) | Government of Ontario | 2024 |
| [Transitions to Postsecondary Education](https://data.ontario.ca/dataset/transitions-to-postsecondary-education) | Government of Ontario | 2024 |
| [Educator Count by Gender and School Board](https://data.ontario.ca/dataset/transitions-to-postsecondary-education) | Government of Ontario | 2020 |
| [Ontario Public School Contact Information](https://data.ontario.ca/dataset/ontario-public-school-contact-information) | Government of Ontario | 2024 |

---

## 🧠 Challenges Faced by Team Members

| Team Member | Challenge & Solution |
|-------------|----------------------|
| **Rahul** | Dealt with inconsistent `' NA'` values; used SQL preprocessing to replace NaNs and enable clean data loading. |
| **Ayush** | Optimized query performance by changing data types to `INT` and `DECIMAL` for efficient aggregations. |
| **Juan** | Managed missing values using `NULL`, and normalized numbers by removing symbols and commas. |
| **Ojas** | Filtered out "Total Entry" rows to avoid duplication and inflated metrics during pathway analysis. |
| **Harsha** | Cleaned special cases like `"SP"` and `"<10"` by replacing them with `NULL`, ensuring numeric consistency. |

---

## 📊 Key Analyses

- Distribution of student demographics by region and school board
- Achievement trends across education boards (e.g., literacy/math scores)
- Post-secondary transition pathways (college vs university)
- Suspension rate analysis by board and gender
- Educator gender balance and staffing ratios by region

---

