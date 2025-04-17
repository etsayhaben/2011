# 🎓 Student Registration System (Console-Based Java Project)

## 📌 Project Overview

This project is a **console-based Java application** developed during the **second semester of my first year**. The application allows users to register multiple students, input their course information, compute GPA, and determine academic status based on performance. The program demonstrates fundamental **Object-Oriented Programming (OOP)** concepts including **class creation**, **inheritance**, **encapsulation**, and **method abstraction**.

---

## 💡 Key Features

- Register multiple students
- Input and store:
  - Student name
  - Gender
  - Department
  - ID number
  - List of courses, credit hours, and grades
- Calculate:
  - GPA (Grade Point Average)
  - Total earned grade points
  - Academic status (e.g., pass/fail)
- Displays a formatted report for each student
- Demonstrates the use of:
  - Classes and objects
  - Setters and getters
  - Loops and conditionals
  - Arrays and String formatting

---

## 🧪 Technologies Used

- **Java** (JDK 8 or later)
- Console/Terminal for Input/Output
- IDE: IntelliJ IDEA / Eclipse / NetBeans (any)

---

## 🛠️ How to Run

1. Ensure **Java JDK** is installed.
2. Compile the Java files:
   ```bash
   javac showstudent.java student.java



**
   sample output**

   how many students do you want to register
enter data for the students
===================================
enter name of the students 1: Alex
enter Alex's gender: Male
enter Alex's department: CS
enter Alex's idno: MU001
how many courses Alex has taken: 2
enter course 1 name: Java
Java credit hour: 3
Java's grade(a-f): A
...
================================================================================
students detail:
===============================================================================
1. name:-Alex           idno:-MU001   sex:-Male   department:-CS

coursename     crhr   grade   gpoint
Java             3       A        12
Math             4       B        12

cumulative gpa: 3.43    status:-Pass
------------------------------------------

