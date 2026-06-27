# CodeAlpha_task_1
Student Grade Tracker
A simple and efficient Java console application designed to input, track, and analyze student grades. The program computes the average score, as well as the highest and lowest grades from the entered data.

🚀 Features
Dynamic Input: Allows the user to specify the exact number of students.

Grade Analysis: Automatically calculates and displays:

The class average.

The top-performing grade (Highest).

The lowest grade.

Clean Architecture: Built using modular programming practices with dedicated helper methods for each calculation (findAverage, findhighest, findlowest).

🛠️ Technical Details & Design Choices
Language: Java

Data Structure: Array (double[])

Note on Design: Since the number of students is defined dynamically at the start of execution and does not change during runtime, a standard primitive Array was chosen over an ArrayList for optimal memory efficiency and fixed-size performance.

Input Handling: Utilizes java.util.Scanner for interactive console input.

📋 How It Works (Sample Execution)
The program prompts you to enter the total number of students.

You input each student's grade sequentially.

The application processes the data and outputs the calculated metrics.
