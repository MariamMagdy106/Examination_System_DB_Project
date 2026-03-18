# 📝 Examination System (ASP.NET MVC + SQL Server)

## 📌 Overview

This project is a **web-based Examination Management System** built using **ASP.NET MVC** and **SQL Server**, designed to automate the process of creating, managing, and evaluating online exams.

The system fulfills all required specifications for managing exams, students, instructors, and generating detailed reports for analysis.

---

## 🎯 Objectives

* Automate the full examination lifecycle
* Manage students, courses, instructors, and exams
* Enable dynamic exam generation and automatic correction
* Provide powerful reporting for academic insights

---

## 🏗️ System Architecture

### 🌐 Web Application (MVC)

* Built using **ASP.NET MVC**
* Structured with:

  * Models
  * Views
  * Controllers

### 🗄️ Database Layer (SQL Server)

* Designed a complete **ERD (Entity Relationship Diagram)**
* Implemented normalized relational database
* Delivered full **database backup**
* Created **Database Dictionary (Documentation)**

---

### ⚙️ Stored Procedures

#### 🔹 CRUD Operations

* Select, Insert, Update, Delete for all main entities

#### 🔹 Core Functionalities

* Exam Generation
* Exam Answer Submission
* Exam Correction (Automatic grading)

---

## 📊 Reports & Analytics

### 📌 Available Reports:

1. 📄 **Students by Department**

   * Input: Department ID
   * Output: Students list

2. 🎓 **Student Grades Report**

   * Input: Student ID
   * Output: Grades in all courses

3. 👨‍🏫 **Instructor Courses Report**

   * Input: Instructor ID
   * Output:

     * Courses taught
     * Number of students per course

4. 📚 **Course Topics Report**

   * Input: Course ID
   * Output: Course topics

5. 📝 **Exam Questions Report**

   * Input: Exam ID
   * Output:

     * Questions
     * Choices

6. 📊 **Student Exam Answers Report**

   * Input: Exam ID + Student ID
   * Output:

     * Questions
     * Student answers

---

## 🔄 System Workflow

1. Admin manages students, courses, and instructors
2. Exams are generated dynamically using stored procedures
3. Students take exams through the web interface
4. Answers are stored in the database
5. System performs automatic correction
6. Reports are generated for analysis

---

## 🛠️ Tech Stack

* **Backend:** ASP.NET MVC (.NET)
* **Database:** SQL Server
* **Data Access:** ADO.NET
* **Reporting:** SSRS
* **Frontend:** HTML, CSS, JavaScript
* **Tools:** Git, GitHub

---

## 📈 Key Achievements

* ✔ Full exam lifecycle automation (creation → answering → correction)
* ✔ Clean MVC architecture implementation
* ✔ Efficient database design with stored procedures
* ✔ Advanced reporting system for academic insights

---
