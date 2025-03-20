# Employee Management System

A Python-based GUI desktop application for managing employee records. This system allows users to add, update, delete, and display employee details, all while connecting to a MySQL database for persistent data storage. It’s an intuitive and efficient tool for small businesses or HR management.

## Features

- **Employee Record Management**:
  - Add new employee details, such as ID, Name, Mobile, and Salary.
  - Update existing records with ease.
  - Delete employee entries.
- **Interactive GUI**:
  - Built using the Tkinter library for an intuitive and responsive graphical user interface.
- **Dynamic Data Table**:
  - Display employee records dynamically using the `Treeview` widget.
- **Database Integration**:
  - Connects to a MySQL database for secure and reliable data handling.

## Usage

To use the application, run the Python script, and interact with the GUI to manage employee records.

### Example

```python
# Launch the application
root = Tk()
root.geometry("800x500")
root.mainloop()
```

1. Use the input fields to enter details such as Employee ID, Name, Mobile, and Salary.
2. Click on the **Add**, **Update**, or **Delete** buttons to perform the respective actions.
3. Double-click an entry in the table to load its details into the input fields for editing.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ramcharan118/employee_management_system.git
```

2. Navigate to the project directory:
```bash
cd employee_management_system
```

3. Install dependencies:
   - Ensure Python 3.x is installed.
   - Install the `mysql-connector-python` library:
     ```bash
     pip install mysql-connector-python
     ```

4. Set up the MySQL database:
   - Create a database named `abc_123`.
   - Create a table named `registation` with the following structure:
     ```sql
     CREATE TABLE registation (
         id INT PRIMARY KEY,
         empname VARCHAR(100),
         mobile VARCHAR(15),
         salary FLOAT
     );
     ```

5. Configure the database connection:
   - Update the connection credentials (`host`, `user`, `password`, `database`) in the script as per your local setup.

6. Run the script:
```bash
python employee_management_sys.py
```

## Contributing

Contributions are welcome! If you’d like to contribute:
- Fork the repository.
- Create a branch for your feature or fix.
- Submit a pull request with a clear explanation of your changes.

## Future Enhancements

- **Search Functionality**: Add a search bar to filter employee records.
- **Data Export**: Include the ability to export data as CSV or Excel files.
- **Enhanced Security**: Implement authentication for secured access.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
