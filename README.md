# College-Management-System-CMS-in-Django
College Management System built with a Python framework Django

# Built from this Article on GeeksforGeeks
https://www.geeksforgeeks.org/college-management-system-using-django-python-project/

# Project Summary
- A college management for education purposes built using Django a Python framework

# Features of the Project

# A. Admin Users Can

  1. See Overall Summary Charts of Students' Performance, Staff's Performance, Add/Remove Courses, Add/Remove Subjects, Check/Reply to Leave application of staffs/students, Check/reply on feedback bt staffs/students, etc.
  2. Manage Staffs (Add, Update, and Delete)
  3. Manage Students (Add, Update and Delete)
  4. Manage Course (Add, Update and Delete)
  5. Manage Subjects (Add, Update and Delete)
  6. Manage Sessions (Add, Update, and Delete)
  7. View Student Attendance
  8. Review and Reply to Student/Staff Feedback
  9. Review (Approve/Reject) Student/Staff Leave
  10. Update Profile
  11. Login/Logout


# B. Staff/Teachers Can

  1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
  2. Take/Update Student's Attendance
  3. Add/Update Result
  4. Apply for Leave
  5. Send Feedback to HOD
  6. Update Profile
  7. Login/Logout


# C. Students Can

  1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
  2. View Attendance
  3. View Result
  4. Apply for Leave
  5. Send Feedback to HOD
  6. Update Profile
  7. Login/Logout

# Tech Stacks
Django, Ajax, Jquery, Bootstrap, Javascript, Python, Owl Carousel, HTML, CSS

# **Running the Project**

- To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your project's dependencies separately. You can install virtualenv with

`pip install virtualenv`

- Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

`virtualenv env`

- That will create a new folder env in your project directory. Next, activate it with this command on mac/linux:

`source env/bin/active`


- Then install the project dependencies with

`pip install -r requirements.txt`


- Now you can run the project with this command

`python manage.py runserver`

- Email_id should be in the following format:

`<username>.<staff|student|hod>@<college_domain>`
