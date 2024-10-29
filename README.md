# Course Management System (CS162 Group Project)

## Overview

The system manages student and staff information, course registration, scoreboards, and more. It is designed to handle operations for both **academic staff** and **students** without using a database, relying on **dynamic arrays**, **linked lists**, and **file storage** (text and binary files).

## Features

### User Authentication
- **Login**: Users (academic staff or students) must log in to access the system.
- **Profile Management**: Users can view and edit their profiles.
- **Password Management**: Users can change their passwords.
- **Logout**: Users can securely log out of the system.

### Academic Staff Functionalities

#### School Year Management
- **Create School Year**: Define a new school year (e.g., 2020-2021).
- **Class Creation**: Set up classes for 1st-year students (e.g., 20APCS1, 20CLC11).
- **Student Enrollment**: Add new students manually or via CSV import (with fields such as Student ID, Full Name, Date of Birth, etc.).

#### Semester Management
- **Semester Creation**: Define semesters within a school year with start and end dates.
- **Course Management**:
  - **Add Courses**: Define course details like ID, name, instructor, and schedule.
  - **Upload Enrollment**: Import a list of students for each course via CSV.
  - **Course List**: View, update, or delete course information.
  - **Student Enrollment in Courses**: Add or remove individual students.

#### End-of-Semester Tasks
- **Scoreboard Import/Export**: Import or export course scoreboards in CSV format.
- **Grade Management**: Update grades and manage fields like Total Mark, Final Mark, Midterm Mark, etc.
- **Class Scoreboard**: View full class scoreboards with course grades, semester GPA, and overall GPA.

### Student Functionalities
- **Course Viewing**: View enrolled courses for the current semester.
- **Scoreboard Viewing**: Access personal grades and GPA once published by academic staff.

### General Features
- **Class & Course Lists**: Academic staff can view lists of classes, students within a class, and students within a course.

## Technical Requirements

- **Programming Language**: C++
- **Data Structures**: Dynamic arrays and linked lists only
- **File Storage**: Text and binary files (databases are not allowed)
- **Source Control**: Git, with each member contributing at least 20 commits over 15 days

## File Structure

- **Source Code**: Organized into modules for user authentication, course management, student records, etc.
- **Data Files**: Text and binary files for storing user data, course lists, and scoreboards.
- **CSV Files**: Used for importing and exporting student data and scoreboards.
  
## Getting Started

1. **Compile the Project**: Compile using a C++ compiler.
2. **Run the Executable**: Start the application by running the generated executable.
3. **Login**: Academic staff or students can log in to access respective functionalities.
4. **Follow the Menu**: Use the interactive menu to navigate through features.

## Note
This project is limited to the use of dynamic arrays and linked lists as required by the course guidelines. No external libraries or databases were used, ensuring the system meets the specific project constraints.
- **Video Demo**: [YouTube Playlist](https://www.youtube.com/playlist?list=PLl5fpvgyLwC2xFbFDS69PD2MQE4FPdb1P)
- **Figma Design**: [Learning Management System (Community)](https://www.figma.com/design/7dgN8q3wOqzgZy9W0LyVlW/Learning-Management-Systems-(Community)?node-id=0-1)
