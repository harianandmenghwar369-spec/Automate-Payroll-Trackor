# Hi, I'm Hari — Data Analytics & Finance Specialist

# 📊 Automated Payroll & Attendance Tracker

<div align="left">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/Fiverr-Hari__dm-00B22D?style=for-the-badge&logo=fiverr&logoColor=white" alt="Fiverr" />
  <img src="https://img.shields.io/badge/Analytics-Finance-0052CC?style=for-the-badge" alt="Analytics-Finance" />
  <img src="https://img.shields.io/badge/Location-Karachi,_Pakistan-1E3A8A?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" />
</div>

A dynamic, fully automated **Payroll and Attendance Tracker** built entirely in Microsoft Excel. This project bridges daily workforce operations with monthly financial reporting, eliminating manual errors, automating the calculation of earned salaries, processing standardized compliance deductions, and rendering real-time metrics for leadership decision-making.

---

## 🚀 Core Functionalities

* **Automated Attendance Analytics:** Logs daily records via standardized operational codes with immediate database summary updates.
* **Dynamic Financial Engine:** Computes exact prorated basic salaries, processes fixed statutory deductions, and maps final net pay numbers flawlessly.
* **Built-In Exception Handling:** Automatically flags accounts exceeding standard absence limits to protect organizational workflows.
* **Management KPI Matrix:** Generates immediate insight into headcount, operational expenditures, and performance averages (currently sitting at a strong **95.8%** attendance rate).
* **Internal Framework Documentation:** Features a comprehensive guide right inside the tool for seamless user onboarding and scalability.

---

## 📂 Architecture & Sheet Breakdown

The tracking matrix is divided into four hyper-linked operational modules:

### 1. Attendance Register (`Attendance.png`)
* **Database Schema:** Direct logging for all team members across operational dates.
* **Automated Calculations:** Uses robust lookup arrays to dynamically aggregate total `Present` days and separate absence incidents, entirely avoiding row-by-row manual sums.

### 2. Monthly Payroll Calculator (`Payroll.png`)
* **Formula Engine:** Integrates parameters from the live attendance registry sheet.
* **Financial Logic:** Dynamically calculates variables using the following operational flow:
    $$\text{Earned Salary} = \frac{\text{Basic Salary}}{\text{Working Days}} \times \text{Days Present}$$
* **Deductions Matrix:** Calculates fixed EOBI metrics (standard PKR 250 logic) and outputs final net payable amounts. Employs conditional logical strings to evaluate compliance checks (`OK` vs `Review`).

### 3. Executive Dashboard (`Dashborad.png`)
* **High-Level KPI Blocks:** Aggregates underlying multi-variable records into absolute top-line indicators:
    * **Total Headcount:** 10 Active Employees
    * **Net Payroll Expenditure:** PKR 287,135
    * **Overall Workforce Attendance Rate:** 95.8%
* **User Interface Design:** Built using an executive deep navy and clean forest green palette, structured for clean cross-tab glance readability.

### 4. Interactive User Guide (`Instructions.png`)
* **Operational Rules:** Explicit structural setup rules detailing how to change global variables (e.g., standard working days, static deduction rates) and cleanly add new employee profiles without destroying cell references.

---

## 🛠️ Technical Skill Inventory

* **Cross-Sheet Workbook Engineering:** Dynamic matrix relationships linked perfectly across operations and finance databases.
* **Advanced Formula Optimization:** Deep logical functions (`IF`, `IFS`), data arrays, and conditional mathematical counting expressions.
* **UI/UX Formatting Standards:** Clean data hierarchies, professional grid control, and muted executive color balancing.
* **Workflow Risk Mitigation:** Standardized status validation rules to isolate and secure cells against manual user typos.

---

## 🧑‍💻 About the Author

**Hari — Data Analytics & Finance Specialist**
* 📍 **Location:** Karachi, Pakistan
* 📈 **Focus:** Translating operational volumes and transaction structures into polished, formula-driven financial frameworks.
* ⚙️ **Expertise:** Advanced Excel & VBA, Linked Financial Modeling, Interactive Dashboards, and Data Sanitization.

### Get In Touch
* **Fiverr:** [hari_dm](https://www.fiverr.com/hari_dm)
* **LinkedIn:** [Connect on LinkedIn](https://linkedin.com)

---
*Note: Layout images linked in documentation (`Attendance.png`, `Payroll.png`, `Dashborad.png`, `Instructions.png`) map out the production-ready state of this tracker.*
