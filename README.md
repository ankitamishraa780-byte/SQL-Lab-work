# SQL-Lab-work
# DBMS Lab – 1  
## SQL (DDL & DML Operations)

---

### 👩‍🎓 Student Details
- **Name:** Ankita Mishra  
- **Roll No:** 23706  
- **Semester:** 5th  
- **Course:** B.Tech (CSE / AI & ML)  
- **Subject:** Database Management Systems Laboratory  

---

## 📌 About the Assignment
This repository contains **DBMS Lab – 1 SQL assignment**.  
The lab focuses on implementing **DDL and DML SQL commands** using properly written `.sql` scripts.

Both the **question paper (PDF)** and the **solution file (`.sql`)** have been uploaded as required.

---

## 📂 Repository Structure
 SQL-exercise │ ├── SQL_exercise_1 │   │ │   ├── Lab-1-Questions.pdf │   ├── Lab-1-Solution.sql ││ ├── README.md
 ---

## ▶️ How to Execute the SQL Scripts
1. Open your SQL editor (MySQL Workbench / Oracle SQL Plus / SQLite)
2. Create or select the required database
3. Open and run the solution file:
4. https://github.com/ankitamishraa780-byte/SQL-Lab-work.git
5. Execute the queries in sequence
6. Verify results using `SELECT` statements

---

## ⚠️ Assumptions
- SQL queries are executed in the given order  
- The user has basic knowledge of SQL  
- The DBMS supports standard SQL syntax  
- The' https://github.com/ankitamishraa780-byte/SQL-Lab-work.git' file is used instead of screenshots or copied output  

****DBMS Laboratory – Lab 2****

College Management System Database Design

📌 **About the Assignment**

This laboratory experiment focuses on the design and implementation of a College Management System database.

The main objective of this lab is to understand how real-world systems are modeled using:

Entity Relationship (ER) Diagrams

Relational Schema

SQL Data Definition Language (DDL)

The complete database design process was followed, starting from conceptual modeling to physical implementation.

🎯 **Objectives**

To understand ER modeling using draw.io

To identify entities, attributes, and relationships

To convert ER diagrams into relational schema

To implement database tables using SQL

To apply constraints for data integrity

🗂** ER Model**

The ER diagram was created using draw.io and includes the following entities:

Student

Department

Faculty

Course

Enrollment

**Key Features:**

Attributes are clearly defined

Primary keys are identified

Relationships and cardinalities are specified

Many-to-Many relationship between Student and Course is resolved using Enrollment

🔗** Relational Schema Design**

The ER model was converted into a relational schema as follows:

Each entity → One table

Primary Keys (PK) → Unique identification

Foreign Keys (FK) → Relationship maintenance

Constraints → Data consistency

Relationships Implemented:

Department ↔ Faculty

Department ↔ Course

Student ↔ Course (via Enrollment)

**💻 SQL Implementation**

The relational schema was implemented using SQL DDL commands.

Features Used:

CREATE TABLE

PRIMARY KEY

FOREIGN KEY

NOT NULL

UNIQUE

CHECK constraints

All tables were created following proper dependency order.

📂** Repository Structure**
DB-Lab-2/
│── ER-Diagram.drawio / ER-Diagram.pdf
│── Relational-Diagram.png
│── Lab-2.sql
│── README.md
▶️ How to Execute

Open any SQL Editor:

MySQL Workbench

Oracle SQL Developer

SQLite Studio

Create or select a database:

CREATE DATABASE college_db;
USE college_db;

Open and run Lab-2.sql

Verify tables:

SHOW TABLES;
SELECT * FROM Student;
✅ Output

All tables are created successfully

Relationships are properly maintained

No constraint violations

Database schema matches ER model

⚠️ Precautions

Follow correct table creation order

Define foreign keys carefully

Avoid circular dependencies

Maintain naming consistency

Verify constraints after creation

📈 Learning Outcome

After completing this lab, students will be able to:

Design ER diagrams professionally

Convert conceptual models to relational models

Implement databases using SQL

Apply integrity constraints

Understand real-world database design

✅ Conclusion

This laboratory experiment provided practical experience in designing and implementing a relational database system.

It strengthened understanding of:

ER Modeling

Relational Schema Design

SQL DDL Commands

Data Integrity

This forms the foundation for advanced database operations.




📘 DBMS Lab–3: Data Collection and Data Insertion
1. Experiment Title

Data Collection and Data Insertion in College Database
2. Objective

The objective of this lab is to understand real-world data collection and insertion in a relational database using SQL.
This experiment focuses on collecting authentic institutional data and storing it in a structured database while maintaining data consistency and integrity.

. Database Used

The database schema created in Lab–2 (ER Diagram and Tables) has been used for this experiment.

Tables Used:

Department

Faculty

Course

Student

Enrollment

4. College Information

All data used in this experiment corresponds to:

B.P. Mandal College of Engineering, Madhepura, Bihar

5. Data Collection Method

All data has been collected from authentic and reliable sources such as:

Official College Website

Department Webpages

Class Timetable

Syllabus / Prospectus

Academic Notices

Class Roll List / Friend’s Details (for variation)

No imaginary or copied data has been used.

6. Data Sources
S.No	Source Type	Link / Reference
1	College Website	https://www.bpmcemadhepura.org

2	Department Page	(Mention Link)
3	Class Timetable	(Attach Screenshot)
4	Syllabus	(Mention PDF Link)
5	Academic Notice	(Attach Screenshot)
7. Data Description
7.1 Department Table

Department ID

Department Name

Office Location / Block

7.2 Faculty Table

Faculty ID

Faculty Name

Designation

Official Email

Department ID

7.3 Course Table

Course ID

Course Name

Credits

Department ID

Faculty ID

7.4 Student Table

Student ID

Student Name

Date of Birth

Gender

Contact Number (Dummy)

Department ID

7.5 Enrollment Table

Student ID

Course ID

Semester

Grade (Assumed)

8. Data Insertion Details

Minimum 10 records inserted in:

Student

Course

Enrollment

All INSERT queries are written in a single SQL file.

Foreign key constraints and primary key rules are strictly followed.

Order of insertion:

Department → Faculty → Course → Student → Enrollment
9. Files Submitted
File Name	Description
college_data.sql	Contains all INSERT queries
Screenshots	Proof of successful data insertion
README.md	Experiment documentation
10. Sample Verification Queries

To verify successful insertion, the following queries were executed:

SELECT * FROM Department;
SELECT * FROM Faculty;
SELECT * FROM Course;
SELECT * FROM Student;
SELECT * FROM Enrollment;

Screenshots of the outputs are attached.

11. Result

All collected data was successfully inserted into the database.
No primary key duplication or foreign key violation occurred.
The database maintains proper relational integrity.

12. Precautions

Only authentic data was used.

No random or fake values were inserted.

Dummy contact numbers were used for privacy.

Data consistency was maintained.

Proper insertion sequence was followed.

13. Conclusion

This experiment helped in understanding real-life data collection and its insertion into a relational database.
It improved practical knowledge of SQL INSERT operations, constraints, and database integrity management.
