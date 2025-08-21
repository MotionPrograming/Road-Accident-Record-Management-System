# Road-Accident-Record-Management-System

# 🚦 Road Accident Record Management System (R-ARMS)

A beginner-friendly **road accident record management system** using Java Servlets and SQL database.  
This repository is designed for practicing **full-stack development, database management, and reporting features**.

---

## 📂 Repository Structure

R-ARMS/
│
├── data/
│ └── database.sql # SQL database schema
│
├── src/
│ ├── UserAuthenticationServlet.java # Login & Role Management
│ ├── AccidentRecordServlet.java # Add/Edit/Delete Accident Records
│ ├── ReportServlet.java # Generate Monthly/Yearly Reports
│ └── DatabaseConnection.java # JDBC Connection Handler
│
├── web/
│ ├── index.html # Login Page
│ ├── dashboard.html # User Dashboard (Admin/Reporter/Viewer)
│ ├── add_accident.html # Add Accident Record Form
│ ├── update_accident.html # Update Accident Record Form
│ ├── search_accident.html # Search Page
│ └── report.html # Report Page
│
├── README.md # Project description & instructions
└── pom.xml / build.gradle # Project build file (if using Maven/Gradle)

pgsql
Copy
Edit

---

## 📊 About the System

This system stores and manages road accident details, allowing users to **add, edit, delete, search**, and **generate reports** for better road safety management.

**Database Tables**

| Table      | Fields |
|------------|-------|
| Users      | `user_id, username, password, role` |
| Accidents  | `accident_id, date, time, location, vehicles, severity, reporter_id` |
| Reports    | `report_id, type, period, generated_on` |

---

## 🚀 Features / Modules

### 1️⃣ User Authentication & Roles
- **Admin:** Full access to all modules, manage users, view reports  
- **Reporter:** Add, edit, delete accident records  
- **Viewer:** Search and view accident records only  

### 2️⃣ Accident Record Management
- Add new accident details (date, time, location, vehicles, severity)  
- Update or delete records  
- Search accidents by date, location, or severity  

### 3️⃣ Report Generation
- Generate **monthly and yearly reports**  
- Display data in **tables and charts** for analysis  

---

## 🛠️ Tools, Libraries, and Software Used

**Programming Language:** Java  
**Frontend:** HTML, CSS, Bootstrap  
**Backend:** Java Servlets, JDBC  
**Database:** SQL (MySQL/Oracle/PostgreSQL)  

**Software & IDEs:**  
- Eclipse / IntelliJ IDEA / VS Code  
- JDK 1.8+  
- Git for version control  

---

## ⚡ How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/R-ARMS.git
Setup database

Import database.sql into your SQL server

Update DatabaseConnection.java with DB credentials

Build & Deploy

Use Eclipse/IntelliJ or Apache Tomcat server

Deploy the project

Open the project in a browser

Navigate to http://localhost:8080/R-ARMS

Login with Admin/Reporter/Viewer credentials

✅ Benefits
Reduces manual paperwork

Provides accurate accident records

Easy search and reporting

Role-based access ensures security

Charts and summaries help decision-making

🌟 Future Enhancements
Google Maps integration for accident locations

Machine learning for accident prediction

Mobile-friendly UI

Real-time notifications via Email/SMS

yaml
Copy
Edit
