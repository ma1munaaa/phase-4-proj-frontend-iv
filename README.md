# Check-In System

The Check-In System is a web application for managing check-ins, students, teachers, and administrators. It allows users to check in, view check-in data, manage students and teachers, and perform administrative tasks. This document provides an overview of the project's structure, features, and instructions for running the application.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the Check-In System locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ma1munaaa/phase-4-proj-frontend-iv.git
Navigate to the project directory:

bash
Copy code
cd check-in-system
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Create and initialize the database:

bash
Copy code
flask db init
flask db migrate
flask db upgrade
Start the application:

bash
Copy code
flask run
The application should now be accessible at http://localhost:5555 in your web browser.

Usage
User Registration: Users can register for an account with their name, phone number, email, ID number, and password.

User Login: Registered users can log in using their email and password.

Check-In: Users can check in by providing their name and room number.

Dashboard: The dashboard displays statistics, including the total number of check-ins and room occupancy.

Manage Students: Admin users can manage student records, including adding, editing, and deleting student profiles.

Manage Teachers (TMs): Admin users can manage teacher (TM) records, including adding, editing, and deleting TM profiles.

JWT Authentication: The application uses JWT (JSON Web Tokens) for user authentication.

Features
User Registration and Authentication
Check-In and Check-Out
Dashboard with Statistics
User Role Management (Admin, Teacher, Student)
CRUD Operations for Students and TMs
JWT Token-Based Authentication
Responsive Web Design
Contributing
Contributions are welcome! If you would like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix: git checkout -b feature-name
Commit your changes and push them to your fork: git push origin feature-name
Create a pull request against the main repository.
Please make sure to follow the code of conduct and contribution guidelines.

License
This project is licensed under the MIT License.


## Contributors:
- Erick Muthui
- Joyce Wachira
- Maimuna Mohamud
- Ian Imbuki