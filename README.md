# EmployeeHub
Deze app voor werknemersbeheer. Berekent en vat de werkuren samen.

Workforce Manager:
This program provides employee management using SQLite database. Thanks to the user interface, it is possible to add and remove employees, add working hours and leave records, and view summary information.
Attention: The program creates its own database when first used. Your data is stored in the same directory as the program in the employee.db file. If you delete it, you will reset the program! It might be a good idea to make backups of it as you use it.
1. Adding and Removing Employees:
• They can add new employees to the system. Information such as name, position and status can be entered for each employee.
• They can remove existing employees from the system.
2. Recording Working Hours:
• They can record the daily working hours of employees. They can determine their working hours by entering details such as start and end times, break start and end times. These are made easier with the help of a calendar.
3. Add and Edit Leave Record:
• They can add employees' leave records. They can create leave records by entering information such as leave type (for example, sick leave or annual leave), start and end dates, and description. Data can be entered via a calendar.
4. Viewing Summary Information:
• They can see the total working hours, break times and net working hours of employees.
• They can monitor employees' total annual leave and sick leave usage.
• You can print summary information into an excel file.
5. Filtering and Searching:
• They can filter the employee list by name, position or status. This allows them to find a specific employee or groups more easily.# Code sample goes here


Explanation:
The program provides employee management through a graphical interface. Employee information, working hours and leave records are stored using the SQLite database. Additionally, each record added to the database contains database triggers that automatically update summary information.
Example Usage:
1. Click the "Add Employee" button to add a new employee.
2. To add work hours, select an employee and click the "Add Work Hours" button.
3. To add a leave record, select an employee and click the "Add Leave Record" button.
4. Click the "Show Summary" button to display the summary information. Get as much as you filter or the entire record as Excel output.
