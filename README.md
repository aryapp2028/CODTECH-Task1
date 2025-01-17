Name:ARYA P P
Company:CODTECH IT SOLUTIONS
ID:CT08FSQ
Domain:SQL
Duration:December 30th 2024 to January 30th 2025
Mentor:NEELA SANTHOSH KUMAR



OVERVIEW OF THE PROJECT:

PROJECT:STRUCTURED QUERY LANGUAGE FOR LIBRARY AND STUDENT MANAGEMENT SYSTEM.


INTRODUCTION:

This document provides a comprehensive overview of two distinct database-driven projects: the Library Management System and the Student Management System. Both projects emphasize the utilization of relational databases, SQL operations, and trigger-based automation to streamline essential functions within their respective domains.

#LIBRARY MANAGEMENT SYSTEM

OBJECTIVE:

To efficiently manage books, members, and transactions in a library setting, ensuring accurate tracking of book availability and lending activities.

KEY FEATURES:

<Books Management: Add, update, and delete book records.

<Members Management: Maintain member details with unique identifiers.

<Transactions Management: Record borrowing and returning activities with automated updates to book availability.

<Triggers for Automation: Decrease Available Copies on Borrowing: Ensures accurate count of books available after a transaction.

<Increase Available Copies on Return: Updates availability upon book return.

DATABASE SCHEMA:

<Books Table: Stores book details, including title, author, genre, and availability.

<Members Table: Captures member information such as name, email, and phone.

<Transactions Table: Logs borrowing and return activities with foreign keys linking to Books and Members.

LIMITATIONS:

*No support for overdue fines.

*Limited tracking of member borrowing history beyond current transactions.

FUTURE IMPROVEMENTS:

*Implement overdue fines and notification system for due dates.

*support for multiple copies of books borrowed by the same member.

#STUDENT MANAGEMENT SYSTEM

OBJECTIVE:

To manage student information, course details, and enrollment records for an educational institution.

KEY FEATURES:

<Students Management: Maintain personal and contact details of students.

<Courses Management: Add and update course information, including credits.

<Enrollments Management: Record student grades for enrolled courses.

COMPREHENSIVE QUERIES:

*Fetch all students and their enrolled courses with grades.

*Count the number of students in each course.

*Retrieve details of students scoring specific grades.

DATABASE SCHEMA:

<Students Table: Stores student details such as name, date of birth, and contact information.

<Courses Table: Maintains course-specific details, including name and description.

<Enrollments Table: Logs student-course associations and grades, with foreign keys linking to Students and Courses.

LIMITATIONS:

*No support for attendance or assignment tracking.

*Limited grading scale representation.

FUTURE IMPROVEMENTS:

*Integrate attendance and assignment tracking.

*Support for advanced grading systems and course prerequisites.

SYSTEM DESIGN:

Both systems employ relational database models with normalization to reduce redundancy and ensure data integrity. Foreign keys enforce relationships between tables, and triggers automate repetitive tasks for consistency.

CONCLUSION:

The Library Management System and Student Management System are robust, foundational projects that highlight the use of SQL in real-world scenarios. They demonstrate efficient database design, query formulation, and trigger-based automation, making them valuable additions to any portfolio. Future enhancements can extend their capabilities, aligning them further with real-world requirements.

