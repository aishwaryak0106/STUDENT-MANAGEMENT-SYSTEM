<h1 align="center">🎓 Student Management System – Oracle APEX</h1>

<p align="center">
  A complete web-based solution for managing departments, teachers, and students efficiently.<br>
  Designed with 💡 <b>Oracle APEX</b> and powered by ⚙️ <b>PL/SQL</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Oracle-APEX-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-PL%2FSQL-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/UI-Theme%3A%20Sunset%20Orange%20%E2%86%92%20Red-ff7e5f?style=for-the-badge">
</p>

---

## 🌟 Overview
This Oracle APEX project enables seamless management of **Departments**, **Teachers**, and **Students** with dashboards, KPIs, charts, and a leave request workflow.  
It’s designed for academic institutions to automate their internal academic operations.

---

## 🧠 Features
- 📊 Interactive dashboards with KPIs and charts  
- 🧑‍🏫 Faculty & student management with photo storage (BLOB)  
- 📅 Leave request & approval system  
- 🧮 Project & attendance tracking  
- 🎨 Themed interface (Sunset Orange → Red)  
- 🔐 Role-based access control (Admin, Teacher, Student)

  ### 👨‍🏫 Teacher Module
  - View and manage students
  - Submit and view their leave requests
  - Enter attendance and project marks
  
  ### 🎓 Student Module
  - View attendance, and internal marks
  - Submit project work
  - Semester registration
  
  ### 🧱 Admin Module
  - Manage departments, teachers, students
  - Control access and user roles
  - KPI dashboard with charts, calendar, and low-stock alerts

---

## ⚙️ Setup Instructions

### 🗄 1. Import Database Objects
1. In Oracle APEX → **SQL Workshop → SQL Scripts**
2. Upload and run: /database/full_database_script.sql 
3. This script will automatically create:
- Tables  
- Sequences  
- Triggers  
- Procedures  
- Functions  
- Scheduler Jobs

### 🧱 2. Import the APEX Application
1. Go to **App Builder → Import**
2. Upload the exported application file: /apex_app/f12345.sql
3. Click **Install Application → Run**

---

## 🧮 Key Technical Components
 ------------------------------------------------
| Category       | Technologies / Tools          |
|----------------|-------------------------------|
| Database       | Oracle 19c                    |
| App Builder    | Oracle APEX 23.x              |
| Programming    | PL/SQL, SQL, JavaScript, HTML |
| Authentication | Custom role-based login       |
| Styling        | Sunset Orange → Red theme     |
 ------------------------------------------------
---

## 📊 Dashboard Highlights
- KPI Cards (Total Students, Active Teachers, Pending Leaves)
- Bar Chart for Low Attendance
- Pie Chart for Leave Types
- Calendar Student Birthdays

1. ADMIN DASHBOARD   -> <img width="960" height="540" alt="admin-dashboard" src="https://github.com/user-attachments/assets/c2dd6245-f0f9-484f-ba73-b7ed8bde151c" />
2. FACULTY DASHBOARD -> <img width="960" height="540" alt="faculty-dashboard" src="https://github.com/user-attachments/assets/5ac005ac-8db4-44e1-8d29-efecf574dafc" />
3. STUDENT DASHBOARD -> <img width="960" height="540" alt="student-dashboard" src="https://github.com/user-attachments/assets/7b4501a7-311b-425f-bafa-71992d070bf0" />

 # 📊 Main Screenshots
 # 1. LOGIN : 
   <img width="960" height="540" alt="login" src="https://github.com/user-attachments/assets/c3def6cb-c350-4e7f-bd2b-e8e07efe0a67" />
   
 # 2. ADMIN : 
   MANAGE LEAVE REQUEST PAGE -> <img width="960" height="540" alt="admin-manage-leave" src="https://github.com/user-attachments/assets/2f68ff0d-34cf-46c6-ac5c-e13d68ff4bfc" />
 
   ISSUED CRITERIAS FOR MARK -> <img width="960" height="540" alt="admin-mark-criterias" src="https://github.com/user-attachments/assets/5484d4e5-841d-4eb7-9778-c06d9eadcd3c" />
 
   MANAGE DEPARTMENTS PAGE   -> <img width="960" height="540" alt="department-1" src="https://github.com/user-attachments/assets/c3381962-8add-40cc-98cc-3d6f450cc8af" /> <img width="960" height="540" alt="department-2" src="https://github.com/user-attachments/assets/2ff9bc4e-f42d-4d07-a623-1d147ab726c2" />

 # 3. FACULTY : 
   ALLOT MARK PAGE         -> <img width="960" height="540" alt="teacher-allot-mark" src="https://github.com/user-attachments/assets/f7ed57d1-e18f-4712-a3fb-a2388c332866" />

   ATTENDANCE PAGE         -> <img width="958" height="453" alt="teacher-attendance" src="https://github.com/user-attachments/assets/9bcc3940-fbc5-4152-b698-99d10fb9d496" />

   STUDENT EVALUATION PAGE -> <img width="960" height="540" alt="teacher-student-evaluation" src="https://github.com/user-attachments/assets/e4cca98c-49aa-427a-9788-6424e41ddb55" />

 # 4. STUDENT :
   PROJECT SUBMISSION PAGE    -> <img width="960" height="540" alt="student-project-submission" src="https://github.com/user-attachments/assets/d0857ff3-8804-413d-8414-74badbab22e1" /> <img width="960" height="455" alt="student-project-submission-final" src="https://github.com/user-attachments/assets/f7ef610d-a5b4-493c-a90f-9129b70f5138" />

   SEMESTER REGISTRATION PAGE -> <img width="960" height="540" alt="student-sem-registration" src="https://github.com/user-attachments/assets/05d0f0b5-5dc7-4c1b-829e-ea6a5a8ce762" /> <img width="960" height="540" alt="student-sem-registration-pay" src="https://github.com/user-attachments/assets/de12a242-fa96-4f04-82c3-9c74915dbc8c" /> <img width="960" height="540" alt="student-sem-registration-paid" src="https://github.com/user-attachments/assets/52909670-3660-4a43-899b-a2e180e73efb" /> <img width="960" height="540" alt="student-sem-payslip" src="https://github.com/user-attachments/assets/6a3663f4-a9eb-4795-b0cc-7b11d514d9d3" />

---

## 👩‍💻 Developer
**Aishwarya K**  

💼 Oracle APEX & PL/SQL Developer  |  📧 aishwaryakavil@gmail.com  |  🌐 www.linkedin.com/in/aishwarya-k-661870249

⭐ *If you found this project helpful, please give it a star on GitHub!* ⭐

---
