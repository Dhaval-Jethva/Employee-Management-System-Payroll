# Employee Management System + Payroll (EMS)

> **Portfolio Project Showcase**

> A web-based Employee Management System with payroll, attendance, salary calculation, reporting.

---

## 📌 Project Overview

The **Employee Management System + Payroll (EMS)** is designed to manage employee information, organizational masters, attendance data, salary-related information, payroll calculations, and employee-facing functionality through APIs.

The system brings employee management, attendance, payroll-related calculations, and reporting into a centralized platform.

---

## 🛠️ Technology Stack

| Area | Technology |
|---|---|
| Frontend | Laravel Blade templates with Vite asset bundling, Bootstrap-based theme |
| Backend / Database | Laravel 10.x, PHP 8.1+, MySQL |
| Authentication | Laravel Sanctum (API token-based), Laravel Session (web) |

---

## ⭐ Key Functional Areas

The system includes the following major functional areas:

- Employee Management
- Organization & HR Masters
- Shift & Holiday Management
- Leave Management
- Attendance Management
- Machine Data Synchronization
- Salary & Payroll Management
- Advance Salary Management
- Employee Additional Wage Management
- Salary History
- Payroll & Attendance Reports
- Employee Salary Slip

---

## 👥 Employee Management

The Employee Management module provides functionality for maintaining employee information within the system.

### Features
- Add new employee
- Manage employee records
- Employee master
- Employee-related management

### Screenshot
![Employee Management](images/employee-management.png)

---

## 🏢 HR & Organization Masters

The system provides centralized master management for important employee and organizational information.

### Employee Master
Manage employee information.

### Department Master
Manage departments used within the organization.

### Designation Master
Manage employee designations.

### Shift Master
Manage employee shifts and shift-related information.

### Holiday Master
Manage organizational holidays.

### Professional Tax Master
Manage professional tax-related configuration.

### Wage Types Master
Manage different wage types used for employee salary calculations.

### Screenshots
![Department Management](images/department-management.png)
![Designation Management](images/designation-management.png)
![Shift Management](images/shift-management.png)
![Holiday Management](images/holiday-management.png)
<!-- ![Professional Tax Management](images/professional-tax.png) -->
![Wage Types Management](images/wage-types.png)

---

## 🏖️ Leave Management

The system provides comprehensive leave management functionality, including leave types and leave policies.

### Leave Types Master
Manage different types of leaves (e.g., sick leave, casual leave, earned leave).

### Leave Policies Master
Define leave policies such as leave entitlement, carry forward rules, encashment policies, etc.

### Screenshots
![Leave Types Management](images/leave-types.png)
<!--![Leave Policies Management](images/leave-policies.png)-->

---

## ⏱️ Attendance Management

The system includes attendance-related functionality for tracking employee attendance information.

### Features
- Machine data synchronization
- Attendance reports
- Missing punch reporting
- Employee attendance reporting
- Attendance count used in salary calculations

### Attendance Reports
The system includes:
- Attendance Report
- Missing Punch Report
- Employee Attendance Report

### Screenshots
![Attendance Report](images/attendance-report.png)
![Missing Punch Report](images/missing-punch-report.png)
![Employee Attendance Report](images/employee-attendance-report.png)

---

## 💰 Payroll & Salary Management

The payroll functionality supports salary-related calculations and salary history management.

### Features
- Manage and calculate salary history
- Salary calculation
- Petrol allowance calculation
- Overtime calculation
- Professional tax calculation
- Advance salary deduction
- Additional wage management
- Salary slip generation

---

## 🧾 Salary Calculation

The salary report supports separate calculation of:
- Salary
- Petrol allowance
- Overtime

Professional tax and advance salary deductions are also included in salary slip calculations.

---
<!--
## 💵 Advance Salary Management

The system includes functionality to manage advance salary information.

### Features
- Manage advance salary entries
- Advance salary deduction during salary slip calculation
- Employee advance salary entry through API

### Screenshot
![Advance Salary](images/advance-salary.png)

---
-->

## 📈 Employee Additional Wage Management

The system provides functionality to manage additional wages for employees.

Wage types are maintained through the **Wage Types Master**, while employee additional wage information can be managed separately.

### Screenshot
![Additional Wage](images/additional-wage.png)

---

