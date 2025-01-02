# Students-Marks-Representation
This program is a simple Python application built using the Tkinter library. It allows users to input student marks for various subjects, calculates the total marks, and assigns a grade to each subject based on the entered marks. The results, including individual grades and total marks, are displayed in a formatted report.

Features:
Input marks for predefined subjects: English, Maths, and Science.
Calculate grades for each subject based on the marks entered.
Generate a formatted report displaying marks, grades, and the total marks.
Simple graphical user interface (GUI) for input and output using Tkinter.

Grade Calculation:
The program uses the following grading criteria:
Marks >= 80: Grade A
60 ≤ Marks < 80: Grade B
50 ≤ Marks < 60: Grade C
Marks < 50: Grade D

Code Explanation:
The subjects list contains the predefined subject names.
The marks dictionary stores the entered marks using tk.IntVar for each subject.
The gradeFinding function determines the grade based on the entered marks.
The generate_report function calculates the total marks and prepares the report.
Tkinter widgets such as Label, Entry, and Button are used to build the GUI.
