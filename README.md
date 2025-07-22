# 📚 Teacher Management System (Java GUI)

A Java-based GUI application for managing teacher information in an educational institution. This project was developed as part of the **Advanced Database Systems Development** module for the Autumn 2023–24 semester.

## 🔍 Overview

This system allows users to:
- Add lecturers and tutors
- Grade lecturer assignments
- Set tutor salaries
- Remove tutors
- Display information of both types of teachers

The GUI is built using **Java Swing**, and the project demonstrates concepts of **object-oriented programming**, **inheritance**, **GUI event handling**, and **error handling** using try-catch blocks.

## 🛠️ Features

- ✅ Add new Lecturer or Tutor with required details
- ✅ Grade assignments for Lecturers (score-based grading system)
- ✅ Set Tutor salaries based on performance index and working hours
- ✅ Remove Tutors (with restrictions)
- ✅ Display data for all stored Teachers
- ✅ Input validation and error dialogs for invalid entries

## 🧱 Class Structure

- `Teacher` – Base class for shared attributes (ID, name, address, etc.)
- `Lecturer` – Inherits from `Teacher`, adds grading-related features
- `Tutor` – Inherits from `Teacher`, includes salary and certification handling
- `teacherGUI` – Main class that creates and manages the Java Swing GUI

## 🧪 Testing

Extensive manual tests were performed including:
- Running via command line
- Adding both Lecturers and Tutors
- Handling edge cases like invalid input
- Verifying grading and salary logic
- Ensuring proper error dialogs appear

## 📸 Screenshots

> Include screenshots of your application GUI, if possible  
> *(e.g., lecturer form, tutor form, error dialog box, etc.)*

## 📁 How to Run

1. Install [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
2. Open the project in **BlueJ** or any Java IDE
3. Compile all `.java` files:
   - `Teacher.java`
   - `Lecturer.java`
   - `Tutor.java`
   - `teacherGUI.java`
4. Run `teacherGUI.java` and start the application

Or use terminal:

```bash
javac Teacher.java Lecturer.java Tutor.java teacherGUI.java
java teacherGUI
🧑‍💻 Developed By
Bachan Timalsina
London Met ID: 23047401
College ID: NP01NT4A230100
Group: N6

🙏 Acknowledgments
Special thanks to:

Mrs. Astha Sharma & Mr. Ujjwal Subedi for mentoring

My classmates for insightful discussions

Tools used: BlueJ, MS Word, Draw.io
