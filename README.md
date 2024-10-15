#HMS-php (Hospital Management System)

Overview
HMS-php is a web-based Hospital Management System built using PHP and SQL to manage hospital operations such as patient records, doctor and staff management, and appointment scheduling. It provides a simple yet effective interface for streamlining hospital management tasks.

#Features
Patient Registration and Management: Add, edit, and manage patient information.
Doctor and Staff Management: Maintain records of doctors and hospital staff, including specializations and availability.
Appointment Scheduling: Schedule, edit, and manage appointments.
Reports: Generate reports on patients and appointments.
User Authentication: Role-based access control for Admin, Doctors, and Receptionists.
#Technologies Used
Frontend: CSS (42.2%), SCSS (32.0%)
Backend: PHP (12.9%)
Scripting: JavaScript (12.0%)
Database: MySQL
#Installation Guide
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/HMS-php.git
Navigate to the project directory:
bash
Copy code
cd HMS-php
Import the database:
Create a MySQL database named hospital_management.
Import the hospital_management.sql file from the database folder to create the necessary tables.
Configure the database connection:
Update the config.php file with your database credentials (host, username, password, and database name).
Run the application:
Use a local server (e.g., XAMPP, WAMP) to run the PHP files. Place the project folder in the htdocs directory and start the server.
#Usage
Admin: Manage doctor and staff records, view patients, and generate reports.
Doctors: Access patient information, view and manage appointments.
Receptionist: Register patients and schedule appointments.
Future Improvements
Enhance patient medical history tracking.
Add notifications for appointment reminders.
Creator
This project was created and maintained by Ram Kolisetti.
