# Library_Management
Project on Library Management System

#Introduction
The Library Management System is a Python-based project designed to help a library administrator manages books,Issue them to students,track their returns
also calculates fine for the late returns.The admin can add, delete,and display books,as well as check issued books

#Features
Admin Login: Secure access with username (admin) and password (1234).
Add Books: Store books with ID, name, author, and availability status.
Issue Books: Assign books to students and update availability.
Return Books: Accept book returns and calculate fines (₹50/day after 30 days).
Delete Books: Remove books from the system.
Display Books: Show all available books.
Issued Books List: View details of all issued books.
Exit System: Allows the admin to quit the program.

#Techical Details
Programming language : Python
Module Used:datetime,timedelta
Data Storage:Uses Dictionaries(self.books and self.issued_books)
Fine Calculation:50 per day for late returns


