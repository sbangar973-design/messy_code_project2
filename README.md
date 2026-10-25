# messy_code_project2
pushed a project from cursor ai
# Student Marks Report Generator 📝

A simple Python program that calculates students' total marks, average marks, grades, class average, and topper using lists, loops, and functions.

## 📌 Project Overview

This project generates a student marks report using predefined student data. It calculates each student's total marks and average, assigns a grade based on the average, calculates the class average, and identifies the topper.

## ✨ Features

- Stores student names and subject marks using nested lists.
- Calculates total marks using a user-defined function.
- Calculates each student's average marks.
- Assigns grades based on average marks.
- Calculates the overall class average.
- Identifies the topper based on the highest average.

## 🛠️ Technologies Used

- **Language:** Python
- **Concepts:** Functions, lists, loops, conditional statements, arithmetic operations, and string formatting.

## 📂 Project Structure

```text
Student-Marks-Report/
├── messy_py.py
└── README.md
```

## ⚙️ How It Works

### 1. Student Data

The program stores each student's name and marks in a nested list.

```python
d = [
    ["Rahul", 78, 88, 92],
    ["Priya", 65, 71, 69],
    ["Amit", 90, 94, 85],
    ["Sneha", 55, 60, 58],
    ["Vikram", 82, 79, 88]
]
```

### 2. Calculate Total Marks

The function `f(x)` calculates the total marks for a student.

```python
def f(x):
    t = 0
    for i in range(1, len(x)):
        t = t + x[i]
    return t
```

The loop starts at index `1` because index `0` contains the student's name. The remaining elements contain numerical marks.

### 3. Calculate Average and Grade

The program divides the total marks by three to calculate the average. It then assigns a grade using conditional statements.

| Average marks | Grade |
|---|---|
| 90 or above | A |
| 80 or above | B |
| 70 or above | C |
| 60 or above | D |
| Below 60 | F |

### 4. Class Average

The program adds all individual student averages and divides the sum by the number of students.

### 5. Find the Topper

The program compares the students' averages and identifies the student with the highest average.

## ▶️ How to Run

1. Install Python 3 if it is not already installed.
2. Open the project folder in VS Code or Cursor.
3. Open the terminal in the project folder.
4. Run the following command:

```bash
python3 messy_py.py
```

On Windows, you can use `python messy_py.py` if Python is available through that command.

## 📊 Sample Output

```text
REPORT
Rahul 258 86.0 B
Priya 205 68.33 D
Amit 269 89.67 B
Sneha 173 57.67 F
Vikram 249 83.0 B

Class average: 76.93
Topper: Amit 89.67
```

*Note: The spacing and decimal precision may differ depending on the print statements in your program.*

## 🎯 Learning Outcomes

Through this project, I practiced:

- Defining and calling functions in Python.
- Working with nested lists and indexing.
- Using `for` loops to process data.
- Applying conditional statements for grade calculation.
- Calculating totals, averages, and maximum values.
- Generating a simple report from structured data.

## 👩‍💻 Author

Created as a Python programming practice project.
