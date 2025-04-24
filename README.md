# Final Lab Task 3.1
This task is to execute a series of MySQL queries on the courses table to retrieve open and full courses, group enrollments by category, calculate total enrollments, and sort courses by student count, following a specific order.


## Step-by-Step MySQL Tasks
Database Setup (Already Done):
A courses table exists with these fields:

id (INT, PK, auto-increment)

course_name (VARCHAR, NOT NULL)

category (VARCHAR, NOT NULL)

enrollment_limit (INT, NOT NULL)

students_enrolled (INT, NOT NULL)

**Note: The table already contains 20 courses.** 

## Tasks to Perform (in order):
**1. Select Open Courses**

Get all courses where students_enrolled is less than enrollment_limit.

**2. Group by Category**

For each category, calculate the total students_enrolled.

**3. Fully Enrolled Courses**

Retrieve courses where students_enrolled equals enrollment_limit.

**4. Total Enrollment**

Calculate the sum of all students_enrolled across courses.

**5. Sort by Enrollment**

Display courses ordered by students_enrolled in ascending order.

## TASK 1 QUERY STATEMENT
![Image](https://github.com/user-attachments/assets/bbc7b02f-b761-4fe0-a176-78c0a4ff6093)
## TASK 1 OUTPUT
![Image](https://github.com/user-attachments/assets/607c3859-301d-4fbe-8e53-d7a1fae47672)
## TASK 2 QUERY STATEMENT
![Image](https://github.com/user-attachments/assets/78572588-4b2d-427d-84b4-f53697d9a00a)
## TASK 2 OUTPUT
![Image](https://github.com/user-attachments/assets/0b3f0c08-162b-4401-a300-ce4f922a5d7f)
## TASK 3 QUERY STATEMENT
![Image](https://github.com/user-attachments/assets/25145a7c-0687-442d-8cbd-6a1ef3da1d9c)
## TASK 3 OUTPUT
![Image](https://github.com/user-attachments/assets/0a97baf9-b0c3-43b6-a38c-0094b80328de)
## TASK 4 QUERY STATEMENT
![Image](https://github.com/user-attachments/assets/19ebf42c-4301-4e48-82db-5bb40a9fe373)
## TASK 4 OUTPUT
![Image](https://github.com/user-attachments/assets/70d5239f-639f-4bbb-938a-73b075b7537a)
## TASK 5 QUERY STATEMENT
![Image](https://github.com/user-attachments/assets/9a43a11a-df8a-4fa5-b816-40bf7ae872cc)
## TASK 5 OUTPUT
![image](https://github.com/user-attachments/assets/7ccf159b-7440-4e09-a4a6-2c679a2a9970)
