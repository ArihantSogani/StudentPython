Student Management System in Python

📋 Overview
A streamlined command-line Student Management System built with Python that provides essential tools for managing student records. This application offers a simple but effective interface for viewing, adding, searching, and removing students from a database.


Student Management

View Students - Display the complete list of registered students

Add Students - Register new students with duplicate checking

Search Students - Quickly find specific students in the database

Remove Students - Delete student records from the system

System Features

User-friendly Interface - Simple menu-driven command line experience

Input Validation - Error handling for incorrect inputs

Cross-Platform Support - Works on both Windows and Unix-based systems

Repeat Operation - Option to continue using the program after each task

🔧 Requirements

Python 3.x

Standard libraries:
os (for system operations)
platform (for OS detection)

📥 Installation



# Navigate to the project directory
cd student-management-system

# Run the application
python student_management.py

🖥️ Usage
When you launch the application, you'll see the following menu:

------------------------------------------------------
|======================================================| 
|======== Welcome To Student Management System  ========|
|======================================================|
 ------------------------------------------------------

Enter 1 : To View Student's List 

Enter 2 : To Add New Student 

Enter 3 : To Search Student 

Enter 4 : To Remove Student

Select an option by entering the corresponding number.

💾 Data Structure
The system uses a Python list to store student names. In the current implementation, the data is initialized with default values but does not persist between program executions.

🚀 Future Enhancements

Persistent data storage using files or database

Additional student details (ID, age, grade, contact information)

Student record modification functionality

Statistical analysis of student data

Export capabilities (CSV, PDF reports)

Graphical user interface
