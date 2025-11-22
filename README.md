# Student Record Management System

 Overview of the Project
This is a simple Python project I built to help manage student marks without needing a messy pile of papers. Instead of calculating grades manually, this program lets you enter student details and marks, and it automatically handles the grading logic. It’s a text-based tool that stores data temporarily while the program is running.

 Features
* Add New Records: You can enter a student's Roll Number, Name, and marks for as many subjects as you need.
* Automatic Grading: The program checks the marks you enter (0-100) and automatically assigns a grade (A, B, C, D, E, or F) based on the score.
* Search Function: If you need to find a specific student, you don't have to look through the whole list. Just type their Roll Number, and it shows their report card.
* Error Handling: If you try to enter marks outside the 0-100 range, it warns you so you can fix it.

 Technologies/Tools Used
* Language: Python 3
* Libraries: None (Standard Python libraries only)
* Editor: VS Code / IDLE (or any text editor)

 Steps to Install & Run the Project
Since this is a simple script, you don't need to install any heavy software or external packages.
1.  Download the Code:
    Download the .py file (e.g., studentrecord.py) to your computer.
2.  Open Terminal/Command Prompt:
    Navigate to the folder where you saved the file.
3.  Run the Script:
    Type the following command and hit Enter:
    bash
    python main.py

 Instructions for Testing
Once the program starts, you will see a menu with 3 options. Here is how to test it:
1.  Enter Data (Option 1):
    * Select 1 to start adding students.
    * Enter a Roll Number (e.g., 101) and Name.
    * Enter the number of subjects (e.g., 3).
    * Enter the Subject Name (e.g., Maths) and Marks (e.g., 95).
    * Check: See if it assigns Grade 'A' automatically.
2.  Search for a Student (Option 2):
    * Select 2 from the main menu.
    * Enter the Roll Number you just created (101).
    * Check: The program should display a neat table with that student's marks and grades.
3.  Exit (Option 3):
    * Select 3 to close the application.

