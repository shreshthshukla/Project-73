# 🎓 Campus Complaint & Grievance System

A simple **Java console-based application** designed to help students submit campus-related complaints and allow administrators to view and update their status.

The project demonstrates important **Object-Oriented Programming (OOP)** concepts in Java through a practical campus-based use case.

---

## 📌 Project Overview

The Campus Complaint & Grievance System provides a simple platform for students to report issues related to their campus, such as hostel problems, infrastructure issues, academics, mess facilities, or other concerns.

Students can submit and view their complaints, while administrators can view all complaints and update their status.

---

## ✨ Features

### 👩‍🎓 Student

* Submit a new complaint
* View submitted complaints
* Check complaint status
* Select complaint category

### 👨‍💼 Admin

* View all complaints
* Search complaints using Complaint ID
* Update complaint status
* Mark complaints as:

  * Pending
  * In Progress
  * Resolved

---

## 🛠️ Technologies Used

* **Java**
* **Object-Oriented Programming**
* **ArrayList**
* **Java Scanner**
* **Console Interface**

---

## 🧩 OOP Concepts Used

| Concept               | Implementation                                        |
| --------------------- | ----------------------------------------------------- |
| **Classes & Objects** | Student, Admin, Complaint, etc.                       |
| **Encapsulation**     | Private fields with getters and setters               |
| **Inheritance**       | Student and Admin inherit from User                   |
| **Polymorphism**      | Parent `User` reference for different users           |
| **Constructors**      | Used for object initialization                        |
| **Abstraction**       | Common properties and behavior through the User class |

---

## 📂 Project Structure

```text
CampusGrievanceSystem/
│
├── src/
│   ├── Main.java
│   ├── User.java
│   ├── Student.java
│   ├── Admin.java
│   ├── Complaint.java
│   └── GrievanceSystem.java
│
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CampusGrievanceSystem.git
```

### 2. Open the project

Open the project folder in **VS Code**, IntelliJ IDEA, or any Java-supported IDE.

### 3. Compile the program

Navigate to the `src` folder and run:

```bash
javac *.java
```

### 4. Run the application

```bash
java Main
```

---

## 🖥️ Sample Application Flow

```text
========================================
       CAMPUS GRIEVANCE SYSTEM
========================================

1. Student
2. Admin
3. Exit

Enter choice: 1

--------- STUDENT MENU ---------

1. Submit Complaint
2. View My Complaints
3. Back

Enter choice: 1

Enter Student ID: 24BCS1234
Enter Name: Pratibha
Enter Category: Hostel
Enter Complaint: Water supply problem

Complaint submitted successfully!

Complaint ID: C101
Status: Pending
```

---

## 📋 Complaint Categories

The system can handle complaints related to:

* 🏠 Hostel
* 📚 Academics
* 🏫 Infrastructure
* 🍽️ Mess/Food
* 💻 IT/Network
* 🚌 Transport
* 📌 Other

---

## 🔄 Complaint Status

Every complaint has a status that can be updated by the administrator:

```text
Pending → In Progress → Resolved
```

---

## 🎯 Objectives

* To develop a simple campus grievance reporting system.
* To provide an easy way for students to submit complaints.
* To allow administrators to manage complaint statuses.
* To demonstrate Java OOP concepts through a real-world application.
* To improve understanding of classes, inheritance, encapsulation, and ArrayList.

---

## 🔮 Future Enhancements

The project can be expanded in the future by adding:

* Database connectivity using MySQL
* Student and admin authentication
* GUI using Java Swing or JavaFX
* Email notifications
* Complaint priority levels
* File-based data storage
* Complaint search and filtering

---

## 👩‍💻 Author

**Anushka Upadhyay**

Computer Science & Engineering — AI & ML

---

## 📜 License

This project is created for **educational and academic purposes**.
