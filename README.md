Student Information System
About the Program

This is a simple Python program that demonstrates how to use functions to divide a program into small and manageable tasks.

The program asks the user for a student ID, creates a student code, checks whether the student ID is valid, creates a message, and displays the final student report.

Program Features

The program has six main functions:

1. get_student_id()

This function asks the user to enter their student ID.

student_id = input("Enter student ID: ")

It then returns the student ID so it can be used by other functions.

2. create_code(student_id)

This function receives the student ID and adds "STU-" before it.

For example:

20251554 → STU-20251554

It returns the new student code.

3. check_id(student_id)

This function checks whether the student ID starts with "2025".

If it starts with 2025, the status is Valid Student.
Otherwise, the status is Check Student ID.

The function uses an if statement and the startswith() method.

4. create_message(status)

This function receives the student status and creates an appropriate message.

If the student is valid:

Welcome to the course!

If the ID is not valid:

Please check your student ID.
5. display_result(student_id, code, status, message)

This function displays the final student report.

It shows:

Student ID
Student Code
Student Status
Message
6. main()

The main() function connects all the other functions together.

The program follows this order:

get_student_id()
       ↓
create_code()
       ↓
check_id()
       ↓
create_message()
       ↓
display_result()

The program starts when main() is called.
