ONLINE QUIZ SYSTEM - C++ OOPS PROJECT
=====================================

ABOUT
-----
A menu-driven Online Quiz System developed fully in C++ using Object-Oriented
Programming concepts. The console menu is the frontend/interface and the
classes, quiz logic and file operations form the backend.

REQUIREMENTS
------------
- Windows 10/11
- MinGW / g++ compiler (C++11 compatible)
- No internet connection or extra library required

HOW TO RUN (Windows)
--------------------
1. Extract the ZIP folder.
2. Open the extracted folder in VS Code.
3. Open Terminal in this folder.
4. Compile:
      g++ main.cpp -o OnlineQuiz.exe
5. Run:
      .\OnlineQuiz.exe

If your terminal does not find g++, install/configure MinGW and add its bin
folder to PATH. Keep questions.txt and results.txt in the same folder as the
EXE while running.

DEFAULT ADMIN LOGIN
-------------------
Username: admin
Password: admin123

STUDENT
-------
Choose Student Login, enter a name, then start the quiz. The system checks
answers, calculates marks and percentage, and saves results in results.txt.

ADMIN
-----
Choose Admin Login. Admin can add questions, view the question bank, delete
questions by ID and view all student results.

DATA FILE FORMAT
----------------
questions.txt stores:
ID|Question|Option A|Option B|Option C|Option D|Correct Option

Do not use the vertical bar character | inside question or option text.

OOPS CONCEPTS USED
------------------
1. Classes and Objects: Question, Result, Quiz, User, Student, Admin, QuizSystem.
2. Encapsulation: class data is private/protected and accessed through methods.
3. Inheritance: Student and Admin inherit from User.
4. Polymorphism: User has a virtual showRole() function overridden by derived
   classes; User is an abstract base class.
5. Constructors: used to initialize objects.
6. File Handling: fstream is used to store questions and quiz results.

NOTE
----
This is a C++ console-based academic project. Both the user interface and
application logic are written in C++. It is not an HTML/browser-based website.

