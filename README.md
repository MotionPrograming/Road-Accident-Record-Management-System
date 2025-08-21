⚙️ Project Working

# 🚦 RA-RMS (Road Accident Record Management System)

## 📌 Introduction
The **RA-RMS** is a Java-based web application that records, manages, and analyzes road accident data.  
Currently, accident records are handled manually, which is slow and error-prone. RA-RMS automates this process using **Java (backend)**, **SQL (database)**, and a **modern frontend with JavaScript**, making accident tracking faster, more reliable, and user-friendly.

---

## 🎯 Objectives
- Store road accident details in a database.
- Allow users to **Add**, **Update**, **Delete**, and **Search** accident records.
- Generate monthly/yearly reports with charts.
- Reduce paperwork and improve accuracy.

---

## 🛠 Tools & Technologies
- **Programming Language:** Java  
- **Frontend:** HTML, CSS, Bootstrap, **JavaScript**  
- **Backend:** Java Servlets, JDBC  
- **Database:** SQL (MySQL recommended)  

---

## ✨ Features
### 🔑 User Authentication
- Secure login system (Admin, Reporter, Viewer).  
- Role-based access control.  

### 📋 Accident Records
- Add accident details (date, time, location, vehicles, severity).  
- Edit or delete accident records.  
- Search records by **date**, **location**, or **severity**.  

### 📊 Reporting
- Generate monthly and yearly accident reports.  
- Interactive **charts and tables (using JavaScript libraries like Chart.js)**.  

### ⚡ JavaScript Enhancements
- Form validation (check empty fields, valid email, date format).  
- Dynamic UI updates without full page reload.  
- Interactive charts for accident reports.  

---

## 🖥 System Design
- **Input:** Accident details (user forms).  
- **Process:** Data validated → stored in SQL database via Servlets/JDBC.  
- **Output:** Accident lists, reports, and interactive charts.  

---

## 📂 Database Design
### Tables:
1. **Users**  
   - user_id (PK)  
   - username  
   - password  
   - role (Admin/Reporter/Viewer)  

2. **Accidents**  
   - accident_id (PK)  
   - date  
   - time  
   - location  
   - vehicles  
   - severity  
   - reporter_id (FK → Users.user_id)  

3. **Reports**  
   - report_id (PK)  
   - type (monthly/yearly)  
   - period  
   - generated_on  

---

## 🚀 Workflow
1. **Frontend (HTML, CSS, Bootstrap, JavaScript):** User fills a form.  
2. **Request:** Form data → sent to backend using HTTP POST/GET.  
3. **Backend (Java Servlets):** Validate data → store in SQL via JDBC.  
4. **Database (SQL):** Accident info stored securely.  
5. **Response:** Backend sends processed results.  
6. **Frontend (JavaScript):** Displays results dynamically (tables & charts).  

---

## 📑 Expected Results
- Simple & efficient way to store and retrieve accident records.  
- Role-based access ensures data security.  
- Accurate accident data for analysis.  
- Interactive JavaScript-powered charts for decision-making.  

---

## ✅ Conclusion
The **RA-RMS** provides a structured and interactive way to manage accident data.  
With **Java backend**, **SQL database**, and **JavaScript UI**, it ensures accurate record-keeping, reduced errors, and better **road safety insights**.

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RA-RMS.git
````

2. Import the project into **Eclipse / IntelliJ IDEA**.
3. Configure **Tomcat Server** in your IDE.
4. Import the database (SQL file in `/database` folder).
5. Run the project and open in browser:

   ```
   http://localhost:8080/RA-RMS/
   ```

---

 👨‍💻 Roles

* **Admin** → Manage users, view all reports, access accident list.
* **Reporter** → Add, edit, delete accident records.
* **Viewer** → Search and view accident details.

---

 📸 Screens (Optional to add later)

* Login Page
* Dashboard (Admin/Reporter/Viewer)
* Add Accident Form
* Accident List (with Search)
* Reports Page (interactive charts)

---

📄 License

This project is for **educational purposes** only.


```
