# Student Management System(SMS) Database

## Project Overview 
The Student Management System (SMS) Database is a fully relational SQL database designed to help educational institutions efficiently manage student information, courses, and enrollments. It enable key administrative functions, from adding students and assigning courses to generating dynamic reports through SQL queries.

The project demonstrates how to: 
  - Design and implement a structured database schema with multiple related tables.
  - Ensure data integrity using primary keys, foreign keys, and constraints.
  - Write SQL queries to retrieve, aggregate, and analyze information across tables.
  - Illustrate the relationships between entities using an Entity-Relationship Diagram (ERD).

### Data Source SMS Data: 
The database uses a **dummy dataset sourced from Kaggle** to represent a typical Student Management System.
- **Students Table:** Contains student records including StudentID, Name, Gender.
- **Courses Table:** Lists courses offered, including Course ID, Course Name.
- **Departments Table:** Contains department information such as Department ID and Name.
- **Enrollments Table:** Shows the relationship between students and courses, indicating which students are enrolled in which courses.
- **Instructors Table:** Created manually in Excel to demonstrate additional data integration, containing Instructor ID, Name, and Department.

### Tools 
- Excel - for cleaning and creating the Instructors table on the dataset.
- Microsoft SQL Server
- SQL Server Management Studio
- MySQL

### Data Exploration 
Basic queries were written to explore and validate the data, such as: 
- Counting students in each department.
- Listing student enrollments per course.
- Which students are enrolled in multiple courses, and which courses are they taking?
- Courses have the highest number of enrollments?
- Department has the least number of students?
- What is the gender distribution of students across courses and instructors?



### Skills Demonstrated 
- SQL database design and table creation
- Defining primary and foreign key relationships
- Data insertion and manipulation
- Writing queries involving JOINs, aggregations, and filters
- Integrating external datasets (Instructors table via Excel)
