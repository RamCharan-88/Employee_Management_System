Employee Management System 🚀

The Employee Management System is a robust and user-friendly desktop application built in Python. It leverages the Tkinter library for its graphical interface and integrates with a MySQL database to manage employee records efficiently. This project is ideal for small businesses, HR teams, or anyone needing a streamlined way to handle employee data.


✨ Key Features

Add Employee Records: Quickly input details like employee ID, name, mobile number, and salary.

Update Information: Easily modify existing employee records with a few clicks.

Delete Entries: Remove outdated or incorrect records from the database.

View All Data: Displays all employee data in an interactive table for easy access and management.

Intuitive GUI: Built with Tkinter for an appealing and straightforward user experience.

Database Integration: Uses MySQL to ensure secure and efficient data management.


🎯 Target Audience

Small business owners seeking an easy solution to manage employee data.

HR professionals looking for simple tools to track employee records.

Developers wanting to learn Python GUI programming with database integration.


🔧 Prerequisites

Python 3.x

Tkinter (part of Python's standard library)

MySQL Server installed and running

mysql-connector-python library (Install via: pip install mysql-connector-python)


🛠️ Setup Instructions

Clone the repository to your local machine.

Install the necessary dependencies: pip install mysql-connector-python.

Set up a MySQL database:

Create a database named abc_123.

Add a table named registation with the following structure:

sql
CREATE TABLE registation (
    id INT PRIMARY KEY,
    empname VARCHAR(100),
    mobile VARCHAR(15),
    salary FLOAT
);
Update the database connection details in the code (host, user, password, database) as per your local setup.


Run the script: 

python employee_management_sys.py


🖥️ How It Works

Launch the application by running the script.

Use the text fields to input employee information.

Manage records using the Add, Update, and Delete buttons.

Double-click on an entry in the table to load it for editing or updating.


🚀 Future Enhancements

Add a Search Functionality to filter employee records.

Enable Export to CSV for reporting and backup purposes.

Implement Role-Based Access Control (RBAC) for added security.

Add advanced features like an attendance tracker or payroll system.


🤝 Contribution Guidelines

Contributions are welcome! Feel free to fork the repository, make changes, and create a pull request. Please ensure your code follows best practices and is well-documented.


📷 Screenshots

Include screenshots or GIFs of the application interface to demonstrate its functionality and design.


📜 License

This project is licensed under the MIT License.
