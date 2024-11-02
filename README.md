# University-Management-System
This C++ program is a comprehensive University Management System designed to handle the main administrative tasks within a university. It provides functionalities for managing departments, students, courses, and instructors.
# University Management System

## Description

The University Management System is a C++ application designed to simplify university administrative tasks by providing an organized menu-driven interface for managing departments, students, courses, and instructors. The program allows users to perform essential operations such as adding and removing departments, admitting and managing students, and overseeing courses within each department.

## Features

1. **University Management**:
   - Adds or removes departments.
   - Displays all departments within the university.

2. **Department Management**:
   - Adds and removes courses within each department.
   - Manages instructors associated with each department.
   - Provides access to department-specific menus.

3. **Student Management**:
   - Admits and removes students with detailed information.
   - Maintains student records, including personal information, CGPA, and admission dates.

4. **Course Management**:
   - Enrolls students in courses within a department.
   - Assigns instructors to courses.
   - Displays students and instructors associated with a particular course.

## Menu Structure

The program offers two primary menu levels:

1. **University Menu**:
   - Options to manage departments, students, and general university details.
   
2. **Department and Course Menus**:
   - Access to courses and instructors within each department.
   - Sub-menus for managing enrolled students and assigned instructors in specific courses.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/UniversityManagementSystem.git
    cd UniversityManagementSystem
    ```

2. Compile the program:
    ```bash
    g++ -o university_system main.cpp
    ```

3. Run the program:
    ```bash
    ./university_system
    ```

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
