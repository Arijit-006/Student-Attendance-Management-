# Student Attendance Management & Analytics System

An Excel based student attendance management and analytics system that will help you track student attendance, determine key performance indicators, find out attendance patterns and provide analytical insights in an interactive dashboard.

---

## Introduction

The attendance of a student is an important academic metric that helps an organization keep track of the attendance of the students and address any concerns.

This project helps convert the attendance records into analytical insights using Microsoft Excel.

The data of student attendance is maintained and we make student-wise, subject-wise, faculty-wise and time based analysis through an analytical dashboard.

The project demonstrates the complete life cycle of data analytics:

Data Collection → Data Organization → Data Analysis → KPI calculation → Visualization → Insights

---

## Objectives

The project aims at:

- Tracking attendance records of students.

- Calculating overall attendance performance.

- Subject-wise analysis of attendance.

- Student-wise analysis of attendance.

- Analyzing the trends of attendance over time.

- Identifying students below the attendance threshold.

- Finding out students below the overall average attendance.

- Understanding attendance distribution across different ranges.

- Analyzing attendance patterns across different faculty.

- Providing important analytical insights in an interactive Excel Dashboard.

---

## Dataset

We have a set of attendance records which include:

| Column | Description |

|---|---|

| Date | Date on which the class was conducted |

| Roll No | Unique student identification number |

| Name | Student name |

| Subject | Subject for which the attendance was recorded |

| Faculty | Faculty/instructor conducting the class |

| Attendance Status | Present or Absent |

Dataset Size:

- Students: 202

- Classes: 10

- Attendance Records: 2,020

- Subjects: 5

- Attendance Status: Present / Absent

> The current repository dataset is made up of simulated attendance records for demonstration and analytical practice. The student master set is based on the given student data set.

---

## Tools and Technologies

- Microsoft Excel

- Excel Formulas

- Pivot-like analytical summaries

- Conditional Formatting

- Data Validation

- Excel Charts

- Dashboard Design

- Data Cleaning & Analysis

---

## Key Performance Indicators (KPIs)

The dashboard comprises the following KPIs:

### 1. Total Students

It indicates the number of students that have been considered for this system.

### 2. Total Classes

It indicates the total number of classes conducted based on unique combination of:

Date + Subject

### 3. Total Present

This represents the total number of attendance records that have been marked as present.

### 4. Total Absent

This represents the total number of attendance records that have been marked as absent.

### 5. Overall Attendance %

Overall attendance percentage is calculated as:

Overall Attendance % = Total Present / Total Attendance Records × 100

### 6. Average Student Attendance

It represents the average student attendance for all the students considered.

### 7. Students Below 75% Threshold

It shows the number of students that have attendance below 75%, which could be considered the attendance threshold for this system.

### 8. Students Below Average

It indicates the number of students whose attendance is below the average student attendance.

---

## Dashboard & Visualizations

The project dashboard gives us various analytical insights.

### Subject-wise Attendance

It shows the attendance percentage for different subjects.

This helps us understand the attendance patterns across the subjects.

### Attendance Distribution

We classify students into different attendance categories such as:

- Below 75%

- 75 - 79%

- 80 - 89%

- 90 - 100%

This helps us understand the attendance pattern of the students.

### Daily Attendance Trend

We plot a line chart to analyze the attendance percentage trends for different class dates.

### Students Below Average

The students below the average attendance are presented in a table.

---

## Analytical Sheets

The workbook is divided into multiple analytical sheet including:

### `Student Master`

We have the master set of students including:

- Roll No

- Name

### `Attendance Data`

This sheet hosts our attendance records including:

- Date

- Roll No

- Name

- Subject

- Faculty

- Attendance Status

### `Student Summary`

This sheet provides student-wise attendance calculation including:

- Total Classes

- Present

- Absent

- Attendance %

### `Subject Analysis`

This sheet provides subject-wise attendance analysis.

### `Daily Analysis`

This sheet analyzes the attendance trends on day-to-day basis.

### `Faculty Analysis`

This sheet provides attendance analysis based on different faculty.

### `Attendance Distribution`

This sheet categorizes students into different attendance categories.

### `Below Threshold`

This sheet indicates students below the 75% attendance threshold.

### `Below Average`

This sheet indicates students below average attendance.

### `Dashboard`

This sheet provides consolidated analytical dashboard providing different insights on the attendance records.

---
