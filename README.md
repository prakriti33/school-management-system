This is a web-based School Management System developed using PHP and MySQL. It includes modules for student registration, attendance, exam forms, study materials, timetables, webinars, and more. It provides separate dashboards and functionality for administrators, staff, and parents.

📁 Project Structure
bash

├── admin/                      # Admin-specific pages (dashboard, attendance, exams, etc.)
│   ├── acadamy-settings/
│   ├── basic-information.php
│   ├── admin-card.php
│   ├── ajax.php
│   ├── attendance.php
│   ├── campus-functions.php
│   ├── classes.php
│   ├── courses.php
│   ├── dashboard.php
│   ├── exam-form.php
│   ├── examination-fee.php
│   ├── footer.php
│   ├── header.php
│   ├── leave.php
│   ├── lessons.php
│   ├── paper-schedule.php
│   ├── parent-meeting.php
│   ├── periods.php
│   ├── profile.php
│   ├── results.php
│   ├── sections.php
│   ├── sidebar.php
│   ├── student-fee.php
│   ├── study-materials.php
│   ├── subjects.php
│   ├── timetable.php
│   ├── user-account.php
│   └── webinar-seminar.php

├── parent/                    # Parent dashboard and related pages
│   ├── dashboard.php
│   ├── footer.php
│   ├── header.php
│   ├── periods.php
│   ├── sidebar.php
│   ├── study-materials.php
│   └── timetable.php

├── assets/                    # Static assets
│   ├── images/
│   │   ├── placeholder.jpg
│   │   └── still-life-851328_1280.jpg
│   ├── dist/
│   │   ├── css/
│   │   ├── img/
│   │   └── js/
│   └── uploads/              # Uploaded files (study materials, images, etc.)

├── includes/
│   ├── config.php            # Database configuration
│   └── functions.php         # Reusable functions

├── actions/
│   ├── login.php             # Login logic
│   ├── student-registration.php
│   └── success.php           # Registration success page
🚀 Features
Student registration and login

Admin dashboard to manage attendance, exams, fees, and timetables

Study materials upload and management

Webinar and seminar scheduling

Parent dashboard to track student progress

Leave management and meetings

Modular structure for scalability

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Other: AJAX, jQuery (if used in ajax.php), XAMPP/WAMP for local development