## 📊 Dashboard & Reports

The dashboard provides visibility into employee and attendance-related information.

### Dashboard Reporting
The system includes reporting for:
- Late Comers
- Early Leavers
- Detailed dashboard reporting is also available.

### Payroll & Attendance Reporting
Reports include:
- Holidays count in salary report
- Attendance count
- Total earnings
- Total deductions
- Employee salary slip
- Salary, petrol allowance and overtime calculations
- Professional tax calculation
- Advance salary deduction

### Screenshots
![Dashboard](images/dashboard.png)
![Dashboard Report](images/dashboard-report.png)

---

## 🔄 Functional Workflow

The major system flow can be represented as:

```
Employee & HR Masters
        ↓
Employee Management
        ↓
Shift / Holiday Configuration
        ↓
Leave Management Configuration
        ↓
Attendance / Machine Data
        ↓
Attendance Reports
        ↓
Salary & Payroll Calculation
        ↓
Earnings & Deductions
        ↓
Salary Slip
        ↓
Payroll / Employee Reports
```

---

## 🖥️ UI Showcase

Use this section to showcase the most important screens of the system.

### 1. Dashboard
![Dashboard](images/dashboard.png)

### 2. Dashboard Report
![Dashboard Report](images/dashboard-report.png)

### 3. Add New Employee
<!-- ![Add Employee](images/add-employee.png) -->

### 4. Employee Management
![Employee Management](images/employee-management.png)

### 5. Department Management
![Department Management](images/department-management.png)

### 6. Designation Management
![Designation Management](images/designation-management.png)

### 7. Holiday Management
![Holiday Management](images/holiday-management.png)

### 8. Shift Management
![Shift Management](images/shift-management.png)

### 9. Leave Types Management
![Leave Types Management](images/leave-types.png)

<!--
### 10. Leave Policies Management
![Leave Policies Management](images/leave-policies.png)
-->

### 11. Attendance Report
![Attendance Report](images/attendance-report.png)

### 12. Missing Punch Report
![Missing Punch Report](images/missing-punch-report.png)

### 13. Employee Attendance Report
![Employee Attendance Report](images/employee-attendance-report.png)

---

## 🎯 Business Value

The EMS platform provides a centralized system for:
- Managing employee information
- Managing HR and organizational masters
- Managing leave types and policies
- Monitoring attendance
- Handling attendance-related reports
- Supporting payroll and salary calculations
- Managing employee salary advances
- Calculating earnings and deductions
- Generating employee salary slips
- Providing employee-facing APIs

---

## 🔧 Customization Possibilities

The system can be extended or customized according to specific business requirements.

Possible customization areas include:
- Additional employee management modules
- Custom payroll rules
- Custom salary components
- Additional attendance rules
- Custom leave policies and types
- Custom reports
- Additional employee APIs
- New HR masters
- Organization-specific workflows
- Additional dashboard metrics

---

## 📋 Module Summary

| Module | Included Functionality |
|---|---|
| Employee Management | Employee creation and management |
| Department | Department master management |
| Designation | Designation master management |
| Shift | Shift master management |
| Holiday | Holiday master management |
| Professional Tax | Professional tax master |
| Wage Types | Wage type management |
| Leave Types | Leave type management |
| Leave Policies | Leave policy management |
| Machine Data Synchronization | Attendance machine synchronization |
| Additional Wage | Employee additional wage management |
| Advance Salary | Advance salary management and deduction |
| Salary History | Manage & calculate salary history |
| Attendance | Attendance and punch-related reports |
| Payroll | Salary, allowance, overtime and deduction calculations |
| Salary Slip | Employee salary slip |
| Dashboard | Employee and attendance-related dashboard reporting |
| APIs | Employee authentication, punch, dashboard, advance salary and monthly report APIs |

---

## 🚀 Project Highlights

- Employee management
- Payroll and salary processing
- Attendance management
- HR master management
- Leave management (types and policies)
- Salary calculation
- Earnings and deduction tracking
- Employee salary slips
- Attendance and payroll reporting
- Laravel Sanctum-based API authentication

---

## 📞 Interested in a Similar Solution?

This project can be customized and extended based on your organization's employee management, attendance, payroll, reporting, and API requirements.

**Custom modules, workflows, reports, and integrations can be developed according to business requirements.**