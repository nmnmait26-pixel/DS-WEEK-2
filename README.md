# 📊 Student Grade Calculator

This project is created as part of Week 2 of The Developers Arena Internship. It focuses on decision-making, loops, functions, and basic error handling in Python.

## 📝 Project Overview

The Student Grade Calculator is a Python-based console application that takes a student's name and marks as input and calculates the corresponding grade using predefined grading rules. The program ensures that only valid marks (0–100) are accepted and displays encouraging messages for each grade. It also prevents the program from crashing when invalid input is provided.

## 🎯 Project Objectives

The objectives of this project are to learn and apply if-elif-else decision-making, use while loops for input validation, create and use functions, handle errors using try-except, and build a structured and user-friendly Python program.

## 🛠️ Technologies Used

Python 3 is used to develop this project. No external libraries are required.

## ⚙️ Setup and Installation Instructions

Install Python 3 from https://www.python.org/downloads/ and make sure to select “Add Python to PATH” during installation. After installation, open the terminal or command prompt and verify Python by running `python --version`. Navigate to the project folder and run the program using `python grade_calculator.py`.

## 🧠 Grading Logic

The grading system used in this project is as follows:
A: 90–100
B: 80–89
C: 70–79
D: 60–69
F: 0–59

Each grade includes a motivational message for the student.

## 🧩 Code Structure Explanation

The program uses a function named calculate_grade(marks) to determine the grade and return an encouraging message. A while loop is used to repeatedly ask for marks until valid input is entered. A try-except block is used to handle non-numeric input and prevent program crashes. The output is displayed using formatted print statements for clarity.

## 📊 Sample Output

Enter student name: Priya  
Enter marks (0-100): 85  

📊 RESULT FOR PRIYA  
Marks: 85 /100  
Grade: B  
Message: Very Good! Keep it up 👍  

## 🧪 Test Cases

The project includes a test_cases.txt file containing multiple test scenarios such as valid input, invalid marks, non-numeric input, and boundary values to verify the correctness of the program.

## 🖼️ Screenshots of Working Application

Screenshots of the working program are stored in the screenshots folder. The screenshots show user input and the final output with grade and message.

## ✅ Technical Requirements Fulfilled

The project uses if-elif-else statements for grading logic, includes input validation using a while loop, defines and uses a function, displays encouraging messages for each grade, and implements basic error handling using try-except.

## 📂 Project Folder Structure

Week2-Grade-Calculator/  
README.md  
grade_calculator.py  
test_cases.txt  
screenshots/output.png  

## 🏁 Conclusion

The Student Grade Calculator successfully meets all Week 2 requirements of The Developers Arena Internship and demonstrates a clear understanding of Python control flow, loops, functions, and error handling.
