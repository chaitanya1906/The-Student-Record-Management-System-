Student Record Management System (SRMS) 

1. The Problem :

Honestly, the worst part of student admin is trying to keep track of marks on paper. It's not just annoying and slow—teachers constantly make calculation mistakes when adding up marks or trying to figure out the final letter grade by hand. Plus, if I need one student's record fast, digging through a stack of papers is a nightmare. My goal was simple: make a program that takes over the math and organization completely.

2. My Project Scope: 

This SRMS is just a CLI (Command Line Interface) tool built in Python. I designed the scope to be super tight to match the CPL 101 requirements.

What it does: It lets you enter a student's details, and their subject marks, and it figures out the final grade instantly.

The Catch (Limitations): I had to store all the data temporarily in lists and dictionaries (pure Python logic) and not in a real database. So, it only works for the current session, but it proves I mastered the memory structures we learned!

3. Target user:

Teachers: They can use it to quickly enter marks and get a neat report card without spending hours on calculations.

Class Monitors: A simple way to keep a digital list of class performance for the short term.

Students: A good, simple example of how a grading algorithm works in code.

4. Features:

Add Records: You can dump a new student's details and marks for as many subjects as you need.

Smart Grading: Forget checking the grading chart! If you enter a 90, the code instantly hits the $\text{'A'}$ block; if you enter 50, it goes to $\text{'E'}$. It's all automated using my manual $\text{if/elif}$ chain.

Search Function: If you want to check a student's status, just type their Roll Number. The code uses a super simple, manual loop to pull up their full record instantly.

Table View: It prints everything in a clean, column-aligned format on the screen, so it looks like a real, professional marksheet!
