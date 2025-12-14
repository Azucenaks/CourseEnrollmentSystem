# 📘 Course Enrollment System

## 📌 Java Console-Based Application

---

## 📌 Description / Overview

The **Course Enrollment System** is a Java-based console application designed to help students enroll in and manage their courses efficiently. It provides a simple and organized way to input course information, select course types, and store enrolled courses while preventing errors through proper input handling.

The system addresses the problem of manually tracking subjects by offering a structured interface that displays all enrolled courses in a clear and readable format. Its design highlights fundamental Object-Oriented Programming (OOP) concepts, making it both a functional system and an educational example of OOP implementation in Java.

---

## 🏷️ OOP Concepts Applied

This project demonstrates several core Object-Oriented Programming principles:

### 1. Abstraction
Abstraction is implemented through the use of an abstract **Course** class, which defines the common structure shared by all course types while leaving specific behavior to its subclasses.

### 2. Inheritance
Inheritance is demonstrated through the **LectureCourse**, **LaboratoryCourse**, and **SeminarCourse** classes. These classes extend the **Course** class and reuse its attributes and methods.

### 3. Polymorphism
Polymorphism is applied when each subclass overrides the `getCourseType()` method, allowing each course type to define and return its own behavior dynamically.

### 4. Encapsulation
Encapsulation is achieved by declaring fields within the **Course** class as private and accessing or modifying them through getter and setter methods. This ensures controlled data management and protects the internal state of objects.

---

## 🧩 Program Structure

The system is composed of multiple classes that work together to create a functional enrollment application:

- **Main** – Handles user interaction by displaying menus and accepting user input.  
- **EnrollmentSystem** – Manages the course array, performs input validation, and handles operations such as adding and viewing courses.  
- **Course (Abstract Class)** – Serves as a template containing shared attributes like course code, course name, and number of units.  
- **LectureCourse, LaboratoryCourse, SeminarCourse** – Subclasses that extend the Course class and define their specific course types.  

Together, these components form a simple yet organized structure suitable for demonstrating OOP concepts in a real-world application.

---

## ▶️ How to Run the Program

1. Open **Visual Studio Code**.  
2. Open the folder containing all Java source files.  
3. Open the **terminal** and ensure you are inside the project directory.  
4. Compile the Java files using:

```
javac *.java

````
Once executed, the program displays the main menu of the Course Enrollment System. Users can enroll multiple courses by entering the course code, course name, number of units, and selecting the course type. Each successful enrollment is confirmed with a message.

Users may also view all enrolled courses in an organized, numbered list showing detailed information and course types. Selecting the exit option ends the program and displays a goodbye message.

This project reinforces core programming skills and provides a practical example of how multiple classes interact in Java to form a complete system. It also serves as a foundation for expanding into more advanced features such as data validation, persistent storage, or graphical user interfaces.

🙏 Author And Acknowledgements
---
  Leo Azucena
---
implements OOP structure and logic

Program: BS Information Technology

Email: ianleoazucena@gmail.com

I would like to sincerely thank my groupmates for their hard work, creativity, and collaboration throughout this project. Your support, dedication, and valuable ideas were essential in overcoming challenges and successfully completing the system.

I would also like to thank our professor for providing us with the opportunity to work on this project. This experience allowed us to apply what we learned in class and further expand our knowledge of Object-Oriented Programming through hands-on practice.
