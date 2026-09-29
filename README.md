# LMNOP Book of Grades
## Project Description
In this program, We are gonna compute the final GWA or final grade of a specific subject that needs the user's inputs which are their grades and meetings per quarter in that specific subject.
## How to run the program
In accessing this GitHub program, someone who has access to it will have to share to you the file link, access it and execute the program and enjoy!
## Features
What appears first when you execute the program is the user's input for grades, meetings per quarter, and subject. To compute for their final grade, *meetings per week* minus one then multiply that by their grade.
## Example Output
- Welcome to LMNOP Book of Grades, where we calculate, store, and display your grades!
- (1) Gradebook
- (2) Results
- (3) Exit
- Enter a subject: Computer Science 2
- Enter your grade: 1.75
- Enter the meeting per quarter with this subject: 9
- Final Grade for Computer Science 2: 1.969
## Contributors: 
Student 1: Shiev Adrhian P. Nielo (input validation, user interface)
Student 2: Marion Patrick Lumen (letter grade conversion and testing)
Student 3: Jacques Anthony Magbanua (Grade Logic and average calculations)
## Pseudocode:
START

DISPLAY "Welcome to LMNOP Book of Grades!"
DISPLAY "(1) Gradebook"
DISPLAY "(2) Results"
DISPLAY "(3) Exit"

INPUT choice

WHILE choice is not 3

    IF choice = 1 THEN

        INPUT subject
        INPUT grade
        INPUT meetings_per_quarter

        COMPUTE final_grade
            final_grade = (meetings_per_quarter - 1) × grade

        STORE subject and final_grade

        DISPLAY "Final Grade for ", subject, ": ", final_grade

    ELSE IF choice = 2 THEN

        DISPLAY stored grades and results

    ELSE
        DISPLAY "Invalid choice. Please try again."

    END IF

    DISPLAY "(1) Gradebook"
    DISPLAY "(2) Results"
    DISPLAY "(3) Exit"
    INPUT choice

END WHILE

DISPLAY "Thank you for using LMNOP Book of Grades!"

END
