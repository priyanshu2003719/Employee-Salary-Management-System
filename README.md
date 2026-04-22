# Employee-Salary-Management-System
**Developed a web-based payroll system**

 **Employee Salary Management System**

-----

## 📈 Project Analysis

### **1. Core Value Proposition**

The system addresses the transition from manual payroll to automation. Its primary impact lies in **accuracy** and **time efficiency**, specifically targeting the reduction of human error in salary calculations and slip distribution.

### **2. Technical Architecture**

  * **Frontend:** Web-based interface (likely using ASP.NET/HTML/CSS based on documentation).
  * **Backend:** Logic handling for tax, deductions, and net pay.
  * **Database:** Oracle 11g (PL/SQL) is used for robust data management, handling complex relational data like employee details, department links, and salary history.
  * **Security:** Focuses on data integrity and restricted access to sensitive financial information.

### **3. Key Features**

  * **Automated Pay Slip Generation:** Digitizing the final output for employees.
  * **Centralized Record Keeping:** Storing employee demographics and salary structures in one place.
  * **Compliance:** Designed to handle standard deductions (PF, Professional Tax) and earnings (DA, HRA).

-----


# Employee Salary Management System

## 📌 Overview

The **Employee Salary Management System** is a web-based application developed for **South Eastern Railway**. It automates the generation and distribution of employee pay slips, replacing manual workloads with a secure, digital-first approach.

## 🚀 Key Features

  * **Automated Calculations:** Instant computation of Gross and Net Pay based on current HRA, DA, and PF rates.
  * **Secure Authentication:** Role-based access to ensure only authorized HR personnel can modify salary data.
  * **Pay Slip Generation:** One-click PDF/Report generation for employees.
  * **Database Management:** Utilizes Oracle 11g for high-concurrency data handling and integrity.

## 🛠 Tech Stack

  * **Frontend:** HTML5, CSS3, JavaScript
  * **Backend:** ASP.NET
  * **Database:** Oracle 11g (PL/SQL)
  * **Tools:** Visual Studio, SQL Plus

## 📂 Project Structure

  * `Documentation/`: Contains the project report and feasibility study.
  * `Presentation/`: The project PPT used for the final walkthrough.
  * `Source/`: Application source code and database scripts.

## 📊 Database Schema

The system relies on an E-R model consisting of the following core entities:

  * **Employee:** Personal details and unique IDs.
  * **Department:** Categorization for payroll scaling.
  * **Salary/Result:** Records of monthly earnings and deductions.

## 👥 Contributors

1.  **Priyanshu Sahoo** (B.Tech, AUK)
2.  **Soumyadip Chatterjee** (B.Tech, RCCIIT)
3.  **Ritam Kar** (B.Tech, RCCIIT)
4.  **Simran Khan** (B.Tech, BBIT)
5.  **Karandeep Singh** (BCA, AJU)
6.  **Meghana Mitra** (B.Tech, DYPU)

-----

## 💡 Suggestions for Improvement

If you want to take this project to the next level (or "Version 2.0"), consider these additions:

1.  **Cloud Integration:** Move the database to a cloud-based service (like Azure SQL or AWS RDS) for better accessibility.
2.  **Employee Dashboard:** Add a portal where employees can log in and download their own historical pay slips.
3.  **Analytics:** Use a library like Chart.js to show "Salary Trends" or "Departmental Cost Distribution" on the HR dashboard.

