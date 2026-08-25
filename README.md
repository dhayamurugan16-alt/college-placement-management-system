
# 🎓 College Placement Management System

> **A MySQL-based relational database system for efficiently managing the complete college placement lifecycle — from student profiles and job applications to interviews and successful placements.**

---

## 📌 Project Overview

The **College Placement Management System** is a relational database project developed using **MySQL** to organize and manage placement-related information in a structured and efficient way.

The system manages:

* 👨‍🎓 Student information
* 🏢 Company details
* 💼 Job openings
* 📝 Student applications
* 📅 Interview records
* 🛠️ Student skills
* 🎯 Placement records

The database is designed using **normalization, primary keys, foreign keys, constraints, joins, aggregate functions, views, stored procedures, and triggers** to maintain data integrity and support efficient reporting.

---

## 🎯 Objectives

* Centralize student and placement-related information.
* Maintain relationships between students, companies, jobs, applications, and interviews.
* Reduce data redundancy through database normalization.
* Maintain data integrity using primary and foreign keys.
* Perform efficient placement-related queries and reporting.
* Automate selected database operations using triggers and stored procedures.

---

## ✨ Key Features

 👨‍🎓 Student Management

Stores and manages student details, skills, and placement information.

 🏢 Company Management

Maintains company information and available job opportunities.

💼 Job Management

Stores job openings, requirements, and related company information.

📝 Application Tracking

Tracks student applications submitted for different job opportunities.

 📅 Interview Management

Maintains interview schedules and interview-related records.

 🎯 Placement Tracking

Records successful placements and related placement information.

📊 Database Reporting

Uses SQL queries, joins, aggregate functions, and views to generate useful placement-related information.

⚙️ Automation

Uses stored procedures and triggers to automate database operations and maintain consistency.

---

 🗄️ Database Structure

The project contains SQL files for different modules:

| SQL File                                  | Purpose                     |
| ----------------------------------------- | --------------------------- |
| `placement_management_companies.sql`      | Company information         |
| `placement_management_jobs.sql`           | Job openings                |
| `placement_management_applications.sql`   | Student applications        |
| `placement_management_interviews.sql`     | Interview records           |
| `placement_management_placements.sql`     | Placement records           |
| `placement_management_skills.sql`         | Available skills            |
| `placement_management_student_skills.sql` | Student-skill relationships |

---

🧠 SQL Concepts Implemented

This project demonstrates practical knowledge of:

* ✅ Database Creation
* ✅ Table Creation
* ✅ Primary Keys
* ✅ Foreign Keys
* ✅ Constraints
* ✅ Normalization
* ✅ CRUD Operations
* ✅ SQL Joins
* ✅ Aggregate Functions
* ✅ `GROUP BY`
* ✅ `HAVING`
* ✅ Subqueries
* ✅ Views
* ✅ Stored Procedures
* ✅ Triggers
* ✅ Relational Database Design



🔗 Database Relationships

The system establishes relationships between major entities such as:


Students
   │
   ├── Student Skills
   │
   ├── Applications ─── Jobs ─── Companies
   │
   ├── Interviews
   │
   └── Placements

These relationships help maintain data consistency and allow meaningful placement-related queries.

---
 🚀 How to Run the Project

 1. Install MySQL

Install **MySQL Server** and a MySQL client such as MySQL Workbench.

 2. Create the Database

```sql
CREATE DATABASE college_placement_management;
USE college_placement_management;
```

 3. Execute the SQL Files

Run the SQL files in MySQL Workbench.

Recommended order:

```text
1. companies
2. jobs
3. skills
4. students / student skills
5. applications
6. interviews
7. placements
```

> If your SQL files already contain `CREATE DATABASE`, `USE`, or table-creation statements, follow the order and instructions provided inside those files.

 4. Execute Queries

After importing the tables and data, run SQL queries to retrieve placement statistics, application information, interview details, and placement records.

---

 📊 Example Use Cases

The database can be used to answer questions such as:

* Which students have applied for a particular company?
* Which companies have the highest number of applications?
* Which students have been placed?
* How many students were selected by each company?
* Which students possess a particular skill?
* How many interviews are scheduled?
* What is the placement status of a particular student?

---

💡 What I Learned

Through this project, I gained practical experience in:

* Relational database design
* SQL query development
* Database normalization
* Data relationships
* Query optimization concepts
* Stored procedures and triggers
* Database integrity and constraints
* Managing real-world structured data

---

🛠️ Tech Stack

| Technology          | Purpose                             |
| ------------------- | ----------------------------------- |
| **MySQL**           | Database                            |
| **SQL**             | Query language                      |
| **MySQL Workbench** | Database development and testing    |
| **GitHub**          | Version control and project hosting |

---

📁 Project Structure


college-placement-management-system/
│
├── placement_management_applications.sql
├── placement_management_companies.sql
├── placement_management_interviews.sql
├── placement_management_jobs.sql
├── placement_management_placements.sql
├── placement_management_skills.sql
├── placement_management_student_skills.sql
│
└── README.md


---

🌟 Project Highlights

> **Designed a structured relational database to manage the end-to-end college placement process using MySQL, applying real-world DBMS concepts such as normalization, relationships, joins, views, stored procedures, and triggers.**

---
 👨‍💻 Author

  Dhayanidhiya

Computer Science Engineering Student

📌 Interested in **Software Development | Java | SQL | DBMS | Data & AI**

---

 ⭐ Support

If you find this project useful, consider giving the repository a **⭐ Star**.

---

**Made with SQL & MySQL 💙**

