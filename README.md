# Data-Related-Projects

A collection of practical projects covering relational database design, SQL queries, Excel and Power BI data cleaning and visualization. Focused on data integrity, reporting, and turning raw data into actionable insights. Each project is based on real-world problems.

---

## 📁 Projects Included

### 1. Ekurhuleni West TVET College - Online Registration MIS [COMPLETED]
**Type:** Group Academic Project - MIS 3, Walter Sisulu University  
**Folder:** `/Management Information System...`

**Project Problem:**
EWC had 6 campuses using manual registration - students queued for hours moving between Finance (for clearance) and Registration. No integration, no real-time reports, high fraud risk.

**My Contribution - Section 5 & 6: Database Implementation and SQL Queries - Decision Support**
I was responsible for the full technical implementation:

**A. Database Implementation:**
- Created database `EWC_RegistrationDB` in SQL Server
- Implemented 5 normalized tables to 3NF: `courses`, `students`, `payments`, `financial_clearance`, `registrations`
- Created PK/FK relationships, CHECK constraints, UNIQUE reference numbers
- Inserted sample data for 13 students, payments and clearance records
- ERD designed in Figure 1

**B. SQL Queries & Decision Support (Figures 8-22) I wrote:**
- **TPS Level (Transaction Processing):** Student Lookup by surname, Clearance Status verification, Course Availability, Registered Students list
- **MIS Level (Management Reports):** Daily/monthly clearance summary, Monthly registration summary, Outstanding clearance report, Payment collection by method, Monthly revenue analysis, Course enrolment summary
- **DSS Level (Decision Support):** Registration trend by week, Aggregated payment statistics, Enrolment growth forecasting, Bottleneck identification (avg days to clear per finance officer), At-risk students report (cleared but not registered)

This implementation turned manual paper slips into a digital workflow with real-time visibility for finance officers and campus managers.

**Other Sections (Done by Team):** Problem Analysis, System Analysis, Proposed Solution Design, System Inputs/Outputs

### 2. Excel Data Cleaning & Visualization [COMING SOON]
**Folder:** `/02-Excel-Data-Cleaning` (to be added)
**What will be included:**
- Data cleaning techniques: removing duplicates, text-to-columns, handling missing values, data validation
- Formulas and functions: VLOOKUP/XLOOKUP, IF, COUNTIFS/SUMIFS
- Pivot Tables and Pivot Charts for summary reporting
- Interactive dashboards and slicers

### 3. Power BI Data Cleaning & Visualization [COMING SOON]
**Folder:** `/03-PowerBI-Dashboards` (to be added)
**What will be included:**
- Power Query for data transformation and cleaning
- Data modeling and relationships
- DAX measures
- Interactive dashboards and visual storytelling

---

## 🛠️ Skills Demonstrated
- **SQL:** DDL, DML, Joins, Aggregations, Constraints, Normalization
- **Database Design:** ERD, 3NF, Data Integrity, Audit Trails
- **Reporting:** TPS, MIS, DSS levels - operational to strategic
- **Next:** Excel (Pivot Tables, Dashboards), Power BI (Power Query, DAX)

## 👥 Credits
Group Project (MIS 3 project) - Team: Masixole Thebe, Tshepo Tsotetsi, Ayanda Mokoele, Luyanda Magagula
My Role: Section 5 and 6 - Database Implementation and All SQL Queries

## 👤 Author
Onalenna Honest Kgosi | Diploma in ICT in Business Analysis - Walter Sisulu University
