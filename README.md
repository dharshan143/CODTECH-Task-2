Name : DHARSHAN D
Intern ID : CT4PP3339
Company : CODTECH IT SOLUTIONS
Domain : PYTHON PROGRAMMING
Duration : june to july 2024
Mentor : SANTHOSH KUMAR M


Project Point Of View :


The provided Python program is a simple grade tracker that allows you to input grades for multiple students, calculate their average grade, determine their letter grade based on the average, and then print a summary of each student's grades and corresponding information.


### Explanation:
1. **Functions**:
   - `calculate_average(grades)`: Computes the average of a list of grades. If the `grades` list is empty (no grades entered), it returns 0.
   - `calculate_grade(average)`: Determines the letter grade based on the average grade. It uses a series of conditional statements (`if`, `elif`, `else`) to assign the appropriate letter grade.

2. **Main Function (`main()`)**:
   - Takes user input for the number of students (`num_students`).
   - Iterates through each student, prompting for their name and their grades.
   - For each student, calculates the average grade and determines the letter grade using the defined functions.
   - Stores all student data in the `students` dictionary, which includes `grades`, `average_grade`, and `grade_letter`.
   - Prints a summary for each student, displaying their name, grades, average grade (rounded to 2 decimal places), and letter grade.

3. **Execution**:
   - The `main()` function is executed if the script is run directly (i.e., `__name__ == "__main__"`).

### Example Usage:
Here's an example interaction with the program:
```
Enter the number of students: 2
Enter name of student 1: Alice
Enter number of grades for Alice: 3
Enter grade 1 for Alice: 85
Enter grade 2 for Alice: 90
Enter grade 3 for Alice: 88
Enter name of student 2: Bob
Enter number of grades for Bob: 2
Enter grade 1 for Bob: 75
Enter grade 2 for Bob: 80

Student Grade Summary:
Student: Alice
Grades: [85.0, 90.0, 88.0]
Average Grade: 87.67
Grade Letter: B

Student: Bob
Grades: [75.0, 80.0]
Average Grade: 77.50
Grade Letter: C
```

This program provides a basic framework for tracking grades and can be expanded further with additional features such as error handling for input, saving data to files, or adding more detailed statistical analysis.
