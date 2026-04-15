# 🏥 Healthcare Database SQL Project

## 📌 Overview

This project focuses on analyzing a healthcare database using SQL Server.  
It demonstrates solving real-world analytical questions using SQL techniques such as joins, aggregations, subqueries, and CTEs.

---

## 🗂 Dataset Description

The dataset represents a healthcare system and is provided in:

- `data.csv` → Contains the raw healthcare data  
- `schema.sql` → Contains the database structure (tables & relationships only)

The system includes the following entities:

- Patients  
- Doctors  
- Hospitals  
- Admissions  
- Medications  
- Test Results

---

## 🧩 Database Design (ERD)

The Entity Relationship Diagram (ERD) shows how the tables are connected.

📷 ERD:  
<img width="648" height="394" alt="Erd" src="https://github.com/user-attachments/assets/0ba5c026-dcee-48e5-99d1-49d3e3270bd4" />


---

## ❓ Project Questions

### 🔹 Basic Queries

1. Retrieve names and genders of all patients  
2. Display patients with blood type O+  
3. Count patients by blood type  
4. List all distinct hospital names  
5. Order patients by age (oldest to youngest)  

---

### 🔹 Intermediate Queries

6. Calculate average billing amount for all admissions  
7. Show patients admitted through Emergency  
8. Count number of cases per doctor  
9. Show doctor names with their hospitals  
10. List patients with Abnormal test results  

---

### 🔹 Advanced Queries

11. Patients treated in Cairo Hospital (JOIN)  
12. Total billing per hospital  
13. Patients who stayed more than 5 days  
14. Medications per admission (JOIN)  
15. Patients per medical condition  
16. Doctors and number of patients treated  
17. Hospitals and number of doctors  
18. Patients discharged before 2024-01-01  
19. Patients with billing above average (Subquery)  
20. Patients who were given Aspirin  
21. Patient–Doctor–Hospital mapping using COALESCE  
22. Patients with multiple admissions  
23. Admission type having more than 3 patients (HAVING)  
24. Patients with multiple medical conditions  
25. Hospitals with total billing > 50,000  
26. Patients over 40 with Urgent admission (CTE)  
27. Patients treated by same doctor as Ahmed  
28. Admissions at Alex Medical Center with medications  
29. Patients discharged after 10+ days stay  
30. Room filtering using CASE  
31. Admissions count per insurance provider  

---

## 📄 Project Files

- <a href="https://github.com/ahmed14420/Healthcare-SQL-Analysis-Project.sql/blob/main/healthcare_dataset.csv"> → Dataset</a>  
- <a href="https://github.com/ahmed14420/Healthcare-SQL-Analysis-Project.sql/blob/main/Healthcare%20SQL%20Analysis%20Project.sql"> → Database schema</a>   
- <a href="https://github.com/ahmed14420/Healthcare-SQL-Analysis-Project.sql/blob/main/Healthcare%20SQL%20Analysis%20Project.pdf"> → Queries + Outputs documentation</a>   
- <a href= "[images/erd.png](https://github.com/ahmed14420/Healthcare-SQL-Analysis-Project.sql/blob/main/Erd.PNG)"> → Database ERD</a>  

---

## 🛠 Tools & Technologies

- SQL Server  
- T-SQL  
- Joins (INNER, LEFT)  
- Subqueries  
- CTE (Common Table Expressions)  
- Aggregate Functions  
- CASE Statements  

---

## 🚀 How to Use

1. Open SQL Server Management Studio (SSMS)  
2. Run `schema.sql` to create the database structure  
3. Import or load `data.csv` into the tables  
4. Execute SQL queries  
5. Open `Healthcare_SQL_Project.pdf` to view outputs  

---

## 📊 Key Skills Demonstrated

- Data analysis using SQL  
- Writing complex queries  
- Working with relational databases  
- Data extraction and insights generation  

---

## 👨‍💻 Author

Ahmed Soliman
