# Student Database Manager

## Introduction

This Python script provides a simple yet effective way to manage a student database. It allows users to add new students, ensure there are no duplicate entries, and generate a unique sequential ID for each student. The program stores each student's name and ID as a tuple within a list. Once the input process is completed, the program will display the entire list of students along with their IDs and various statistics related to the student names.

## Key Features

- **Add New Students**: Enter student names and automatically assign a unique sequential ID to each one.
- **Duplicate Detection**: The program checks for duplicate names to prevent adding the same student more than once.
- **Input Termination**: Users can end the input process by typing "stop".
- **Student List Display**: Outputs the full list of students along with their respective IDs.
- **Name Statistics**: Displays the total number of students, the cumulative length of all student names, and highlights the students with the longest and shortest names.

## Prerequisites

- Python 3.x

## Execution Instructions

1. Clone or download this repository to your local machine.
2. Open the terminal and navigate to the directory where the script is located.
3. Execute the script with Python by running the following command:

   ```bash
   python manage_student_database.py
