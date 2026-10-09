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

2. IWS BizConnect - Web Application Testing (WAT) [COMPLETED]
   
Type: Group Academic Project - Web and Application Software Testing (WAT), Walter Sisulu University
Folder: /04-WAT-Testing-Report
Report: Group_8_WAT_Testing_Report.docx

Project Problem: Walter Sisulu University needed a platform (iWS BizConnect) to help student entrepreneurs (tutoring, design, catering) advertise their services to fellow students. The development team built a prototype with two roles - Student Customer and Student Entrepreneur - but it had functional and usability issues before deployment.

Testing Objective: As the testing team (Group 8), our responsibility was to verify the system functions correctly, securely, and efficiently using black-box testing from the end-user perspective.

Testing Methodology Used:
- Levels: Unit, Integration, System, User Acceptance, Security, Performance, Usability, Compatibility Testing
- Approach: Manual black-box testing, Positive & Negative testing, High-risk first (login/registration)
- Environment: Windows 10/11, Chrome, Laptops & Smartphones
  
My Contribution - Bug Tracker & Retester:
I was the Bug Tracker & Retester, responsible for quality assurance and defect lifecycle:

A. Defect Logging & Reporting:
I recorded and documented 8 major defects with full reproduction steps, severity, and suggested fixes, including:
- DEF001: Home button logs user out instead of returning to feed (Major)
- DEF002: Business profile requires duplicate data entry (Major)
- DEF003: Business price not displayed on customer dashboard - shows "price not set" (Major)
- DEF004: PDF portfolio export logs entrepreneur out and fails to generate (Major)
- DEF005 & DEF006: Share button fails, Customers cannot submit reviews (Major)
- DEF007 & DEF008: Interests feature incomplete, Report Business lacks business selection

B. Test Execution & Retesting:
Participated in executing 20 test cases (TC001-TC020) covering registration, profile creation, messaging, media uploads, category filtering, password changes, and PDF export. After developer fixes, I retested to confirm issues were resolved and no regression was introduced.

C. Test Reporting:
Contributed to the final Test Report, Recommendations, and Overall Evaluation - concluding that while core functions like registration, messaging, and media upload were working (PASS), 5 Major defects must be fixed before deployment.

Other Sections (Done by Team): System Overview, Test Plan, Functional Testing (Registration, Profile Creation), Usability Testing.

Skills Demonstrated for this project: Software Testing Life Cycle (STLC), Test Case Design, Bug Tracking, Defect Reporting, Black-Box Testing, QA Documentation.

### 3. Excel Data Cleaning & Visualization [COMING SOON]
**Folder:** `/02-Excel-Data-Cleaning` (to be added)
**What will be included:**
- Data cleaning techniques: removing duplicates, text-to-columns, handling missing values, data validation
- Formulas and functions: VLOOKUP/XLOOKUP, IF, COUNTIFS/SUMIFS
- Pivot Tables and Pivot Charts for summary reporting
- Interactive dashboards and slicers

### 4. Power BI Data Cleaning & Visualization [COMING SOON]
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
- Software Testing & QA: STLC, Test Planning, Manual Testing, Bug Tracking, Defect Reporting, Retesting
- **Next:** Excel (Pivot Tables, Dashboards), Power BI (Power Query, DAX)

## 👥 Credits
👥 Credits
Group Projects - Team: Masixole Thebe (Group Leader), Tshepo Tsotetsi, Ayanda Mokoele, Luyanda Magagula, Onalenna Kgosi
My Roles: Section 5 and 6 - Database Implementation and All SQL Queries (EWC Project) | Bug Tracker & Retester - Defect Documentation & Retesting (IWS BizConnect Project)
## 👤 Author
Onalenna Honest Kgosi | Diploma in ICT in Business Analysis - Walter Sisulu University
