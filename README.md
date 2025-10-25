# Role-Based-Access-Control
Supporting SDG 16: Peace, Justice, and Strong Institutions

Project Overview

This project demonstrates a Role-Based Access Control (RBAC) system using Python CLI.
Users are assigned roles (admin, auditor, user) and can access resources based on their permissions.

Key features:

User registration and login with secure password hashing (SHA-256)

Role-based access control for different resources (read_data, delete_data, view_logs)

Activity logs for all user actions (registration, login, access attempts)

Admin-only log viewing for transparency and accountability

How to Run

Clone or download the repository.

Run the program in terminal / VS Code:

python iam_system.py


Follow the menu to register users, login, access resources, and view logs.

Sample Users

admin → full access

auditor → can view logs and read data

user → read-only access

Screenshots / Sample Output

You can include a terminal screenshot showing registration, login, access, and logs.

Technologies Used

Python 3.x

hashlib (for password hashing)

getpass (for hidden password input)
