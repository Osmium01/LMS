# Library Management System

This is a simple library management system implemented using Python and MySQL.

# Requirements

Python 3.x

MySQL database

Setup

Clone the repository: git clone <repository_url>

Install the required dependencies: pip install mysql-connector-python

Import the database schema from database.sql into your MySQL server.

Update the database connection details in the code (host, user, passwd, database) to match your MySQL server configuration.

# Usage

Run the program: python library.py

Enter the password to access the system.

Choose an option from the menu to perform the desired task:

  1: Add a book to the library.
  2: Issue a book to a user.
  3: Submit a book from a user.
  4: Delete a book from the library.
  5: Display all books in the library.
  6: Exit the program.
# Functionality

Add Book: Allows you to add a book to the library by providing the book name, code, total quantity, and subject.

Issue Book: Lets you issue a book to a user by entering their name, registration number, book code, and date.

Submit Book: Allows users to submit a book by providing their name, registration number, book code, and date.

Delete Book: Deletes a book from the library based on the book code.

Display Book: Displays all books currently available in the library.
