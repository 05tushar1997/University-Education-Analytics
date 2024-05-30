# University-Education-Analytics

This repository contains a project aimed at generating and analyzing data related to student performance, enrollment, and faculty metrics for a university. The goal is to create a detailed Power BI dashboard to help university administrators monitor academic performance, resource allocation, and student demographics.

## Objectives

- Analyze student performance.
- Analyze enrollment data.
- Analyze faculty metrics.
- Create detailed visualizations in Power BI.

## Datasets

The project generates the following datasets:

1. **Student Enrollment Data**: Information about students, including demographics and enrollment details.
2. **Grades Data**: Records of student performance in various courses.
3. **Courses Data**: Information about courses offered, including course codes, names, and departments.
4. **Faculty Data**: Details of faculty members, including their departments and courses taught.
5. **Departmental Budgets**: Budget allocations for different departments.

## Generated Data

The data is generated using the `Faker` library to create realistic, synthetic data for each dataset.

### Student Enrollment Data

- `student_id`: Unique identifier for each student.
- `first_name`: First name of the student.
- `last_name`: Last name of the student.
- `gender`: Gender of the student.
- `date_of_birth`: Date of birth of the student.
- `enrollment_date`: Date of enrollment.
- `major`: Major field of study.
  

### Grades Data

- `student_id`: Unique identifier for each student.
- `course_code`: Code of the course.
- `grade`: Grade received in the course.

### Courses Data

- `course_code`: Unique code for each course.
- `course_name`: Name of the course.
- `department`: Department offering the course.

### Faculty Data

- `faculty_id`: Unique identifier for each faculty member.
- `first_name`: First name of the faculty member.
- `last_name`: Last name of the faculty member.
- `department`: Department of the faculty member.
- `courses_taught`: Courses taught by the faculty member.

### Departmental Budgets

- `department`: Name of the department.
- `budget`: Budget allocated to the department.
