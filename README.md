# ⚙️ Project Overview((Road Accident Record Management System))

**Owned by:** MotionPrograming (Md Abdullah Rajeeb)

## 🚦 RA-RMS (Road Accident Record Management System)

### 📌 Introduction

RA-RMS is a Java-based web application designed to record, manage, and analyze road accident data efficiently.
Currently, accident records are maintained manually, which is slow and prone to errors. RA-RMS automates this process using Java for the backend, SQL for the database, and a modern frontend powered by JavaScript, ensuring faster, more accurate, and user-friendly accident tracking.

---

### 🎯 Objectives

* Store detailed road accident information in a secure database.
* Enable users to Add, Update, Delete, and Search accident records seamlessly.
* Generate interactive charts to analyze accident trends.
* Minimize paperwork and improve data accuracy through automation.

---

### 🛠 Tools & Technologies

* **Programming Language:** Java
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Backend:** Java Servlets, JDBC
* **Database:** SQL (MySQL recommended)

---

### ✨ Features

#### 🔑 User Authentication

* Secure login system supporting Admin, Reporter, and Viewer roles.
* Role-based access control for data security and management.

#### 📋 Accident Records

* Add detailed accident reports (date, time, location, involved vehicles, severity).
* Edit or delete existing records.
* Search and filter records by date, location, and severity.

#### 📊 Reporting

* Interactive charts and tables using Chart.js for data visualization.

#### ⚡ JavaScript Enhancements

* Form validations for empty fields, valid emails, and date formats.
* Dynamic UI updates without needing full page reloads.
* Interactive reporting charts for insightful analysis.

---

### 🖥 System Design

* **Input:** User inputs accident details through web forms.
* **Process:** Data validation → JDBC operations to store/retrieve data in/from SQL database.
* **Output:** Display of accident records and interactive charts.

---

### 📂 Database Design

**Users Table**

* `user_id` (Primary Key)
* `username`
* `password`
* `role` (Admin / Reporter / Viewer)

**Accidents Table**

* `accident_id` (Primary Key)
* `date`
* `time`
* `location`
* `vehicles`
* `severity`

---

### 🚀 Workflow

1. User fills out accident form on the frontend.
2. Form data is sent via HTTP POST/GET to the backend.
3. Java Servlets validate the input and interact with the database using JDBC.
4. Data is stored securely in the SQL database.
5. Backend returns processed data/results.
6. Frontend dynamically displays data and charts using JavaScript.

---

### 📑 Expected Outcomes

* Efficient and accurate storage and retrieval of accident records.
* Secure, role-based access to system functions.
* Reliable accident data enabling effective analysis.
* Interactive, user-friendly charts to assist in decision-making.

---

### ✅ Conclusion

RA-RMS delivers a comprehensive and interactive solution to manage road accident data effectively. Using Java on the backend, a SQL database for storage, and JavaScript for a dynamic frontend, it ensures data accuracy, reduces manual errors, and provides valuable insights for improving road safety.

---

### 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/MotionPrograming/Road-Accident-Record-Management-System.git
```

* Import the project into **Eclipse** or **IntelliJ IDEA**.
* Configure a **Tomcat Server** in your IDE.
* Import the database using the SQL file found in the `/database` folder.
* Run the project and open in your browser at:

  ```
  http://localhost:8080/RA-RMS/
  ```

---

### 👨‍💻 User Roles

* **Admin:** Manage users and view all accident records.
* **Reporter:** Add, edit, and delete accident records.
* **Viewer:** Search and view accident details only.

---

### 📄 License

This project is for **educational purposes only**.

