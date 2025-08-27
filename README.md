⚙️ Project Working

Owned by MotionPrograming (Md Abdullah Rajeeb)
# 🚦 RA-RMS (Road Accident Record Management System)

## 📌 Introduction
The **RA-RMS** is a Java-based web application that records, manages, and analyzes road accident data.  
Currently, accident records are handled manually, which is slow and error-prone. RA-RMS automates this process using **Java (backend)**, **SQL (database)**, and a **modern frontend with JavaScript**, making accident tracking faster, more reliable, and user-friendly.


## 🎯 Objectives

* Store road accident details in a database.
* Allow users to **Add, Update, Delete, and Search** accident records.
* Generate **interactive charts** for accident analysis.
* Reduce paperwork and improve data accuracy.

---

## 🛠 Tools & Technologies

* **Programming Language:** Java
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Backend:** Java Servlets, JDBC
* **Database:** SQL (MySQL recommended)

---

## ✨ Features

### 🔑 User Authentication

* Secure login system (**Admin, Reporter, Viewer**)
* Role-based access control

### 📋 Accident Records

* Add accident details (date, time, location, vehicles, severity)
* Edit or delete accident records
* Search records by date, location, or severity

### 📊 Reporting

* Interactive charts and tables (using **Chart.js**)

### ⚡ JavaScript Enhancements

* Form validation (empty fields, valid email, date format)
* Dynamic UI updates without full page reload
* Interactive charts for accident reports

---

## 🖥 System Design

* **Input:** Accident details through user forms
* **Process:** Data validation → stored in SQL database via Servlets/JDBC
* **Output:** Accident lists and interactive charts

---

## 📂 Database Design

**Tables:**

**Users**

* `user_id` (PK)
* `username`
* `password`
* `role` (Admin / Reporter / Viewer)

**Accidents**

* `accident_id` (PK)
* `date`
* `time`
* `location`
* `vehicles`
* `severity`


---

## 🚀 Workflow

1. **Frontend:** User fills a form (HTML, CSS, JS)
2. **Request:** Form data sent to backend using HTTP POST/GET
3. **Backend:** Java Servlets validate data → store in SQL via JDBC
4. **Database:** Accident info stored securely
5. **Response:** Backend sends processed results
6. **Frontend:** JavaScript dynamically displays results (tables & charts)

---

## 📑 Expected Results

* Efficient storage and retrieval of accident records
* Role-based access ensures data security
* Accurate accident data for analysis
* Interactive charts for better decision-making

---

## ✅ Conclusion

RA-RMS provides a structured and interactive way to manage accident data.
With **Java backend, SQL database, and JavaScript frontend**, it ensures accurate record-keeping, reduces errors, and delivers actionable insights for road safety.

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/MotionPrograming/Road-Accident-Record-Management-System.git
```

1. Import the project into **Eclipse / IntelliJ IDEA**
2. Configure **Tomcat Server** in your IDE
3. Import the database (SQL file in `/database` folder)
4. Run the project and open in browser:

```
http://localhost:8080/RA-RMS/
```

---

## 👨‍💻 Roles

* **Admin:** Manage users, view all accident records
* **Reporter:** Add, edit, delete accident records
* **Viewer:** Search and view accident details

---


## 📄 License

This project is for **educational purposes** only.
