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
<img width="697" alt="Screenshot (603)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/646542f6-0d9f-419f-b3fb-0da4bd0188cf">


### Grades Data

- `student_id`: Unique identifier for each student.
- `course_code`: Code of the course.
- `grade`: Grade received in the course.
<img width="516" alt="Screenshot (605)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/01ebbfb0-3a78-468a-a1a0-010cabf890da">

### Courses Data

- `course_code`: Unique code for each course.
- `course_name`: Name of the course.
- `department`: Department offering the course.
<img width="510" alt="Screenshot (604)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/62f68eac-e907-4f90-829b-ac31e995b2d3">


### Faculty Data

- `faculty_id`: Unique identifier for each faculty member.
- `first_name`: First name of the faculty member.
- `last_name`: Last name of the faculty member.
- `department`: Department of the faculty member.
- `courses_taught`: Courses taught by the faculty member.
<img width="601" alt="Screenshot (606)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/8e6c735a-f7c6-44c8-ab2b-1bef2359e77e">

### Departmental Budgets

- `department`: Name of the department.
- `budget`: Budget allocated to the department.
<img width="539" alt="Screenshot (607)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/c5520067-5c38-40c3-93b1-98c7c563d5c3">

### Dashboard Visualizations

The dashboard features a variety of visualizations to help users understand and interpret the data effectively:

- **KPI Indicators:** Highlight key performance indicators such as total budget, Number of Departments, Number of Students & Number of Faculties.
- **Bar Charts:** Shows, How many number of Faculties are their by each Department.
- **Pie Charts:** Illustrate the distribution of Number of students by the Major.
- **Donut Charts:** Illustrate the distribution of Number of students by their grades.
- **Column Charts:** Display's number of students enrolled by each month.
- **Tree Map:** Shows total budget by each department.
- **Slicers:** Enable users to filter data dynamically based on Department and Grades.
<img width="707" alt="Screenshot (609)" src="https://github.com/05tushar1997/University-Education-Analytics/assets/161101934/401a6626-4627-40b7-85bb-5bc0d1d3d8a8">


## THANKING YOU!   
