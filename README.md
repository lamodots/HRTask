# HRTask Employee Management System - Django(Python)

HRTask is a robust web application built using Django (Python framework) and PostgreSQL as its database, designed to streamline HR processes and manage employee information effectively. This system provides a centralized platform for managing essential employee data, tracking performance, and automating routine HR tasks.

1. Login / Registration (Admin, Employee)
2. Add / Manage Employee (Admin)
3. Publish / Manage Notice (Admin)
4. Add / Manage Attendance (Admin)
5. Assign / Manage Work (Employee)
6. Send Request (Employee)
7. View Request, Notice, Works etc...

## How to Use this Project?

---

- Install Python to your System.
- Run Following command to your terminal.
  ```python
  pip install django
  ```
- Install Pipenv for Virtual Environment, run the command...
  ```python
  pip install pipenv
  ```
- Clone the repository to your local system.
- Enter in Virtual Environment by running following command in Current Working Directory.
  ```python
  pipenv shell
  ```
- Setup PostgreSQL Database and update database name and password in settings.py file in employeemanagement.
- Make the Migrations, run the command
  ```python
  python manage.py makemigrations
  ```
- Migrate the App, run the command
  ```python
  python manage.py migrate
  ```
- Finally Run the App, run the command.
  ```python
  python manage.py runserver
  ```
- Hola, It's running !!

## Screenshots

Login
![Login](/screenshots/Login.png 'Login')

Dashboard
![Dashboard](/screenshots/Dashboard.png 'Dashboard')

Assign Work
![Assign Work](/screenshots/Assign%20Work.png 'Assign Work')

Notice
![Notice](/screenshots/Notice.png 'Notice')

Admin (Manage Employee)
![Admin (Manage Employee)](/screenshots/Admin%20Employee.png 'Admin (Manage Employee)')

### Check out more Screenshots in Screenshot Folder...

## Thank You!!
