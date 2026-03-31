                                                              Birthday Reminder (Python)

A simple Python script that reminds you of birthdays based on the current date and allows you to add new birthdays.

Features-
Stores a list of birthdays (name + date of birth)
Checks if today matches any stored birthday
Displays birthday message with correct age and suffix (e.g., 21st, 22nd)
Allows user to add new birthdays dynamically

Requirements-
Python 3.x
No external libraries required (uses built-in datetime module)

How to Run-
Clone or download this repository
Open terminal/command prompt

Run the script-
python source-code.py
Adding a Birthday

When prompted:

To add birthday type y:
Type y to add a new birthday
Enter date in format:
yyyy-mm-dd
Enter the person's name

Example:

To add birthday type y: y
Add birthday in format yyyy-mm-dd: 2000-05-12
Whose bday? Rahul

Output Example-

If today matches a birthday:

It's Rahul's 24th Birthday
How It Works
The script gets the current date using datetime
Compares it with stored birthdays (month & day)
If matched:
Calculates age
Adds correct ordinal suffix (st, nd, rd, th)
Prints a birthday message

Data Structure-

Birthdays are stored as:

bday_log = [
   ('Name', ('YYYY', 'MM', 'DD')),
]

Limitations-
Data is not saved permanently (resets every run)
No file/database storage
Manual input required each time

Future Improvements-
Save birthdays to a file (CSV/JSON)
Add notification system
GUI version using Tkinter
Sort upcoming birthdays
