# 📚 Online Exam Management System

## 🔹 Project Overview

The **Online Exam Management System** is a web-based application developed using **JSP, Servlets, and MySQL**. It allows users to register, log in, attempt exams, and view results instantly.

---

## 🚀 Features

* User Registration & Login
* Online Exam Attempt
* Automatic Result Calculation
* Database Storage using MySQL
* Simple and Responsive UI using CSS

---

## 🛠️ Technologies Used

* Java (Core)
* JSP (Frontend)
* Servlets (Backend)
* MySQL (Database)
* JDBC (Database Connectivity)
* Apache Tomcat (Server)
* HTML & CSS (UI Design)
* Apache NetBeans (IDE)

---

## 📂 Project Structure

```
OnlineExamSystem/
 ┣ Web Pages/
 ┃ ┣ index.jsp
 ┃ ┣ login.jsp
 ┃ ┣ register.jsp
 ┃ ┣ exam.jsp
 ┃ ┗ result.jsp
 ┣ css/
 ┃ ┗ newcss.css
 ┣ Source Packages/
 ┃ ┣ DBConnection.java
 ┃ ┣ LoginServlet.java
 ┃ ┣ RegisterServlet.java
 ┃ ┗ ExamServlet.java
 ┗ web.xml
```

---

## ⚙️ Setup Instructions

1. Install Apache NetBeans and Apache Tomcat
2. Install MySQL and create database:

```sql
CREATE DATABASE online_exam;
```

3. Update database credentials in `DBConnection.java`:

```
username = root
password = 3804
```

4. Run the project on Tomcat Server
5. Open browser:

```
http://localhost:8080/OnlineExamSystem/
```

---

## 👤 Default Login (for testing)

```
Username: admin
Password: 1234
```

---

## 🎯 Output

* Register User
* Login System
* Attempt Exam
* View Score

---

## 📌 Conclusion

This project demonstrates the integration of frontend and backend technologies to build a dynamic and efficient online examination system.

---

## 👨‍🎓 Author

**Avinesh Kumar**

---

## ⭐ Note

This is a mini project for **Advanced Internet Programming (AIP)**.
