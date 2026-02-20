# StudentRecordManagement
Student Record Management System is a console-based C++ application that manages student data using structs and static arrays. It supports adding, displaying, searching, modifying, and deleting records through a menu-driven interface. The project demonstrates core C++ concepts including control flow, data handling, and manual memory management.

⸻


🎓 Student Record Management System (C++)


📌 About The Project


This is a simple console-based Student Record Management System built using C++.

The program allows users to manage student records using a menu-driven interface. It is designed as a beginner-level project to practice core C++ fundamentals such as structs, arrays, loops, and functions.

This project does not use STL containers or file handling. All data is stored in a static array and is lost once the program exits.


⸻


🚀 Features
	•	Add a new student
	•	Display all students
	•	Search student by roll number
	•	Modify student details
	•	Delete student record
	•	Exit system


⸻


🧠 Concepts Used

This project helps in understanding:
	•	struct in C++
	•	Static arrays
	•	Menu-driven programming
	•	Functions
	•	Loops and conditionals
	•	Linear search
	•	Manual array shifting (for delete operation)
	•	Basic memory boundary checking


⸻


🏗️ How Data is Stored

Each student is stored using a struct:

struct student {
    int roll;
    char name[50];
    float marks;
};


All student records are stored in:

student students[100];

Maximum capacity: 100 students.


⸻


▶️ How to Run

Step 1: Compile

g++ main.cpp -o student_system

Step 2: Run

./student_system

(Windows users may run student_system.exe)


⸻


⚠️ Limitations
	•	Maximum 100 students
	•	No file storage (data resets after program exit)
	•	Name input does not support spaces
	•	Duplicate roll numbers are not validated


⸻


🔮 Future Improvements
	•	Replace array with vector
	•	Add duplicate roll validation
	•	Support full name input using getline
	•	Add file handling for permanent storage
	•	Convert to class-based (OOP) version


⸻


📚 Purpose

This project was built to strengthen C++ fundamentals before moving to advanced topics like STL, object-oriented programming, and data structures.

