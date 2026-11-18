# Student Information Formatting Tool (Version 2)

## Description
An improved Python formatting tool that cleans up messy user input and displays student information in a neat, consistent format for teachers and class advisers.

## How to Run
1. Ensure Python 3 is installed on your computer.
2. Run the file in your terminal: `python student_formatter_v2.py`
3. Enter the student details (even with extra spaces or inconsistent capitalization).

## What Changed in Version 2
- **Whitespace Cleaning:** Added `.strip()` to remove accidental leading or trailing spaces.
- **Standardized Capitalization:** Used `.title()` for proper names and subjects, and `.upper()` for the name code and section.
- **Accurate Character Count:** Ensures spaces at the start or end do not inflate the character total.
