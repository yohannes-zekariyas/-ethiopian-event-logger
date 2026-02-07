Ethiopian Calendar Event Logger 📅
This is a simple C++ console program that lets users add, view, search, save, and load events using the Ethiopian calendar.
I built this project to practice basic C++ programming concepts such as dynamic memory, file handling, structures, and input validation.
✨ Features
➕ Add events with:
Event title
Event description
Ethiopian date (day, month, year)
📖 View all saved events
🔍 Search events by:
Day
Month
Year
💾 Save events to a file called events.txt
📂 Load saved events automatically when the program starts
✅ Date validation based on the Ethiopian calendar:
Months 1–12 have 30 days
Month 13 (Pagume):
5 days in normal years
6 days in leap years
🛠️ Technologies Used
Programming language: C++
Standard libraries:
<iostream>
<fstream>
<string>
📚 C++ Concepts Practiced
Using struct to store data
Dynamic memory allocation (new and delete)
Reading from and writing to files
Input validation
Loops and conditional statements
Functions
Arrays and pointers
Menu-based console program
▶️ How to Run the Program
Save the source code in a file named:
Copy code

calendar_event_logger.cpp
Compile the program using a C++ compiler, for example:
Copy code
Bash
g++ calendar_event_logger.cpp -o calendar
Run the program:
Copy code
Bash
./calendar