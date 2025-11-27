📚 Library Management System (Python CLI)

A simple menu-driven Library Management System built using Object-Oriented Programming, text-file storage, and logging. The project is fully modular and packaged using a clean folder structure.

🚀 Features ✅ Book Class (OOP)

Title, Author, ISBN, Status

Issue / Return methods

Convert to/from text-file format

✅ Inventory Manager

Add books

Search by title or ISBN

Issue / Return

Display all

Stores all books in books.txt

Uses library_log.log for logging

✅ Persistence (Text File)

Books are stored as:

title|author|isbn|status

One book per line inside books.txt.

✅ Command Line Interface

Menu options include:

Add Book

Issue Book

Return Book

View All Books

Search Book

Exit

✅ Logging

Every operation (add, issue, return, errors) is logged in:

library_log.log

🎁 BONUS: Packaged Folder Structure

Clean, modular project layout:

Library_Manager/ │ ├── library_manager/ │ ├── init.py │ ├── book.py │ ├── inventory.py │ ├── cli/ │ ├── main.py │ ├── books.txt ├── library_log.log ├── README.md ├── requirements.txt └── .gitignore

📂 Folder Explanation 📁 library_manager/

Package containing:

book.py → Book class

inventory.py → Inventory manager + logging + file handling

init.py → Makes folder importable (from library_manager import ...)

📁 cli/

Entry-point for the menu-driven program

main.py

output:
<img width="1920" height="1020" alt="main py - Lib-Book-Management - Visual Studio Code 27-11-2025 11_09_36" src="https://github.com/user-attachments/assets/bb23abae-1613-47f2-843a-43a6c6bdbe24" />
output2:
<img width="1920" height="1020" alt="main py - Lib-Book-Management - Visual Studio Code 27-11-2025 11_09_45" src="https://github.com/user-attachments/assets/f568c12e-869c-402e-8eef-738fb9d0fdd5" />



