
# 💻 Java Desktop Aptitude Test System (QuizApp GUI)

A robust, desktop-based examination and aptitude testing system engineered with Java Swing, JDBC, and a relational MySQL database to deliver seamless interactive testing workflows.

---

## 🚀 Overview
This application provides a secure, structured platform for students to take exams, answer multiple-choice questions (MCQs), and receive instant score evaluations. Designed with clean desktop GUI principles, it bridges backend database operations with an intuitive user experience.

---

## 📸 Application Screenshot

<p align="center">
  <img src="./QuizeApp/src/icons/imageApp.png" width="600" alt="QuizApp GUI Interface" />
</p>

---

## 🔥 Key Technical Features

* **Secure Authentication System:** Student credential verification and session handling for safe exam access.
* **Dynamic Question Management:** Fetches and renders multiple-choice questions dynamically from the relational database.
* **Instant Evaluation & Scoring:** Automated real-time score calculation and immediate result display upon exam completion.
* **Relational Data Persistence:** Managed backend data storage and retrieval using MySQL via JDBC and XAMPP.
* **Performance Reporting:** Generates student performance metrics and historical exam result summaries.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Java (Swing GUI Framework)
- **Database Connectivity:** JDBC (Java Database Connectivity)
- **Database & Local Server:** MySQL / XAMPP
- **Architecture:** Model-View-Controller (MVC) pattern separating UI components from database logic.
- **Version Control:** Git & GitHub

---


## ⚙️ Getting Started & Installation

 **Clone the repository:.....**
   
Set up the Database:
Start XAMPP and run the MySQL service.
Import the provided SQL database schema into your MySQL server.
Configure Database Connection:
Update your JDBC connection string, username, and password in the database connection utility class within the project.
Run the Project:
Open the project in your preferred Java IDE (such as IntelliJ IDEA, Eclipse, or NetBeans).
Run the main application entry point to launch the Swing desktop interface.
