### codealphaonemonthintership2 ###
### Task Student Grade Tracker ###
The Student Grade Tracker is a simple Java console application that allows users to input student grades and calculate the average, highest, and lowest grades in a class.

Features
Grade Input: Enter grades for multiple students.
Average Grade Calculation: Automatically calculates the average grade for the class.
Highest Grade: Identifies the highest grade among the students.
Lowest Grade: Identifies the lowest grade among the students.
How It Works
1. Input Student Grades
The application prompts the user to enter the number of students in the class and then allows the user to input grades for each student.

2. Calculate Average Grade
The application calculates the average of all the entered grades and displays it.

3. Identify Highest and Lowest Grades
The application identifies and displays the highest and lowest grades from the entered data.

Usage
Clone the repository to your local machine.
Compile the StudentGradeTracker class.
Run the application.
Follow the on-screen instructions to enter grades and view the calculated results.
bash
Copy code
javac StudentGradeTracker.java
java StudentGradeTracker
Code Structure
Main Method: Handles user input for the number of students and their grades, and then displays the average, highest, and lowest grades.
calculateAverage Method: Calculates and returns the average grade.
findHighestGrade Method: Identifies and returns the highest grade.
findLowestGrade Method: Identifies and returns the lowest grade.
Example Interaction
yaml
Copy code
Enter the number of students: 3
Enter grade for student 1: 85.5
Enter grade for student 2: 90.0
Enter grade for student 3: 78.5

Average grade: 84.66666666666667
Highest grade: 90.0
Lowest grade: 78.5
Requirements
Java Development Kit (JDK) 8 or higher
License
This project is open-source and available under the MIT License.
