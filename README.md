# -Student-GraduateStudent-and-NonDegreeStudent
# Program 5: Student Inheritance and Polymorphism

## Course
CS145 Intro / CMPS 2143 Object Oriented Programming

## Description
This program demonstrates object-oriented programming concepts such as inheritance, polymorphism, static variables, and switch statements. You will build upon a class hierarchy involving `Person`, `Student`, `GraduateStudent`, and `NonDegreeStudent`.

## Objectives
- Utilize polymorphic variables for dynamic object behavior.
- Implement and use a static variable to track student count.
- Use a switch statement to handle object instantiation based on type.
- Read and process data from an input file.
- Output formatted student information to a file.

## Requirements
- Dynamically allocate an array of pointers to `Person`.
- Use a switch to instantiate objects of `Person`, `Student`, `GraduateStudent`, or `NonDegreeStudent` using input codes: `P`, `S`, `G`, `N`.
- Exploit polymorphism: store all objects as `Person*` and call overridden methods.
- Track and print the number of `Student` objects using a static variable.
- Print **only** students' data.
- Specifically update and reprint data for the student named **Carl M. Sagan** after granting a Ph.D.

## Input File Format
- First line: an integer `N` indicating the number of people.
- Each person starts with a type code: `P`, `S`, `G`, `N`.
- Example line:

## Output Requirements
Write to a file with:
- A clear heading
- The number of students
- Data for all students
- Updated information for Carl M. Sagan

## Submission Instructions
Submit the following:
1. `main.cpp` (you may modify other files, but only submit this one)
2. A printout of your `main.cpp` code
3. A printout of your input file
4. A printout of your output file

## Notes
- Use `getline()` and `infile.ignore()` as needed to correctly parse input lines.
- Avoid redundant code; read shared fields before the type-specific switch logic.
- Follow proper formatting and output clarity.


